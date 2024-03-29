# CodeCareer Open-Source
> A global repository to store information and gather feedback about our current and future open-source projects

## CodeCareer As an Organization
Our Why: Save coders time & stress by creating a platform to source & match jr developers with 50,000 unfilled software development roles.
How We Do It: Code. Coffee. Curiosity. Empathy. Tenacity.

How We Conduct Ourselves:
- "Why" Focused - "Save developers time and stress"
- No Bullshit - politics, ideologies, pissing contests, cliques, or big egos? Yeet!
- Be Humble - one has a right to be correct; one does not have a right to be an asshole.
- Have Grit - be resourceful, own your portion of the product, ask for help when stuck.
- Embrace Neurodiversity - each person has a unique way of creating solutions and getting work done.
- Fully Async Remote - multiple continents, multiple timezones & yet strong collaboration.

## Our Open Source Vision
Our vision for CodeCareer's open-source initiatives is to help budding developers on their journey to landing a full-time position in tech by providing the opportunity and guidance a new developer needs to make their first real world contribution that has a meaningful impact.

## Current Open-Source Projects
- Barebones Hiring System | Job postings, admin dashboard, job applications. | (node/express/react) | https://github.com/GitCodeCareer/hacktoberfest--hiring-system
- Discord Bot | Motivational quotes, podcast link, quote of the day, youTube link, random .gif | ( nodejs discordjs ) | https://github.com/GitCodeCareer/discord-bot
- A Click Through Career Roadmap that Asks Users About Work Style Prefferences to Help Them Determine a Career Focus. | https://github.com/GitCodeCareer/Career-Roadmaps
- The Ultimate List of Startup Resources | An ever growing list of start up resources to save founders time and stress. | https://github.com/GitCodeCareer/The-Ultimate-List-of-Startup-Resources
- 301DaysOfCode.com | https://github.com/GitCodeCareer/301DaysOfCode.com
- CoderStory | A compilation of programmers sharing their journey in code. | https://github.com/GitCodeCareer/coder-story

## Past Open-Source Projects
- CodeCareer CLI | https://github.com/GitCodeCareer/codecareer-cli

## Contribution Policy
- The Code Career admin team has the right to start new open-source projects at any time.
- The Code Career admin team has the right to stop promoting and/or supporting existing projects for any reason with 1 week notice. However, the repository will remain available on GitHub and publicly accessible.
- If a member of the Code Career community wishes to start a project, he must pitch it by creating an issue using the "Project idea" template first in order to inhibit open discussion about the idea's feasibility.
- The member that submits an approved project idea will work with the CodeCareer team to maintain the repo and dictate future changes for that particular project. They will be able to: 
  - set contribution guidlines, code of conduct and regulations for project team members.
  - change, modify, remove and add rules of contribution. Changes will be made with 1 weeks notice.
