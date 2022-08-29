---
layout: post
title:  Pokémon Unite Console Game
image:  '/images/Project1.png'
tags:   [UX Research, Heuristic Evaluation, UX Design]
description: Identifying usability issues based on heuristic and design principles
---
## Summary
**Pokemon Unite** is a strategy multiplayer online battle arena (MOBA) video game released in 2021. The goal of this *3-month-long* project was to identify usability/design principle violations within the product interface and generate recommendations for each issue. 

While it was not part of the course, I have also developed low-fidelity mockups of my main design recommendations using Figma to showcase how these recommendations could be implemented to design.

## Process
<center><img src="/images/EvalProcess.png" alt="Evaluation process"></center> <br>

First, I conducted user survey and review analysis to learn about users and narrow down the scope of the project. Then, I identified usability issues based on heuristic principles, providing each with actionable design recommendation(s).

## Understanding Users and Use Cases
An online survey was conducted with 12 current users to learn about their experience with Pokemon Unite interfaces. Web reviews were analyzed to identify common patterns in current users' experiences with the interface and validate the survey results from a broader audience.

Based on the findings, I decided to focus my heuristic evaluation on:
- <mark style="background-color: #FFE599">Usability</mark> and <mark style="background-color: #FFE599">discoverability</mark> of in-game features 
- <mark style="background-color: #FFE599">Learnability</mark> of the game
- Navigation for collecting <mark style="background-color: #FFE599">rewards</mark>

## Examples

### Inviting other players to lobby
![Lobby Invite]({{site.baseurl}}/images/Lobby_1.png)

![Invite Other Friends]({{site.baseurl}}/images/Lobby_2.jpg)

A popup appears when users try to invite players that are not their friends to their lobby; however, there is no action users can perform rather than to close the popup. This ultimately does not guide users achieve their goal of inviting other friends. 

<span style="color: #6fb4ca;">**My recommendation**</span>

![Invite Other Players]({{site.baseurl}}/images/InviteOtherPlayers.gif)

As shown above, provide users an option to search for other players and invite them to the Lobby directly instead of requiring users to remember an 8-digit ID.

### Remembering Pokémon Moves
![Pokemon Page Description]({{site.baseurl}}/images/Recognition_1.jpg)

![In Game Description]({{site.baseurl}}/images/Recognition_2.png)

There are lengthy descriptions of different moves available on the Pokémon page; however, there is no explanation of moves at all when users have to choose during the match. This poses a high memory load to users.

<span style="color: #6fb4ca;">**My recommendation**</span>

![Pokemon Page with Video Clips]({{site.baseurl}}/images/PokemonMove.gif)

Instead of having a lengthy description for each move on the Pokémon page, have a concise description with a short video clip or graphic of what each move looks like in the game.

![Select Move in-game]({{site.baseurl}}/images/SelectMove.png)

For selecting a Pokémon move during a match, include the type of the moves (i.e. ranged, hindrance) as a simple way to inform users about what the moves do.

### Navigating to Pokémon Held Items
![Held Item Page]({{site.baseurl}}/images/Cross_1.jpg)

Users are able to give three different items to a Pokémon of their choice on the Held Items page as seen above. 

![Pokemon Page]({{site.baseurl}}/images/Cross_2.jpg)

While these items can be assigned to each specific Pokémon, the Pokémon page does not provide any information about these items nor a way to directly navgate to the Held Items page.

<span style="color: #6fb4ca;">**My recommendation**</span>

![Pokemon Page with Held Item]({{site.baseurl}}/images/HeldItems.gif)

Present selected held items on the Pokémon's page, and allow users to navigate to the Held Items page when they click them.

### Learnings
**Stay objective** <br>
Video games are unique in a way that users can experience a wide range of emotions. While I spent a lot of time familiarizing myself with common UX/UI patterns used in the game, I learned that it is important to put the <mark style="background-color: #FFE599">user</mark> and <mark style="background-color: #FFE599">heuristic principle</mark> first and set aside my personal opinions.