---
layout: default
title: "Abstract Writing Exercise: Crafting Your Research Narrative"
---

<!-- Interactive Abstract Generator Form -->
<form id="abstractForm">
  <!-- TITLE FIELD -->
  <label for="title">
    Title (in Title Case): 
    <span class="learnMore" onclick="toggleExample('exampleTitle')">Learn More</span>
  </label>
  <div id="exampleTitle" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      <span title="Title must be in title case.">Are Whooping Cranes Destined for Extinction? Climate Change Imperils Recruitment and Population Growth</span>
      (Butler, M., Metzger, K., &amp; Harris, G., 2017)
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      <span title="Title must be in title case.">Feeding Preferences and the Effect of Temperature on Feeding Rates of the Graceful Kelp Crab, Pugettia gracilis</span>
      (Johnson, K. H., Dobkowski, K. A., Seroy, S. K., Fox, S., &amp; Meenan, N., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 3:</strong> 
      <span title="Title must be in title case.">Timing Is Everything: The Effect of Tidal Timing on Biodiversity During Heatwaves</span>
      (Sanfilippo, J., Guthery, H., Pop, J., &amp; Eklund, B., 2023)
      <!-- No DOI provided for this one -->
    </p>
  </div>
  <input type="text" id="title" name="title" placeholder="Enter your title" required>
  
  <!-- BACKGROUND/CONTEXT FIELD -->
  <label for="and">
    Background/Context: 
    <span class="learnMore" onclick="toggleExample('exampleBackground')">Learn More</span>
  </label>
  <div id="exampleBackground" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      “Identifying climatic drivers of an animal population's vital rates and locating where they operate steers conservation efforts to optimize species recovery.”
      (Butler et al., 2017)
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      “Graceful kelp crabs (Pugettia gracilis) are abundant consumers in shallow subtidal ecosystems of the Salish Sea. These dynamic habitats are currently experiencing multiple changes including invasion by non-native seaweeds and ocean warming.”
      (Johnson et al., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="and" name="and" placeholder="e.g., CO₂ is increasing in the atmosphere" required></textarea>
  
  <!-- RESEARCH GAP FIELD -->
  <label for="but">
    Research Gap: 
    <span class="learnMore" onclick="toggleExample('exampleGap')">Learn More</span>
  </label>
  <div id="exampleGap" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      “However, little is known about P. gracilis’ foraging ecology.”
      (Johnson et al., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      “The anthomedusa Sarsia tubulosa has long been considered a ‘variable’ species, yet recent observations reveal the existence of at least three species.”
      (Miller, R., 1982)
      <a href="https://doi.org/10.1016/0022-0981(82)90089-2" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="but" name="but" placeholder="e.g., leads to ocean acidification, but little is known about species' capacity to evolve in response to pH stress" required></textarea>
  
  <!-- RESEARCH OBJECTIVE FIELD -->
  <label for="therefore">
    Research Objective: 
    <span class="learnMore" onclick="toggleExample('exampleObjective')">Learn More</span>
  </label>
  <div id="exampleObjective" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      “Therefore, we identify climatic drivers of whooping crane recruitment throughout the species’ life cycle.”
      (Butler et al., 2017)
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      “Therefore, we investigated their feeding preferences between native and invasive food sources, as well as feeding rates at elevated temperatures.”
      (Johnson et al., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 3:</strong> 
      “Here, we present a brief observational account of the first‐known record of brooding, development, and hatching of fertilized eggs for O. californicus.”
      (Khen et al., 2022)
      <a href="https://doi.org/10.1002/ece3.9481" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="therefore" name="therefore" placeholder="e.g., we conducted this study to assess..." required></textarea>
  
  <!-- RESEARCH QUESTION/HYPOTHESES FIELD -->
  <label for="researchQuestion">
    Research Question/Hypotheses: 
    <span class="learnMore" onclick="toggleExample('exampleQuestion')">Learn More</span>
  </label>
  <div id="exampleQuestion" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      “What are the feeding preferences of P. gracilis and how do elevated temperatures affect their feeding rates?”
      (Johnson et al., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      “How does tidal timing during heatwaves affect biodiversity in tidepool communities?”
      (Sanfilippo et al., 2023)
      <!-- No DOI provided -->
    </p>
    <p>
      <strong>Example 3:</strong> 
      “Do deep-sea cephalopods exhibit reproductive aggregations and what role might sexual cannibalism play?”
      (Vecchione, M., 2019)
      <a href="https://doi.org/10.3389/fmars.2019.00403" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="researchQuestion" name="researchQuestion" placeholder="State your research question, hypothesis, or goal" required></textarea>
  
  <!-- METHODOLOGY/APPROACH FIELD -->
  <label for="methodology">
    Methodology/Approach (Use present or past tense; avoid “will be”): 
    <span class="learnMore" onclick="toggleExample('exampleMethodology')">Learn More</span>
  </label>
  <div id="exampleMethodology" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      “We collected P. gracilis from San Juan Island, WA and conducted no‐choice and choice experiments with two food sources.”
      (Johnson et al., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      “We examined how eight tidepools at Friday Harbor Labs were impacted by a four‑day heating event.”
      (Sanfilippo et al., 2023)
      <!-- Link if available -->
    </p>
    <p>
      <strong>Example 3:</strong> 
      “A series of morphological and behavioral observations, coupled with an extensive program of hybridization testing.”
      (Miller, R., 1982)
      <a href="https://doi.org/10.1016/0022-0981(82)90089-2" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="methodology" name="methodology" placeholder="Describe your methodology, measurements, tools, and participant demographics (if applicable)" required></textarea>
  
  <!-- EXPECTED/PRELIMINARY FINDINGS FIELD -->
  <label for="findings">
    Expected/Preliminary Findings: 
    <span class="learnMore" onclick="toggleExample('exampleFindings')">Learn More</span>
  </label>
  <div id="exampleFindings" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      “In no‐choice experiments, P. gracilis ate equal amounts of native kelp and invasive seaweed; in choice experiments, P. gracilis preferred native kelp. Crabs exposed to elevated temperatures ate significantly more.”
      (Johnson et al., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      “Biodiversity did not change significantly over time in tidepools that remained submerged during the heatwave.”
      (Sanfilippo et al., 2023)
    </p>
    <p>
      <strong>Example 3:</strong> 
      “The incubation time was a maximum of 10 months at 8–10°C and embryos hatched over a period of 2.5 months.”
      (Khen et al., 2022)
      <a href="https://doi.org/10.1002/ece3.9481" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="findings" name="findings" placeholder="State your anticipated or preliminary findings" required></textarea>
  
  <!-- IMPLICATIONS FIELD -->
  <label for="implications">
    Implications: 
    <span class="learnMore" onclick="toggleExample('exampleImplications')">Learn More</span>
  </label>
  <div id="exampleImplications" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #007BFF; padding-left: 10px;">
    <p>
      <strong>Example 1:</strong> 
      “We predicted whooping crane recruitment and population growth may fall below long‐term averages under increased CO₂, indicating that species recovery may require eight times longer.”
      (Butler et al., 2017)
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 2:</strong> 
      “Warming ocean temperatures may prompt P. gracilis to increase feeding, exacerbating harmful impacts on native kelp.”
      (Johnson et al., 2023)
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      <strong>Example 3:</strong> 
      “These observations may indicate a deep-sea spawning aggregation and potentially sexual cannibalism, offering insights into cephalopod reproduction.”
      (Vecchione, M., 2019)
      <a href="https://doi.org/10.3389/fmars.2019.00403" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="implications" name="implications" placeholder="Explain the significance and impact of your findings" required></textarea>
  
  <br>
  <button type="button" onclick="generateAbstract()">Generate Abstract</button>
  <button type="button" onclick="toggleHighlight()">Toggle Segment Highlighting</button>
  <button type="button" onclick="copyToClipboard()">Copy to Clipboard</button>
</form>

<div id="output" class="output" contenteditable="true"></div>
<div id="wordCount" class="output"></div>
<div id="warning" class="warning"></div>

<!-- Additional Instructions and Guidelines Below the Generator -->
<h2>Story Structure: And, But, Therefore</h2>
<p>
When drafting your abstract, use the following structure to present your research clearly and logically:
</p>
<ul>
  <li><strong>And:</strong> State an established fact or background information.
    <br><em>Example:</em> “CO₂ is increasing in the atmosphere AND leads to ocean acidification…”</li>
  <li><strong>But:</strong> Introduce the problem or gap in knowledge.
    <br><em>Example:</em> “…BUT little is known about species’ capacity to evolve in response to pH stress.”</li>
  <li><strong>Therefore:</strong> State your research purpose, objective, or action taken.
    <br><em>Example:</em> “THEREFORE, we conducted this study to determine…”</li>
</ul>
<p>
Use this structure as a guide to create a compelling narrative that logically connects your background, problem, and research objectives.
</p>

<h2>Abstract Guidelines & Criteria</h2>
<ol>
  <li><strong>Text Formatting</strong>
    <br><em>Title:</em> Must be in title case format.
    <br><em>Genus and Species Names:</em> All genus and species names should be capitalized and italicized appropriately.
    <br><em>Spacing:</em> Ensure there are no extra spaces at the beginning of the title or abstract.
  </li>
  <li><strong>Abstract Inclusions</strong>
    <br>The abstract must be a single paragraph with no headings. Include minimal-to-no citations.
  </li>
  <li><strong>Spelling &amp; Punctuation</strong>
    <br>Ensure there are no spelling or punctuation mistakes. Acronyms must be defined after their first use.
  </li>
  <li><strong>Present or Past Tense</strong>
    <br>Use present or past tense in the Methods section. Avoid “will be” statements in the Background and Methodology.
  </li>
  <li><strong>Context or Purpose</strong>
    <br>Provide a clear statement of purpose that includes the background or context of the project.
  </li>
  <li><strong>Questions/Hypotheses</strong>
    <br>Clearly state your project’s research question, hypothesis, or goal.
  </li>
  <li><strong>Methodology/Approach</strong>
    <br>Describe your methodology including measurements, tools, and, if applicable, participant demographics.
  </li>
  <li><strong>Expected/Preliminary Findings</strong>
    <br>If your project is in progress, indicate your anticipated or preliminary findings.
  </li>
  <li><strong>Implications</strong>
    <br>Explain why these findings matter: the impact on the field, implications for future work, or why the research is significant.
  </li>
  <li><strong>Length:</strong>
    <br>The abstract is 300 words or less.
  </li>
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
  // Toggle the display of an example block by ID.
  function toggleExample(id) {
    const el = document.getElementById(id);
    if (el.style.display === "none" || el.style.display === "") {
      el.style.display = "block";
    } else {
      el.style.display = "none";
    }
  }
  
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
    
    let warnings = "";
    if (!isTitleCase(title)) {
      warnings += "Warning: Title is not in title case.\n";
    }
    
    // Build abstract without auto‑inserting punctuation.
    let plainAbstract = title + "\n\n" + andText + " " + butText + " " + researchQuestion + " " + thereforeText + " " + methodology + " " + findings + " " + implications;
    plainAbstract = plainAbstract.replace(/\s+/g, ' ').trim();
    
    // Build highlighted abstract with spans for each segment.
    let highlightedAbstract = title + "<br><br>";
    highlightedAbstract += "<span class='segment and-seg' title='Background/Context'>" + andText + "</span> ";
    highlightedAbstract += "<span class='segment but-seg' title='Research Gap'>" + butText + "</span> ";
    highlightedAbstract += "<span class='segment rq-seg' title='Research Question/Hypotheses'>" + researchQuestion + "</span> ";
    highlightedAbstract += "<span class='segment therefore-seg' title='Research Objective'>" + thereforeText + "</span> ";
    highlightedAbstract += "<span class='segment methodology-seg' title='Methodology/Approach'>" + methodology + "</span> ";
    highlightedAbstract += "<span class='segment findings-seg' title='Expected/Preliminary Findings'>" + findings + "</span> ";
    highlightedAbstract += "<span class='segment implications-seg' title='Implications'>" + implications + "</span>";
    
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
