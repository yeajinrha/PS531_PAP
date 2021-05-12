---
title: Final Project Template for PS 531: A Pre-Analysis Plan
author: Jake Bowers
date: Spring 2021
output:
  pdf_document:
    number_sections: true
    fig_caption: yes
    latex_engine: xelatex
    citation_package: biblatex
    keep_tex: true
    fig_height: 8
    fig_width: 8
graphics: yes
geometry: "left=1.25in,right=1.25in,top=1in,bottom=1in"
mainfont: "Helvetica"
fontsize: 10pt
bibliography: classbib.bib
biblio-style: authoryear-comp

---

This is a rough sketch of a template for the final paper project for PS 531. If you want to write some other kind of paper, you must talk with me and provide a template of your own before writing.

The task before you is to write a very complete pre-analysis plan for a paper that you are working on. I have built the guide below based on the [EGAP Guide to Pre-analysis Plans](https://egap.org/resource/10-things-to-know-about-pre-analysis-plans/).

Each question should be answered in order. The answers should not go beyond the length specified unless you have a prior arrangement with the instructor.

You should follow the advice in the Final Paper Guide in regards style and writing. I will grade the paper using this template (each step receives some points) and also using the following rubric (each criteria also receives some points):

 - Writing

    Can I read your writing? Is your paper written clearly? [I agree
    with @howardsbecker1986a’s analysis of the evils of passive voice
    and the literature review.]

- Final Paper Guide

    Did you follow the [Final Paper
    Guide](https://github.com/bowers-grad-stats-illinois/531-syllabus/finalpaperguide.md)?
    That is, did you write your final paper as if you had read and paid
    attention to that guide. In order to help you with this, I also wrote 

## The detailed paper outline/template

1. Describe a substantive question in social science. What theory are you
   assessing? Why should anyone care? (2 paragraphs)

2. The study you propose involves learning about a theory by observing certain
   of its implications. What one or two hypotheses that arise from the theory
   are you planning to assess? Why or how does the theory justify your
   expectations about these hypotheses? (1 or 2 paragraphs)

3. What data and research design will help you answer this question? Why are
   you making these choices? (Remember that a statistical model is not a
   research design.) (2 paragraphs)

4. What are the advantages and disadvantages of this research design to
   addressing your question? (2 paragraphs discussing **both** advantages and
   disadvantages of the research design; could be 1 paragraph for advantages
   and 1 for disadvantages or combined discussion across 2 paragraphs.)

5. Describe your measures and any indices you construct. (1 paragraph)

6. Use data to make the case that your research design allows you to interpret
   observed quantities (like observed data comparisons or parameters of models
   fit to data) as theoretically relevant and clear: (Most people will only
   have to do either 6.1 and 6.2 **or** 6.3 and 6.4 here depending on whether
   you have a randomized design or an observational design).

   1. **If you are using an observational study design** then explain how you
      will make the case for interpretable comparisons (this is the same as
      question as 'What is your identification strategy?'). That is, explain
      how you will use statistical adjustment  (like matching or covariance
      adjustment aka "controlling for") to persuade yourself and others that
      the comparison that you are showing reflects what you say it does. If you
      are making comparative or causal inference, I assume you will explain the
      natural or quasi-experimental design and approach you will be using here.
      "I controlled for a lot of background variables in a linear model." will
      not be acceptable here. If you are making population inferences, you
      should explain your approach as well. (2 paragraphs plus some tables or
      figures)

   2. **If you are using an observational study design**, explain how you will
      judge the success of your adjustment strategy. For example, you may
      explain here about balance tests and other diagnostics that refer to the
      problem of adjustment for confounding or making the case for an
      as-if-randomized comparison, or an as-if-randomly sampled set of
      observations, etc.. (1 paragraph)

   3. **If you are using an randomized study design**, explain how the experiment
      will help you make the case for interpretable comparisons. What counter
      arguments and/or weaknesses of your approach might you expect? (For
      example, how will you think about Hawthorne effects or alternative
      explanations of your results arising from crticisms of your measurement
      and conceptualization strategy or missing data problems.) (1 paragraph)

   4. **If you are using a randomized study design**, explain how you will know
      that your randomization and/or other aspects of your design turned out as
      they should (for example, you might explain about randomization tests
      here). (1 paragraph)

7. Explain your plans for any missing data or extreme outcome or covariate
   values you may encounter when you get the real data (or perhaps you have the
   background data but not the real outcomes, so you can explain your plans for
   such data issues in that case here too). (1 or 2 paragraphs)

7. What statistical tests do you plan to use? Explain why you chose these tests
   and any decision making criteria you will use upon seeing the results of the
   tests. You should also engage with the problem of multiple testing here if
   you are going to show the results of more than one test. (Recall that
   confidence intervals and hypothesis tests convey more or less the same
   information. So a confidence interval is a form of testing.) (1 paragraph)

8. Explain how you will judge the performance of those tests. Will you only use
   simple false positive rate and power? Or do you need to add family-wise
   error rate? false discovery rate?  Or something else? Explain why you made
   this choice. (1 paragraph)

9. Show and explain how your test performs in regards those properties (at
   least you will show false positive rate and power). (2--4 paragraphs)

10. What statistical estimators do you plan to use? Explain why you chose these
    estimators. Especially explain what is your target of estimation --- what
    is the estimand? (1 paragraph)

11. Explain how you will judge the performance of those estimators (especially
    bias and MSE)? (1 paragraph)

12. Show and explain how your estimator performs in regards those properties
    (at least bias and MSE).  (2--4 paragraphs)

13. Make one mock figure or table of the kind you plan to make when you use the
    actual outcome. Interpret the results of the mock analysis as if it were
    the real analysis. Saying something like, "If the real outcome were as I
    have simulated it, then the following table/figure would mean such and so
    about the theory." (1 paragraph)

14. Include a code appendix and a link to the github repository for this paper.

15. Include references with appropriate in-text citations.
