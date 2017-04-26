# Contributing to aptly

:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to [aptly](https://github.com/smira/aplty) and related repositories, which are hosted in the [aptly-dev Organization](https://github.com/aptly-dev) on GitHub.
These are just guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## What should I know before I get started?

### Code of Conduct

This project adheres to the Contributor Covenant [code of conduct](CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code.
Please report unacceptable behavior to [team@aptly.info](mailto:team@aptly.info).

### List of Repositories

* [smira/aptly](https://github.com/smira/aptly) - aptly source code, functional tests, man page
* [apty-dev/aptly-dev.github.io](https://github.com/aptly-dev/aptly-dev.github.io) - aptly website (https://www.aptly.info/)
* [aptly-dev/aptly-fixture-db](https://github.com/aptly-dev/aptly-fixture-db) & [aptly-dev/aptly-fixture-pool](https://github.com/aptly-dev/aptly-fixture-pool) provide
  fixtures for aptly functional tests

## How Can I Contribute?

### Reporting Bugs

1. Please search for similar bug report in [issue tracker](https://github.com/smira/aptly/issues)
2. Please verify that bug is not fixed in latest aptly nightly ([download information](https://www.aptly.info/download/))
3. Steps to reproduce increases chances for bug to be fixed quickly. If possible, submit PR with new functional test which fails.
4. If bug is reproducible with specific package, please provide link to package file.
5. Open issue at [GitHub](https://github.com/smira/aptly/issues)

### Suggesting Enhancements

1. Please search [issue tracker](https://github.com/smira/aptly/issues) for similar feature requests.
2. Describe why enhancement is important to you.
3. Include any additional details or implementation details.

### Improving Documentation

There are two kinds of documentation:

* [aptly website](https://www.aptly/info)
* aptly `man` page

Core content is mostly the same, but website contains more information, tutorials, examples.

If you want to update `man` page, please open PR to [main aptly repo](https://github.com/smira/aptly),
details in [man page](#man-page) section.

If you want to update website, please follow steps below:

1. Install [hugo](http://gohugo.io/)
2. Fork [website source](https://github.com/aptly-dev/aptly-dev.github.io) and clone it
3. Launch hugo in development mode: `hugo -w server`
4. Navigate to `http://localhost:1313/`: you should see aptly website
5. Update documentation, most of the time editing Markdown is all you need.
6. Page in browser should reload automatically as you make changes to source files.

We're always looking for new contributions to [FAQ](https://www.aptly.info/doc/faq/), [tutorials](https://www.aptly.info/tutorial/),
general fixes, clarifications, misspellings, grammar mistakes!

### Your Fist Code Contribution

Please follow [next section](#development-setup) on development process. When change is ready, please submit PR
following [PR template](.github/PULL_REQUEST_TEMPLATE.md).



## Development Setup

### Go & Python

### Forking and Cloning

### Dependencies

### Building

### Unit-tests

### Functional Tests

### Style Checks

### man Page

### Bash Completion

## Design

### Database

### Package Pool

### Package

### PackageList, PackageRefList

### LocalRepo, RemoteRepo, Snapshot

### PublishedRepository

### Context

### Collections, CollectionFactory
