# Collaboration guide for a public repository

## Starting:
**Fork the repository**

*On this repository on GitHub on the top right, press the button "Fork" then, "Create Fork"*

**Clone it**

*On your computer, clone the fork:*

    git clone https://github.com/your-user-name/ecommerce-node-backend.git
    cd ecommerce-node-backend
    git checkout -b userName@feature

**Now create .env file, copy the keys from .env.example and add your config**

    npm install
    npm run dev

## Git committing guide:

    git add --all
    git commit -m "feat: amazing feature description"

*(use present tense)*

- feat: The new feature you're adding to a particular application
- fix: A bug fix
- style: Feature and updates related to styling
- refactor: Refactoring a specific section of the codebase
- test: Everything related to testing
- docs: Everything related to documentation
- chore: Regular code maintenance, update packages

## Contributing:

### Do multiple commits with small features

*Once you have something functional push your code*

### First push

    git push --set-upstream origin your-branch-name

### After the first one

    git push

### Now, go back to this repository on GitHub and create a Pull Request

*You will see a new button on top that says "Compare & pull request"*

*(you could instead click "pull request" on the menu and select manually a branch from your fork)*

**The owner will review the Pull Request and merge it**