- A contributor to one of Code Career's open-source projects is simply called "Contributor".
- The "Contributor" may suggest changes to any Code Career open-source project through [GitHub Issues](https://github.com/GitCodeCareer/open-source/issues).
- The "Contributor" may submit changes to the codebase of any of the Code Career open-source projects through a GitHub Pull Request (PR).
- To create a PR, the "Contributor" has to fork project first and create a PR through this forked repository.
- A "Contributor" is not considered part of the Code Career admin team and does not have admin-related permissions and roles.

## Key Contributors

Alex Crocker - Fullstack Developer | https://github.com/crock | https://twitter.com/crockerbytes

Jess Wallace - Data Analyst | https://github.com/JessWallace94 | https://twitter.com/jessxahmet

Daniel Philip Johnson - Front-end (React) Developer | https://github.com/danielphilipjohnson | https://twitter.com/danielp_johnson

Igor Gavelyuk - Front-end (React) Developer | https://github.com/igavelyuk | https://twitter.com/igavelyuk

Ajea Smith - Front-end (React) Developer | https://twitter.com/ajeasmith | https://github.com/AjeaSmith

Samuel T. Afolabi - UI/UX Designer | https://github.com/Folaborn1 | https://twitter.com/Folabornn 

Benjamin Spak - Product Manager - Full-stack Devloper | https://github.com/benjaminspak | https://twitter.com/benjaminspak

## Jira Ticket Naming Conventions

- Task names are in Capital Case.
- (category) - (task name)
  - Plan - Opensource Project Ideas
- Categories
  - Plan
  - Create
  - Integrate
  - Review
  - UX
  - Bug

## GitHub Branch Naming Conventions

- (category)--(feature name)
  - feature--foobar
  - improvement--fizzbuzz
  - bug-fix--wambam

## Naming Conventions & Code Style Overview:

### Defining Variables

- var - is a global variable and should be used in only extreamly exceptional cases.
  - var host = "http://localhost:5000";
- let - is a local varible that is block scoped. Use this for variables that will have their value altered.
  - let alteredData = [];
- const - is a local varible that is block scoped and is not expecited to have its value altered.
  - const DATA_WONT_CHANGE = 1;

### Picking File and Directory Names:

- Find a balance between descriptive and terse. When in doubt, be more descriptive than terse.
  - Why? To make debugging easier. Keep names as unique and descriptive as possible.
- Naming can be broken into a few basic parts.

#### Naming Functions & Files With Examples:

##### How to name a file: <action/quantity><who it belongs to><what it is>

##### Action/Quantity Categories for Naming Functions.

    - getAll
    - get
    - create
    - update
    - remove

##### Best:

    - getDevUserPostString()
    - getAllDevUserPosts()
    - single_dev_user_comment.css

##### Good:

    - getPostString()
    - getDevUserPosts()
    - dev_user_comment.css

##### Bad:

    - postString()
    - comments.css

##### File Name Formatting:

- Snake case view file names and database file names.
- Camel case helper JS files, functions & methods.
- Upper camel case for class file names, class based components and functional components.

##### Snake case examples:

- (Style Sheet) "commencement_registration_form.css", "commencement.css"
- (DB Table) "section_evaluation_question"

##### Upper camel case example:

- (Controller) "CommencementController.js"
- (React Component) "DevUserFeed.js"

##### Camel case example:

- (Function name) "getBackground()", "getColoredString()"
- (Functional Component) "employerUserFeed.js"

### Code Style

#### Quotes

- Use double quotes for stings, imports, includes, etc (""). We do not use single quotes.

#### Spacing

- Use two space indents (4 by default) when formatting code.

#### Component Design Pattern

- Include component specific css and helper functions within React components.
- /components/(component category)/(component dir)/
  - PostComment.js
  - Comments.js
- /components/(component category)/(asset dir)
  - /components/social/css
  - comments.css
  - posts.css

`

## :books: Dev Environment & Settings

[MERN Stack Front To Back: Full Stack React, Redux & Node.js > Environment & Setup](https://www.udemy.com/course/mern-stack-front-to-back/learn/lecture/10055132#overview) - Emmet and Prettier settings.

### Tools

- [MongoDB Atlas (Free Plan)](https://www.mongodb.com/cloud/atlas) - MongoDB Cloud Hosting
- [POSTman](https://www.postman.com/) - API End Point Checker
- [MongoDB Compass](https://www.mongodb.com/products/compass) - Mongo DB Management
- [Heroku](heroku.com) - Deployment
- [VSCode](https://code.visualstudio.com/) - IDE
- [DataDog](https://app.datadoghq.com/signup/agent#overview) - Monitoring & Security
- [Azure Data Studio](https://docs.microsoft.com/en-us/sql/azure-data-studio/download-azure-data-studio?view=sql-server-ver15) - DBMS

### Stack (MERN)

- [MongoDB](https://www.mongodb.com/)
- [React.js](https://reactjs.org/)
- [Node.js](https://nodejs.org/en/)
- [Express.js](https://expressjs.com/)
- [Mongoose.js](https://mongoosejs.com/)

### VSCode Extensions (Recommended)

- [Bracket Pair Colorizer](https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer)
- [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
- [Debugger for Chrome](https://marketplace.visualstudio.com/items?itemName=msjsdiag.debugger-for-chrome)
- [ES7 React/Redux/GraphQL/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
- [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
- [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
- [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
- [markdownlint](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint)
- [Peacock](https://marketplace.visualstudio.com/items?itemName=johnpapa.vscode-peacock)
- [Prettier - Code formatter](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- [Remote - SSH](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh)
- [Remote - SSH: Editing Configuration Files](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-ssh-edit)
- [Remote - WSL](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.remote-wsl)
- [WakaTime](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime)
- [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
- [DotENV](https://marketplace.visualstudio.com/items?itemName=mikestead.dotenv)
- [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)

### Chrome Extensions (Recommended)

- [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en)
- [Redux DevTools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en)
- [JSON Formatter](https://chrome.google.com/webstore/detail/json-formatter/bcjindcccaagfpapjjmafapmmgkkhgoa?hl=en)

## Workarounds and Fixes

- [Fix npm cmd error “internal/modules/cjs/loader.js:605” throw err](https://youtu.be/95zwKjgpMcE)

```
rm -rf node_modules package-lock.json && npm install && npm start
```

#### Odd CORS Issues While Developing in localhost

 Error: https as origin, locahost is on http. - HTTPS Everywhere
  
 Fix: Whitelist localhost or switch off HTTPS Everywhere extension for it. Protip: disable any other privacy/ad blocker plugins on localhost.
