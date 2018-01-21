# ZSL Application

## [1] Design History
Version 1.0

Produced by Matthew Sides, Sam,Luke,Luke and Joe

01/11/2017

## Table of contents

[1] Design History

[2] Game Overview

[3] Specification

[4] Game Mechanics | InGame Elements

[5] Project Backlog

[6] Evalutation 

## [2] GameOverview

### Introduction

This document specifies a design for the conceptual features and mechanics (gameplay) of a game with the provisional title “GreenHouse Menace”, commissioned by the Zoological Society of London. It is based on elements discussed in various meetings, held since 2nd October, between cliental (ZSL) and group members involving Matthew, Sam, Joe, Luke and Luke.

### Scope

This documentation is meant to be read by programmers, artists and producers involved in the design implementation and testing of “GreenHouse Menace”. The App is for a target age of 12-15 year olds, along with this the app has to be very informative and inteactive, ZSL required these for the app to be successful.


## [3] Specification

### Concept

The aim is to produce a game which suits the client’s requirements, creating an educational application that is informative, engaging and interactive based on the proposed or pre-set subject (In this instance; Greenhouse gases, production, Manufacturing and the impact of said gases and manufacturing or production phases on the environment in addition to the influence on climate change). 

### Story 

The story relates to the green house gases and chain, of the production and manufacturing proccess of four products to four habitats. The user is presented with the production and manufacutring proccess or segments of the green house gas chain and are then responsible or asked to recreate the chain after viewing the proccess once. Moreover once the chain is completed the user is then presented with what could be done to help alleviate the problem or rate at which green house gases are emmitted, which links in to the pledges the user is then shown and asked to pick at least one pledge to enact in their daily lives.

### Setting

This game will be set in the present/modern day. 

### Application Structure 

The Menu will consist of four images, each representating a different area or enviroment. 
In the application all areas will be unlocked automatically to give the user a choice as to which area they may want to begin with.

<img src="BackgroundWithDividers.png" alt="GameMenu"
     title="GameMenu" />


Furthermore the graphic styles within the enviroments and menu will be consistent throughout, though what is represented within each area and the colour palette will change so that differentiation may be made for the 4 different areas (Tundra, Rain Forest, British countryside and the Ocean).

Once an area or habitat has been clicked on a comic strip will be shown spanning one to two scenes (pages) showing the manufacturing and production proccess of a product relevant to that enviroment. Moreover after the comic strips have faded the game screen will appear with an empty chain and numerous draggable images, which need to be put by a user in a specific order. 

After the green house gas chain has been compeleted and put into the correct order, more images are presented showing what could be done to help alleviate the amount of gases released,with pledges then being presented once the images have been removed from the screen with the user given a choice.

Moreover once a pledge has been chosen the user will then be taken (transitioned) back to the main menu screen.

### Players | Platform

The application will adhere to 11-16 year olds, being compatible on the following system;

Apple-IPAD-IOS-Chrome

The application itself though not built with multiplayer, may be used by multiple people through sharing one system or machine and  straightforward discussion  (as to what should be inputted).

### Genre 

	2D

	Educational

	Memory Game

### Intended Audience

The intended audience of the game is for casual or non-gamers of all genders spanning from the age of 11 to 16, however the primary age range is 11 to 12 years old.

### Sound Consideration

The game is not sound dependant since it was requested by the client(no sound or audio).

### Language 

The only language avaliable in the game will be english. 

### IDE

Inregards to the IDE set to be used in the creation of the application, it was either between notepad++ and visual studios, since that is what the group is most adept at using, whilst both are considerate in regards to layout,tools, etc. and target beginners (with visual studios also targeting other demographics). 

Thereafter now that two IDE's (both text editors) had been chosen it was necassary to decide which one to use, considering in particular the tools as well as the ease of use. In the end visual studios was chosen since it is compatiable with unity (works inconjunction and automatically opened attempting to program when in unity) which in itself is a program that provides flexability, adaptability and overall makes the development easier and more smooth. 

Whilst language was also integral in the decision though as C# was used as the language since it was the only avliable language in unity that was avaliable to the group at the beggining since other languages arent  appplicable in unity until  a premumium subscription is purchased, whilst C# also has some simialities to C++ (the intended/initially proposed language to be applied and used), in addition since not all IDE's may use all programming languages it was necassary to check to ensure that visual studios would be compatiable with C#, evidently visual studios does allow the incorparation of C#, whilst notepad++ is compatiable with all languages (useful for some circumstances, but not in this instance since visual studios is also compatiable).

