# Development Process – Number Guessing Game

## 1. Project Setup
The project was created in a dedicated folder using Visual Studio Code. A Git repository was initialized using the command:

git init

This allowed version control from the very beginning of the project.


## 2. Writing the Program
The game was built step-by-step:

### a) Importing Required Modules
The `random` module was used to generate a random number between 1 and 100.

### b) Designing the Game Flow
A function `number_guessing_game()` was created to contain all game logic. The steps included:
- Displaying welcome messages  
- Generating a random number  
- Allowing the user up to 10 attempts  
- Comparing each guess with the target number  
- Providing hints (too high / too low)  
- Handling invalid input  
- Displaying the result (win/lose)

### c) Input Validation
A check using `user_input.isdigit()` ensures only numeric input is processed. This prevents crashes and improves user experience.

### d) Exception Handling
To make the game robust, multiple exceptions were handled:
- `ValueError` for invalid conversion  
- `KeyboardInterrupt` to handle manual interruption  
- A general exception block to catch unexpected errors  

### e) Running the Game
The function was executed with a simple call:
number_guessing_game()


## 3. Using Version Control (Git)
Throughout development, Git was used to track progress:
- Staging changes with `git add .`
- Creating meaningful commits with `git commit -m "message"`
- Connecting the local repository to GitHub using:
  git remote add origin <repo-link>
- Pushing updates with:
  git push -u origin main



At least five commits were made to document milestones such as logic creation, input validation, improvements, and documentation.

## 4. Repository Structure
A clean repository structure was maintained, including:
- Python source file  
- README.md with screenshots and instructions  
- A `.gitignore` file to exclude unnecessary files  
- A `docs/` folder for all project documentation  

This ensures the project follows professional development standards.
  
