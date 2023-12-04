# BetTracker
The BetTracker is a simple Python program designed to help users keep track of their betting activities. The program allows users to manage monthly betting limits, place bets, plan future bets, and see a exhaustive summary of their performance.

# Table of Contents
1. [Objective](#Objective)
2. [Features](#Features)
3. [Usage](#Usage)
4. [Installation](#Installation)
5. [Authors](#Authors)
6. [Resources](#Resources)
7. [License](#License)

## 1. Objective

The objective of this code it to have a better control on the money bet, also to see a summary to know in which sports do you win more or lose more and have a control over your months limits.
In short, the purpose is to have much greater control over our bets. 

## 2. Features

- Place bets. Enter your bet details, including amount, odds, outcome, and sport.
- Place planned bets, users can plan their bets in advance by specifying the amount, odds, and sport without determining the outcome initially.
- Monthly Limit. The program keeps track of the user's monthly spending and ensures that the total spending remains within the defined monthly limit.
- Risk Analysis. Provides an overall risk analysis based on the total spending and winnings.
- Display Summary. View a summary of your total spending, total winnings, and sports performance.

## 3. Usage

At the time you run the code, the console will ask you the first action that will consist in four possible outputs. You should answer 1 if you want to place a bet, 2 if you want to set a planned bet , 3 if you want to display the summary, or q if you want to quit. This action will be asked for the user every time he places a bet, also after answering the question the user will see its remaining limits.

### 3.1 If placing a bet

If in the previous action you entered "1", you will be again asked by the console about the details of your bet, the amount, the oods, the outcome and the sport, in that order and you will have to answer them separated by a comma. To answer the amount and the odds, the format is with the dot for decimals, like this, 3.14, if you are going to add thousands, or even millions you mustn't use commas. And in the outcome you will have to answer win in the case that you have win the bet or lose in the case that you have lose it.

### 3.2 If setting a planned bet

In the case that you want to set a planned bet is the same escenario than in the first case but now you won't have to set the outcome as you don't know it.

### 3.3 If displaying a summary

In the event that in the question of placing a bet, showing a summary or removing the algorithm you have pressed "3", the algorithm will display you a summary where you will view your total spending, total winnings, the sports performance with a rank of the best from the best to the worst, the monthly limits, the risk overall which measures the risk of the amount bet according to your limits, also the console will display a message telling you which is the sport in which you win more, and its respective amount and also the sport in which you lose more. 

### 3.4 How to set months limits.

The algorithm has established monthly limits of 1000 for already finished bets and 500 for planned ones. If the user wants to establish other limits, they can do so at the end of the code by changing the value of the variables on line 124.

## 4. Installation 

The program provides two ways for visualizing the code that contains the bet tracker algorithm; from Google Collab or directly in Python.

- [Python installation](#PythonInstallation)
- [Google Collab instalation](#GoogleCollabInstallation)

### Python Installation
Firstly, install [Python](https://www.python.org/downloads/) and [PyCharm](https://www.jetbrains.com/pycharm/download/).

Once you have installed both programs you are ready to begin seeing the bet Tracker algorithm.
You will have to install now the betTracker.py , which is the algorithm. It is recommended to create a folder on the desktop of your computer for easy access.

Files >> Desktop >> 'Right Click' >> New Folder >> type: 'BetTracker'

Once you have created this folder, create a Pycharm environment in this folder. Follow the next steps to do it correctly.

- Step 1: Open PyCharm and create a 'New Project'
- Step 2: Change the project directory to the folder you previously created
- Step 3: Select the folder you created before as your PyCharm project directory
- Step 4: Create the project

The next step is the final one. Open the 'BetTracker.py' file which is the one containing the program with PyCharm.
Now, you will be able to start tracking your bets in your computer.

### Google Collab Installation

Download the ['BetTracker.ipynb'](BetTracker.ipynb) file from the 'main' directory in this GitHub and have it located.

After this, you will need to visit [Google Drive](https://www.google.com/drive/) and sign in.

Now, follow this steps to run it in google collab.
-   Step 1: In my drive main page, notice that you are on My Drive tab and click the "+ New" button.
-   Step 2: Once you have pressed the button, you will see a new tab and you will need to press "File upload"
-   Step 3: Then the computer will open the documents page of your computer, you will need to select the ['BetTracker.ipynb'](BetTracker.ipynb) file and click on open.
-   Step 4: You will see on my drive page the download and you click on it.
-   Step 5: Now you should be already on google collab placing your bets.

  ## 5. Authors and contact

-   Angel Benito  abenito.ieu2022@student.ie.edu
-   Eloy Sanchez  esanchez.ieu2022@student.ie.edu
-   Santiago Llorca  sllorca.ieu2022@student.ie.edu
-   Enrique Roca de Togores  erocadetogor.ieu2022@student.ie.edu
-   Juan Diaz  jdiazbernard.ieu2022@student.ie.edu

  ## 6. Resources
  
For the project we have used the knowledge obtained through the algorithms course in IE University coursed by Alejandro Martinez. And also Chatgpt has helped us fixing bugs.

  ## 7. License
Copyright (c) [2023] [BetTracker]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "BetTracker.py"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
  
