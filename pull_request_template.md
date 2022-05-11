## Discussions and documentations

- [ ] Has a discussion happened between the developer and reviewer/s about the task and the implementation approach?
- [ ] Is there an LLD attached?
- [ ] Is there a brief task description of the task and the implementation approach written on the PR?
- [ ] Have the unit test cases been written? (https://payufin.atlassian.net/wiki/spaces/TEC/pages/1054016232/PSCore+unit+test+cases+conventions)
- [ ] Is there a brief description of the above test cases and the scenarios they cover?

## Coding guidelines
- [ ] Have the Python/Django coding conventions been followed? (https://payufin.atlassian.net/wiki/spaces/TEC/pages/1054016118/Python+Django+coding+conventions)
- [ ] Is there sufficient documentation/comments for new functions/classes/methods?
- [ ] Are the commit messages succinct and precise? (https://medium.com/swlh/writing-better-commit-messages-9b0b6ff60c67)
- [ ] Are there sufficient logs or alerts to debug potential issues?

## Design guidelines
- [ ] Have in-funnel users been taken into consideration?
- [ ] Is the design scalable and/or easily understandable (preferably both)?
- [ ] Are database migrations written in a non-breaking fashion?
- [ ] Is there no unnecessary refactoring mixed in with a feature?
- [ ] Are the changes independent of inter-service deployment order?