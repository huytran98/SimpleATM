# SimpleATM

# Problem Statement

Write code for a simple ATM. It doesn't need any UI (either graphical or console), but a controller should be implemented and tested.

Requirements
At least the following flow should be implemented: Insert Card => PIN number => Select Account => See Balance/Deposit/Withdraw

For simplification, there are only 1 dollar bills in this world, no cents. Thus account balance can be represented in integer.

Your code doesn't need to integrate with a real bank system, but keep in mind that we may want to integrate it with a real bank system in the future. It doesn't have to integrate with a real cash bin in the ATM, but keep in mind that we'd want to integrate with that in the future. And even if we integrate it with them, we'd like to test our code. Implementing bank integration and ATM hardware like cash bin and card reader is not a scope of this task, but testing the controller part (not including bank system, cash bin etc) is within the scope.

A bank API wouldn't give the ATM the PIN number, but it can tell you if the PIN number is correct or not.

Based on your work, another engineer should be able to implement the user interface. You don't need to implement any REST API, RPC, network communication etc, but just functions/classes/methods, etc.

You can simplify some complex real world problems if you think it's not worth illustrating in the project.

# How To Submit
Please upload the code for this project to GitHub or anywhere, and post a link to your repository below. Please attach the instruction to clone your project, build and run tests in README.md file in the root directory of the repository.

# Directory

SimpleATM.cpp - ATM class file containing functions to create, delete, and modify accounts within the banking system.
user.txt - File management containing information about the existing accounts creating within the banking system.

# Build and Devel

1. Clone this repo
2. Run the script ```./run``` to compile and run.
3. Follow the on-screen prompts of the controller
   - First you will be prompted to login as an admin or a user. Create a user account by logging in as an ```1. Administrator``` with the ```PIN : 1234```.
   - Create a new user and insert a ```account number```, ```PIN```, and a ```starting balance```.
   - ```View all users``` to make sure the account is created with the right information.
   - Return to the main menu by selecting ```Exit```.
   - Select to login as ```2. User``` and enter your PIN.
   - Choose any of the options to modify or view the balance on your account.
