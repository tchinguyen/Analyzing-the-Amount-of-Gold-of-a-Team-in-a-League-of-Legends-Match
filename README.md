# Analyzing the Amount of Gold of a Team in a League of Legends Match
## Overview
League of Legends is a popular multiplayer online battle arena game where two teams fight each other, and each team has five players controlling a fighter or champion. The game has five roles, and each role involves specific activities such as gaining the enemy’s territory, helping other champions in the game, or collecting gold and experience for the team. The objective of the game is to destroy the enemy base, known as the nexus.

In this project, we use a dataset of actual League of Legends matches to find the most important variables that affect the gold collection of the blue team.

## Game Events and Objectives
To understand all the attributes in the dataset, it is important to know about the following most important events and objectives in the game:

Gold and experience: To make your champion stronger, you need to buy objects and obtain experience to level up. To do so, for example, you have to kill minions, destroy towers and kill rival champions.
Nexus: This is the most important structure in the game since destroying it means winning the game.
Inhibitors: If the blue team destroys an inhibitor of the red team, the blue team’s minions get a lot stronger, and the blue team’s minions have more chances to keep pushing lanes and winning map presence. Inhibitors will regenerate themselves in five minutes.
Towers: Towers are the ones that defend a team’s base (part of the map). A team gains the enemy’s territory by taking towers down.
Wards: To increase the chances of winning the game, it is important to place wards on the map. Wards help a team to obtain map vision of the opposite team. Moreover, they allow a team to identify the rival champions in the map.
KDA: KDA (Kills, deaths, assist) is one of the most important things about a game. Having a good KDA ratio means you have obtained a lot of gold and taken a lot of time from the enemy. This is because killing a rival champion puts the champion on hold for some seconds.
Dragons, Herald and Baron: These three types of monsters have a very strong impact on the game. If a team kills them, it obtains a certain bonus that will give the team advantage in the game. For example, by killing the Herald, the team can invoke him so as to help destroy the enemy’s towers. Killing dragons give a team specific bonus which depends upon the dragon, such as more damage and health regeneration. Killing the Baron will give the team a four-minute boost that makes all minions a lot stronger.
Goal of the Project
In this project, we analyze the performance of the blue team using data from actual matches. More specifically, the goal is to find a model that explains the difference between the acquired gold by the blue and red team. To build the model, we use several match features such as the number of champions killed by the blue team, the number of champions killed by the red team, the total experience acquired by the champions during the game, among other features.

## Data
The data for the project are in the file `lol_games.csv`. In the dataset, each row corresponds to a match, and each column corresponds to a feature of the match. Some of the features included in the dataset are the number of kills, deaths, and assists for each team, the total gold collected by each team, and the total experience earned by each team.

