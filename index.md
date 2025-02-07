---
layout: default
title: "Abstract Writing Exercise: Crafting Your Research Narrative"
---

<!-- Interactive Abstract Generator Form -->
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

<div id="output" class="output" contenteditable="true"></div>
<div id="wordCount" class="output"></div>
<div id="warning" class="warning"></div>

<!-- Additional Instructions Below the Generator -->
<h2>Story Structure: And, But, Therefore</h2>
<p>
When drafting your abstract, use the following structure to present your research clearly and logically:
</p>
<ul>
  <li><strong>And:</strong> State an established fact or background information.<br>
      <em>Example:</em> “CO₂ is increasing in the atmosphere AND leads to ocean acidification…”</li>
  <li><strong>But:</strong> Introduce the problem or gap in knowledge.<br>
      <em>Example:</em> “…BUT little is known about species’ capacity to evolve in response to pH stress.”</li>
  <li><strong>Therefore:</strong> State your research purpose, objective, or action taken.<br>
      <em>Example:</em> “THEREFORE, we conducted this study to determine…”</li>
</ul>
<p>
Use this structure as a guide to create a compelling narrative that logically connects your background, problem, and research objectives.
</p>

<h2>Abstract Guidelines & Criteria</h2>
<ol>
  <li><strong>Text Formatting</strong><br>
      <em>Title:</em> Must be in title case format.<br>
      <em>Genus and Species Names:</em> All genus and species names should be capitalized and italicized appropriately.<br>
      <em>Spacing:</em> Ensure there are no extra spaces at the beginning of the title or abstract.</li>
  <li><strong>Abstract Inclusions</strong><br>
      The abstract must be a single paragraph with no headings. Include minimal-to-no citations.</li>
  <li><strong>Spelling &amp; Punctuation</strong><br>
      Ensure there are no spelling or punctuation mistakes. Acronyms must be defined after their first use.</li>
  <li><strong>Present or Past Tense</strong><br>
      Use present or past tense in the Methods section. Avoid “will be” statements (e.g., “I will be conducting…”) in the Background and Methodology.</li>
  <li><strong>Role in Research</strong><br>
      Use active voice (e.g., “I conducted analyses” rather than “Analyses were run”). Make explicit your personal contributions to the project.</li>
  <li><strong>Context or Purpose</strong><br>
      Provide a clear statement of purpose that includes the background or context of the project.</li>
  <li><strong>Questions/Hypotheses</strong><br>
      Clearly state your project’s research question, hypothesis, or goal.</li>
  <li><strong>Methodology/Approach</strong><br>
      Describe your methodology including measurements, tools, and, if applicable, participant demographics.</li>
  <li><strong>Expected/Preliminary Findings</strong><br>
      If your project is in progress, indicate your anticipated or preliminary findings.</li>
  <li><strong>Implications</strong><br>
      Explain why these findings matter: the impact on the field, implications for future work, or why the research is significant.</li>
</ol>

<h2>Writing Your Abstract</h2>
<p>
<strong>Your Task:</strong> Using the “And, But, Therefore” framework and the criteria listed above, draft a single‑paragraph abstract (300 words or less) for your research project. Remember to:
</p>
<ul>
  <li>Start with a background statement,</li>
  <li>Introduce the research gap,</li>
  <li>And then state your research purpose or action.</li>
</ul>
<p>
<strong>Example Structure:</strong><br>
“CO₂ is increasing in the atmosphere AND leads to ocean acidification BUT little is known about species’ capacity to evolve in response to pH stress. THEREFORE, we conducted this study to [state your research objective].”
</p>

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
    
    // Build abstract without auto‑inserting punctuation.
    let plainAbstract = title + "\n\n" + andText + " " + butText + " " + researchQuestion + " " + thereforeText + " " + methodology + " " + findings + " " + implications + " " + role;
    plainAbstract = plainAbstract.replace(/\s+/g, ' ').trim();
    
    // Build highlighted abstract with spans for each segment.
    let highlightedAbstract = title + "<br><br>";
    highlightedAbstract += "<span class='segment and-seg' title='Background/Context'>" + andText + "</span> ";
    highlightedAbstract += "<span class='segment but-seg' title='Research Gap'>" + butText + "</span> ";
    highlightedAbstract += "<span class='segment rq-seg' title='Research Question/Hypotheses'>" + researchQuestion + "</span> ";
    highlightedAbstract += "<span class='segment therefore-seg' title='Research Objective'>" + thereforeText + "</span> ";
    highlightedAbstract += "<span class='segment methodology-seg' title='Methodology/Approach'>" + methodology + "</span> ";
    highlightedAbstract += "<span class='segment findings-seg' title='Expected/Preliminary Findings'>" + findings + "</span> ";
    highlightedAbstract += "<span class='segment implications-seg' title='Implications'>" + implications + "</span> ";
    highlightedAbstract += "<span class='segment role-seg' title='Role in Research'>" + role + "</span>";
    
    let finalAbstract, finalOutput;
    if (highlightEnabled) {
      finalAbstract = highlightedAbstract;
      finalOutput = finalAbstract;
    } else {
      finalAbstract = plainAbstract;
      finalOutput = finalAbstract.replace(/\n/g, '<br>');
    }
    
    const wordCount = plainAbstract.split(/\s+/).length;
    
    document.getElementById('output').innerHTML = "<strong>Final Abstract (editable):</strong><br>" + finalOutput;
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
