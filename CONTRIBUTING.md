# Contribution Guide

Contributing to an open source project doesn't have to be through code alone. There are various ways in which you can contribute, and we're happy to accept all kinds of help. This guide will give you information on what kind of contributions you can make, and what steps you should follow.


(This is a living document and will be updated over time to help make contributions easier. Please make sure to read this guide from time to time and check what has changed.)

## Types of Contributions (Beginners and Advanced)

We're all just regular folks, those that write code, add comments, oversee the projects and of course those that use it. The rule of thumb is: if in doubt, **be kind**.

### Opening issues
Filing issues with the project is a great step in helping the project - you're helping us learn what's not working, what you might want to see in the project or what we can do better. Even questions like 'how do I do X?' help us know where documentation may be lacking. When opening an issue, please make sure to follow the issue templates. Doing that helps us gather the required initial information to be able to further assist.

### Commenting
Adding meaningful comments to issues and pull requests, helps the community as a whole. Providing suggestions, helping solving issues, giving feedback - it all helps. The main guideline we have here is 'be kind'.

### Voting
We're not big fans of adding comments like "+1", or "any updates on this?" but adding a :thumbsup: reaction to the opening comment helps us track what attracts more interest in our community, and what we should focus on next. 

### Code reviews
Even if you don't have time to contribute your own code, you may have time to review existing pull requests, helping us process those faster.

### Documentation
Improving the project documentation is a huge help. You don't need to be an expert in the project, or understand all the bits and pieces. Have you dealt with an issue and think that if there was better documentation it'd have been easier? Document that part! If you tried going through the documentation and found it hard to navigate - fix that!

### Improve the build process
Think we can make the build faster? Should we incorporate additional things in the build process? Make a suggestion.

### Tests
Adding tests is highly beneficial to any open source project. Tests can help in everal ways. They can ensure the current behavior is working properly and future changes don't break the functionality. They can also help expose existing issues for us to solve.

### Submitting code changes
Always welcome, but to reduce the chances of your PR being rejected see the section below.



## Code Contributions

Code changes can come in several forms, and the way they're handled differ.

### Documentation
For the most part, documentation PRs would be accepted after an initial review. Be aware that a large documentation change may require longer review and potentially a discussion.

### Bug fixes
Bug fixes are always welcome as PRs. If you found a bug and would like to fix it, it's almost always better to open a ticket describing the issue alongside the PR solving it. Sometimes, bug fixes can be controversial. If you think this may happen with your fix, please start a discussion through a ticket before filing an actual fix.

### Features
Adding features is a great way to improve an open source project. That said, each project has its own roadmap, requirements, constraints and needs. Before submitting a PR for _any_ feature, please file an issue first describing the change you want to make, and wait for feedback. Trying to analyze a feature contribution directly through a pull request is stressful for both sides, and a lot of concerns can be avoided by having an initial discussion.

### UI/UX Features (Swagger UI and Swagger Editor Only)
These are more challenging than regular features, as we need to make sure they play well with other features and requirements. We have an internal UX team that reviews such suggestions, making this process a bit longer. This does not mean such changes will not be accepted, but be prepared to take more extensive feedback, and at times, even have a proposal declined.

## Code Contribution Considerations

- As mentioned, in most cases it's better to open a ticket discussing the suggested change before actually making the change.

- Smaller changes are better. If you're working on a large change, it'd be much better to use smaller pull requests that are easier to manage and review than one large PR that contains a large amount of changes. If each PR cannot encapsulate a series of non-breaking changes, feel free to ask us to create a branch for you. You will then be able to make sequential PRs for review, and we will merge the branch when the work is complete.

- In a case where we, unfortunately, have to reject your code change, we'll try to suggest a way to plug the functionality externally. That way,  you (and others) can still make use of the change without it being part of the main codebase.
