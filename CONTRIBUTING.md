# Contributing to the Project

Thank you for considering contributing to this project! Your help is much appreciated.

Before you begin, please read the following guidelines.

## How to Contribute

1. [Open an issue](#open-an-issue)
2. [Submit a pull request](#submit-a-pull-request)
3. [Coding guidelines](#coding-guidelines)
4. [Commit style](#commit-style)
5. [Tests](#tests)

## Commit Standards

According to the Conventional Commits documentation, semantic commits are a simple convention to use in commit messages. This convention defines a set of rules for creating an explicit commit history, making it easier to build automated tools.

These commits will help you and your team understand easily what changes were made in the code snippet that was committed.

### Type and Description

The semantic commit has the structural elements below (types), which inform the intention of your commit to the user of your code.

- `feat`: Commits of type feat indicate that your code snippet is including a new feature (relates to MINOR semantic versioning).
- `fix`: Commits of type fix indicate that your committed code snippet is fixing a problem (bug fix), (relates to PATCH semantic versioning).
- `docs`: Commits of type docs indicate that there have been changes in documentation, such as in the Readme of your repository. (Does not include code changes).
- `test`: Commits of type test are used when changes are made to tests, whether creating, modifying, or deleting unit tests. (Does not include code changes)
- `build`: Commits of type build are used when modifications are made to build files and dependencies.
- `perf`: Commits of type perf are used to identify any code changes related to performance.
- `style`: Commits of type style indicate that there have been changes related to code formatting, semicolons, trailing spaces, lint... (Does not include code changes).
- `refactor`: Commits of type refactor refer to changes due to refactorings that do not alter its functionality, such as a change in the format of how a certain part of the screen is processed, but that maintained the same functionality, or performance improvements due to a code review.
- `chore`: Commits of type chore indicate updates to build tasks, administrator settings, packages... such as adding a package to the gitignore. (Does not include code changes)
- `ci`: Commits of type ci indicate changes related to continuous integration.
- `raw`: Commits of type raw indicate changes related to configuration files, data, features, parameters.

### Recommendations

- Add a type consistent with the content title.
- We recommend that the first line should have a maximum of 4 words.
- To describe in detail, use the commit description.
- Use an emoji at the beginning of the commit message representing the commit.
- Links need to be added in their most authentic form, i.e., without link shorteners and affiliate links.

### Commit Add-ons

- **Footer**: information about the reviewer and the card number on Trello or Jira. Example: Reviewed-by: Elisandro Mello Refs #133
- **Body**: more detailed descriptions of what is contained in the commit, presenting impacts and reasons for the code changes, as well as essential instructions for future interventions. Example: see the issue for details on typos fixed.
- **Descriptions**: a concise description of the change. Example: correct minor typos in code

### Emoji Standards

| Commit Type                | Emoji                 | Keyword  |
| -------------------------- | --------------------- | -------- |
| Accessibility              | ♿ `:wheelchair: `      |          |
| Adding a test              | ✅ `:white_check_mark:` | test     |
| Adding a dependency        | ➕` :heavy_plus_sign: ` | build    |
| Code review changes        | 👌 `:ok_hand: `         | style    |
| Animations and transitions | 💫 `:dizzy:`            |          |
| Bugfix                     | 🐛 `:bug:  `            | fix      |
| Comments                   | 💡 `:bulb: `            | docs     |
| Initial commit             | 🎉 `:tada:`             | init     |
| Configuration              | 🔧 `:wrench:`           | chore    |
| Deploy                     | 🚀 `:rocket: `          |          |
| Documentation              | 📚 `:books:`            | docs     |
| In progress                | 🚧 `:construction: `    |          |
| Interface styling          | 💄 `:lipstick:`         | feat     |
| Infrastructure             | 🧱 `:bricks:`        | ci       |
| Ideas/tasks list           | 🔜 `:soon:`             |          |
| Move/Rename                | 🚚 `:truck:`            | chore    |
| New feature                | ✨ `:sparkles:`         | feat     |
| Package.json in JS         | 📦 `:package:`          | build    |
| Performance                | ⚡ `:zap:`               | perf     |
| Refactoring                | ♻ `:recycle:`           | refactor |
| Removing a file            | 🔥 `:fire:`             |          |
| Removing a dependency      | ➖ `:heavy_minus_sign`: | build    |
| Responsiveness             | 📱 `:iphone:`           |          |
| Reverting changes          | 💥 `:boom:`             | fix      |
| Security                   | 🔒️ `:lock:`             |          |
| SEO                        | 🔍️ `:mag:`              |          |
| Version tag                | 🔖 `:bookmark: `        |          |
| Approval test              | ✔️ `:heavy_check_mark:`  | test     |
| Tests                      | 🧪 `:test_tube:`        | test     |
| Text                       | 📝 `:pencil:`           |          |
| Typing                     | 🏷️ `:label:`            |          |
| Error handling             | 🥅 `:goal_net:`         |          |
| Data                       | 🗃️ `:card_file_box:`    | raw      |
