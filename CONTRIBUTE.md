# How to contribute

Support and contributions from the open source community are essential for keeping
this projects up to date and always improving! There are a few guidelines that we need
contributors to follow to keep the project consistent, as well as allow us to keep
maintaining this project in a reasonable amount of time.

## Creating an Issue :bookmark:

Before you create a new Issue:

* Check the Issues of the repo concerned on Github to ensure one doesn't already exist, [node](https://github.com/weareopensource/Node/issues), [swift](https://github.com/weareopensource/Swift/issues), [angular](https://github.com/weareopensource/Angular/issues)
* Clearly describe the issue, including the steps to reproduce the issue, try to use a template on of our template defined in the repository
* If it's a new feature, enhancement, or restructure, explain your reasoning on why you think it should be added, as well as a particular use case.

And whatever your participation, we thank you :) !

## Making Changes :pencil:

* Fork the repository and create a topic branch from the master branch
* Check for unnecessary whitespace / changes with `git diff --check` before committing.
* Also check that your code is formatted properly, respect linter of every repo : 
	- EsLint
	- SwiftLint
	- ...
* Keep git commit messages clear and appropriate, we use [commitlint](https://github.com/conventional-changelog/commitlint), `type(scope): subject` , some examples : 
	- **type** : build, ci, chore, docs, feat, fix, perf, refactor, revert, style, test
	- **scope** : related to scopre / module concerned, helpers, config, core, users, tasks ..
	- refactor(helpers): subject :hammer: 
	- fix(task): subject :bug:
	- chore(tests): subject :fire:
	- feat(tasks): subject :sparkles:
	- docs(wiki): subject :books:
	- ci(travis): subject :construction_worker:


if you want to add some fun, [emoji](https://gitmoji.carloscuesta.me) :) 

* Make Sure you have added any tests necessary to test your code and run **all** the tests. Don't rely on the existing tests to see if you've broken code elsewhere; test the changes you made too!
* Update the Documentation to go along with any changes in functionality / improvements in a separate pull request against the gh-pages branch.
* If possible, please "squash" your commits to as few commits as possible/reasonable such as one commit for implementation, one for tests, and one for documentation before finally squashing to one commit when getting the LGTM from a collaborator.

And whatever your participation, we thank you a lot for participation :) !


## Submitting the Pull Request :racehorse:

* Push your changes to your topic branch on your fork of the repo.
* Submit a pull request from your topic branch to the master branch on the repository.
* Be sure to tag any issues your pull request is taking care of / contributing to.
* By adding "Closes #xyz" to a commit message will auto close the issue once the pull request is merged in.
* Small changes are usually accepted and merged in within a week 
* Larger changes usually spark further discussion and possible changes prior to being merged in.

## Generating a new Release :rocket:

* Don't forget to update the changelog! with standard-version
* Review, and commit changes

*Sharing of knowledge - #LetsGetTogether*
