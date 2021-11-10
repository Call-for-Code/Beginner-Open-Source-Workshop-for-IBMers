# Beginner's Open Source Workshop (for IBMers)

[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Slack](https://img.shields.io/static/v1?label=Community&message=%23open-source-general&color=blue)](https://callforcode.org/slack)

Simple lab for IBMers to start to use GitHub and submit their first pull request.

- [Create a GitHub Enterprise account](#create-a-github-enterprise-account)
- [Create a GitHub account](#create-a-github-account)
- [Link your GHE account with your GH account](#link-your-ghe-account-with-your-gh-account)
- [Exercise 1: Create your first pull request](#exercise-1-create-your-first-pull-request)
- [Exercise 2: Create your first repo from a template](#exercise-2-create-your-first-repo-from-a-template)
- [Next steps](#next-steps)

## Create a GitHub Enterprise account

[IBM uses GitHub Enterprise internally](https://www.youtube.com/watch?v=4wbxxzDp98c) for various software projects, project management, and general inner source development.

By [signing into GHE with your intranet id](https://github.ibm.com/), you'll create an account if you don't already have one. 

## Create a GitHub account

Now, go ahead and [sign up a public GitHub account](https://github.com/signup). It doesn't have to have the same user name, email, or password as your GHE account. We'll link the two in the next step.

## Link your GHE account with your GH account

Click the [GitHub account mapper button](https://w3.ibm.com/developer/open-source/) on the **Open Source @ IBM** page at on the intranet. Go through the steps to link your accounts.

## Exercise 1: Create your first pull request

With that done, it's now time to create your first GitHub contribution! Follow the steps in the [**Practice-Pull-Requests**](https://github.com/Call-for-Code/Practice-Pull-Requests) repo.

## Exercise 2: Create your first repo from a template

Ok, now that you've learned how to contribute to an existing project, it's time to create and configure your own repository from the [**Project Sample template**](https://github.com/Call-for-Code/Project-Sample).

First, click the green "Use this template" button at the top of the repo. Create a copy under your GitHub user name. You can make it public or private if you want to work on something before releasing it later.

![Fix](img/template.png)

This repo is a bit more complex than the pull reqest practices repo, but you'll notice that it has the same key `README.md`, `CONTRIBUTING.md`, and `LICENSE` files as you saw there.

From here, you'll want to get familiar with 4 of the tabs at the top of your repo. You've already worked with issues and pull requests. Let's ignore ZenHub (if you have it) and Actions for now and focus on **Projects**, **Wiki**, **Security**, **Insights**, and **Settings**.

![Fix](img/tabs.png)

### Projects

This is GitHub's built in project management feature for tracking issues on a board. It can be used similar to Trello or ZenHub. This is a good way to manage your wall of work and track progress during standups or scrums. You can create projects at the repo level, or manage tasks in many repos by using one at the organization level.

### Wiki

This is an alternative to providing your documentation alongside what's in the Code part of the repo. There are pros and cons to this, as folks may not know you have a wiki unless you explicitly point to it from your `README.md`. For a good example of how wikis are used alongside code, have a look at the **ClusterDuck Protocol** [**README.md**](https://github.com/Call-for-Code/ClusterDuck-Protocol) and [**wiki**](https://github.com/Call-for-Code/ClusterDuck-Protocol/wiki).

### Security

Here you can review how security issues are handles. There are some options you can check, and you'll quickly become familar with the GitHub [**dependabot**](https://github.com/dependabot) which will scan public repos for dependency vulnerabilities and often send you pull requests. If you're building a Node.js app, dependabot will be your new best friend.

### Insights

This tab serves as your metrics dashboard. You can see how your code is being updated over time, who your leading contributors are, and how many people are finding your repo from various links.

### Settings

Finally, this tab contains just about every other configuration for your project. You can manage user permissions here and invite others to collaborate on your project. One other interesting item is Pages. This allows you to publish a public website from your repository. So if you're looking for free webhosting (you can even point a custom domain at it) this could be interesting. This is used to host [**pyrrha-platform.org**](https://github.com/Pyrrha-Platform/Pyrrha-Website).

## Next steps

After you've gotten the hang of things through this workshop repository, we encourage you to continue learning more about contributing to open source.

1. Spend 4-6 hours on the [**free "Introduction to Open Source" class**](https://cognitiveclass.ai/courses/introduction-to-open-source). It's intended for technical and non-technical folks alike to learn about open source, which is becoming a key skill in today's world. You can earn a badge and certificate after completion.

1. Explore the existing [**Call for Code projects**](https://github.com/Call-for-Code/Project-Catalog) and make your first contribution! Anything from a small typo fix, to a language translation or documentation update, to an important code fix is welcome!
