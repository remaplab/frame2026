---
title: Call for Contributions
layout: page
permalink: /cfp/
intro_image_absolute: false
intro_image_hide_on_mobile: false
---

<style>
.track-tabs {
  display: flex;
  gap: 0;
  margin-bottom: 30px;
  border-bottom: 1px solid #e0e0e0;
}

.track-tab {
  background-color: transparent;
  border: none;
  border-bottom: 3px solid transparent;
  padding: 12px 20px;
  cursor: pointer;
  font-weight: 500;
  transition: all 0.3s ease;
  font-size: 25px;
  color: #666;
  font-family: 'Playfair Display', serif;
}

.track-tab:hover {
  color: #333;
  border-bottom-color: #ddd;
  font-weight: 100;
}

.track-tab.active {
  color: #333;
  font-weight: bolder;
  border-bottom-color: #007bff;
}

.track-content {
  display: none;
}

.track-content.active {
  display: block;
}

.track-content {
  color: #666;
}

.track-content h2 {
  color: black;
  font-weight: normal;
  font-family: 'Playfair Display', serif;
}

.track-content h3 {
  color: black;
  font-weight: bolder;
}

.track-content ul,
.track-content ol,
.track-content li {
  margin-top: 1em;
  margin-bottom: 1em;
  line-height: inherit;
  padding-left: 1em;
  color: inherit;
  font-size: inherit;
}

.track-content a {
  color: #007bff;
  text-decoration: none;
}

.track-content a:hover {
  text-decoration: underline;
}
</style>

Recommender systems research is highly empirical, but many published claims remain difficult to interpret, compare, or generalize because evaluation practices vary substantially across papers. Choices concerning task definition, datasets, data partitioning, baselines, metrics, and statistical testing can all influence the conclusions of a study, yet the community still lacks broadly shared standards for experimental rigor and methodological reporting.
This workshop aims to create a venue for discussing and advancing stronger research assessment practices in recommender systems. In particular, we seek both to encourage more rigorous evaluation of algorithmic papers and to recognize experimental methodology itself as a contribution to the field.
The workshop features two tracks. The Research Papers track welcomes papers proposing new algorithms, models, or methods, and uses a methodology-first, results-blind review process. The Experimental Methodologies track welcomes submissions proposing, discussing, or critiquing evaluation methodologies, protocol designs, and methodological standards, with the goal of supporting discussion during the workshop and informing longer-term community efforts.

<h3>Important Dates</h3>
<ul>
<li>Paper submission deadline: July 20, 2026</li>
<li>Author notification: August 14, 2026</li>
</ul>

<div class="track-tabs">
  <button class="track-tab active" onclick="switchTrack(event, 'track1')">Track 1: Research Papers</button>
  <button class="track-tab" onclick="switchTrack(event, 'track2')">Track 2: Experimental Methodologies</button>
</div>

<div id="track1" class="track-content active">

