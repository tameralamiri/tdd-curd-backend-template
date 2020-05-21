# How to contribute

Here are some important resources:
* where we are now: [this project life demo]
* what is the project roadmap: [project roadmap jira board]
* for bugs, and new features refer to the [github-issues](https://github.com/tameralamiri/tdd-curd-backend-template/issues)
* messaging channel to quick Q&A: slack or email-list

## TDD Test-Driven Development
This project is using [test-drive-development](http://agiledata.org/essays/tdd.html) which means requirements are turned into very specific test cases, then the code is improved so that the tests pass.

![tdd](tdd.png)

`Go` is the chosen dev language for this project, this means all the testing scripts should be written using the same language for automated testing and should live inside the `testing` directory.

### Golang Testing resources 
* official golang testing docs https://golang.org/pkg/testing/
* other golang resources https://quii.gitbook.io/learn-go-with-tests/


## Submitting changes
Before submitting any pull request for a new feature:
* Write a test script to test the new code that was developed
* Run a full coverage test to ensure the new code does not break anything of the current `master` code base
* Format the code to follow golint style
* Write a document to explain the internal processes and assumptions were used for this feature, add it to the `contribute` folder and append a link for it to `contribute/README.md` document under `APIs Development documentation` header
* writing an API document to explain the usage of this process for third party processes, add it to the `documentation` folder and append a link for it to `documentation/README.md` document under `APIs usage documentation` header

Before submitting any pull request for a bug fix:
* Write a test script to test the new code that was developed
* Run a full coverage test to ensure the new code does not break anything of the current `master` code base
* link the github bug issue to the submitted pull request


## Reporting bugs:
To report a bug create github issue for it:
* Write a clear title for the bug
* label the github issue  with `bug` label
* In the description section write:
    * how to recreate this bug
    * include all the error messages
    * what's the expected behavior
    * if applicable: which line of code causing the problem 

## Requesting features:
To request a feature create github issue for it:
* Write a clear title for the feature
* Use github issue labels to categorize the new feature type
* In the description section:
    * include any document or jira ticket to explain the feature in more details

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* When only changing documentation, include `[ci skip]` in the commit title
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :memo: `:memo:` when writing docs
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :lock: `:lock:` when dealing with security
    * :arrow_up: `:arrow_up:` when upgrading dependencies
    * :arrow_down: `:arrow_down:` when downgrading dependencies
    * :shirt: `:shirt:` when removing linter warnings

### Golang Style
Use golint to format the codes https://github.com/golang/lint

## APIs Development documentation
Here's the table of content for documentations of all the APIs and the logic that was developed up to date:

