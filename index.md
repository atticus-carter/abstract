---
layout: default
title: "Abstract Writing Exercise: Crafting Your Research Narrative"
---

<!-- Quick description at the top -->
<p>
  Welcome to the IBIS Abstract Writing Exercise website. This interactive tool guides you through the “And, But, Therefore” framework to help you craft your research abstract. Remember that an abstract:
</p>
<ul>
  <li>Helps readers decide whether to read the full manuscript.</li>
  <li>Must stand on its own.</li>
  <li>Summarizes key points of the research.</li>
  <li>Acts as a miniature version of your manuscript.</li>
</ul>

<!-- Interactive Abstract Generator Form -->
<form id="abstractForm">
  <!-- TITLE FIELD -->
  <label for="title">
    Title (in APA title case): 
    <span class="learnMore" onclick="toggleExample('exampleTitle')">examples and help</span>
  </label>
  <div id="exampleTitle" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      Your title is the hook. Ensure it follows APA title case rules.
      In APA title case – note that minor words such as 'and', 'for', 'of', etc. should be lowercase except when first
    </p>
    <p>
      “Are Whooping Cranes Destined for Extinction? Climate Change Imperils Recruitment and Population Growth”  
      (Butler, M., Metzger, K., &amp; Harris, G., 2017)  
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      “Feeding Preferences and the Effect of Temperature on Feeding Rates of the Graceful Kelp Crab, Pugettia gracilis”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “Timing Is Everything: The Effect of Tidal Timing on Biodiversity During Heatwaves”  
      (Sanfilippo et al., 2023)
    </p>
  </div>
  <input type="text" id="title" name="title" placeholder="Enter your title (the first word is your hook)" required>
  
  <!-- BACKGROUND/CONTEXT FIELD -->
  <label for="and">
    Background/Context: 
    <span class="learnMore" onclick="toggleExample('exampleBackground')">examples and help</span>
  </label>
  <div id="exampleBackground" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      This field should start with a hook. Although we suggest "And:" to introduce background information, feel free to use alternatives (e.g., "Additionally," "Furthermore,").
    </p>
    <p>
      “Identifying climatic drivers of an animal population's vital rates steers conservation efforts to optimize species recovery.”  
      (Butler et al., 2017)  
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      “Graceful kelp crabs (Pugettia gracilis) are abundant consumers in shallow subtidal ecosystems experiencing invasion by non-native seaweeds and ocean warming.”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “Fish communities inhabiting soft-sediment tidepools are representative conservation targets for coastal habitats.”  
      (Kunishima &amp; Tachihara, 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
    <p>
      “By ameliorating environmental conditions, foundation species underpin the structure and function of tidepool communities.”  
      (Shelton, 2010)  
      <a href="https://doi.org/10.1016/j.jembe.2010.06.003" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="and" name="and" placeholder="e.g., CO₂ is increasing in the atmosphere" required></textarea>
  
  <!-- RESEARCH GAP FIELD -->
  <label for="but">
    Research Gap:
    <span class="learnMore" onclick="toggleExample('exampleGap')">examples and help</span>
  </label>
  <div id="exampleGap" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      This field shows the gap in knowledge your research fills. You can start with "But:" or other similar cues.
    </p>
    <p>
      “However, little is known about P. gracilis’ foraging ecology.”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “The anthomedusa Sarsia tubulosa has long been considered a ‘variable’ species, yet recent observations reveal at least three species.”  
      (Miller, R., 1982)  
      <a href="https://doi.org/10.1016/0022-0981(82)90089-2" target="_blank">[Link]</a>
    </p>
    <p>
      “Although fish communities in soft-sediment tidepools are conservation targets, how ecological functions drive diversity remains unknown.”  
      (Kunishima &amp; Tachihara, 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
    <p>
      “Despite rapid lionfish invasion, genetic connectivity among MPAs is still unclear.”  
      (Guzmán‐Méndez et al., 2020)  
      <a href="https://doi.org/10.3389/fmars.2019.00403" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="but" name="but" placeholder="e.g., little is known about species' capacity to evolve in response to pH stress" required></textarea>
  
  <!-- RESEARCH OBJECTIVE FIELD -->
  <label for="therefore">
    Research Objective: 
    <span class="learnMore" onclick="toggleExample('exampleObjective')">examples and help</span>
  </label>
  <div id="exampleObjective" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      This field describes how you fill the research gap. Use a cue word like "Therefore:" (alternatives are acceptable). Sometimes it works well to write with the cue first, and delete it later to make it flow better! :)
    </p>
    <p>
      “We identify climatic drivers of whooping crane recruitment throughout the species’ life cycle.”  
      (Butler et al., 2017)  
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      “We investigated feeding preferences between native and invasive food sources, as well as feeding rates at elevated temperatures.”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “To examine the ecological functions of soft-sediment tidepools according to topographical types on Okinawa-jima Island.”  
      (Kunishima &amp; Tachihara, 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
    <p>
      “To assess how the removal of surfgrass affects the thermal environment and community structure in tidepools.”  
      (Shelton, 2010)  
      <a href="https://doi.org/10.1016/j.jembe.2010.06.003" target="_blank">[Link]</a>
    </p>
    <p>
      “To identify genetic connectivity among MPAs in the Gulf of Mexico and Caribbean Sea using microsatellite analysis.”  
      (Guzmán‐Méndez et al., 2020)  
      <a href="https://doi.org/10.3389/fmars.2019.00403" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="therefore" name="therefore" placeholder="e.g., we conducted this study to assess..." required></textarea>
  
  <!-- RESEARCH QUESTION/HYPOTHESES FIELD -->
  <label for="researchQuestion">
    Research Question/Hypotheses:
    <span class="learnMore" onclick="toggleExample('exampleQuestion')">examples and help</span>
  </label>
  <div id="exampleQuestion" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      Clearly state the question or hypothesis your study addresses.
    </p>
    <p>
      “What are the feeding preferences of P. gracilis and how do elevated temperatures affect their feeding rates?”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “How does tidal timing during heatwaves affect biodiversity in tidepool communities?”  
      (Sanfilippo et al., 2023)
    </p>
    <p>
      “What patterns in species composition characterize tidepool fish assemblages along a latitudinal gradient?”  
      (Castellanos-Galindo et al., 2014)  
      <a href="https://doi.org/10.15517/RBT.V62I0.16362" target="_blank">[Link]</a>
    </p>
    <p>
      “Are there differences in lipid content and fatty acid profiles between juvenile red squat lobster populations in distinct fishing areas?”  
      (Guzmán-Rivas et al., 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="researchQuestion" name="researchQuestion" placeholder="State your research question, hypothesis, or goal" required></textarea>
  
  <!-- METHODOLOGY/APPROACH FIELD -->
  <label for="methodology">
    Methodology/Approach:
    <span class="learnMore" onclick="toggleExample('exampleMethodology')">examples and help</span>
  </label>
  <div id="exampleMethodology" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      Describe the methods, measurements, tools, and sampling details. Be as specific as necessary. (Use present or past tense; avoid “will be”)
    </p>
    <p>
      “We collected P. gracilis from San Juan Island, WA and conducted no‑choice and choice experiments with two food sources.”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “We examined how eight tidepools at Friday Harbor Labs were impacted by a four‑day heating event.”  
      (Sanfilippo et al., 2023)
    </p>
    <p>
      “We measured the lipid content and fatty acid profiles of juvenile female red squat lobsters from two breeding areas.”  
      (Guzmán-Rivas et al., 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
    <p>
      “We analyzed 12 microsatellites from 475 lionfish samples to assess genetic connectivity among MPAs.”  
      (Guzmán‐Méndez et al., 2020)  
      <a href="https://doi.org/10.3389/fmars.2019.00403" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="methodology" name="methodology" placeholder="Describe your methodology, measurements, tools, and participant demographics (if applicable)" required></textarea>
  
  <!-- EXPECTED/PRELIMINARY FINDINGS FIELD -->
  <label for="findings">
    Expected/Preliminary Findings:
    <span class="learnMore" onclick="toggleExample('exampleFindings')">examples and help</span>
  </label>
  <div id="exampleFindings" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      Summarize your key results or anticipated outcomes.
    </p>
    <p>
      “In no‑choice experiments, P. gracilis ate equal amounts of native kelp and invasive seaweed; in choice experiments, they preferred native kelp. Crabs exposed to elevated temperatures ate significantly more.”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “Biodiversity did not change significantly over time in tidepools that remained submerged during the heatwave.”  
      (Sanfilippo et al., 2023)
    </p>
    <p>
      “We observed an inverse trend in α- and β-diversity between topographic types, shaped by habitat heterogeneity.”  
      (Kunishima &amp; Tachihara, 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
    <p>
      “Juvenile females from the southern fishing unit had a higher lipid content compared to those from the northern unit.”  
      (Guzmán-Rivas et al., 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="findings" name="findings" placeholder="State your anticipated or preliminary findings" required></textarea>
  
  <!-- IMPLICATIONS FIELD -->
  <label for="implications">
    Implications:
    <span class="learnMore" onclick="toggleExample('exampleImplications')">examples and help</span>
  </label>
  <div id="exampleImplications" class="example" style="display:none; margin:5px 0 10px 20px; border-left: 2px solid #9370DB; padding-left: 10px;">
    <p>
      Explain why your findings matter and what impact they might have.
    </p>
    <p>
      “We predicted whooping crane recruitment and population growth may fall below long‑term averages under increased CO₂, indicating that species recovery may require eight times longer.”  
      (Butler et al., 2017)  
      <a href="https://doi.org/10.1002/ece3.2892" target="_blank">[Link]</a>
    </p>
    <p>
      “Warming ocean temperatures may prompt P. gracilis to increase feeding, exacerbating harmful impacts on native kelp.”  
      (Johnson et al., 2023)  
      <a href="https://doi.org/10.7717/peerj.15223" target="_blank">[Link]</a>
    </p>
    <p>
      “These findings provide crucial insights into the bioenergetic health of lobster populations, informing fisheries management strategies.”  
      (Guzmán-Rivas et al., 2021)  
      <a href="https://doi.org/10.1016/j.marenvres.2021.105442" target="_blank">[Link]</a>
    </p>
    <p>
      “Limited genetic connectivity among MPAs suggests potential for localized control of invasive lionfish.”  
      (Guzmán‐Méndez et al., 2020)  
      <a href="https://doi.org/10.3389/fmars.2019.00403" target="_blank">[Link]</a>
    </p>
    <p>
      “Surfgrass plays a foundational role in tidepools by reducing pool temperatures and stabilizing community composition.”  
      (Shelton, 2010)  
      <a href="https://doi.org/10.1016/j.jembe.2010.06.003" target="_blank">[Link]</a>
    </p>
    <p>
      “Genetic connectivity data reveal that despite high dispersal potential, local genetic differentiation exists among lionfish populations.”  
      (Guzmán‐Méndez et al., 2020)  
      <a href="https://doi.org/10.3389/fmars.2019.00403" target="_blank">[Link]</a>
    </p>
  </div>
  <textarea id="implications" name="implications" placeholder="Explain the significance and impact of your findings" required></textarea>
  
  <br>
  <button type="button" onclick="generateAbstract()">Generate Abstract</button>
  <button type="button" onclick="toggleHighlight()">Toggle Segment Highlighting</button>
  <button type="button" onclick="copyToClipboard()">Copy to Clipboard</button>
  <p style="margin-top:10px; font-style: italic;">
    This is the time to stitch your sections together and get them to flow well. It is likely that you will need to merge some sections together—just ensure that you can still pick out the distinct parts afterward.
  </p>
</form>

<div id="output" class="output" contenteditable="true"></div>
<div id="wordCount" class="output"></div>
<div id="warning" class="warning"></div>

<!-- Additional Instructions and Guidelines Below the Generator -->
<h2>Story Structure: And, But, Therefore</h2>
<p>
  When drafting your abstract, use this framework to present your research clearly and logically. (Note: The first word in each segment is intended as a hook. While we suggest “And:”, “But:”, and “Therefore:”, you may use alternatives such as “Additionally,” “Yet,” “However,” “Thus,” etc.)
</p>
<ul>
  <li><strong>And:</strong> State an established fact or background information.
    <br><em>Example:</em> “CO₂ is increasing in the atmosphere and leads to ocean acidification…”</li>
  <li><strong>But:</strong> Introduce the problem or gap in knowledge.
    <br><em>Example:</em> “...but little is known about species’ capacity to evolve in response to pH stress.”</li>
  <li><strong>Therefore:</strong> State your research purpose, objective, or action taken.
    <br><em>Example:</em> “Therefore, we conducted this study to determine…”</li>
</ul>
<p>
  Use this structure as a guide to create a compelling narrative that connects your background, research gap, and objective.
</p>

<h2>Abstract Guidelines &amp; Criteria</h2>
<ol>
  <li><strong>Text Formatting</strong>
    <br><em>Title:</em> Must be in APA title case format.
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
  <strong>Your Task:</strong> Using the “And, But, Therefore” framework and the criteria above, draft a single‑paragraph abstract (300 words or less) for your research project. Remember to:
</p>
<ul>
  <li>Start with a background statement,</li>
  <li>Introduce the research gap,</li>
  <li>And then state your research purpose or action.</li>
</ul>
<p>
  <strong>Example Structure:</strong><br>
  “CO₂ is increasing in the atmosphere and leads to ocean acidification, but little is known about species’ capacity to evolve in response to pH stress. Therefore, we conducted this study to [state your research objective].”
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
  
  // Check title case per APA expectations.
  function isTitleCase(str) {
    const minorWords = ["and", "or", "for", "nor", "but", "a", "an", "the", "in", "on", "at", "by", "with", "as", "of", "yet", "so"];
    const words = str.split(' ');
    if (words.length === 0) return true;
    // First word must be capitalized.
    if (words[0][0] !== words[0][0].toUpperCase()) return false;
    // Check subsequent words.
    for (let i = 1; i < words.length; i++) {
      let word = words[i];
      // Remove punctuation from the word for checking.
      let cleanWord = word.replace(/[^a-zA-Z]/g, '').toLowerCase();
      if (minorWords.includes(cleanWord)) continue;
      if (word[0] !== word[0].toUpperCase()) return false;
    }
    return true;
  }
  
  let highlightEnabled = false;
  
  function generateAbstract() {
    const titleField = document.getElementById('title').value.trim();
    
    // For these fields, if the text doesn't already begin with the suggested cue (ignoring case), add it.
    let bgText = document.getElementById('and').value.trim();
    if (!bgText.toLowerCase().startsWith("and:")) {
      bgText = "And: " + bgText;
    }
    
    let gapText = document.getElementById('but').value.trim();
    // Allow flexibility: the user may use "but", "yet", "however", etc.
    if (!/^(but:|yet:|however:)/i.test(gapText)) {
      gapText = "But: " + gapText;
    }
    
    let objText = document.getElementById('therefore').value.trim();
    if (!objText.toLowerCase().startsWith("therefore:")) {
      objText = "Therefore: " + objText;
    }
    
    const rqText = document.getElementById('researchQuestion').value.trim();
    const methText = document.getElementById('methodology').value.trim();
    const findingsText = document.getElementById('findings').value.trim();
    const implText = document.getElementById('implications').value.trim();
    
    let warnings = "";
    if (!isTitleCase(titleField)) {
      warnings += "Warning: Title is not in APA title case.\n";
    }
    
    // Build the final abstract by concatenating the fields.
    let plainAbstract = titleField + "\n\n" + bgText + " " + gapText + " " + rqText + " " + objText + " " + methText + " " + findingsText + " " + implText;
    plainAbstract = plainAbstract.replace(/\s+/g, ' ').trim();
    
    // Build a highlighted version.
    let highlightedAbstract = titleField + "<br><br>";
    highlightedAbstract += "<span class='segment and-seg' title='Background/Context'>" + bgText + "</span> ";
    highlightedAbstract += "<span class='segment but-seg' title='Research Gap'>" + gapText + "</span> ";
    highlightedAbstract += "<span class='segment rq-seg' title='Research Question/Hypotheses'>" + rqText + "</span> ";
    highlightedAbstract += "<span class='segment therefore-seg' title='Research Objective'>" + objText + "</span> ";
    highlightedAbstract += "<span class='segment methodology-seg' title='Methodology/Approach'>" + methText + "</span> ";
    highlightedAbstract += "<span class='segment findings-seg' title='Expected/Preliminary Findings'>" + findingsText + "</span> ";
    highlightedAbstract += "<span class='segment implications-seg' title='Implications'>" + implText + "</span>";
    
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