<h2 style="margin-top: 0;"><strong>Track 1: Research Papers</strong></h2>
This track is intended for regular research papers, with a particular emphasis on experimental rigor. 
We welcome submissions that introduce new recommendation methods, industry-meaningful variants, new formulations of recommendation problems, as well as papers presenting modifications to existing algorithms, provided that the contribution is technically sound, well-motivated, and evaluated through an appropriate and well-documented experimental methodology.
Papers should either present genuine novelty, even if they do not necessarily outperform the current state-of-the-art, or, if the contribution is more incremental, they must show improvement over existing methods. In all cases, the strength of the evaluation design is essential.
Because the workshop focuses on experimental rigor, submissions to the Research Papers track should:
<ul>
<li>clearly specify the target task and the underlying problem assumptions;</li>
<li>motivate the choice of datasets and any preprocessing decisions, the data partitioning strategy, the measures taken to avoid leakage, the choice of baselines and why they are appropriate;</li>
<li>provide a detailed description of the hyperparameter optimization process, and the evaluation metrics adopted.</li>
</ul>
Submissions are also encouraged to report statistical testing, confidence intervals, or other uncertainty estimates when applicable, and include ablations, sensitivity analyses, or robustness checks when relevant. 
<h3>Review Process for Research Papers</h3>
Research papers will be peer-reviewed by members of the program committee in two stages using a methodology-first, results-agnostic reviewing process.
At the first stage, reviewers will evaluate the paper’s technical and theoretical soundness, and the evaluation methodology, without taking into account the study results. Reviewers will assess whether the proposed method constitutes a well-motivated contribution, whether its design choices are adequately justified, and whether the experimental methodology is described in detail and it is appropriate to support the claims of the paper. Reviewers will also assess the completeness and quality of artifacts like source code and datasets. Submissions lacking a rigorous evaluation framework or presenting artifacts that are not aligned with the stated evaluation methodology will be rejected during this review phase.
At the second stage, the manuscripts that passed the first stage will be reviewed. At this stage, reviewers will consider the reported results, their interpretation, and the reproducibility of the work, primarily as a consistency and completeness check. Papers that successfully pass the first-stage methodological review are expected to be accepted in most cases, provided that the full manuscript is consistent with the reviewed methodology and does not reveal major issues. The final decision will therefore not depend on whether the results are positive or outperform a baseline. Negative results, failed hypotheses, or outcomes that do not improve over existing methods will not constitute grounds for rejection, as long as the problem addressed is important, the proposed method is technically sound and well-motivated, and the evaluation methodology is rigorous and informative. Conversely, papers reporting positive results obtained with a methodology that is not deemed reliable enough will be rejected in the first phase without the reviewers ever having access to the results.
Authors of Research Papers are asked to submit two versions of their manuscript:
<ol>
<li><strong>Methodology version (restricted):</strong> This version must not report anything related to the results of the study. At this stage, manuscripts will be evaluated based on the importance of the problem addressed, the soundness of the proposed method, and the quality of the methodology. Manuscripts may include an introduction, related work, a description of the proposed methodology, the task definition, the datasets used, and the planned evaluation protocol, with all the relevant details. However, there should be no section reporting results or discussing outcomes. Authors should also remove any mention of results from the included sections, such as the abstract and introduction. Authors may use a note like "[result-blind]" to highlight that parts of the text have been removed to ensure this version is result-blind. Authors are also strongly encouraged to provide source code (including code for the baseline and code to partition datasets), datasets, configuration details, and any other reproducibility material.</li>
<li><strong>Experimental version (complete):</strong> The complete manuscript containing all sections of the paper, including results and their discussion.</li>
</ol>

Submissions to this track will be double-blind. Papers should be anonymous, and any code or supplementary material shared with reviewers should be provided through anonymous repositories whenever possible.
Submissions that are not anonymous as well as restricted versions that are not result-blind will be desk-rejected.

<h3>Submission Format</h3>
Research Papers should be submitted in PDF format via <a href="https://easychair.org/my/conference?conf=recsys2026workshops">EasyChair</a>.
The proceedings will be published on CEUR-WS, submissions should follow the CEUR-WS single-column format.
The length should be commensurate to the contribution, the page limit for the complete version is 8 pages + references.

<h3>Presentation</h3>
At least one author of each accepted Research Paper must attend the workshop and present the paper in person. Presentation is mandatory for acceptance in this track.

</div>

<div id="track2" class="track-content">

<h2 style="margin-top: 0;"><strong>Track 2: Experimental Methodologies</strong></h2>
The Experimental Methodologies track is intended for submissions that propose, discuss, critique, or systematize evaluation methodologies for algorithmic research papers on recommender systems. In addition to full papers, we also welcome shorter position statements that raise relevant methodological questions, identify gaps, or outline promising directions for discussion at the workshop. The goal of this track is to foster contributions that can help the community move toward more rigorous, transparent, and comparable empirical research practices.
In particular, we welcome submissions that aim to identify and motivate best practices that researchers can follow when designing and conducting an experimental study in recommender systems. We are especially interested in contributions that can serve as a useful methodological reference for future work, helping authors design experiments that are technically sound, clearly justified, and easier to compare across papers. We also welcome contributions that highlight missing resources (datasets, frameworks, etc.) for certain underexplored tasks.
Given the exploratory and community-building nature of this debate, submissions to this track may combine descriptive, critical, and normative elements. For example, a submission may define a methodological problem, analyse current practice in the literature, discuss its limitations, and propose one or more rigorous alternatives. Because this discussion is still at an initial stage, we also welcome survey-style contributions and papers that organize, compare, and distil existing methodological practices, and suggest directions for methodological standardization. 
We are interested both in widely studied recommendation tasks, such as top-N recommendation, sequential recommendation, and session-based recommendation, and in more challenging settings that are less well explored by the research community and are harder to evaluate consistently, such as tasks involving interest drift or other dynamic phenomena.
Overall, the goal is not to discuss point-wise methodological aspects, but rather to encourage broader contributions that can provide a complete description of best practices on how to conduct a comparative experiment for a specific task.

