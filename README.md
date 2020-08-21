# FlashCards Starter Kit
A [Mod2 Project](https://frontend.turing.io/projects/flash-cards.html) by [Matthew Lane](https://github.com/GreyMatteOr)

## Overview

Ever want to run-through some flash-cards but didn't want to bother others to drill you on them? Introducing the flashcards Start Kit!

This small program runs in the console and run a round of multiple choice flashcards. By default, it stores 30 'cards' over Javascript iterator methods and Object Oriented Programming, but could be modified for any flash-cards you'd like.

## Setup

Clone down the repo (from your GitHub). If you don't want to name your project "flashcards-starter", you can use an optional argument when you run `git clone` (you replace the `[...]` with the terminal command arguments):

```bash
git clone [remote-address] [what you want to name the repo]
```

After this, open your console and navigate to the root directory of the program. Run the command

```bash
node index.js
```

to start a game. 

## Playing

Before we begin, please note it is possible to quit the program at any time by pressing `control + C` in the console. Once it's running, the program should display a short greeting followed by the first card in the set. It might look like the following:

<img width="350" alt="Example Launch" src="https://user-images.githubusercontent.com/65369751/90833559-26931c80-e2fd-11ea-844d-6107b884078e.png">

Afterwards, you can navigate using up and down to jump between different answers. Pressing `Return` will select the choice, and it will tell you if you were correct or incorrect. Hitting `Return` again will advance to the next question. It's also possible to enter the answer number followed by `Return` to select an answer.

<img width="350" alt="Screen Shot 2020-08-20 at 3 55 07 PM" src="https://user-images.githubusercontent.com/65369751/90833757-8db0d100-e2fd-11ea-8ae2-00038d871037.png">

Finally, at the end, the program will display your percentage of question gotten right, as well as how long it took you to complete before closing down.

<img width="463" alt="Screen Shot 2020-08-20 at 5 01 01 PM" src="https://user-images.githubusercontent.com/65369751/90837399-c6a17380-e306-11ea-9cec-6cf2827ab7c6.png">
