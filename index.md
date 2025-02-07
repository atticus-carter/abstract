<div id="instructionsContainer">
</div>


## Instructions:
Use this document to help you draft an abstract that meets the following guidelines. Your abstract should be written as a single, cohesive paragraph (300 words or less) that follows the **“And, But, Therefore”** structure to set up your research story.

## Story Structure: And, But, Therefore
When drafting your abstract, use the following structure to present your research clearly and logically:

- **And:** State an established fact or background information.  
  *Example:* “CO₂ is increasing in the atmosphere **AND** leads to ocean acidification…”
- **But:** Introduce the problem or gap in knowledge.  
  *Example:* “…**BUT** little is known about species’ capacity to evolve in response to pH stress.”
- **Therefore:** State your research purpose, objective, or action taken.  
  *Example:* “**THEREFORE,** we conducted this study to determine…”

Use this structure as a guide to create a compelling narrative that logically connects your background, problem, and research objectives.

## Abstract Guidelines & Criteria

### 1. Text Formatting
- **Title:**
  - Must be in title case format.
- **Genus and Species Names:**
  - All genus and species names should be capitalized and italicized appropriately.
- **Spacing:**
  - Ensure there are no extra spaces at the beginning of the title or abstract.

### 2. Abstract Inclusions
- The abstract must be a single paragraph with no headings.
- Include minimal-to-no citations.

### 3. Spelling & Punctuation
- Ensure there are no spelling or punctuation mistakes.
- Acronyms must be defined after their first use.

### 4. Present or Past Tense
- Use present or past tense in the Methods section.
- Avoid “will be” statements (e.g., “I will be conducting…”) in the Background and Methodology.
  (See the abstract writing workshop examples for further clarification.)

### 5. Role in Research
- Use active voice (e.g., “I conducted analyses” rather than “Analyses were run”).
- Make explicit your personal contributions to the project.

### 6. Context or Purpose
- Provide a clear statement of purpose that includes the background or context of the project.

### 7. Questions/Hypotheses
- Clearly state your project’s research question, hypothesis, or goal.

### 8. Methodology/Approach
- Describe your methodology including measurements, tools, and, if applicable, participant demographics.

### 9. Expected/Preliminary Findings
- If your project is in progress, indicate your anticipated or preliminary findings.

### 10. Implications
- Explain why these findings matter: the impact on the field, implications for future work, or why the research is significant.

<details>
  <summary><strong>Final Checklist Before Submission (click to expand):</strong></summary>

- [ ] Title is in title case.
- [ ] All genus and species names are formatted correctly.
- [ ] No extra spaces at the beginning of the title or abstract.
- [ ] The abstract is written as a single paragraph with minimal citations.
- [ ] No spelling or punctuation errors; all acronyms are defined.
- [ ] The Methods section uses present or past tense without “will be” statements.
- [ ] Active voice is used and personal contributions are explicit.
- [ ] A clear statement of purpose and background is provided.
- [ ] Research questions/hypotheses are clearly stated.
- [ ] Methodology details (measurements, tools, participant demographics) are described.
- [ ] Expected or preliminary findings are mentioned if applicable.
- [ ] The significance and implications of your findings are explained.
- [ ] The abstract is 300 words or less.
</details>

## Writing Your Abstract

### Your Task:
Using the **“And, But, Therefore”** framework and the criteria listed above, draft a single-paragraph abstract (300 words or less) for your research project. Remember to:
- Start with a background statement,
- Introduce the research gap,
- And then state your research purpose or action.

**Example Structure:**  
“CO₂ is increasing in the atmosphere **AND** leads to ocean acidification **BUT** little is known about species’ capacity to evolve in response to pH stress. **THEREFORE,** we conducted this study to [state your research objective].”

Fill in your specific research details following this pattern.

<!-- Interactive Abstract Builder Form -->

<form id="abstractForm">
  <label for="title">Title (in Title Case):</label>
  <input type="text" id="title" name="title" placeholder="Enter your title" required>
  
  <label for="and">Background/Context:</label>
  <textarea id="and" name="and" placeholder="e.g., CO₂ is increasing in the atmosphere" required></textarea>
  
  <label for="but">Research Gap:</label>
  <textarea id="but" name="but" placeholder="e.g., leads to ocean acidification, but little is known about species' capacity to evolve in response to pH stress" required></textarea>
  
  <label for="therefore">Research Objective:</label>
  <textarea id="therefore" name="therefore" placeholder="e.g., we conducted this study to assess..." required></textarea>
  
  <label for="researchQuestion">Research Question/Hypotheses:</label>
  <textarea id="researchQuestion" name="researchQuestion" placeholder="State your research question, hypothesis, or goal" required></textarea>
  
  <label for="methodology">Methodology/Approach (Use present or past tense; avoid “will be”):</label>
  <textarea id="methodology" name="methodology" placeholder="Describe your methodology, measurements, tools, and participant demographics (if applicable)" required></textarea>
  
  <label for="findings">Expected/Preliminary Findings:</label>
  <textarea id="findings" name="findings" placeholder="State your anticipated or preliminary findings" required></textarea>
  
  <label for="implications">Implications:</label>
  <textarea id="implications" name="implications" placeholder="Explain the significance and impact of your findings" required></textarea>
  
  <label for="role">Role in Research (Describe your personal contributions):</label>
  <textarea id="role" name="role" placeholder="Explain your personal contributions to the project" required></textarea>
  
  <button type="button" onclick="generateAbstract()">Generate Abstract</button>
  <button type="button" onclick="toggleHighlight()">Toggle Segment Highlighting</button>
  <button type="button" onclick="copyToClipboard()">Copy to Clipboard</button>