Moreover linking in with the compatability point in this project the client wanted the app to be hosted on a website using Ipads to access the website.Therefore it was recommended/decided that WebGL would be used as it is compatiable with chrome and can function to an extent in safari, this is also another reeason as to why unity was used and the language and IDE was chosen for the development of the application. 

Thereafter the decision was essentially made after evaulating the ease of use, compatability with other software in use, a comparision of own- self-  knowledge, whether it ran the intended to use language and basically functioned and met with and functioned or worked with the purpose in which the group had in mind (whether it could do what the group intended or wanted it to do)(capability of the software).



## [4] Game Mechanics | InGame Elements

### Camera 

The camera will be projected from a 2D front side angle of the menu, comics, pledges  and chain.

### General Movement

The users will be able to drop and drag certain objects across the screen (for the chain segment).
Whilst users will also be able to use the tap function (on the menu and comic slides to transition between scenes).

### Fonts

Ingame Font: 
Jupiter (Menu,Game Screen)
.... (Comic Font)

### In Game Text

Menu Text-
Tundra
Ocean
British Country Side
Rain Forest

Rain Forest | Mobile Phone Comic Strip | Production Green House Gas Chain-
1. Mining takes place in the forest which releases carbon as oil drilling rigs and mines are constructed, installed and run to extract raw materials which are mainly native to rainforests.
2. The raw materials are then transported to factories in China, Taiwan, Japan or Korea releasing carbon in the process.
3. In theses factory's raw materials are made into usable phone parts, releasing carbon as electricity is generated in the process. 
4. The mobile phones are then packaged releasing more carbon.
5. During transportation of the phones to the phone shop further carbon is released.
6. In the Phone shop electricity powers lights, computers, heating, water and many more resources produce excess amounts of carbon. 
7. Carbon is also released as customers travel to the phone shop.
8. Once the phone is purchased and plugged in to charge additional carbon is excelled. 
9.More carbon is released as more resources are mined if the phone is not recycled creating a cycle.   
Rainforest Comic Strip | Images | Shows 3 things that could be done - 
what can be done: 
Recycle old Mobile Phones 
Take Better care of the Phone
Reconsider upgrading if the phone works ok
British Countryside |Beef Comic strip |Production Greenhouse Gas Chain-
1. trees and plants are cut down to make space for cows and to grow their feed thus releasing Greenhouse Gases.
2. Carbon is also  released from pesticides that are put on cow feed to stop them being damaged by pests. Even the production of pesticides produces greenhouse gases.
3. Carbon and nitrous oxide are released from fertilisers that are used to help cow feed grow.
 4. when electricity pumps water from rivers/reservoirs/streams etc. to provide drink for the cows and to water their feed in the fields more carbon is released.
5. Carbon is also released when farm vehicles and machinery are used on the farm and fields.
6. Methane is also released when grazing cows pass wind. 
7. During transportation of livestock to slay, carbon is released when.
8 Electricity powers such as fridges, lights, computers, water and m more resources found in a slaughter house release carbon.
9. From the production of the materials used to package the beef carbon is released.
10. When beef is transported to the shops and restaurants carbon is released. Sometimes it is flown over from a different country!
11. Carbon is released as electricity powers fridges, lights, computers, heating, water and many more resources in the shops and restaurants. 
12. Additional carbon released as customers travel to the shops and restaurants.
13. Methane is released as beef and packaging decomposes in landfill.
Countryside Comic Strip | Images | Shows 3 things that could be done - 
What can be done:
eat less beef (skip eating beef for one day a week)
throw beef and any other food if possible in a special waste bin
When ordering food pick an alternative meat instead of beef (or a vegetarian option)
Ocean | Plastic Bottle comic strip |production Green House gas chain-
1. As drilling rigs are constructed, installed and run carbon is released. 
2. Carbon is also further released as oil is transported via pipes/ships to treatment plants.
3.  Electricity is then required to clean the oil releasing more carbon.
4. As oil is transported via pipes/ships/rail/tankers to manufacturers additonal Carbon is released.
5. Further carbon is released when electricity is generated to form the oil into plastic bottles and lids.
6. The empty bottles are then transported to a bottling plant generating more carbon.
7. machinery then fills the empty bottles with drink releasing more carbon!
8. Carbon is also released during packaging.
9. After Packaging more carbon is released as plastic bottles are transported to shops and restaurants.
10. Electrical powers like fridges, lights, computers, heating, water and many more resources in the shops and restaurants cause more carbons to be released. 
11.Moreover Carbon is released as customers travel to the shops and restaurants.
12. Methane is also released as plastic bottle decomposes in landfill. 
Ocean | Plastic Bottle comic strip |Images | Shows 3 things that could be done - 
what can be done: 
Reuse a bottle instead of buying a new one
Recycle Plastic Bottles
Ask for tap water when eating out