<h3>Examples of Relevant Contributions</h3>
As examples, we are particularly interested in submissions that discuss the following:
<ul>
<li>critical analysis of current practice, supported by a state-of-the-art study, including discussion of known methodological issues already raised in prior work;</li>
<li>proposal for an evaluation methodology tailored to a specific and relevant task, or a comparison and discussion of multiple possible methodological choices;</li>
<li>discussion of which datasets are suitable or unsuitable for a target problem, and which baselines should be considered the minimum reasonable set for comparison;</li>
<li>suggestions on how to improve comparability across papers adopting a given methodology or protocol;</li>
<li>methodological recommendations for hyperparameter optimization and model selection;</li>
<li>what should count as a fair comparison, for example in terms of computational budget, hyperparameter optimization effort, hardware resources, or number of optimization trials;</li>
<li>missing resources needed, such as frameworks, datasets, simulation tools etc.</li>
</ul>
These examples are intended to illustrate the kinds of contributions we consider interesting for this track. They should not be interpreted as a checklist or as mandatory components of every submission.
Accepted submissions in this track will be used to seed an interactive workshop session, structured as a moderated discussion among researchers from academia and industry who are actively engaged in recommender systems evaluation. The discussion will focus on identifying and refining candidate tasks, both established and emerging, where methodological questions remain open, and on outlining shared evaluation protocols.
Participation in this session will be primarily driven by accepted contributions, but depending on the number of submissions and overall interest, we aim to keep the workshop format flexible and inclusive. This may include opening participation to a broader audience and organizing additional activities such as panel discussions or themed breakout groups. The goal is to collaboratively define best practices, clarify key design choices (e.g., data assumptions, splitting strategies, baselines, metrics, and statistical analysis), and discuss how tasks and protocols can be treated as shared community infrastructure rather than paper-specific decisions.
We aim to encourage post-workshop outcomes based on the discussions and contributions. This may include a jointly authored report or perspective article summarizing key insights and recommendations. We also envision refining and integrating the proposed methodologies in future editions of the workshop as part of an ongoing community effort.

<h3>Review Process</h3>
This track will use a single-blind review process. Review will focus on clarity, relevance, discussion value, methodological insight, and the potential of the submission to support useful workshop exchange and longer-term community progress.
<h3>Participation Expectations</h3>
Authors of accepted Experimental Methodologies papers will be expected to actively contribute to the workshop discussion. In particular, accepted submissions are intended to inform and support the interactive session on candidate tasks, evaluation protocols, and methodological best practices. Depending on the final program design, participation may take the form of a short presentation, moderated discussion, or contribution to the longer-term community effort on task formalization and evaluation methodology.

<h3>Submission Format</h3>
Methodological Papers should be submitted in PDF format via <a href="https://easychair.org/my/conference?conf=recsys2026workshops">EasyChair</a>.
The proceedings will be published on CEUR-WS, submissions should follow the CEUR-WS single-column format.
The length should be commensurate to the contribution, the page limit is 8 pages + references.

</div>


<script>
function switchTrack(event, trackId) {
  // Hide all track contents
  const contents = document.querySelectorAll('.track-content');
  contents.forEach(content => {
    content.classList.remove('active');
  });
  
  // Remove active class from all tabs
  const tabs = document.querySelectorAll('.track-tab');
  tabs.forEach(tab => {
    tab.classList.remove('active');
  });
  
  // Show the selected track
  document.getElementById(trackId).classList.add('active');
  
  // Mark the clicked tab as active
  event.target.classList.add('active');
}
</script>

