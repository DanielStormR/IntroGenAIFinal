# Water Polo Assistant
Short description of project. Replace this and the project section below with a 1-3 sentence description of your project. 
The custom made GPT is designed to be assistant for water polo players and coaches; it can help with learning core/advanced mechanics in terms of bodily movements, strategies both for personal plays and holistic team integration, as well as analytics of data for team performance improvement. 

## Daniel Bashirov (PI)

Daniel Bashirov, daniel.i.bashirov@vanderbilt.edu, bashirdi, Creator, Tester, Evaluator

## Proposal 

### Description of Problem/Opportunity
Water polo is an Olympic sport, with growing leagues in the United States, particularly in Florida and California. Playing water polo since the start of High School, I have found myself traversing through online sources on the ways how I can improve as a player and contribute to better performance of my team. The challenge lies in the magnitude of sources, frequently containing repeated information. Moreover, I have not encountered wide-range available analytics tools for team performance in the sport. Finally, the collegiate water polo rules frequently get updated — it may be difficult to understand the changes on the nuanced level, as well as mentally incorporate them within the rest. I believe that there is an opportunity for my own self-improvement in the sport, as well as to others starting the sport, attempting to get the basics down and build on their skills milestone to milestone. In regards to coaching, it is possible to leverage data analysis tools in an efficient manner for analytics, as well as create team-building plans pertinent. 

### Proposed Solution/Approach
I want to create a chatGPT Assistant that will help with learning techniques and planning progress for coaches and players. To do so, I will give custom instructions to the GPT model outlining the tasks the assistant is meant to do. I will enable PDF output congifuration, such that the model can give the practice plans for coaches (drills, exercise, eg.) and personal tailored learning plans for players, such that they can improve on their skills milestone to milestone. Given vast idea-generation power of GPT, I will ask it the model in the builder chat on the potential future directions of added functionality to the assistant expanding on my ideas. Moreover, I will upload the official NCAA Collegiate Water Polo Rules 2023 file to the model, such that it can clarify the complex rules as well as how they holistically integrate. Such will also be a great feature for continuing players, as rules change almost every year and the assistant will be able to explain them in simpler terms and emphasize their impact on the game as a whole. Finally, I will add a code interpreter feature that will permit the user to input a CSV document with game statistics, from which the assistant will draw improvement insights. 

### Project Outline and Timeline

## Goals of project 

### Goal 1: A model is able to provide improvement insights for players both in regard to individual and team play
### Goal 2: A model is able to create a milestone to milestone improvement plan for players
### Goal 3: A model is able to create a PDF of practice plan for coaches
### Goal 4: A model is able to consult well on the NCAA Collegiate Water Polo Rules
### Goal 5: A model is able to analyze game statistics well

## Project Metrics 

Compose 2-5 metrics to determine the success of the project. These should be measureable, and should translate to a letter grade for each. 
### Metric 1 : Plan quality (A, B, C, D, F) — the metric will assess how well the model creates the plans for learning and practice. The criteria will be based on the usefulness of the techniques and strategies and the effectiveness of practice terms. As an experienced player, I will be able to access them as such. For each method, I will assign a letter grade then average all of them to arrive at the metric score. 

### Metric 2: Readability, explanation quality (A, B, C, D, F) — the metric will assess how readable and easily understandable the content the model provides is. The way I will evaluate this is by assigning a letter grade to each of the responses it provides pertinent to content. Such will be evaluated objectively, as I will have my teammates read the responses provided and ask their judgement. Additionally, I may utilize a text processing software (e.g. Grammarly) that can give a plain text readability score. 

### Metric 3: Code Interpreter Analysis Insight Quality (A, B, C, D, F) — the metric will assess how well the model is able to draw insights by analyzing a CSV file of game statistics. The criteria here will lie in the quality of the insights provided; first seeing if they pass a sanity check to an experience water polo player, then judging whether the insight can be implemented in practice, and finally judging the results of the insight. If possible, I will ask the coach to implement the insight in practice and report the results after four weeks of practices. 

## Self-Evaluation

The Assistant receives a score of A-/B+ in plan quality
In terms of plan quality, five plans were created tailoring to the needs of particular personas. The first one was of an intermediate goalkeeper, second of an intermediate center (set) player, third for a complete beginner player, and last two for a coach training the driver players, and for a coach training wing players
In the intermediate center, the report receives a B+ in terms of content. The guide discussed the specific body handling tactics and their respective drills,  team strategies, and tailored workout plan targeting areas needed for the position. The limitation was in the bodily movements, as the model did not include the level of detail for an advanced player. However, in conversation, the model was able to climb to such level of complexity. The aspect lacking was practical perception, and holistic awareness of the game. 
For the intermediate goalkeeper plan, the report receives A- in terms of content. The guide is more comprehensive and holistic, referencing specific training areas and how to address them. This report is exceptional and exemplary of the potential of the assistant, as it shows its ability to cover breath as well as narrow it down. The limitation was lack of knowledge on some specific drills necessary. 
For the beginners guide, the report receives a B+ in terms of content. The model was able to narrow down the most important rules and skills for the beginner to learn, however I found that a beginner could benefit from additional information provided on game dynamics. 
For the coaching reports, the model performs at A- level for both. The model was able to break down the time into specific drills and be quite detailed at the areas targeted, however the report could have benefited in specificity. 