</form>

<div id="output" class="output"></div>
<div id="wordCount" class="output"></div>
<div id="warning" class="warning"></div>

<!-- Additional Criteria Section -->
<h2>Abstract Criteria & Checklist</h2>

<ul>
  <li><strong>Text Formatting:</strong> Title in title case, properly formatted genus/species names, no extra spaces.</li>
  <li><strong>Abstract Inclusions:</strong> A single paragraph with minimal-to-no citations.</li>
  <li><strong>Spelling &amp; Punctuation:</strong> No spelling or punctuation errors; acronyms defined after first use.</li>
  <li><strong>Present or Past Tense:</strong> Use present or past tense in methods; avoid “will be” statements.</li>
  <li><strong>Role in Research:</strong> Use active voice and explicitly state your personal contributions.</li>
  <li><strong>Context or Purpose:</strong> Provide a clear statement of purpose with background context.</li>
  <li><strong>Questions/Hypotheses:</strong> Clearly state your research question, hypothesis, or goal.</li>
  <li><strong>Methodology/Approach:</strong> Describe your methodology, including measurements, tools, and participant demographics (if applicable).</li>
  <li><strong>Expected/Preliminary Findings:</strong> Indicate anticipated or preliminary findings if the project is in progress.</li>
  <li><strong>Implications:</strong> Explain why these findings matter and their impact on the field or future work.</li>
  <li><strong>Length:</strong> The abstract must be 300 words or less.</li>
</ul>

<script>
  let highlightEnabled = false;
  
  // Check if each word in the title begins with an uppercase letter.
  function isTitleCase(str) {
    const words = str.split(' ');
    for (let word of words) {
      if (word.length === 0) continue;
      if (word[0] !== word[0].toUpperCase()) {
        return false;
      }
    }
    return true;
  }
  
  function generateAbstract() {
    // Retrieve and trim input values.
    const title = document.getElementById('title').value.trim();
    const andText = document.getElementById('and').value.trim();
    const butText = document.getElementById('but').value.trim();
    const thereforeText = document.getElementById('therefore').value.trim();
    const researchQuestion = document.getElementById('researchQuestion').value.trim();
    const methodology = document.getElementById('methodology').value.trim();
    const findings = document.getElementById('findings').value.trim();
    const implications = document.getElementById('implications').value.trim();
    const role = document.getElementById('role').value.trim();
    
    let warnings = "";
    if (!isTitleCase(title)) {
      warnings += "Warning: Title is not in title case.\n";
    }
    
    // Build abstract without connector words.
    let plainAbstract = `${title}\n\n${andText}. ${butText}. ${researchQuestion}. ${thereforeText}. ${methodology}. ${findings}. ${implications}. ${role}.`;
    plainAbstract = plainAbstract.replace(/\s+/g, ' ').trim();
    
    // Build highlighted abstract with spans.
    let highlightedAbstract = `${title}<br><br>`;
    highlightedAbstract += `<span class="segment and-seg" title="Background/Context">${andText}</span>. `;
    highlightedAbstract += `<span class="segment but-seg" title="Research Gap">${butText}</span>. `;
    highlightedAbstract += `<span class="segment rq-seg" title="Research Question/Hypotheses">${researchQuestion}</span>. `;
    highlightedAbstract += `<span class="segment therefore-seg" title="Research Objective">${thereforeText}</span>. `;
    highlightedAbstract += `<span class="segment methodology-seg" title="Methodology/Approach">${methodology}</span>. `;
    highlightedAbstract += `<span class="segment findings-seg" title="Expected/Preliminary Findings">${findings}</span>. `;
    highlightedAbstract += `<span class="segment implications-seg" title="Implications">${implications}</span>. `;
    highlightedAbstract += `<span class="segment role-seg" title="Role in Research">${role}</span>.`;
    
    let finalAbstract, finalOutput;
    if (highlightEnabled) {
      finalAbstract = highlightedAbstract;
      finalOutput = finalAbstract;
    } else {
      finalAbstract = plainAbstract;
      finalOutput = finalAbstract.replace(/\n/g, '<br>');
    }
    
    const wordCount = plainAbstract.split(/\s+/).length;
    
    document.getElementById('output').innerHTML = "<strong>Final Abstract:</strong><br>" + finalOutput;
    document.getElementById('wordCount').innerText = "Word Count: " + wordCount;
    document.getElementById('warning').innerText = warnings + (wordCount > 300 ? "Warning: Your abstract exceeds 300 words!" : "");
  }
  
  function toggleHighlight() {
    highlightEnabled = !highlightEnabled;
    generateAbstract();
  }
  
  function copyToClipboard() {
    const text = document.getElementById('output').innerText;
    navigator.clipboard.writeText(text).then(() => {
      alert("Abstract copied to clipboard!");
    }).catch(err => {
      alert("Error copying to clipboard: " + err);
    });
  }
</script>
