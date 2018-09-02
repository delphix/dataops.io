# dataops.io

DataOps open source site at datops.github.io.

#### Table of Contents
1.  [Installation](#installation)
2.  [Contribute](#contribute)
    *   [Code of conduct](#code-of-conduct)
    *   [Community Guidelines](#community-guidelines)
    *   [Contributor Agreement](#contributor-agreement)
3.  [Reporting Issues](#reporting-issues)
4.  [Statement of Support](#statement-of-support)
5.  [License](#license)

## <a id="installation"></a>Installation

To get started, you will need to follow the instructions for installing
<a href="https://jekyllrb.com/">jekyll</a>. For a vanilla Ubuntu 16.04 ec2 instance,
this will look like the following:

```
	sudo apt-get update
	sudo apt-get install -y ruby ruby-all-dev gcc make g++ zlib1g-dev libcurl3
	sudo gem install jekyll bundle
	git clone <url>
	cd dataops.github.io
```

One you have jekyll installed, you will need to install the bundle from within the
repository, which will include the latest github-pages plugin required to
get the repository data:

```
	bundle install
```

From then on, you can start the webserver with:

```
	bundle exec jekyll serve
```

## <a id="contribute"></a>Contribute

1.  Fork the project.
2.  Make your bug fix or new feature.
3.  Add tests for your code.
4.  Send a pull request.

Contributions must be signed as `User Name <user@email.com>`. Make sure to [set up Git with user name and email address](https://git-scm.com/book/en/v2/Getting-Started-First-Time-Git-Setup). Bug fixes should branch from the current stable branch. New features should be based on the `release` branch.

#### <a id="code-of-conduct"></a>Code of Conduct

This project operates under the [Delphix Code of Conduct](https://delphix.github.io/code-of-conduct.html). By participating in this project you agree to abide by its terms.

#### <a id="contributor-agreement"></a>Contributor Agreement

All contributors are required to sign the Delphix Contributor agreement prior to contributing code to an open source repository. This process is handled automatically by [cla-assistant](https://cla-assistant.io/). Simply open a pull request and a bot will automatically check to see if you have signed the latest agreement. If not, you will be prompted to do so as part of the pull request process.


## <a id="reporting_issues"></a>Reporting Issues

Issues should be reported [here](https://github.com/delphix/delphix.github.io/issues).

## <a id="statement-of-support"></a>Statement of Support

This software is provided as-is, without warranty of any kind or commercial support through Delphix. See the associated license for additional details. Questions, issues, feature requests, and contributions should be directed to the community as outlined in the [Delphix Community Guidelines](https://delphix.github.io/community-guidelines.html).

## <a id="license"></a>License

This is code is licensed under the Apache License 2.0. Full license is available [here](./LICENSE).
