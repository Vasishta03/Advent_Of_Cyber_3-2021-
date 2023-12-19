# Save The Gifts
## Story

The inventory management systems used to create the gifts have been tampered with to frustrate the elves. It's a night shift, and McStocker comes to McSkidy panicking about the gifts all being built wrong. With no managers around to fix the issue, McSkidy needs to somehow get access and fix the system and keep everything on track to be ready for Christmas!

## Learning Objectives

    What is an IDOR vulnerability?
    How do I find and exploit IDOR vulnerabilities?
    Challenge Walkthrough.

## Questions
### 1. What is the received flag when McSkidy fixes the Inventory Management System?
 `THM{AOC_IDOR_2B34BHI3}` is the answer.
 I changed the user id to *9* and found the *GRINCH* character, and reverted all the actions to find the flag like this.
 ![image](https://github.com/pixie-nukes/Advent_Of_Cyber_3-2023-/assets/94845416/20c2f5c5-daf3-474a-9b7e-05eb9d428b0c)

### 2. After finding Santa's account, what is their position in the company?
Santa's user id is `1`
and their position is `The Boss!`

### 3. After finding McStocker's account, what is their position in the company?
positionis `build manager` and their user-id is `3`.

### 4. After finding the account responsible for tampering, what is their position in the company?
name is `grinch` user-id is `9`. 
their position is `Mischief Manager`
