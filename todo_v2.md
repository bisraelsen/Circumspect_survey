# Section 4
In section four, dedicate a paragraph or so to some of the different methods and how they affect normality, competence, and predictability.

# Section 5
* Perhaps the "perception of TRBs" block should be gray. The only reason it shouldn't be is because i have some interesting thoughts about it. However, I am not convinced how well it fits in a survey of assurances... I am inclined to keep the section because assurances must have some sort of goal to measure against.
## Calculated/Designed (wrap planning into calculating, basically not much changes except the diagram)
* Planning Objectives
    * many assurances are static, they are initially designed and are unchanging after that -- Chen 20 (SA-based agent transparency), 
    * Rouse 112 (assurances need to be changed based on the role of the user, i.e. expert/novice)
    * assurances can be planned in real time... teach the user
    * can a user cognitively grasp a planned assurance -- this probably has links to a lot of material in the "expressing and perceiving" section
    * questions: if time is a factor, there may not be time to plan, consider limitations in giving assurances (i.e. can't plan to use for radio bandwidth than is available), does planning need to take place in a given design scenario?

* Quantifying Uncertainty
    * what methods have been used? WHAT DOES *UNCERTAINTY* MEAN, I.E. WHAT KINDS OF UNCERTAINTY? basically from section,  Wang 134 (communicate uncertainty in natural language), Aitken [2,3] (uncertainty in model, expected outcome, solver quality, past performance), Zhang 141 (analyze inputs by supervised learning), Gurau 51 (GPs), Kaipa 63 (iterative closest point to a truth model),  Kuter 70 (counter planning, sum over probability of success for each counter example), Laskey 74 and Zagorecki 140 and Habbema 53 and Ghosh 45 (model checking, i.e. how certain are we that this model is correct), Active learning (robot knows how sure it is about things, and seeks to reduce uncertainty THE UNCERTAINTY HERE COULD BE *ERROR*), 
    
* Reducing Complexity -- Sheridan 117 (transparency), Muir [97,98] (summary information, domain of competence, history of competence), Kaniarasu 65 (confidence indication), Aitken [3,2], *any of the "interpretable models" section. global/local models, Van Belle 127 (nomograms, rule induction, graphical models, data visualization, each has strengths/weaknesses), Caruana 15 (GA^2M, more complicated still easy to understand, i.e. features are easy to understand), Huysmans 58 (decision trees/tables), Faghmous 37 (begin with theoretical foundation), Venna 30 and Vellido 129 and Kadous 62 (reducing dimensionality, visualizing data), Lomas 85 (translate between POMDP and user), Representation learning (can be used to make more human understandable features) THE HYPOTHESIS IS TO MAKE THINGS SIMPLES, BUT NOT ALL METHODS HAVE BEEN TESTED USING EXPERIMENTS
* Modifying Objectives (explainable by design)-- Choi 21 (re-structure ANN to pay attention to doctor visits and diagnoses), Abdollahi 1 (add an additional explainable element), Ridgeway 110 (use weight of evidence for boosting), Park 105 and Jovanovic 61 (make decision trees more intuitive by changing objectives of training decision trees), Swartout 121 (train expert system differently to store needed information), Freitas 40 (human-involved learning), Safety and learning under uncertainty (makes systems more robust, how to communicate it?), Lipton 83 (supervised danger model), Curran 26 (robot ask for help), constrained models (guarantee the solution is some domain), V&V (similar to model checking, how to communicate it?)

## Expressing and Perceiving
* Methods
    * general considerations -- Chen 20 (display of uncertainty) 
    * display value, assume user will create statistical model -- Muir 99, Wickens 137, Sheridan 117, Hutchins 56 (display competency boundaries via likert scale), 
    * observe behavior, user fill in blanks --   Freedy 39 (operators trained to recognize sings of failure), Desai 31, Salem 116 (mannerisms, success/failure),
    * physical presence, movements -- bainbridge 6, Dragan 34, 
    * display intended movement -- Chadalavada 18, 
    * Natural language -- Wang 134
    * display -- Van Belle 128 (scoring tables, color bars), Huysmans 58 (decision trees/tables, better in different situations)
    * Wallace 132 and Kuhn 69 and Lacav 71 (how should explanations be presented)
* Mediums -- sight, sound, *touch* [smell, taste] - smell and taste haven't been investigated, likely some difference in efficiency between different methods
* human-like -- Wu 139 (coin entrustment), Dragan, 
* implicit/explicit
* efficiency
* cognitive limitations -- Riley 111 (framing effects of pilots), wickens 137 (change in TRBs, but not self-reports), Chen 20 (many different ways to communicate, some better than others)

## Perceiving TRBs (i'm not convinced this is the right name, an AIA can also observe self-reports)
* Gathering self-reports -- McKnight [88,73,126], Muir 99, wickens 137, Salem 116, Desai 100, Kaniarasu 65
* Changes in user's TRBs -- Freedy 39 (relative expected loss), Desai 31 (amount of time in autonomous vs. manual), Salem 116, Wu 139, Bainbridge 6 (cooperation/non-cooperation), 
