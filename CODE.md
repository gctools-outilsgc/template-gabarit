# Code Standards :tada:

## Intro :boom:

Here we will have a happy little intro about the purpose of this document :ok_hand:

## Code Styles, Codacy and Linters :muscle:

We like to use existing code style guides and standards. These are well documented, have linters and packages to help write consistent code with other devs!

Here we will talk about [Codacy](https://app.codacy.com/project/gctools-outilsgc/concierge/dashboard) and how we will use it.

Explain how it will run on each commit / pull request and must pass before we merge the pull request.
Explain how we have our own code standards configured in Codacy based on the documentation below.

We should talk about code test coverage that may also be tested by Codacy.

I'd like to discuss how to use and install linters and configs for linters. Maybe I'll discuss that in each language section. :fire:

## Languages :sparkles:
Here are the code standards for different languages. We also have links to linters that are supported by Codacy. You can add these linters to your projects. :+1:

### PHP :older_man:

#### Code Style
* [PEAR](https://pear.php.net/manual/en/standards.php)
#### Linter
* [PHP Code Sniffer](https://github.com/squizlabs/PHP_CodeSniffer)
#### Test Coverage
* [PHP Code Coverage for Codacy](https://github.com/codacy/python-codacy-coverage)

### Javascript :godmode:

#### Code Style
* [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
#### Linters / Config
* [ESLint](https://eslint.org/)
* [GCTools ESLint Config Package](https://github.com/gctools-outilsgc/gctools-components/tree/master/packages/eslint-config)
#### Test Coverage
* [Code Coverage for Codacy](https://github.com/codacy/node-codacy-coverage)

### Python :snake:

#### Code Style
* [PEP 8](https://www.python.org/dev/peps/pep-0008/)
#### Linter
* [Pylint](https://www.pylint.org/)
#### Test Coverage
* [Code Coverage for Codacy](https://github.com/codacy/python-codacy-coverage)

### CSS / Sass :art:

#### Code Style
* [Airbnb Style Guide](https://github.com/airbnb/css)
#### Linters
* [CSSLint](https://github.com/CSSLint/csslint)
* [Stylelint](https://stylelint.io/)

### Go :rat: (no gopher emoji :cry:)

#### Code Style
* [Effective Go](https://golang.org/doc/effective_go.html)
* [CodeReviewComments](https://github.com/golang/go/wiki/CodeReviewComments)
#### Linter
* [Golint Repo](https://github.com/golang/lint)
#### Test Coverage
* [Code Coverage for Codacy](https://github.com/schrej/godacov)

### Dockerfile :whale:

#### Style
* [Dockerfile Best Practices](https://docs.docker.com/develop/develop-images/dockerfile_best-practices/)
#### Linter
* [Hadolint](https://github.com/hadolint/hadolint)

## Document Naming Convention?

## Reference