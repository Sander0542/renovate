# Major Releases

## When will we push a major version?

- There is no set schedule for major version releases **??**
- If we need to bump the **minor** (or major) version of Node.JS required to run Renovate
- At **??**
- If we have a few breaking changes "piling up" **??**
- If we have **??**

## Preparing

- Determine what's in the next release by looking at the [Milestones view](https://github.com/renovatebot/renovate/milestones)

### Draft release notes

It is worthwhile drafting the release notes ahead of time, ideally on a GitHub Discussion or Issue, so you can preview what GitHub Flavoured Markdown thinks **??**.

For example see [how v42 release notes were drafted](https://github.com/renovatebot/renovate/discussions/38841#discussioncomment-14770478).

### Branches

1. create a temporary branch for release, eg next-major (from main)
1. merge all planned breaking pr's to that branch
1. note issues to close
1. create a pr from temp branch to main (add ci:fulltest label)
1. add closes issues keywords (from noted above, so they get auto-closed)
1. wait for ci
1. rebase release branch onto main if required and goto 6.
1. use git cli to push release branch to main (no force! github will close pr as merged)
1. wait for release
1. update release notes if needed

## Implementing

When ready to "push the button", **??**

## Post-release

- Monitor Discussions for early insights about post-release bugs that need to be resolved
