# Git

## Git commit messages

Good git commit messages are helpful for consistency with your collaborators. They also make your code workflow thoughtful and professional. There doesn't seem to be an industry-wide standard on _the_ perfect message format, but for our purposes, the most helpful guide to reference is [this one](http://chris.beams.io/posts/git-commit/). It proposes this easy [rule set to follow](http://chris.beams.io/posts/git-commit/#seven-rules):

> 1. Separate subject from body with a blank line
> 1. Limit the subject line to 50 characters
> 1. Capitalize the subject line
> 1. Do not end the subject line with a period
> 1. Use the imperative mood in the subject line
> 1. Wrap the body at 72 characters
> 1. Use the body to explain what and why vs. how

Please read through and reference the post for more detail on each of the items above.

We also have a few in-house additions to this:

> 1. Reference the relevant Redmine/GitHub issue at the beginning of each commit, e.g. "Issue #123: Fix git commit message docs"
> 1. If you find yourself leaving important/lengthy notes in the commit body, consider whether that message should also be present as code comments for improved discoverability

## Creating a good pull request

A pull request is an important piece of communication, both to other developers reviewing your code and to future developers who need to understand the history of the project.
Like commit messages, pull request titles should start with `Issue #___: ` and be a one-line summary of what the PR does. **If your pull request is not ready for review**, mark it
as a work-in-progress by putting `[WIP]` in front of the title.

 A good pull request description should:
 
* Give a concise summary of what changes are introduced to the codebase and/or functionality in the pull request. Often we do this using a bullet list.
* List any steps which will necessary to deploy the pull request, both locally and in production -- this should have all the information necessary to deploy.
* Give any specific instructions that are necessary for testing. Include links to URLs for testing whenever you can!
* Specify any specific issues that you want developers doing peer review to be sure to investigate thoroughly.
* Give a timeframe for review.

Once the pull request is open, you should also assign a specific reviewer in GitHub, set the applicable Redmine task(s) status to `Developer Review`, assign those
 tasks to the reviewer, and paste a link to the pull request in the `GitHub PR` field. If the request is urgent, you should also communicate with the reviewing developer
 via some other channel rather than relying on them to get GitHub or Redmine notifications.

## Git workflows

### Git flow

### GitHub flow

## Code review
