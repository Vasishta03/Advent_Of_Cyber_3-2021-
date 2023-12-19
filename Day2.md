# Elf HR Problems
## Story

McSkidy needs to check if any other employee elves have left/been affected by Grinch Industries attack, but the systems that hold the employee information have been hacked. Can you hack them back to determine if the other teams in the Best Festival Company have been affected?

## Learning Objectives

    Understanding the underlying technology of web servers and how the web communicates.
    Understand what cookies are and their purpose.
    Learn how to manipulate and manage cookies for malicious use.

## Questions
### 1. What is the name of the new cookie that was created for your account?
`user-auth` under cookies storage after registering a new account
![image](https://github.com/pixie-nukes/Advent_Of_Cyber_3-2023-/assets/94845416/7b4bdd0e-8f10-42bf-a944-c05cc6011536)

### 2. What encoding type was used for the cookie value?
the encoding type used in hex so `Hexadecimal`

### 3. What object format is the data of the cookie stored in?
When i decoded it in cyberchef, it appears to be in `JSON` Format.

### 4. What is the value of the administrator cookie? (username = admin)
`7b636f6d70616e793a2022546865204265737420466573746976616c20436f6d70616e79222c206973726567697374657265643a2254727565222c20757365726e616d653a2267676767227d`

### 5. What team environment is not responding?
![image](https://github.com/pixie-nukes/Advent_Of_Cyber_3-2023-/assets/94845416/01236943-9325-4ee3-b6f5-a052c20f9d24)
We can See that `HR` is in RED.

### 6. What team network environment has a netwrok warning.
`application` has a netwrok warning.
