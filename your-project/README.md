<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Title of My Project
*[Fabia Höhne Tarragona]*

*[Data, Barcelona & Summer 2019]*

## Content
- [Project Description](#project-description)
- [Workflow](#workflow)
- [Organization](#organization)
- [Links](#links)

<a name="project-description"></a>

## Project Description
Write a short description of your project. Write 1-2 sentences about what what you chose to build and why.
Game = Blackjack
Basic Rules/ Assumptions:
1. There are two players: you as player, the computer as dealer.
2. Each card is worth their value, face cards are worth 10, the ace is worth 1 or 11 (player will be asked)
3. The person who has a sum of 21 or the maximum sum value under 21 wins. The player who has over 21 looses automatically. 
4. The player will be asked if he wants to draw another card as long as he is under 21
5. The dealer can only add a card to the deck if his sum is under 17. 


<a name="workflow"></a>

## Workflow
Outline the workflow you used in your project. What were the steps you went through?
1. Define rules and assumptions.
2. Program basic game - who wins and who looses in a simple round of balckjack?
    1. create deck - dictionary (key:values of cards)
        if ace ask desired value 1 or 11
        
    2. randomise function
    
    3. PLAYER FUNCTION
        #- hand out two cards and sum 
        #- if the sum is 21 WIN 
            else hit/stand 
            stand + card
                if over 21 LOSE
                else hit/stand
                
    4. COMPUTER FUNCTION
        #- hand out two cards and sum 
        #- if sum 21 WIN
           elif the sum over 17 - hit
                elif sum(player) > sum(dealer) + card
                        if over 21 LOSE
                        if over 17 - hit 
                    else - hit
                    
    5. winner definition
        if sum (player) > sum (dealer) WIN
        
3. Add more rounds and betting value: input questions regarding betting value and while loop, counter for amount won/lost. 
    - add variables: player_value, game_bet
    - while player_value > 0 - continue


<a name="organization"></a>

## Organization
How did you organize yourself? Did you use any tools?

Tools expected to use:
- stack overflow for questions and error resolving 
- trello for time management 
- jupyter notebook for text explanations and clear overview

<a name="links"></a>

## Links
Include the links to your repository, slides and trello. Feel free to include any other links associated to your project. 

[Repository](https://github.com/FHnt97/Project-Week-1-Build-Your-Own-Game)  
[Slides](https://slides.com/)  
[Trello](https://trello.com/b/QtxFVOwN/project-1)  