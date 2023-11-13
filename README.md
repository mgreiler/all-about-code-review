# All About Code Review

This is a curated collection of articles, tools, checklists and other awesome resources about code reviews.
For more insights into code reviews go to [awesomecodereviews.com](https://www.awesomecodereviews.com/).

Contributions welcome - especially highlighting how different companies do code reviews.
If you want to suggest a new ressource, please open a pull request.

## Contents
- [Company Insights](#company-insights)
- [Code Review Articles](#code-review-articles)
- [Code Review Tools](#code-review-tools)
- [Code Review Videos](#code-review-videos)
- [Code Review Checklists](#code-review-checklists)


## Company Insights
Inisghts of different companies on their code review practices:
- [Facebook: Scaling Static Analyses at Facebook](https://research.fb.com/publications/scaling-static-analyses-at-facebook/)
- [Gitlab's Code Review Values](https://about.gitlab.com/handbook/engineering/workflow/reviewer-values/)
- [Google: Focusing on fast code reviews](https://www.michaelagreiler.com/code-reviews-at-google/)
- [Google: Code review guidelines](https://google.github.io/eng-practices/review/)
- [Microsoft: Understanding code review best practices](https://www.michaelagreiler.com/code-reviews-at-microsoft-how-to-code-review-at-a-large-software-company/)
- [Netlify: Feedback Ladders to encode review feedback](https://www.netlify.com/blog/2020/03/05/feedback-ladders-how-we-encode-code-reviews-at-netlify/)
- [New Relic: Creating Simple and Effective Guidelines for Code Reviews](https://blog.newrelic.com/engineering/code-review-guidelines/)
- [Palantir: How we do code reviews](https://medium.com/palantir/code-review-best-practices-19e02780015f)
- [Quora: Using post-commit reviews to increase speed.](https://www.quora.com/q/quoraengineering/Moving-Fast-With-High-Code-Quality)
- [PayPal's take on code reviews](https://medium.com/paypal-engineering/effective-code-reviews-53d62a203b2f)
- [Plaid Code Review Culture](https://plaid.com/blog/building-an-inclusive-code-review-culture/)
- [Raycast: No code reviews by default](https://www.raycast.com/blog/no-code-reviews-by-default/)
- [Shopify: Code Review Superpower](https://shopify.engineering/great-code-reviews)
- [SIG: how we do code reviews](https://medium.com/softwareimprovementgroup/how-we-do-code-reviews-at-sig-6e5189fb1e6c)
- [Squarespace: Creating a Code Review Culture Part 1](https://engineering.squarespace.com/blog/2019/code-review-culture-part-1)
- [Squarespace: Creating a Code Review Culture Part 2](https://engineering.squarespace.com/blog/2019/code-review-culture-part-2)


## Code Review Articles
This is a list of articles about code reviews grouped by the main topic.
- [Command Line Code Review](https://blog.jez.io/cli-code-review/)

- Do's and Don'ts in Code Reviews
  - [Satirical post about how to make code reviews soul crushing](https://daedtech.com/how-to-use-a-code-review-to-execute-someones-soul/)
  - [Satirical post: How to make enemies through code reviews](https://repohealth.io/blog/code-review-how-to-make-enemies/)
- Giving and Receiving Feedback
  - [Code Review Guidelines for Humans](https://phauer.com/2018/code-review-guidelines/)
  - [How to Do Code Reviews Like a Human by Michael Lynch](https://mtlynch.io/human-code-reviews-1/)
  - [How to Give Respectful and Constructive Code Review Feedback](https://www.michaelagreiler.com/respectful-constructive-code-review-feedback/)
  - [Unlearning Toxic Behaviors in a Code Review Culture by Sandya Sankarram](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c) A how-to guide for pull requests via how-not-too.

- Stacked Pull Requests:
  - [Stacked Diffs: Keeping Phabricator Diffs Small by Kurtis Nusbaum](https://medium.com/@kurtisnusbaum/stacked-diffs-keeping-phabricator-diffs-small-d9964f4dcfa6)
  - [Stacked Pull Requests for easier and faster code reviews by Michaela Greiler](https://www.michaelagreiler.com/stacked-pull-requests/)
  - [Stacked Pull Requests: Keeping GitHub Diffs Small by Grayson Koonce](https://unhashable.com/stacked-pull-requests-keeping-github-diffs-small/)
  - [Stacked Pull Requests Hackernews Discussion](https://news.ycombinator.com/item?id=18119570)
  - [Stacked Pull Request Tools](https://roman.pt/posts/large-pull-requests/)

- Truck-based Development and Code Reviews:
  - [Code Reviews in Trunk Based Development by Robert Ecker](https://team-coder.com/code-reviews-in-trunk-based-development/)

- [Interpersonal conflicts in code reviews](https://arxiv.org/pdf/2201.05425.pdf)
  -  Rejecting OSS contributions:
    - [SO discussion: unhelpful contribution](https://opensource.stackexchange.com/questions/1556/how-to-react-to-unhelpful-contributions-to-otherwise-unnoticed-projects)
    - [Linus Torvald rejecting a security fix](https://lkml.org/lkml/2020/6/1/726)
    - [Open source, not open contribution](https://news.ycombinator.com/item?id=25940195) and [project](https://github.com/benbjohnson/litestream)
    - [The art of closing](https://blog.jessfraz.com/post/the-art-of-closing/)
    - [Conflict management in OSS](https://codeengineered.com/blog/2018/open-source-conflict/)

- Bias in Code Reviews
  - [Facebook rejects female engineers’ code more often, analysis finds](https://www.theverge.com/2017/5/2/15517302/facebook-female-engineers-gender-bias-studies-report)
  - [Did gender bias drive code review differences at Facebook?](https://medium.com/inclusion-insights/did-gender-bias-drive-code-review-differences-at-facebook-2e1e4dbd8d62)
  - [Research study: Gender bias in open source pull requests](https://www.researchgate.net/publication/308716997_Gender_bias_in_open_source_Pull_request_acceptance_of_women_versus_men)

- Splitting Up Too Large Code Reviews
  - [Shrinking Code Reviews](https://alexgaynor.net/2015/dec/29/shrinking-code-review/)
  - [Splitting PRs](https://www.thedroidsonroids.com/blog/splitting-pull-request)
  - [Breaking up code](https://softwareengineering.stackexchange.com/questions/244688/breaking-up-classes-and-methods-into-smaller-units)
  - [Strategies for Small PRs](https://artsy.github.io/blog/2021/03/09/strategies-for-small-focused-pull-requests/)
  - [Planning Fallacy - why we underestimate work](https://thedecisionlab.com/biases/planning-fallacy)
  - [The art of small PRs](https://www.redoxengine.com/blog/the-art-of-the-small-pr/)
  - [Iterative reviewing without PRs using CodeStream](https://www.codestream.com/blog/smaller-pull-requests-are-like-faster-horses)


- Best Practices:
  - [Making Good Code Reviews Better](https://stackoverflow.blog/2019/09/30/how-to-make-good-code-reviews-better/)   
  - [20 questions for a valuable code review](https://www.darraghoriordan.com/2021/12/28/21-questiosn-how-to-do-valuable-code-reviews/)
  
— Rejecting OSS contributions
  — [Stack Overflow discussion: unhelpful contribution](https://opensource.stackexchange.com/questions/1556/how-to-react-to-unhelpful-contributions-to-otherwise-unnoticed-projects)
  — [Linus Torvald rejecting a security fix](https://lkml.org/lkml/2020/6/1/726)
  - [Using labels to make comments clearer: conventional comments](https://conventionalcomments.org/)
- Open Source Best Practices
  - [Open source maintainer guide](https://opensource.guide/best-practices/)
  - [Building Welcoming Communities](https://opensource.guide/building-community/)
  - [Ten simple rules for helping newcomers become contributors to open projects](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007296)
- Clean code and smells/ anti-patterns
community/)
  - [185 code smells](https://maximilianocontieri.com/series/code-smells)
  
- Code Review Survey
  - [Smartbear cide review survey 2021](https://smartbear.com/blog/top-10-insights-on-the-state-of-code-review/)

## Interesting Discussions
- [Tweet about why PRs are a bad idea](https://twitter.com/allenholub/status/1424040299764932623?s=20)
- [How to speed up code review assignment](https://news.ycombinator.com/item?id=11416746)
- [What do we know about the ROI of code reviews?](https://twitter.com/hhariri/status/1315606185937166336?s=20)
- [Discussion about PR foucs: Clean code not good. Bugs much better.](https://twitter.com/copyconstruct/status/1317277666823741440?s=20)
- [AWS team lead summarizes how to do PRs](https://twitter.com/curtiseinsmann/status/1317149417330364421?s=20)
- [How does one get better at reading code?](https://twitter.com/Madisonkanna/status/1463596918496399362?s=20)
- [Code Review Guidelines](https://twitter.com/gkcs_/status/1475781104821063681?s=20)
- [What to talk about when talking abot code reviews?](https://twitter.com/sback_/status/1488792150158495746?s=20&t=t5_-h_dBv8fG8ujfTjUF-w)
- Mini JavaScript Code Reviews in a Tweet from Simon Høiberg
  - [What to do about the average function?](https://twitter.com/SimonHoiberg/status/1317488112147234817?s=20)
  - [Should we approve or reject?](https://twitter.com/SimonHoiberg/status/1313803838357467136?s=20)
  - [Clean refactoring?](https://twitter.com/SimonHoiberg/status/1310136847197061121?s=20)
  - [What about this DOM element?](https://twitter.com/SimonHoiberg/status/1311191044915179521?s=20)
  - [Using the filter method in JavaScript](https://twitter.com/SimonHoiberg/status/1320299813657825281?s=20)
- [Subjectivity of clean code](https://twitter.com/tottinge/status/1649172861670821889?s=46&t=tYr5H3Z8rM69vGoM-6z9bA)

## Code Review Videos
- [10 Tips on How to give respectful code review feedback by Michaela Greiler](https://youtu.be/NNXk_WJzyMI)
- [Amazing Code Reviews: Creating a Superhero Collective by Alejandro Lujan for GOTO 2019](https://youtu.be/ly86Wq_E18o)


## Code Review Tools
- [Crucible](https://www.atlassian.com/software/crucible) Atlassian's on-premise code review tool.
- [Codacy](https://www.codacy.com/) Static analysis tool that acts as automated code review.
- [CodeGuru](https://aws.amazon.com/codeguru): Amazon's AI enabled automated code analysis tool.
- [Codelantis](https://www.codelantis.com): for understanding & reviewing pull requests (GitHub) or merge reqeusts (GitLab) faster
- [CodeSandbox CI bot](https://codesandbox.io/docs/ci) builds and deploys every pull request to allow code reviewers to see the code change in action.
- [CodeSee](https://www.codesee.io/): Visualize your codebase for code reviews.
- [CodeStream](https://www.codestream.com/) Code Collaboration Tool that allows for continious code reviews.
- [Gerrit](https://www.gerritcodereview.com/) Open source git code review tool originating out of Google.
- [GitHub](https://github.com) Git hosting and pioneer of the "Pull Request".
- [Gitpod](https://gitpod.io) Code review pull requests in a full IDE within your browser.
- [GitRise](https://www.gitrise.com/) Slack Reminders for GitHub pull requests
- [Kiro](https://www.kiro.io/) GitHub app that is your PR coach: review reminder and reviewer selection.
- [LGTM](https://lgtm.com) Automated Git code review for GitHub and Bitbucket pull requests for finding security vulnerabilities and code quality issues.
- [Phabricator](https://www.phacility.com/phabricator/) Open source git/mercurial/svn code review tool originating out of Facebook.
- [Prout: Deploy Reminder](https://github.com/guardian/prout) that reminds you that your pull request has been deployed in production and is ready to be tested.
- [PullRequest](https://www.pullrequest.com/) Code review as a service for GitHub pull requests.
- [Pull Reminders](https://pullreminders.com) Automated Slack reminders and metrics for GitHub pull requests.
- [Reviewable](https://reviewable.io/) Code review tool built on top of GitHub pull requests.
- [Review Board](https://www.reviewboard.org/) Open source review tool that is SCM/platform neutral.
- [ReviewNB](https://www.reviewnb.com/) Code review tool dedicated to review Jupyter Notebooks.
- [Rubberduck](https://www.rubberduck.io) Browser extension to adds code-aware navigation to GitHub pull requests.
- [Sider](https://sider.review/) Automated code review service for GitHub.
- [Softagram](https://softagram.com/) Automated code change visualization (and dependency analytics) for pull requests, merge requests (GitLab) and patch sets (Gerrit).
- [SonarCloud](https://sonarcloud.io) Detect code smells, bugs and vulnerabilities in Azure DevOps, Bitbucket and GitHub repositories.
- [TugBoat](https://www.tugboat.qa/) Builds and deploys each pull request for easier previews of the code under review.
- [Upsource](https://www.jetbrains.com/upsource/) JetBrain's on-premise git/mercurial/perforce/svn code review tool.
- [whatthediff.ai](https://whatthediff.ai/) AI based code review tool that explains your PR


## Code Review Checklists
- [A curated list of code review checklists](https://github.com/mgreiler/awesome-code-review-checklists) Contains code review checklists from General to Language-based (Java, C# etc.)
- [General Code Review Checklists](https://github.com/mgreiler/code-review-checklist) A language agnostic code review checklist containing all relevant aspects.
- [30+ items for Reviewing Java Code](https://www.java-success.com/30-java-code-review-checklist-items/) A checklist with concrete examples, covering aspects relevant to object-oriented programming.
- [Frontend pull request checklist](https://github.com/sapegin/frontend-pull-request-checklist) This a meta checklist that makes sure you have done all necessary checks before your frontend code goes through a pull request.
- [Practical short checklist](https://github.com/ryanmcdermott/code-review-tips): Shows a couple of basic readability/maintainability and security issues to check for.
- [Short Checklist for C#](https://github.com/samuelwill/csharp-code-review-checklist): Highlightning some basic checks.


## Developer Discussions about Code Review
- [Discussion on UX of Goodle Critique and other code review tools](https://news.ycombinator.com/item?id=19102930)


## Live Code Reviews
- [Code Review on YouTube for Python](https://youtu.be/Tf70szZwWgA): Small Pyhton game, where the reviewer also uses tests to see how the code works. Part of the review is fixing one bug, and making it Pep 8 conform, as well as fixing static analysis problems.
- [Java code review with a focus on making the code DRY](https://www.youtube.com/watch?v=uD37ZTosqmI&ab_channel=strager): Applying the don't repeat yourself principle during a code review.
- [Live refactoring of React code](https://www.youtube.com/watch?v=CF7uDDDe2BM&ab_channel=WebDevCody)
- [Live C++ Code Review](https://www.youtube.com/watch?v=rFnRzW3vvsQ&ab_channel=C%2B%2BWeeklyWithJasonTurner)
- [GERMAN: Code review JavaScript](https://www.youtube.com/watch?v=LxGDI0aG3rk&ab_channel=thenativewebGmbH)
- [Live Code Review - CTRE](https://www.youtube.com/watch?v=h1Qf_DYpfqs&ab_channel=C%2B%2BWeeklyWithJasonTurner): Reviewing a compile time PCRE compatible regular expression matcher - Compile time regular expressions
- [Security focused code review](https://www.youtube.com/watch?v=xBZps1k1sxI&ab_channel=FarahHawa): Bug bounty style review
- [Review for/by data scientists](https://www.youtube.com/watch?v=i6kVLu_Jx7M&ab_channel=Kaggle)
- [Flutter Code Review](https://www.youtube.com/watch?v=76P_0-loqzM&ab_channel=Flutter): 

## Losses due to low-quality software and technical debt
- [Security upgrades by major banks in wake of Russian cyber hacks spark IT glitches and crash mobile banking](https://www.dailymail.co.uk/news/article-6217839/Chaos-HSBC-customers-hundreds-locked-account.html)
- [Millions more bank customers hit by online account misery](https://www.thetimes.co.uk/article/millions-more-bank-customers-hit-by-online-account-misery-7xkcstxj3)
- [Traders switch to rival after IT bug downs London Stock Exchange](https://www.thetimes.co.uk/edition/business/traders-switch-to-rival-after-it-bug-downs-london-stock-exchange-ct06tmlmp)
- [Frequent Software Releases, Updates May Injure App Security](https://www.darkreading.com/application-security/frequent-software-releases-updates-may-injure-app-security/d/d-id/1330412)


## Initiatives
- [Code Review in Research by the Oxford Code Review Network](https://github.com/OxfordCodeReviewNet/)

## Practice Code Snippets
- [Vulnerable code snippets from We Hack](https://github.com/yeswehack/vulnerable-code-snippets)