The assistant receives a score of an A- in readability and explanation quality, compiling the results of each interaction. I found the model responses to be in clear and actionable language, with explanations being simple to understand for a non-familiar user. The limitation was rather in my design of the assistant, as I did not incorporate diction tailoring to the particular type of user. However, I believe that it will be possible to incorporate such tailoring gauging experience level to judge the jargon to employ. Finally, I have used Grammarly to see how readable the plain text is, the scores received were in the 90-100 range out of 100 max. 
	
The assistant receives a score of B+ for the code interpreter criteria. Giving the assistant simulated game data, the model was able to draw reasonable, while basic, insights. For instance, it focused on the distributions of goals scored amongst the players, noting the week positions. Finally, it suggested training plans to remedy the issue, training such players. However, in the training plans references, the connections made were at times rudimentary. 

In regard to consultation with NCAA rules, the model receives an A-. The model is able to identify when consulting the guide would be desired by the user without them explicitly stating so. Referencing specific rules, the assistant consults the user on pertinent request. Moreover, it was able to recognize the new changes made to the NCAA guide, focusing on them and even discussing ther impact per the user request. The limitation was some rare mistakes model made, as once it stated incorrect information. Additionally, it was somewhat generic occasionally, as in regard to changes in women’s water polo NCAA rules

Overall, all goals of the project were met with satisfactory performance (B+). At this level, the model can already benefit the coaches and players in significant ways — organizing plans, consulting on the rules, identifying areas of improvement. 

Additional notes:
Ball stealing tactics offer a solid foundation for identifying areas for improvement, but they are not specific enough. It seems that prompt engineering might still be necessary, particularly in demanding "specific" details. Nonetheless, there is commendable work in highlighting these areas. The analysis on offensive positioning provides some insightful thoughts but falls short in its applicability, lacking specificity to the game context. Similarly, the strategy of turning the defender, while insightful, needs more detailed elaboration. The description of the frontal steal is well-outlined. However, the over-the-shoulder steal, although technically legal, should be used sparingly as it often leads to fouls, being generally perceived as aggressive or reckless.



## Reflection on Learning

This project allowed me to get a better understanding of the way generative AI, particularly Large Language models work. My model was able to meet the foundational demands of a water polo assistant, however can be improved upon in the specificity of the plans created and analysis of data. Holistically, I noticed the model including rather generic information, which is a major problem in the employment of LLMs. It is common for chatGPT to summarize the results, branching onto more well-discussed topics rather than staying fit to task. Moreover, I noticed occasional mistakes in the responses, conflicting with water polo rules (e.g. “This includes catching, passing with both hands, and dribbling while swimming.”, it is illegal to touch the ball with two hands for any player besides goalie). Moreover, when discussing the nuanced techniques, especially the ones that are in gray areas/against the rules of the game, the assistant was hesitant to provide complete information. It is important to remember that it is a statistical model based on frequency of words online, rather than a conscious entity. The sense of ethical though is present due to Reinforcement Learning human in the loop fine-tuning of the model. The model does not in practicality understand the real meaning of ethics and proper treatment. I suppose that the fine-tuning used was created in such a way to avoid potential ethical pitfalls at the cost of occasionally not providing relevant information I also noticed some formatting issues, although it was directly instructed for the assistant to provide PDFs of the plans, it required for it to be specifically stated in the prompt on some occasions. 

Working with this project, I understood the cruciality of prompt engineering. Constructing the prompt in a specific way, as well as being ethical in the line of questioning, is crucial for the best results. I found that using action words such as “comprehensive” allows for a shortcut for detailed output from the model. For the assistant to work properly here, it was still up to the user to provide details. The major issue I noticed is that the assistant still left it up to the user to provide materials on the format expected of the output and the level of specificity and detail. Even further, the model would generally try to be as generic as possible, reluctant to delve into details. Further, large language models are trained on information available online, and while it may seem that in 2024 practically everything is online, this project showcases that that may not be the complete case. Some experience-acquired skills and strategies in a highly specific area may not be openly discussed online, and if they are, may not be expressed well enough to account for years, decades, and even centuries of human to human passed information. 
As an idea for the future development of AI, I think it will be interesting how we can incorporate more advanced data sources into our models. Particularly, data covering the way we see the world, working closely with computer vision. Perhaps, showing the models the way we see will indeed make it more human…



## What's Next?

To make the use of the assistant faster and more convenient, I will be adding more instructions for it in the preset. The instructions need to holistically establish all possible output format based on the prompts, leaving the prompt to only include the user type, their level of experience, and their goals. Moreover, I plan on expanding on the directions to code interpreter, focusing on key performance indicators and evaluating how the model performs with real data. Finally, for making the assistant complete and ready for deployment, I am going to use OpenAI API portal for fine-tuning the model. 

## ChatGPT Assistant Link
https://chat.openai.com/g/g-O9nXiboGp-waterpolo-assistant

## ChatGPT Conversation Testing Link
https://chat.openai.com/share/fe7d0555-9647-4291-b2d0-17abff0ed531

## Video Link
https://drive.google.com/file/d/1rnWKNTOR0DUZWRxv28uxkVFud7m7HMUC/view?usp=share_link

## Model Constructed Files Link
https://drive.google.com/drive/folders/1pjdXymgZTF9gfPmqN4KISyeZcw9De3T3?usp=share_link




