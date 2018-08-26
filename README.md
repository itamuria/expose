# expose
 Introduction: 
 
Although the general population is exposed to multiple chemicals, most environmental epidemiology studies consider each chemical separately when estimating the adverse effects of environmental exposures, partly because of the lack of software accessible to environmental epidemiologists. 

Objective: 

We developed a statistical R package, accessible to environmental health scientists that can provide valid estimates for effects of environmental contaminants, dose-response relationships, and interactions in a multi-pollutant setting. 

Methods: 

This package implements the work of Oulhote et al (2017) that combines the G-formula, a maximum likelihood estimator, with the ensemble learning technique Super Learner. It incorporates a wide range of statistical techniques (e.g. generalized linear and additive models, random forest, extreme gradient boosting) to estimate and provide valid inference in multi-pollutant settings and reconstruct dose-response relationships non-parametrically. 

Results: 

This package will facilitate multi-pollutant analysis of environmental epidemiology. We also developed a user-friendly Shiny application that can be used by biomedical researchers modeling complex mixtures. We ran multiple simulations based on real scenarios and the proposed method yielded promising results across all the scenarios. Our approach was also able to estimate the true underlying structure of the data. We will present a tutorial describing the package functions and visualizations to illustrate our developed methods. 

Conclusion: 

This package will help to unravel the effects of chemical mixtures and their interactions in epidemiological studies. 


Youssef Oulhote, Marie-Abele Bind, Brent Coull, Chirag, Patel, Philippe Grandjean. 2017. Combining Ensemble Learning Techniques and G-Computation to Investigate Chemical Mixtures in Environmental Epidemiology Studies. Biorxiv. https://www.biorxiv.org/content/early/2017/06/30/147413.article-info