Tundra |Arctic | Electronics left on standby comic strip | production Greenhouse Gas Chain-
1. Natural gas drilling rigs are constructed, installed and run in the Tundra, which releases carbon.
2. natural gas is then transported via pipes/ships/tankers to treatment plants releasing more carbon.
3. Carbon is also released as electricity is required to clean and dry the natural gas. 
4. Natural gas is usually odorised so people can smell it and be alerted to a gas leak, though this causes the release of carbon.
5. As natural gas is transported via pipes/ships/tankers to power stations in the UK further carbon is excelled. 
6. The natural gas is then burned in power stations to drive turbines, which then produces electricity but also releases carbon in the process.
7. Additionally carbon is  released as electricity is needed for pylons/power lines to carry electricity. 
8. 15kg of carbon waster per year by leaving TV on standby.
Tundra | Arctic | Electronics left on standby comic strip |Images | Shows 3 things that could be done - 
what can be done: 
Switch off electronics of standby when not in use
Switch of lights when not in use
Unplug Mobile phone charger from wall

Pledges by Habitat:
Text (on pledges screen)
1. Write School name
Countryside
1.	I will try to skip eating beef (and better yet, meat!) for one day a week (you could follow @meatfreemonday).
2.	If I have access to a special food waste bin, I will throw beef (and any other food waste) in it.
3.	When ordering food, I will pick an alternative meat (or better yet, a vegetarian option) instead of beef .

Ocean
1.	I will use a reusable bottle instead of buying single use plastic bottles.
2.	I will recycle any plastic bottles I use.
3.	If I want water when eating out, I will ask for tap water instead of getting it in a plastic bottle.

Arctic Tundra
1.	I will switch electronics off of standby when I am not using them.
2.	I will switch light switches off when I am not using them .
3.	I will unplug my mobile phone charger from the wall.

Rainforest
1.	I will reconsider upgrading my phone every year/two years if it still works okay.
2.	I will take care of my phone to make it last as long as possible.
3.	I will recycle my phone instead of throwing it in landfill.

Interesting Fact (One per Habitat) | Shown in game screen once button is pressed on bottom of the screen

British Countryside
1.Nitrous oxide is 300 times more harmful to the environment than carbon.
Ocean
1. Methane is 23 times more harmful to the environment than carbon.
Rain Forest
1. 80% of the carbon footprint of a phone happened before it’s turned on for the first time!
Tundra
1.  9-16% of the electricity consumed in homes is used to power appliances when they are in standby mode.

## [5] Project Backlog
Group Details

Group Name: Ducks and Bucks

Group Members: Luke Shead, Joe Williams, Sam Dearing, Matthew Sides, Luke Bruni

Project Definition

Create an app for ZSL that teaches students how greenhouse gases are produced and how they affect certain habitats. Students will be required, at the end of the session, to create a pledge of how they can reduce their greenhouse footprint.
Project Specification

ZSL has given us the task of creating a web based application for children aged 11-16 which will be used in their climate change sessions. The purpose of the app is to teach students how greenhouse gases are produced and the effects they have of habitats and show them what they/society can do to reduce the levels of greenhouse gases. The app will need to include 4 habitats with their own greenhouse chain that will be displayed to the user: Artic (Plastic Bottles), British Wildlife(Beef), Ocean (Leaving electronics on standby/oil rigging), rainforest (Mobile phones). At the end of the app students will need to create ‘pledges’ of how they will reduce their greenhouse footprint.

Schedule

-Monday 2nd-Sunday 8th: Create Idea for project

-Monday 9th- Sunday 15th: Create Pitch for project 

-Monday 16th October: First Review

