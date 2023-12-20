---
layout: post
title:  Pokémon Unite Console Game
image:  '/images/Project1.png'
tags:   [UX Research, UX Design]
description: Identifying usability issues within a video game based on heuristic and design principles
---
## Overview
Pokemon Unite is a strategy multiplayer online battle arena (MOBA) video game on Nintendo Switch. The goal of this *3-month-long* academic project was dedicated to uncovering usability and design principle violations embedded within the product interface and generating recommendations for each, aiming to enhance the overall user experience. 

Following the course's completion, I translated these recommendations into mid-fidelity mockups, showcasing visual representations of how these recommendations can be integrated. 

**Methods**<br>
Survey, Review Analysis, Heuristic Evaluation, Prototyping (Figma)

<br>

## Process
<center><img src="/images/EvalProcess.png" alt="Evaluation process"></center> <br>

First, I conducted user survey and review analysis to learn about users and narrow down the scope of the project. Subsequently, employing heuristic principles, I identified usability challenges and provided actionable design recommendations for each issue encountered.

<br>

## Understanding Users and Use Cases
An online survey was conducted with 12 current users to learn about their experience with Pokemon Unite interfaces. Web reviews were analyzed to identify common patterns in current users' experiences with the interface and validate the survey results from a broader audience.

Based on the findings, I focused the heuristic evaluation on:
* Usability and discoverability of in-game features 
* Learnability of the game
* Navigation for collecting rewards

<br>

## Sample Issues & Redesigns

### Inviting other players to lobby
![Lobby Invite]({{site.baseurl}}/images/Lobby_1.png)

![Invite Other Friends]({{site.baseurl}}/images/Lobby_2.jpg)

A popup appears when users try to invite players that are not their friends to their lobby; however, there is no action users can perform rather than to close the popup. This ultimately does not guide users achieve their goal of inviting other friends. 

<span style="color: #545ed4;">**My Redesign**</span>

![Invite Other Players]({{site.baseurl}}/images/InviteOtherPlayers.gif)

Provide users an option to search for other players and invite them to the Lobby directly instead of requiring users to remember an 8-digit ID.

<br>

### Learning about Pokémon Moves
![Pokemon Page Description]({{site.baseurl}}/images/Recognition_1.jpg)

The lengthy descriptions of moves/abilities for each Pokémon poses a high cognitive load and makes it difficult for users to learn.

<span style="color: #545ed4;">**My Redesign**</span>

![Pokemon Page with Video Clips]({{site.baseurl}}/images/PokemonMove.gif)

Provide a concise description with a short video clip of what each move looks like in the game.

<br>

### Remembering Pokémon Moves

![In Game Description]({{site.baseurl}}/images/Recognition_2.png)

Players can choose a move/ability for their Pokémon during a match; however, the interface does not provide much explanation of moves at all, forcing them to remember the previous lengthy descriptions of the moves prior to the match.

<span style="color: #545ed4;">**My Redesign**</span>

![Select Move in-game]({{site.baseurl}}/images/SelectMove.png)

Include the type of the moves (i.e. ranged, hindrance) as a simple way to inform users about what the moves do so that users *recognize* these moves more easily.

<br>

### Navigating to Pokémon Held Items
![Held Item Page]({{site.baseurl}}/images/Cross_1.jpg)

Users are able to give three different items to a Pokémon of their choice on the Held Items page as seen above. 

![Pokemon Page]({{site.baseurl}}/images/Cross_2.jpg)

While these items can be assigned to each specific Pokémon, the Pokémon page does not provide any information about these items nor a way to directly navigate to the Held Items page.

<span style="color: #545ed4;">**My Redesign**</span>

![Pokemon Page with Held Item]({{site.baseurl}}/images/Pokemon_v2.png)

Present selected held items on the Pokémon's page, and allow users to navigate to the Held Items page directly.

<br>

## Learnings
* **Stay objective** <br>
While video games are unique in a way that users can experience a wide range of emotions and I spent a lot of time familiarizing myself with the product, I realized the significant importance of prioritizing <mark style="background-color: #FFE599">users</mark> and <mark style="background-color: #FFE599">heuristics</mark> over my personal opinions and biases.

* **Use other additional methodologies to prioritized major usability issues** <br>
During my heuristic evaluations, I noticed a tendency to get caught up with minor design issues rather than focusing on the more impactful issues that directly affected the user experience. Using data about the <mark style="background-color: #FFE599">users</mark> and <mark style="background-color: #FFE599">use context</mark> from the user inquiries (i.e. survey and review analyses) not only allowed me to narrow down the focus of my evaluation but also facilitated the validation of my evaluation against real user experiences.
