What do I still need to do?

* There is still a question of whether section 4 is even valuable, putting material in section 4 into 5 would make 5 a bit more practical, **however** I feel like leaving the nitty-gritty details of 4 out of 5 is kind of nice. It is almost like people could skip 4 and then look at it later for more detail about 5.
* assuming I keep seciton 4, I need to spend some more time tying 4 and 5 together, or at least making the tie clear.
* I'm not really sure how to refer to 'competence', 'predictability', and 'situational normality' in section 4... or how useful it is. Do I just add a sentence to the end of each paragraph that says what things the paper addressed? Talk about what might be used from the current literature, what ideas might we connect? 
* Get rid of EHM section?

* I really want to focus on section 5, and I think some ideas for 4 will fall out.
* Some concrete ideas for section 5 -- **somewhere it would be good to talk about assuring a user about multiple capabilities**. I think I'll make a 'key considerations for design' table or something for each section. I want a simple way for people to get the results of the survey, with the ability to read further if they want.
    * Planning (possible adjustment of assurances based on user, or environment) -- **this isn't really discussed in literature that I can think of, but I think it should be, I guess it could be wrapped up into the 'calculation' section, planning requires calculation after all. The reason this was separated to begin with is because planning might happen before doing intensive calculations: basically figure out what you want to calculate and then do it**
        * is it desirable to be able to plan for different users?
        * does a typical encounter give enough time for planning?
        * limitations of use, and it's own limitations
        * have any methods been used? I don't think so
    * Calculating -- **need more material here, need some detail about algorithms**
        * limitations of AIA, and situation. are there time limitations (i.e. i need an answer now), or computational limitations (i.e. ability to store enough data, physically perform calculations)
        * will the method provide sufficient information to communicate to 'competence', 'predictability', 'situational normality'? -- human experiments may be needed to verify
        * can the AIA obtain the necessary inputs?
        * 'quantifying uncertainty' helps to convey information to all 3 trust dimensions
        * 'reducing complexity' is meant to address predictability (i.e. interpretability, comprehensibility), but may also give information (perhaps indirect) about competence and normality
        * 'changing objective' is can convey all three as well
        * **I am not really sure how to approach this section, in my opinion there really isn't a clear split between the 3 dimensions, and a certain type of algorithm.**
        * I really like the generality of 'quantifying uncertainty', 'reducing complexity', etc. because it helps people come up with other ideas of their own. I do discuss some approaches in detail, but others that achieve the same ends are just as valid.
        * It seems like using the 3 dimensions (and possible the other dimensions) can guide the selection of information that needs to be provided, but not necessarily the algorithm. A GP can contribute to competence or predictability based on how it is applied.
        * Use the 3 dimensions to guide questions like: am I designing enough assurances to help the user? 
        * with certain algorithms (ANNs) amount of data may be an issue, over/under fitting, biased models.... the list goes on, basically it is important to consider the limitations of the algorithms being used, but it always is, so should i even say it?
    * Expressing and Perceiving assurances -- **human-like assurance should be moved to planning/calculating section I think**
        * What limitations does the AIA have for expressing assurances?
        * Within those limitations can the assurance be communicated?
        * How robust does the assurance need to be to communication error?
        * appropriate medium, and method?
        * does a method exist for the calculated assurance?
        * is the appropriate meduim being used?
        * what will the absence of an explicit assurance mean?
    * Measuring the effects of assurances -- **might this section also be wrapped into calculation? basically we need to measure TRBs in order to make calculations? I think I actually like this as its own topic, it is the result of assurances, my basic message is if you are going to design assurances you better know if they are working or not**
        * can the desired effects be quantified?
        * observing implicit human behaviors? or explicit ones? (here implicit is thought of as behavior not consciously meant to convey trust) basically did you ask the human "do you trust me?" or did they just treat you like they do?
        * is it important for a specific trust dimension to be affected, or is the only important outcome the TRB
        *
