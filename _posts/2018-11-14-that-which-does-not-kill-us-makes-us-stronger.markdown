---
layout: post
title:  Pokémon Unite Console Game
image:  '/images/Project1.png'
tags:   [UX Research, UX Design]
description: Identifying usability issues based on heuristic and design principles
---
## Overview
**Pokemon Unite** is a strategy multiplayer online battle arena (MOBA) video game on Nintendo Switch. The goal of this *3-month-long* academic project was to identify usability/design principle violations within the product interface and generate recommendations for each issue. 

After completion of the course, I developed mid-fidelity mockups to showcase how these recommendations can be implemented to design. 

**Methods**<br>
Survey, Review Analysis, Heuristic Evaluation, Prototyping (Figma)

<br>

## Process
<center><img src="/images/EvalProcess.png" alt="Evaluation process"></center> <br>

First, I conducted user survey and review analysis to learn about users and narrow down the scope of the project. Then, I identified usability issues based on heuristic principles, providing each with actionable design recommendation(s).

<br>

## Understanding Users and Use Cases
An online survey was conducted with 12 current users to learn about their experience with Pokemon Unite interfaces. Web reviews were analyzed to identify common patterns in current users' experiences with the interface and validate the survey results from a broader audience.

Based on the findings, I decided to focus my heuristic evaluation on:
* <mark style="background-color: #FFE599">Usability</mark> and <mark style="background-color: #FFE599">discoverability</mark> of in-game features 
* <mark style="background-color: #FFE599">Learnability</mark> of the game
* Navigation for collecting <mark style="background-color: #FFE599">rewards</mark>

<br>

## Sample Issues & Solutions

### Inviting other players to lobby
![Lobby Invite]({{site.baseurl}}/images/Lobby_1.png)

![Invite Other Friends]({{site.baseurl}}/images/Lobby_2.jpg)

A popup appears when users try to invite players that are not their friends to their lobby; however, there is no action users can perform rather than to close the popup. This ultimately does not guide users achieve their goal of inviting other friends. 

<span style="color: #6fb4ca;">**My recommendation**</span>

![Invite Other Players]({{site.baseurl}}/images/InviteOtherPlayers.gif)

Provide users an option to search for other players and invite them to the Lobby directly instead of requiring users to remember an 8-digit ID.

<br>

### Learning about Pokémon Moves
![Pokemon Page Description]({{site.baseurl}}/images/Recognition_1.jpg)

On Pokémon page, there are lengthy descriptions of moves/abilities for each Pokémon; this poses a high cognitive load and makes it difficult for users to learn.

<span style="color: #6fb4ca;">**My recommendation**</span>

![Pokemon Page with Video Clips]({{site.baseurl}}/images/PokemonMove.gif)

Instead of having a lengthy descriptions, have a concise description with a short video clip of what each move looks like in the game.

<br>

### Remembering Pokémon Moves

![In Game Description]({{site.baseurl}}/images/Recognition_2.png)

Players can choose a move/ability for their Pokémon during a match; however, the interface does not provide much explanation of moves at all, forcing them to remember the previous lengthy descriptions of the moves prior to the match.

<span style="color: #6fb4ca;">**My recommendation**</span>

![Select Move in-game]({{site.baseurl}}/images/SelectMove.png)

For selecting a Pokémon move during a match, include the type of the moves (i.e. ranged, hindrance) as a simple way to inform users about what the moves do so that users *recognize* these moves more easily.

<br>

### Navigating to Pokémon Held Items
![Held Item Page]({{site.baseurl}}/images/Cross_1.jpg)

Users are able to give three different items to a Pokémon of their choice on the Held Items page as seen above. 

![Pokemon Page]({{site.baseurl}}/images/Cross_2.jpg)

While these items can be assigned to each specific Pokémon, the Pokémon page does not provide any information about these items nor a way to directly navgate to the Held Items page.

<span style="color: #6fb4ca;">**My recommendation**</span>

![Pokemon Page with Held Item]({{site.baseurl}}/images/Pokemon_v2.png)

Present selected held items on the Pokémon's page, and allow users to navigate to the Held Items page directly.

<br>

## Learnings
* **Stay objective** <br>
While video games are unique in a way that users can experience a wide range of emotions and I spent a lot of time familiarizing myself with common design patterns used in the game, I learned that it is important to put the <mark style="background-color: #FFE599">users</mark> and <mark style="background-color: #FFE599">heuristics</mark> first and set aside my personal opinions or assumptions.

* **Use other methodologies to identify major issues and fewer minor issues** <br>
While conducting heuristic evaluation, I often found it very easy to get caught up with many of the minor issues within the interface rather major issues that users might experience. Using data about the <mark style="background-color: #FFE599">users</mark> and <mark style="background-color: #FFE599">use context</mark> from the *inquiry methods* (i.e. survey and review analysis) really helped me narrow down the focus of my evaluation and later verify my statements to actual users' experience.
