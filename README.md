# TheGeniusWithAI

# Introduction
[The Genius](https://en.wikipedia.org/wiki/The_Genius_(TV_series)) is a South Korean reality game show which broadcasts on tvN that is a South Korean cable channel. In this reality game show, 13 contestants should play various games and compete for the top spot. 13 contestants played 12 episodes of the game and they eliminated one contestant every episode.  Despite not only plagiarism controversies but also accidents and incidents, It is still a famous TV program in South Korea. I had not studied any programming or programming language. However, I learned simple Tensorflow for the interest of artificial intelligence. It make me remind a game in [The Genius : Grand Final](https://en.wikipedia.org/wiki/The_Genius:_Grand_Final).

# About the Game
A game in a final episode of [The Genius : Grand Final](https://en.wikipedia.org/wiki/The_Genius:_Grand_Final) is Mystery Sign. There is two people who participate in this game. In the game, There is a secret formula in each round and the participants should guess the formula and use it with the two numbers which are already given. The each players give a number to the host and the host give a answer to them. 

# Data Preparation
I use [this video](https://youtu.be/vFnTtf15ZtE), [this video](https://youtu.be/s0kCnFiZPN4) and [this video](https://youtu.be/x329VEJjjdU) for gather informations. All videos are from channels which is the official account of tvN which is broadcast company of The Genius : Grand Final.  

# About the Data
First of all, Tensorflow must read a draft which I gather data on. For that, I used [Pandas](https://pandas.pydata.org/) to read my drafts. Also, the draft should be a .csv file. That is the reason why I used Google Sheets to make a .csv file that Tensorflow and Pandas can read the draft. You can see the datas at [this sheet](https://docs.google.com/spreadsheets/d/1zMR0-eyFT5Dln8N-7rrnY1rUEOE2V1K6vLw8oZPWs8o/edit?usp=sharing). Also, since my laptop is not that good. So I used [Google Colab](https://colab.research.google.com/).

# Round 1
The text in which I put a bold effect is the number in the actual TV program. 
You can see code in [here](https://colab.research.google.com/drive/1OVp6zCMFOJBSRk5vZ7xvCA71VMD0L9X8?usp=sharing) 

# Result of Round 1
![alt text](Images/TheGeniusWithAI_Round1_Result.png)

It **success.** The answer formula of this question is (bigger number) * 2 + (smaller number). AI matches the number with the aberration ±1. 

# Round 1 - How is it possible? 
Then you have curiosity in this part. How does AI match the number? 