-Monday 16th- Sunday 29th: Develop demo for app and design product design document

-Monday 30th October: Second Review

-Tuesday 7th November: Final Presentation

#### Monday 2nd- 8th
We first started with a 1 hour sprint to put our ideas together, we began brainstorming ideas of what the main gameplay of the game would be. We decided to go with an item finding game where the user would have to find certain items in environments, which would give the user information based on each item (how greenhouse gases are created by the item etc.). We also decided on a main menu where the user would be able to decide which environment they would be using (this would depend on the environment table they are at in the ZSL session). We then spent the rest of the week fine tuning this idea and creating concepts of how the app interface would look. In our second sprint on the 5th we then decided on the aesthetic of the app, we decided upon using a comic book style as we felt that would be appealing for the children using the app.

Tasks for 9th-15th
•	design App pitch presentation (Luke) 
•	Create storyboard of app (Joe and Matthew)
•	Start Product Backlog and design flow chart(Sam)
•	Design concept art (Luke)

#### Monday 16th sprint 1

| Task    | Group Member         | Time Allocated               | Completed                      |
|----------------------------------------------------------|-----------------|----------------------|--------------------------------|
|Provide a project specification supported with a definition of the problem |   Sam     | 45 Minutes |  Yes |                 
| Plan and research your App Game Genre, theme, style, Play and Mechanics| Joe | 45 Minutes | Yes | 
| Add to mock ups for the games overall story board |    Matthew  |     45 Minutes   |   Yes     | 
| Create mock ups for your games UI |   Luke Bruni   |   45 minutes    |      Yes       |
| Create a full list of features and how it relates to clients requirements |  Luke Shead  |   45 minutes | Yes |                        | Compile, create and practise concept pitch  |   Whole Group |      1 hour    |  Yes    |                                    



#### Monday 16th Sprint 2


| Task    | Group Member         | Time Allocated               | Completed                      |
|----------------------------------------------------------|-----------------|----------------------|--------------------------------|
| Identify project outcomes using a GANTT chart|   Joe and Matthew   | 30 mins |  Yes |                 
| Add possible contingency options against risk, time, technology etc. to overall plan | Luke Shead | 30 Minutes | Yes | 
| Create a full set of user stories | Luke Bruni |30 mins   |	Yes     |   
| Create mock ups for your games UI |   Luke Bruni   |   45 minutes    |      Yes       |
| Use stories to add to the backlog | Sam  |   30 minutes | Yes |                        
| Create this week’s sprint backlog  |   Sam |      30 minutes    |  Yes    |                                    


This week’s sprints first started with our group meeting and discussing what we had achieved before the first week, Luke Shead had created the pitch presentation, Joe and Matthew had created some storyboards of how the app would function, Luke Bruni had created some concept art of the main menu and the artic habitat background and Sam had started the backlog of the previous sprints we had completed. Once we had confirmed that the tasks from last week were complete, we then assigned each other tasks that we needed to complete within a 45 minute timeframe (See in table sprint 1). This sprint was focused on our pitch and adding details to certain parts of our pitch, for example we needed to add more details to our storyboard to include the part where the students would give their pledges. Once we had completed the tasks we took an hour break then moved onto our second sprint. This sprint was more focused on how we would manage our project (see in table sprint 2); a way we are doing this is by creating user stories, so we have clear simple tasks that we can complete in our sprints.

#### 30th October-7th November


| Task    | Group Member         | Time Allocated               | Completed                      |
|----------------------------------------------------------|-----------------|----------------------|--------------------------------|
| Complete Drag-and-drop chain sections of the app |  Matthew   | 5 Days |  Yes |                 
| Complete student pledges part of app | Sam | 5 Days | Yes | 
| Continue creating assets to be used in game | Luke Bruni | 5 Days |	Yes |   
| Figure out how to get the app up on the  Ipad |   Joe and Luke shead   |   5 Days    |      Yes       |
| Test all aspects of the app| All Members  |   5 Days | Yes |                        
| Continue Project Documentation  |   Sam |      5 Days   |  Yes    |                                    
|Combine all sections of the app, when all sections are done | All Members | 2 hours | Yes|

### Research

## [6] Evalutation 


### Motivational theories, contrast and impact on the workplace

#### Hierarcy of Needs

