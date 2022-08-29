---
layout: post
title:  Pokémon Unite on the Switch
image:  '/images/Project1.png'
tags:   [UX Research, Heuristic Evaluation]
description: Identifying usability issues based on heuristic and design principles
---
### Summary
**Pokemon Unite** is a strategy multiplayer online battle arena (MOBA) video game released in 2021. The goal of this *3-month-long* project was to identify usability/design principle violations within the product interface and generate recommendations for each issue. 

While it was not part of the course, I have also developed low-fidelity mockups of my main design recommendations using Figma to showcase how these recommendations could be implemented to design.

### Process
<center><img src="/images/EvalProcess.png" alt="Evaluation process"></center> <br>

Prior to the evaluation, an appropriate amount of time was spent by the evaluator to get familiarized with the product interface. In addition, user survey and review analysis were used to obtain information about its users and use cases. Then, principle violations were identified throughout the Pokemon Unite interfaces with recommendations for mitigating each violation.

### Understanding Users and Use Cases
An online survey was conducted to learn about users and their experience with Pokemon Unite. Web reviews were analyzed to identify common patterns in current users' experiences with the interface and validate the survey results from a broader audience.

Based on the issues that users reported and changes they have suggested, it was decided that the evaluation should focus on the following areas:
- Usability and discoverability of in-game features 
- Learnability of the game
- Navigation for collecting rewards

### Examples
Below are some examples of issues found from my hueristic evaluation.

#### Inviting other players to lobby
![Lobby Invite]({{site.baseurl}}/images/Lobby_1.png)

![Invite Other Friends]({{site.baseurl}}/images/Lobby_2.jpg)

A popup appears when users try to invite players that are not their friends to their lobby; however, it does not perform the intended action nor instruct users what to do next, therefore does not help them achieve their goal of inviting other friends. 

**My recommendation** <br>
Provide users an option to search for other players and send an invite to the Lobby directly instead of using a 8-digit Lobby ID, which can be difficult to remember.

#### Recognition rather than Recall
![Pokemon Page Description]({{site.baseurl}}/images/Recognition_1.jpg)

![In Game Description]({{site.baseurl}}/images/Recognition_2.png)

For each Pokémon that they own, users are able to select special moves that they want to use when playing a particular Pokémon in a match. This can be pre-selected before the match on the Pokémon page or during match preparation or chosen by the user during the match. While there are lengthy descriptions of different moves available on the Pokémon page or match preparation page, there is no explanation of moves at all when users have to choose them during the match. This poses a high memory load to users.

**Recommendation** <br>
Two recommendations are made regarding this issue:
- For selecting a Pokémon move during a match, include the type of the moves (i.e. ranged, hindrance) as a simple way to inform users about what the moves do.
- Instead of having a lengthy description for each move on the Pokémon page, have a concise description with a short video clip or graphic of what each move looks like in the game.

#### Cross-pollination
![Held Item Page]({{site.baseurl}}/images/Cross_1.jpg)

Users are able to give three different items to a Pokémon of their choice on the Held Items page. 

![Pokemon Page]({{site.baseurl}}/images/Cross_2.jpg)

While held items are directly related to a specific Pokémon, the Pokémon page does not provide any information about them or a way to navigate directly to the Held Items page of a specific Pokémon.

**Recommendation** <br>
My recommendation is to present the three items that a particular Pokémon is holding on the Pokémon page, and direct users to the Held Items page if users select the items to make changes.

### Summary of Evaluation
Four high level criteria were addressed and graded to evaluate the overall usability of the product interface.

**Does it communicate its purpose, function, and value?** <br>
There seems to be a gap between the novice gamers and expert gamers in the understanding of the interface. Novice gamers may struggle with understanding the purpose and function of some actions and features as it requires some knowledge in how MOBA video games work. Thus, it is important that the interface promotes more recognition rather than recall to shorten users’ learning curve.

**Is it easy to navigate between functions and features?** <br>
It is relatively difficult to navigate within Pokémon Unite for both novice and experienced users due to a lot of hidden features that are not always easily accessible. Users can have difficulty figuring out what features to use to collect rewards because there are too many different paths and types of rewards everywhere. The discoverability of and cross-pollination between some functions and features need to be improved for easier navigation.

**Does the screen design support efficient interaction?** <br>
The screen design of Pokémon Unite is easy to understand and use, but there is a room for more customization and shortcuts in some features to make it more efficient, such as the home page and in-game communication tool. It is important to note that the current interface design is focused more on novice users’ experience, as the product is relatively new.

**Is the user guided through the interface or left on their own?** <br>
Pokémon Unite guides users through the interface very well by providing users an option to view the Help or Details content on many pages throughout the product. However, there are few areas for improvement when it comes to feedback and navigation.

![Evaluation Final Grade]({{site.baseurl}}/images/EvaluationGrade.PNG)
