# Apps Empathy Issues

This repository is to be used to reproduce build-related issues sent to the apps team.

The `main` branch was created with `yarn create storybook` as a react+vitest project using `yarn`.

## Chromatic Projects

There are linked projects on production and staging that can be used to run builds on:

- `yarn chromatic`
- `yarn chromatic-staging`

Feel free to create you own projects to build against if necessary.

## Workflow

- Create a new branch named for the issue you're reproducing (you can use the linear branch name or ticket number for this)
- Make the necessary changes
- Run builds, make note of any necessary build parameters
- Share in the ticket/QA steps

Typically these branches highlight a specific setup and won't be merged back to `main`, but feel free to update `main` with changes we'll typically want in all of these branches, and/or make new base branches with different long-term setup that we'll want to share (like `a11y-disabled` for example).

### Needless change

Making a needless change to the readme!