The Hierarcy of needs, developed by Psychologist Abraham Maslow, is a motivational theory comprising a five tier model of human needs, often depicted as hierarchical levels within a pyramid. Maslow (1943, 1954) stated that people are motivated to achieve certain needs and that some needs take precedence over others. Moreover once one level is attained it is human nature to move onto the next and what further motivates us.



This five-stage model can be divided into deficiency needs and growth needs. The first four levels are often referred to as deficiency needs (D-needs), and the top level is known as growth or being needs (B-needs).

#### Carrot and Stick

This traditional motivational theory, attributed to philosopher Jeremy Bentham, dates back to around 1800 during the Industrial Revolution. The theory essentially splits motivation into two basic components: incentives and fear.There are instances where some are motivated by material gain,yearning to achieve status and power, comparitive to where some act out of fear of losing their job  being reprimanded by a supervisor or not being able to adequately perform an assignment.


#### Comparsion and Impact

The relation and differences between the two motivational theories above essentially pertain to the factors that lead to motivation and the driving forces behind said motivation, as briefly explained above, "the Carrot and Stick theory essentially splits motivation  into two compentents: Incentives and fear", similiar to the Hierarcy of Needs the first few (two-three) tiers in the pyramid model refer to survival and the following that factors that trail behind the lack of ability to access the basic needs to survive are fear and incentive, thus it is easy to relate the two theorys in the beggining tiers (D-needs) of the Hierarcy of Needs model. 

Though in comparision to the carrot and stick theory, the Hierarcy of Needs covers a more indepth analysis into what may motivate someone not just briefly stating that incentive and fear are the driving forces behind motivation, but splitting the theory into a 
five layered ordered model, pertaining to the idea that certain needs take precidence over others for instance physiological needs must first be met before security needs and not vice versa. 

Thereafter the theories do not clash but rather collate, with the Hierarcy of Needs theory merely exapanding on the Carrot and Stick
motivational theory formed in the 1800's, delving more into the incentives one may crave (self fufilment, Pyschological needs,Basic Needs) and the fears one may experience during a peroid of work (stress).

In relation to the ZSL Project and own experience, the theorys can be seen to have a huge impact, deemed important , as during the project there were numerous instances in which we were behind and this is where the idea of fear that leads motivation can be seen (may be noted that this was particuarly prominent after the first presentation when morale was low and work was stagment, it took the idea or fear of not having anything to present in the next meeting and failing to meet expectations to motivate the group further). Whilst the incentives in this regard pertain to the fifth and fourth level, particuarly of self actualization and Esteem needs, as the ZSL opportunity beckoned competition and growth, with the chosen group being able to present their work and see their application used in a proffessional manner. 

Therefore it may be seen that the motivational theories play an integral role and severely impact work produced, however the differences in the worked produced out of fear and incentives being different in the sense that depending on the situation the quality of work produced may be different regardless of whether either of the theorys idealogical basis. 

References used: 

http://smallbusiness.chron.com/three-main-theories-motivation-1888.html
https://www.simplypsychology.org/maslow.html

### Importance of team dynamics in the success and/or failure of group work

Team dynamics is integral to the success or failure of any project and its management, in particular in relation to the ZSL project entrusting that everyone knew their part was crucial especially since there were multiple intervals where the group was unable to meet with eachother due to extended breaks (half-term) , furthermore if communication was not kept and team dynamics not applied it would be likely that work is duplicated or that one member may go off track. For instance in the first draft the drawn artwork and graphical artwork differed greatly due to a lack of communication and thus caused inconsistency in the graphics overall look.

Moreover during the extended break the group was expected to organise times as to when to come in doing the equivalent to overtime to ensure that the groups were on target for a time deference already below the usual industry standards as to what would be coined as acceptable or reasonable. This was not done due to a lack of euthusiam of one member, no communication by two, whilst the team leader was not taking charge, stating that they were busy, thus leaving the team with one member (me) having to arrange a date for the group to meet up (a job meant for the team leader), which did not happen meaning one member was left attending or coming in on monday and tuesday, to  hoist the group to an acceptable standard of work within that time (which did not happen), leaving that one member to not enjoy their work (morale decreased and not come in the wenesday of that week as was origninally attended), hence another reason why team dynamics is important as it may affect performance. 

