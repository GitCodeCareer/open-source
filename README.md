# CodeCareer Open-Source
> A global repository to store information and gather feedback about our current and future open-source projects

## CodeCareer As an Organization
Our Why: Save developers time and stress.
How We Do It: Code. Coffee. Curiosity. Empathy. Tenacity.
What We Make: A Social Career Development Platform and Suite of SaSS Tools for Developers.

How We Conduct Ourselves:
- "Why" Focused - "Save developers time and stress"
- No Bullshit - politics, ideologies, pissing contests, cliques, or big egos? Yeet!
- Be Humble - one has a right to be correct; one does not have a right to be an asshole.
- Have Grit - be resourceful, own your portion of the product, ask for help when stuck.
- Embrace Neurodiversity - each person has a unique way of creating solutions and getting work done.
- Fully Async Remote - multiple continents, multiple timezones & yet strong collaboration.

## Our Open Source Vision
Our vision for CodeCareer's open-source initiatives is to help budding developers on their journey to landing a full-time position in tech by providing the opportunity and guidance a new developer needs to make their first real world contribution that has a meaningful impact.

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
