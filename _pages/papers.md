---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true
---

<section class="page__content" itemprop="text">
<hr>
<h2 id="working-papers">Working Papers</h2>
<ul><li><a href="http://samzl1.github.io/files/Liang_s_JMP_arxiv.pdf" style="text-decoration:none" target="_blank">Unconditional Randomization Tests for Interference</a>   

<br> <a href="#/" style="color:black" onclick="visib('jmp')"><em>Abstract</em></a> | <em>Job Market Paper </em></li></ul>

<div id="jmp" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px"> In social networks or spatial experiments, one unit's outcome often depends on another's treatment, a phenomenon called interference. Researchers are interested in not only the presence and magnitude of interference but also its pattern based on factors like distance, neighboring units, and connection strength. However, the non-random nature of these factors and complex correlations across units pose challenges for inference. This paper introduces the partial null randomization tests (PNRT) framework to address these issues. The proposed method is finite-sample valid and applicable with minimal network structure assumptions, utilizing randomization testing and pairwise comparisons. Unlike existing conditional randomization tests, PNRT avoids the need for conditioning events, making it more straightforward to implement. Simulations demonstrate the method's desirable power properties and its applicability to general interference scenarios.</div>


<ul><li><a href="https://arxiv.org/abs/2304.14386" style="text-decoration:none" target="_blank">Convexity Not Required: Estimation of Smooth Moment Condition Models</a> (with <a href="http://jjforneron.com/" style="color: inherit; text-decoration-style: dotted" target="_blank">Jean-Jacques Forneron</a>) 

<br> <a href="#/" style="color:black" onclick="visib('gauss')"><em>Abstract</em></a> | <em>Revise & Resubmit, Review of Economic Studies </em></li></ul>

<div id="gauss" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px"> Generalized and Simulated Method of Moments are often used to estimate
 structural Economic models. Yet, it is commonly reported that optimization
 is challenging because the corresponding objective function is non-convex. For
 smooth problems, this paper shows that convexity is not required: under a global
 rank condition involving the Jacobian of the sample moments, certain algorithms
 are globally convergent. These include a gradient-descent and a Gauss-Newton
 algorithm with appropriate choice of tuning parameters. The results are robust to
 1) non-convexity, 2) one-to-one non-linear reparameterizations, and 3) moderate
 misspecification. In contrast, Newton-Raphson and quasi-Newton methods can
 fail to converge because of non-convexity. The condition precludes non-global op
tima. Numerical and empirical examples illustrate the condition, non-convexity,
 and convergence properties of different optimizers.</div>


<ul><li><a href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4430334" style="text-decoration:none" target="_blank">COPPAcalypse? The Youtube Settlement's Impact on Kids Content</a> (with <a href="https://www.garjoh.com/" style="color: inherit; text-decoration-style: dotted" target="_blank">Garrett Johnson</a>, <a href="https://tesarylin.github.io/" style="color: inherit; text-decoration-style: dotted" target="_blank">Tesary Lin</a>, and <a href="https://scholar.google.com/citations?user=nYEyFMYAAAAJ" style="color: inherit; text-decoration-style: dotted" target="_blank">James Cooper</a>) 

<br> <a href="#/" style="color:black" onclick="visib('coppa')"><em>Abstract</em></a> | <em>Revise & Resubmit, Management Science</em> </li></ul>

<div id="coppa" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px"> We examine the tradeoff between privacy and personalization for online content by evaluating the impact of YouTube's settlement with the Federal Trade Commission over violating the Children's Online Privacy Protection Act (COPPA). Under the settlement, YouTube removed all forms of personalization for child-directed content starting in January 2020, which included personalized ads and platform features like personalized search and recommendations. We study the resulting impact on 5,066 top American YouTube channels by comparing the child-directed content creators to their non-child-directed counterparts using a difference-in-differences design. On the supply side, we find that child-directed content creators produce 18% less content and pivot towards producing non-child-directed content. Child-directed content creators also invest less in content quality: the proportion of original content falls by 11% and manual captioning falls by 27%, while user content ratings fall by 10%. On the demand side, views of child-directed channels fall by 20%. Consistent with the platform's degraded capacity to match viewers to content, both content creation and content views become more concentrated among top child-directed YouTube channels.</div>


<ul><li><a href="https://www.nber.org/papers/w33186?utm_campaign=ntwh&utm_medium=email&utm_source=ntwg25" style="text-decoration:none" target="_blank">Racial Screening on the Big Screen: Evidence from the Motion Picture Industry</a> (with <a href="https://angela-crema.com/" style="color: inherit; text-decoration-style: dotted"  target="_blank">Angela Crema</a> and <a href="https://sites.google.com/view/paserman/home" style="color: inherit; text-decoration-style: dotted"  target="_blank">M. Daniele Paserman</a>) 

<br> <a href="#/" style="color:black" onclick="visib('movie')"><em>Abstract</em></a> | <em>NBER Working Paper No.33186</em> </li></ul>

<div id="movie" style="display: none; background-color: #F1F1F1; color: #666; padding: 10px"> We develop a model of discrimination that allows us to interpret observed differences in outcomes across groups, conditional on passing a screening test, as taste-based (employer,) statistical, or customer discrimination. We apply this framework to investigate the nature of non-white underrepresentation in the US motion picture industry. Leveraging a novel data set with racial identifiers for the cast of 7,000 motion pictures, we show that, conditional on production, non-white movies exhibit higher average revenues and a smaller variance. Our findings can be rationalized in the context of our model if non-white movies are held to higher standards for production.</div>



<h2 id="works-in-progress">Selected Work in Progress</h2>


<ul><li><p>Contextual Bandit Mechanism: Optimal Delegation in the Experimentation Cycle (with Zixian Liu)</p> </li></ul>

<script>
function visib(id) {
  var x = document.getElementById(id);
  if (x.style.display === "none") {
    x.style.display = "block";
  } else {
    x.style.display = "none";
  }
}
</script>
</section>