Furthermore team dynamics may not just affect the success or failure of said group work or one project but a company's overall reputation, the company in this instance being Reboot games which I am under, where the first draft was not up to the clients (ZSL) standards (meeting around 40%) missing the core point of the application and areas they wished covered, thus in a competetive enviroment it is likely that the client would not invest into the company's app but rather another organisation that may sate their needs. This being mainly caused by the lack of communicaton not just internally but externally with the client, whilst if the documentation was read thoroughly, the group communicated and committed it would have been less likely for the mistake to occur as the project would have been less rushed with multiple people working on it and the group/team working inconjunction. Inaddition the team dynamics affect on reputation may also cause a drought of influx of money as work is less likely to come through and with staff morale falling due to not applying team dynamics, the staff retention rates and quality of work will go down. This therefore highlighting the importance of team dynamics and the insufficent use of the methodlogy in this project thus showing flaws and room for improvement.

The success that team dynamics bring is essentially the vice versa to what is covered in the previous and above paragraphs, allowing people to have high morale, work meets standards, excellent reputation as work is delivered, retention of staff, constant secure/safe flow of money and team and individual performance improving. Which can been seen more in the second draft as their was more communication after getting feedback from the client and people completed the work allocated and based around the time given or remaining for completion a acceptable outcome was achieved, though not chosen, the use of team dynamics and effect may be observed and the project can be deemed succesful in the scope of meeting the clients standards, though evidently a failure for the group not being chosen, which in a sense shows the flaws and leaves room for development.

### Critical Evalutation of self contribution

In relation to my own self contribution to the project, I believe in regards to the first draft I was integral to some of the key concepts thought up , though not as useful in the documentation of said concept, instead opting to handle the storyboard aspect as to how the game may function and look, though as explained in the above section (Importance of team dynamics in the success and/or failure of group work) the whole team dynamic was not functioning to an acceptable standard and thus confusion ensued as to the graphical outlook of the game and thus a re-evaulation of said drawings was required to ensure consistency with other graphics made by another group member.Furthermore I took attempted to take on roles that were supposed to be covered by the team leader,organising meetings during breaks, though not successful this shows the lack of team dynamic and room for improvement. Although in the (second meeting with the client) meeting where the first draft was introduced and presented to the client I contributed slightly to the answering of questions though maybe not necessary it helped relive the pressure of the chosen presenter of are group.

Furthermore in relation to the contribution for the second draft I believe the contribution I garned was integral and significant as the main core coneceptual idea was thought up by me, with the game design documentation, text documentation and the majority of the applications core features, excluding the graphics were covered and developed by me, thus allowing the client to see visual development and also a finished product within the time limit set by the client. That is not to say that the group did not have a hand in said development, but shows that I had an evident and significant impact on the final outcome of the project application.

Moreover following the critical evalutation if I were to undertake a similiar project in the future I would suggest that I work on my time management, communication (required for the whole team/group) and overall handling of the project in the first instance ensuring that the brief is thoroughly read as in the first instance or draft it missed the point as to what the client wanted the application to bring across and be centered around.

### Event and Design evaluation

In regards to the event it was  satisfactory, producing perhaps not a desiarable outcome but an exceptable one, as a solid idea was layed out to the client meeting the criteria that was talked over with the client days before in a prior meeting before the final event. Whilst although the application prototype failed to function in some areas the base for the application was there showing the client as to what to expect and considerble commitment considering that it was manufactured and put together within a short span of time.

Moreover there was an appliciation of savvy interpersonal skills during the event, showcasing the ideology behind the application, reasons for making the decisions we did and what could have been had more time been allocated.Further communicating with the clients bouncing ideas off eachother and accepting crude criticism as to what they would have liked to have seen or what could have been done to further improve the app. 

Inaddition during the design proccess the first draft and the follow up to the second was lacking in the use of interpersonal skills and actually meeting the clients requirements or standards, which can be seen to be linked with the lack of interpersonal skills and team dynamics within the group. Furthermore the effectiveness of interpersonal skills can be seen through the stark contrast in work covered in the weeks that meetings were held, whilst through comparing the first draft that did not fully meet the clients (ZSL) standards unlike the second idea that was met with favorable feedback.  The lack of interpersonal skills particularly near the beginning of the project can be further seen through the graphical and drawn designs of the application as the drawn designs or storyboards had to be scrapped as it did not meet the asthetic look of the graphical images, thus leading to inconsistency. 

