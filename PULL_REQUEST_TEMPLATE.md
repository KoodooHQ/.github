## Description

<!--
High level description for the PR, what feature or fix is this PR delivering?
HINT: include link to the Jira ticket or GitHub issue, eg. "Fixes #127"
-->

### Summary

<!--
Summary of what has changed in this PR to deliver the feature or fix. Highlight
anything that is particularly important as a change so that it's in the
forefront of the reviewer's mind.
-->

### Prerequisites

<!--
Do I need any specific tools, applications, account access or configuration
to review and manually test this PR? Below are some examples, if specific
versions required, ensure this is specified:

  - `jq`
  - `docker`
  - `yarn`
  - `poetry`
  - `terraform >= 0.12`
  - https://gist.github.com/username/link-to-some-config
  - Access to Auth0 production

Delete this section if necessary or specify "None".
-->

### Commitment to review

<!--
How much time and effort is required to review this PR? If this commitment is
large, can you break the PR up into smaller PRs?

Don't worry about accuracy, we're trying to give a rough estimate to reviewers
so that they can plan this in around their other work. Think about how long it
might take you to review a similar PR.

Delete this section if you don't want/need it, however it's good to try to be
kind and courteous to your reviewers and set some expectations on how much
time you might require for them to look at your changes.
-->

  - Reviewing changes takes about _n minutes_.<!-- Rough estimate.  -->
  - Reviewing _n files_.<!-- The number of relevant files to review.  -->

### Review instructions

<!--
This should be a list of any manual tests to run, or links to the relevant
files to review. Picking key files to link to is important if there are a lot
of changes in formatting.

Keep in mind that if you are requesting reviews across multiple disciplines
(dev, platform, data), that you may need to put in links to documentation for
workstation setup or instructions on how to run the code to ensure
accessability to everyone.

These should form the basis for building an acceptance criteria, think about
how to demonstrate that the changes contribute to the desired fix or feature
referenced in the Jira ticket/GitHub issue.

For example:

  - Ensure your workstation is set up as per the
    [Macbook Setup guide](https://xxx.atlassian.net/wiki/workstation-setup)
  - Ensure you have installed dependencies as per the
    [README.md](https://github.com/...#installing-dependencies)
  - Open the project in the VSCode devcontainer
  - AC1: `molecule test --all`
  - AC2: Ensure this file has changes in the container
    - `molecule login -h sles`
    - `grep "server" /etc/ntp.conf`
  - AC3: Review the changes to [README.md](https://github.com/...)
-->

### Acceptance criteria

<!--
A checklist that relates to how the changes will deliver the desired fix or
feature. This is evidence of you being aware of any acceptance criteria defined
in the ticket/issue, but also serves to help the reviewer focus on what is
important that is delivered by this PR.

A reviewer might have their own acceptance criteria as well with regards to
code quality or style, if you feel it is relevant or would like your reviewer
to consider this include this in the checklist.

Examples:

  - [ ] AC1: Molecule tests pass
  - [ ] AC2: NTP config is updated as expected
  - [ ] AC3: README has been updated to include the new NTP options
  - [ ] Tests pass in GitHub Actions
  - [ ] LGTM :+1:

The below are standard acceptance criteria that should be included in most
PRs, however feel free to delete items that are not relevant (eg. if there are
no changes to documentation required).
-->

  - [ ] Documentation updated <!-- A reminder to do this! -->
  - [ ] Checks pass in GitHub Actions/CircleCI <!-- Goes without saying! -->
  - [ ] LGTM :+1: <!-- Just because ;) -->

### References

<!--
Delete this section if it is not required.

Links to articles, wikis, Stack Overflow questions, etc. that are relevant and
support the changes being made in this PR.
-->
