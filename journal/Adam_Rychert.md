# Adam Rychert Data Science Project Competition journal (Curent total 137.5)

## February 2024 (4h)

* 1. (1h): Creating a group, discord and whatsapp groups
* 2. (30 min): Meeting about the project on zoom
* 3. (1h): Watching a lecture about a hybrid inteligence -> ,,From artificial intelligence to hybrid intelligence - with Catholijn Jonker'' 
* 4. (30 min): Meeting with mentors and than follow up short meeting with co-workers
* 5. (1h): filling and sending nda, setting up Trello and figuring out a system go gather research, share notes etc.  

## March 2024 (19)
* 5. (2h): Reading research papers: Neurosymbolic AI -- Why, What, and How | Towards Cognitive AI Systems: a Survey and Prospective on Neuro-Symbolic AI
* 6. (1h): Reading research papers: Neuro-Symbolic AI: An Emerging Class of AI Workloads and their Characterization
* 7. (1h): Meeting with Siemens and mentor: Hybrid AI deep dive, followed by team meeting about which topic to choose 
* 8. (1.5h): Watching video ,,Tutorial 1a: Basics of Neurosymbolic Architectures'', adding literature to trello 
* 9. (1h): Watching video ,,MIT 6.S191 (2020): Neurosymbolic AI''
* 10. (1h): Watching video about semantic AI
* 11. (0.5h):Reading Neuro-symbolic approaches in artificial intelligence
* 12. (1h): Preparing materials, some improvements of the trello board rules
* 13. (0.5h): Watching ,,Logic Tensor Networks Pt 1 of 3: Introduction and Real Logic'', started reading Neurosymbolic AI: The 3rd Wave
* 14. (1h): Learning about SHAP, Interpretable vs Explainable Machine Learning, watching Explainable AI explained! | #4 SHAP
* 15. (2h): Reading Neurosymbolic AI: the 3rd wave
* 16. (1.5h): Reading Neurosymbolic AI: the 3rd wave, Logic Tensor Networks
* 17. (1h): Reading Logic Tensor Networks
* 18. (1h): Mentor meeting + reading materials
* 19. (1h): Initial data exploration
* 20. (2h): Researching data exploration methods, watching videos, studying some keggle notebooks


## April 2024 (38.5)
* 21. (3h): Data exploration 
* 22. (1h): Preparing the report template, abstract etc.
* 23. (1h): Meentor meeting, planning, thinking about the questions to ask
* 24. (1h): Team meeting
* 25. (4h): More data analysis, XGBoost model
* 26. (1.5h): Materials, repositories about LTN, learning about it 
* 27. (4h): Studying about NN
* 28. (3h): Trying to predict ,,Peak shaving'', writing down some questions about the dataset
* 29. (4h): ANN and explainable AI
* 30. (1.5h): Writing structure of interm. report
* 31. (2.5h): Working of interm. report
* 32. (2h): Mentor call, report edit, group call
* 33. (1h): Final fixes for report
* 34. (3h): Continuation of (finishing the) studyin about Neural Networks, planning for the implementation of LTN
* 35. (2h): Starting the LTN part of code, finding materials about LTNTorch, reading tutorials
* 36. (2h): Meeting with mentor, comming up with a plan of LTN implementation, looking for some examples that can be applied
* 37. (2h): Going through tutorials on logictensornetworks github

## May 2024 (76)
* 38. (1.5h): Going through some of the examples on LTN, looking for an example of rule extraction with LTN
* 39. (4h): Testing different examples of both LTNTorch and LTN. Figured out the issue for LTNTorch was with the version of dependencies and got the example of binary and multiclass classification to work.
* 40. (2h): Got the multiclass example to work on our dataset 
* 41. (1h): Meeting with Jevgenij to exchange informations, comu up with future plan
* 42. (1.5h): Exploring more examples of LTNTorch, thinking how can we use it for explainability, finding new rules or rule optimization: what we could maybe do is run the model with diferent predicates (for example: When SOC <= 20, stop using batery) and see what is the satisfaction level of that predicat. Than we could try modifing the treshold and see if the satisfaction increases. 
* 43. (3.5h): Trying to implement the idea for rules validation/treshold optimization on a dataset where we try to predict peak shaving. 
* 44. (2h): Got the rule satisfaction to work for a single rule - is that the right direction? + Testing how well the LTN works with a smaller dataset
* 45. (4.5h): Planinng and implementing my new idea of how to optimze the treshold with LTNTorch
* 46. (1h): Realised I forgot about finalizing the testing of rules satisfaction, decided to spent some more time on it - prepared some more lgoic rules as an example
* 47. (1h): Mentor meeting, planning the next steps
* 48. (4h): Catching up what work of my teammates, working on model for treshold search/optimization (got quite stuck with this problem: tried analysing the regression example of LTNTorch)
* 49. (2h): Tried to get the predicates for sat. calculation to work 
* 50. (2h): Looking for some research, examples of using knowledge with LTN 
* 51. (1h): Meeting with teammates 
* 52. (4h): Watching videos about LTN, preparing short topic distribution for the meeting with Seemens, cleaning code and preparing it for presentation  
* 53. (2.5h): Continuation of tries to get the treshold prediction with LTN to work, no success -- somehow there has to be a way to train a tresholds based on their satisfaction levels, for now I figured out it is not possible with just constants 
* 54. (1h): Watching yt video Learning with Logical Constraints 
* 55. (4h): Reading through all of the resources on LTNTorch github again - actually turned out to be a very good idea and now I understanded much more than when I read it initially 
* 56. (2h): Meeting with teammates before the Semens meeting, discusion about curent project status
* 57. (2.5h): Final preparation for the meeting with Semens, call with the team before it, meeting with Semens
* 58. (3.5h): Working on treshold optimization - started from scratch, might be going in the right direction now 
* 59. (4.5h): Gettin a treshold using LTN - got some result ( maybe I will switch to the main model), planning next steps for this task, figuring out if my result could be corect, tried to werify some theory about the base model, started doing changes to my treshold optimization
* 60. (3h): Menage to retrive lower treshold for the model, still not sure if that validates my approach or is happening by chance
* 61. (2h): Call with teammates about my results, researching and testing my method a bit more
* 62. (4h): Testing if there is really a need for two models, maybe just the regression one is enough, figured out that the predicate rule that is being used for the treshold is super important. Probably the initialy received 15% treshold was due to chance. With a rule that generates smaller loss value we get a value that seems to be close to 40% treshold (which would more agree with my data analysis)
* 63. (3h):Verification of the treshold prediction for the base model, trying new predicates to find a treshold
* 64. (3h): Meeting with teammate to verify the results, testing some more tresholds. Fixing some problems with the used predicate, menage to retrive both thresholds at the same time
* 65. (2.5h): Meeting with Urh and Jevgenij about finalizing the project, deciding on what to put into the report.  
* 66. (3.5h): Preparing the final LTN file, rethinking some approaches 
* 67. (): 
* 68. (): 


## Total: [total sum of hours]
