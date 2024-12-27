# A Conventional Commit Cheat Sheet

An easy-to-follow guide that helps you become a 🚀 better developer 🚀 by mastering the [Conventional Commit](https://www.conventionalcommits.org/en/v1.0.0/) standard for versioning in your projects.

---
### Helps You Be a Better Developer

By adopting Conventional Commits, it enhances your communication skills with clear, structured commit messages, helping you focus on the impact of your changes. This not only improves the way you work but also leads to smoother project management and better code quality, making collaboration more efficient.

## 🚀 How to use Conventional Commits?

### 1. **Commit messages using `git commit` in the Terminal**

You will use the `git commit` command in your terminal when you make changes to your code and want to commit them using **Conventional Commits**. The key is to follow the **Conventional Commit** format for your commit messages.

#### Example Command:
In your terminal, run the following:


git commit -m "feat(booking): add Update Booking feature"

## Steps to Commit in the Terminal

1. **Make Changes**: Modify your files as needed.

2. **Stage Your Changes**: Add your modified files to the staging area.
    git add <files>
    Or to add all changed files at once:
    git add .

3. **Commit with Conventional Commit Message**: After staging the changes, use the following command to commit:
    git commit -m "feat(DataTable): add no data found message"

4. **Push the Changes**: Push your commits to the remote repository.
    git push
    Or if you are pushing to a specific branch:
    git push origin <branch-name>



## 🚀 Basic Structure

Each commit message follows this structure:

- **type**: Describes the change (e.g., `feat`, `fix`, `chore`)
- **scope**: Optional. Refers to the area of the project being affected (e.g., `api`, `frontend`)
- **description**: A short description of the change.

---

## 📋 Types of Commit

1. **feat**: A new feature for the system  
   Example: `feat(Booing): add Update Booking feature`

2. **fix**: A bug fix for the system  
   Example: `fix(DataTable): resolve issue with DataTable filter state`

3. **chore**: Routine tasks like maintenance or updating dependencies  
   Example: `chore(deps): update antd to version 5.22.7`

4. **docs**: Documentation updates  
   Example: `docs(readme): update installation instructions`

5. **style**: Changes related to code style (e.g., formatting, missing semi-colons)  
   Example: `style(DataTable): fix item alignment in CSS`

6. **refactor**: Code change that neither fixes a bug nor adds a feature  
   Example: `refactor(usePageParams): simplify usePageParams hook`

7. **test**: Adding or updating tests  
   Example: `test(usePageParams): add unit tests for usePageParams hook`

8. **build**: Changes that affect the build system or external dependencies  
   Example: `build(vite): add vite config for production build`

9. **ci**: Continuous integration-related changes  
   Example: `ci(bitbucket): update CI config for deployment pipeline`


## 🧑‍💻 Learn More

For a deeper understanding of Conventional Commits, check out the official documentation: [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/).

---

## 💡 Tips

- Keep your messages clear and concise.
- Use the type that best represents the change you made.

Written with ❤️ by [Saroar Shahan](https://shahansdiary.com/)