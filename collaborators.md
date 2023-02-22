# Collaboration guide for repository Collaborators

## Starting:
    git clone https://github.com/Eloi-Perez/repository-name.git
    cd repository-name
    git checkout -b new-feature

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

Once you have something functional push your code

### First push

    git push --set-upstream origin your-branch-name

### After the first one

    git push

**Once your feature or fix is finished, resolve conflicts before Pull Request**

    git merge origin/main
    git push

### Now Go to GitHub and create a Pull Request
**The owner will review the Pull Request and merge it**
