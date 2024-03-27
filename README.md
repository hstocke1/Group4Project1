# Team 4 MIST 4610 Group Project 1

## Team Name:
47114 Group 4

## Team Members:
1. Morgan Busbee
2. Corbin Gay @CorbinGay
3. Carson Harris @clh15315
4. Ashley Seelochan
5. Hank Stocke
6. Katie White

## Problem Description:
The task for this project is to model and build a relational database as the owner of a soccer club. In the data model, the central entity is represented as Team which contains the attributes of all of the information for each of the teams that will be playing in matches at the soccer club. The Teams table will be connected with the information about the members on the team, the facilities, the individual matches, etc. We are interested in accurately modeling this data and their relationships, as well as generating sample data and understanding these entities and their attributes within the data. We will also be creating queries to help us understand the business insights and the operations throughout the soccer club. 

## Data Model:
Explanation of Data Model:

Our data model is based on a hypothetical soccer club composed of many complex relationships among the different entities of the club.

The club revolves around the teams and their matches. This many to many relationship is displayed in our model by the associative entity matchSchedule which allows a team to participate in many matches and allows a match to be played between two teams. 

A match can only exist within a single season and can only be held at one facility. A match can have multiple referees and referees can participate in more than one match. This many to many relationship is displayed by the associative entity refSchedule. 

Teams are made of many players and a parent can have multiple players. Teams are made of multiple coaches and teams practice in multiple training sessions. Teams can own and use many different pieces of equipment.

Leagues are composed of many teams that play each other and members that pay a fee to watch games of a certain league. 


<img width="569" alt="Screenshot 2024-03-25 at 3 01 07 PM" src="https://github.com/clh15315/group4project1/assets/150160152/12570176-a2c6-43ad-86ae-68122175b83b">




## Data Dictionary:
### Table: Players

### Table: Teams

### Table: Coaches

### Table: Leagues

### Table: Matches

### Table: Match Schedule

### Table: Training Sessions

### Table: Season

### Table: Facilities

### Table: Equipment

### Table: Parents

### Table: Memberships

### Table: Referees

### Table: Referee Schedule


## Queries:

## Database Information: 
Name of the database: ns_Sp24_47114_Group4
