# How to Contribute

We welcome contributions to this repo and encourage you to fork the project.
Thank you for your interest and time spent contributing!

## Issues and Pull Requests

If you are submitting an issue or a pull request, please prefix the title of the issue
or Pull Requests with the package name.

For Pull Requests, please target the `development` branch for any contributions.
To contribute, please check out the `development` branch, and then create your feature
branch from there:
```
  $ git checkout development         # start with the development
  $ git pull origin development      # pull remote repo changes
  $ git checkout your-feature-branch # create your feature branch
```
Then when you submit a Pull Request, please select the `development` branch to request
to merge your commits.

If you are interested in understanding this development style a bit further,
we follow the [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/)
model of branching, meaning that the `master` branch should be "stable". The quick
summary is that only release branches and bug-hotfixes are committed in the `master`
branch. The `release-*.*`branches are used for testing and bugfixes only.

## Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Remove dependency..." not "Removes dependency...")
- Limit the first line to 50 characters or less, and subsequent lines to 72 or less
- Reference issues and pull requests liberally with a hash and Issue or PR number

## Style

We follow the [C++ ROS style guidelines](http://ros.org/wiki/CppStyleGuide) and
[Python ROS style guidelines](http://wiki.ros.org/PyStyleGuide) as closely as possible.
Please ensure that any new contributions are compatible with C++11, Python2.7, and Python3.x.
