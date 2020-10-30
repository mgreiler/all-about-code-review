# All About Code Review

This is a collection of articles, tools, trainings, checklists and other awesome resources about code reviews.

Contributions are very welcome. 

## Contents

- [Company Insights](#company-insights)
- [Code Review Articles](#code-review-articles)
- [Code Review Tools](#code-review-tools)
- [Code Review Videos](#code-review-videos)
- [Code Review Checklists](#code-review-checklists)


## Company Insights
Inisghts of different companies on their code review practices:
- [Facebook: Scaling Static Analyses at Facebook](https://research.fb.com/publications/scaling-static-analyses-at-facebook/)
- [Google: Focusing on fast code reviews](https://www.michaelagreiler.com/code-reviews-at-google/)
- [Google: Code review guidelines](https://google.github.io/eng-practices/review/)
- [Microsoft: Understanding best practices](https://www.michaelagreiler.com/code-reviews-at-microsoft-how-to-code-review-at-a-large-software-company/)
- [Netlify: Feedback Ladders to encode review feedback](https://www.netlify.com/blog/2020/03/05/feedback-ladders-how-we-encode-code-reviews-at-netlify/)
- [Palantir: How we do code reviews](https://medium.com/palantir/code-review-best-practices-19e02780015f)
- [Quora: Using post-commit reviews to increase speed.](https://www.quora.com/q/quoraengineering/Moving-Fast-With-High-Code-Quality)
- [PayPal's take on code reviews](https://medium.com/paypal-engineering/effective-code-reviews-53d62a203b2f)


## Code Review Articles
This is a list of articles about code reviews grouped by the main topic.
- Do's and Don'ts in Code Reviews
  - [Satirical post about how to make code reviews soul crushing](https://daedtech.com/how-to-use-a-code-review-to-execute-someones-soul/)
- Giving and Receiving Feedback
  - [How to Do Code Reviews Like a Human by Michal Lynch](https://mtlynch.io/human-code-reviews-1/)
  - [How to Give Respectful and Constructive Code Review Feedback](https://www.michaelagreiler.com/respectful-constructive-code-review-feedback/)
  - [Unlearning Toxic Behaviors in a Code Review Culture by Sandya Sankarram](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c) A how-to guide for pull requests via how-not-too.
- Stacked Pull Requests:
  - [Stacked Diffs: Keeping Phabricator Diffs Small by Kurtis Nusbaum](https://medium.com/@kurtisnusbaum/stacked-diffs-keeping-phabricator-diffs-small-d9964f4dcfa6)
  - [Stacked Pull Requests for easier and faster code reviews by Michaela Greiler](https://www.michaelagreiler.com/stacked-pull-requests/)
  - [Stacked Pull Requests: Keeping GitHub Diffs Small by Grayson Koonce](https://unhashable.com/stacked-pull-requests-keeping-github-diffs-small/)
  - [Stacked Pull Requests Hackernews Discussion](https://news.ycombinator.com/item?id=18119570)
- Truck-based Development and Code Reviews:
  - [Code Reviews in Trunk Based Development by Robert Ecker](https://team-coder.com/code-reviews-in-trunk-based-development/)


## Interesting Twitter Discussions
- [What do we know about the ROI of code reviews?](https://twitter.com/hhariri/status/1315606185937166336?s=20)
- [Discussion about PR foucs: Clean code not good. Bugs much better.](https://twitter.com/copyconstruct/status/1317277666823741440?s=20)
- [AWS team lead summarizes how to do PRs](https://twitter.com/curtiseinsmann/status/1317149417330364421?s=20)
- Mini JavaScript Code Reviews in a Tweet from Simon Høiberg
  - [What to do about the average function?](https://twitter.com/SimonHoiberg/status/1317488112147234817?s=20)
  - [Should we approve or reject?](https://twitter.com/SimonHoiberg/status/1313803838357467136?s=20)
  - [Clean refactoring?](https://twitter.com/SimonHoiberg/status/1310136847197061121?s=20)
  - [What about this DOM element?](https://twitter.com/SimonHoiberg/status/1311191044915179521?s=20)
  - [Using the filter method in JavaScript](https://twitter.com/SimonHoiberg/status/1320299813657825281?s=20)
  

## Code Review Videos
- [10 Tips on How to give respectful code review feedback by Michaela Greiler](https://youtu.be/NNXk_WJzyMI)
- [Amazing Code Reviews: Creating a Superhero Collective by Alejandro Lujan for GOTO 2019](https://youtu.be/ly86Wq_E18o)


## Code Review Tools
- [Crucible](https://www.atlassian.com/software/crucible) Atlassian's on-premise code review tool.
- [CodeGuru](https://aws.amazon.com/codeguru): Amazon's AI enabled automated code analysis tool.
- [CodeStream](https://www.codestream.com/) Code Collaboration Tool that allows for continious code reviews.
- [Gerrit](https://www.gerritcodereview.com/) Open source git code review tool originating out of Google.
- [GitHub](https://github.com) Git hosting and pioneer of the "Pull Request".
- [Gitpod](https://gitpod.io) Code review pull requests in a full IDE within your browser.
- [GitRise](https://www.gitrise.com/) Slack Reminders for GitHub pull requests
- [LGTM](https://lgtm.com) Automated Git code review for GitHub and Bitbucket pull requests for finding security vulnerabilities and code quality issues.
- [Phabricator](https://www.phacility.com/phabricator/) Open source git/mercurial/svn code review tool originating out of Facebook.
- [PullRequest](https://www.pullrequest.com/) Code review as a service for GitHub pull requests.
- [Pull Reminders](https://pullreminders.com) Automated Slack reminders and metrics for GitHub pull requests.
- [Reviewable](https://reviewable.io/) Code review tool built on top of GitHub pull requests.
- [Review Board](https://www.reviewboard.org/) Open source review tool that is SCM/platform neutral.
- [Rubberduck](https://www.rubberduck.io) Browser extension to adds code-aware navigation to GitHub pull requests.
- [Sider](https://sider.review/) Automated code review service for GitHub.
- [Softagram](https://softagram.com/) Automated code change visualization (and dependency analytics) for pull requests, merge requests (GitLab) and patch sets (Gerrit).
- [SonarCloud](https://sonarcloud.io) Detect code smells, bugs and vulnerabilities in Azure DevOps, Bitbucket and GitHub repositories.
- [TugBoat](https://www.tugboat.qa/) Builds and deploys each pull request for easier previews of the code under review.
- [Upsource](https://www.jetbrains.com/upsource/) JetBrain's on-premise git/mercurial/perforce/svn code review tool.

### Experiemental tools 
This section contains experiemental or small but handy bots that aim at making your live easier during code reviews.
[Prout: Deploy Reminder](https://github.com/guardian/prout) that reminds you that your pull request has been deployed in production and is ready to be tested.
[CodeSandbox CI bot](https://codesandbox.io/docs/ci) builds and deploys every pull request to allow code reviewers to see the code change in action.


## Code Review Checklists
- [General Code Review Checklists](https://github.com/mgreiler/code-review-checklist) A language agnostic code review checklist containing all relevant aspects.
- [30+ items for Reviewing Java Code](https://www.java-success.com/30-java-code-review-checklist-items/) A checklist with concrete examples, covering aspects relevant to object-oriented programming.
- [Frontend pull request checklist](https://github.com/sapegin/frontend-pull-request-checklist) This a meta checklist that makes sure you have done all necessary checks before your frontend code goes through a pull request.


## Losses due to low-quality software and technical debt
- [Security upgrades by major banks in wake of Russian cyber hacks spark IT glitches and crash mobile banking](https://www.dailymail.co.uk/news/article-6217839/Chaos-HSBC-customers-hundreds-locked-account.html)
- [Millions more bank customers hit by online account misery](https://www.thetimes.co.uk/article/millions-more-bank-customers-hit-by-online-account-misery-7xkcstxj3)
- [Traders switch to rival after IT bug downs London Stock Exchange](https://www.thetimes.co.uk/edition/business/traders-switch-to-rival-after-it-bug-downs-london-stock-exchange-ct06tmlmp)
- [Frequent Software Releases, Updates May Injure App Security](https://www.darkreading.com/application-security/frequent-software-releases-updates-may-injure-app-security/d/d-id/1330412)