Though the communication between the tutor unlike the group members for the design phase was satisfactory in regards to my own communication though as a group the communication was abysmal as times regarding when work shall be completed were not sent, thus meaning that the tutor could not update the client or know as to what phase the development was at.

Therefore in regards to the standard of the application of interpersonal communication during the design pahse and an event, during the first half of the design phase it was appalling, though improved as the project got into the later stages of the design phase, due to a sense of urgency and obligation to the client to fufill prior promises made, thus enabling the event in particular the use of interpersonal skills to soar as there was an abudant amount of content to cover and talk over with the client, also receving constructive criticsm well and applying a range of techniques such as using body language, a presentation, being verbal, well spoken and applying other proffesional practices to ensure that the group was recieved well and the intent of the group was clearly put across.

### Problem solving techniques used in the design and delivery of an event

The ZSL project hailed the use of numerous problem solving techniques during the design and deliverly of an event, below a few techniques applied are listed-

-Brainstorming: By encouraging the open expression of any and all ideas, the perspective of all those involved in solving the problem can contribute to identifying possible options to solve the problem and then selecting the best solution from those possibilities.

-Process evaluation: Problems can be approached by breaking systems into sections which can be analyzed for the source of the problem.

-Word analysis: Through focusing on the essential questions; who, what, where, why, when, and how; team members can gather the essential facts about a problem without dealing with confusing details.

-Data collection: By making sure relevant information is collected, team members can develop a more suitable response.

References- 

https://www.mediate.com/articles/thicks.cfm

http://www.brighthubpm.com/resource-management/87541-problem-solving-techniques-in-project-management/

https://www.project-management-skills.com/problem-solving-techniques.html

http://www.managers.org.uk/knowledge-bank/problem-solving

http://asq.org/learn-about-quality/problem-solving/overview/overview.html

### Justification of use of solution Methodologies

Throughout the project numerous encounters left the group unable to further progress until a solution was found to a certain problem, detailing the problems, methods and solutions, justification for the steps taken when encountered with said problem may be found in the below paragraphs. 

The project was approximently 6 weeks in length, within that time the group was tasked with making an educational application for kids, focusing in particular on the green house gas chain, during the coding  and conceptual design phase of the project one such problem that occurred though not evident until ported to Ipad devices (the chosen system for the applicaiton to run on)  was that the dimesions of the frame outscaled the device, meaning that the application went of screen and certain features were not able to be accessed. 

Thus problem solving meetings occurred to objectively address the issues that threaten the project. This was particuarly benifical as it encouraged open experession with the perspective of all those involved in solving the problem being contributed to identifying possible options to solve the problem and then selecting the best solution from those possibilities.

In correlation to the above method of internal meetings, external outsourcing for solutions through the web and other groups were also carried out, to seek their views and other possible ways to fix a problem, this can be seen to be successful during the project as inrelation to the illustrated problem put out in the second paragraph, one of the groups that was consulted encountered the same problem ealier on in the project and thus helped solve a problem that otherwise would have been elongated. Further illiterating this point the solution involved altering a setting native to the Unity software, which is pre-set until manually changed (resolution setting/option).

With regards to the project as a whole the project itself can be viewed as a problem that the client requires to be solved, thereafter the method of proccess evalution breaking the project down was applied, seperating theses broken tasks and sharing among group members to accomplish, thus ensuring optimal efficency and increasing the rate at which the project as a whole would be completed. The use of this method can be further justified as through proccess evaluation in particular to the latter stage of the project enabled a solid idea to come to fruition. 

### Critique of the proccess used to give critical Reasoning

The method or proccess applied to anaylse and question the steps taken through out the project or more specifically critically assess the thought proccess behind said actions,consisted of considering  whether the choice made was approriate, also further questioning as to if there were any other alternatives to said decision before and after application. Moreover then reading through the documented plan  and researching as to what could have been improved upon, other methods or ideas that can or could have been used, essentially comparing or using other documented information relating to what is being overlooked and seeing as to what method or ideology would have or better suits the situation and work. 

In regards as to the steps that could have been taken to further improve the critique proccess, rather than just analysing documented information or written work, vocal or verbal feedback could have helped influencing decisions and aiding the evaulation of work using critical reasoning, getting a more solid idea as to the hidden problems with said planning and decisions rather than just comparing work (second opinion), ensuring the same mistakes are not encountered on future projects.





