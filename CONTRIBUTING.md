<!--lint disable alphabetize-lists-->

[![test](https://github.com/aks-builds/awesome-rule-engines/actions/workflows/test.yml/badge.svg?event=push)](https://github.com/aks-builds/awesome-rule-engines/actions/workflows/test.yml)

# Contributing

Your contributions are always welcome!

## Guidelines

- Add one link per commit.

- Add one commit per Pull Request.

- Add the link: `- [project-name](http://example.com/) — A short description ends with a period.`

  - Keep descriptions concise, maximum number of characters is 350.
  - Each entry must be a real, current project. Verify license, maintenance status, and version compatibility against the upstream docs before submitting.

- Add a section if needed.

  - Add the section description.
  - Add the section title to the Table of Contents.

- Search previous suggestions before making a new one, as yours may be a duplicate.

- Check your spelling and grammar.

- Remove any trailing whitespace.

- Send a Pull Request with the reason why the project is worth including.

- Make sure the tests are passing.

## Styleguide

We use [`remark-lint`](https://github.com/remarkjs/remark-lint) to validate the style of `README.md` and `CONTRIBUTING.md`. Lint configuration lives in `.remarkrc`.

Refer to the [remark-lint rule docs](https://github.com/remarkjs/remark-lint#rules) when in doubt.

## Testing

To run tests locally you will need [Node.js](https://nodejs.org/) installed, then:

```shell
$ npm install
$ npm test
```
