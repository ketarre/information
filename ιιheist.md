# /heist

The `/heist` command is a fun earning money command that let's you:
- Attempt to break into the bot's bank balance to earn some money.
- You get 10 attempts to try to solve a randomized 4 digit code.
- Be careful! Failing to crack the code within 10 guesses will set off the alarm and get you caught and fined!
- This command has a **86,400 second (24 hour) cooldown time.**

## Minigame Gameplay:

At first glance, the /heist command may seem a bit confusing, so here's how it works:

#### Guessing: To enter a guess, press the `Enter Guess` button. This will open up a modal.
- Remember your guesses, because once you submit it, it won't be visible to you again.
- You will be given an error if you try to enter anything besides a valid 4 digit code.

#### Bot Response: Once you enter a guess, the bot will give a certain response in the embed:
- There are two outputs: **Correct Digits (1)** and **Correct Positions (2)**

**Correct Digits** are how many digits of the code are correct.
- **For Example:** Guess: 1234, Code: 2341, **Correct Digits = 4**

**Correct Positions** are how many digits are in the right spot.
- **For Example:** Guess: 1234, Code: 2341, **Correct Positions = 0**

## Risk vs. Reward:

`/heist` is a very risky command due to the risk of getting caught and fined, but it can be very worth it!
- A failed heist will result in a fine of $250-1000.
- However, a successful heist will let you steal a random amount from $100-1000.

The money taken from your balance from fines will be transferred from your balance to the bot's bank balance.

## Side Note:
However, don't forget that you're stealing from the bot's bank balance. So in the very, very rare instance the bot has <$1000, you will only be able to steal what there is to grab.


###### Created by: [@kismisp](https://discordapp.com/users/1206865169846632450), Last Edited: 11/08/24
