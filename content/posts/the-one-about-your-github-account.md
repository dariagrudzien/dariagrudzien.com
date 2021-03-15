---
title: "The One About Your GitHub Account"
date: 2020-05-23T14:37:58+02:00
featured_image: "/img/richy-great-MAYEkmn7G6E-unsplash.webp"
---

**Or an opinionated guide to using your commit messages to show your work style to others.**

---

You may be interested in this post if you are:

* Thinking of getting a job in the field of web development, software engineering or a related discipline which includes writing code
* A **career-changer**, either going through a programming bootcamp or self-learning
* A **student** of Computer Science, IT or a related major, thinking of getting your first internship or a part-time job

* Early on in your career and thinking about looking for your next job
* Have been working in the same company, mostly on proprietary code, for many years now and are considering making a change

## tl;dr - In the world of web and software development, your [GitHub](https://github.com/) profile is your portfolio—you point people to it to show off your public work.

Your account activity tells people much more about you than just how well you can program. It’s worth knowing what your potential employers and colleagues are looking at, so that you can identify gaps in your knowledge and present your best work.

While there are other platforms that do the same—Atlassian’s [Bitbucket](https://bitbucket.org/) being one of them—this post will focus on GitHub as it has the largest community, most projects and is most commonly referred to—notice how many services ask for your GitHub URL.

## Learn Git—One Of The Most Popular Version Control Systems

Before we go on to discuss pushing code to GitHub, let’s start with a simplified introduction to Version Control Systems (VCS). A VCS allows multiple people to work on the same code base without it imploding much. This [intro from Atlassian does a good job of explaining in a bit more detail why VCS are used in the industry](https://www.atlassian.com/git/tutorials/what-is-version-control). Most companies use VCS during their day-to-day work, so showing that you know some basics will make your potential employers feel like there will be one thing less they will need to teach you during onboarding.

Git is one of the most common technologies used both by the industry and academia. Because it’s so popular, it comes with a lot of tooling—GitHub being one of them. It is a platform originally used to host Git repositories, which has since evolved to developing Git itself. GitHub is also home to a large community of developers who work on projects together. Those can include [Open Source Software (OSS)](https://learning.lpi.org/en/learning-materials/010-160/1/1.3/1.3_01/) which can be read by the public, and private projects including [proprietary software](https://en.wikipedia.org/wiki/Proprietary_software).

Resources to get you started with Git & GitHub:

* [Git Handbook by GitHub](https://guides.github.com/introduction/git-handbook/) is a good start
* [Git Tutorial By Atlassian](https://www.atlassian.com/git/tutorials/setting-up-a-repository) is a solid guide on working with repositories and collaborating with others
* [GitHub Guide To Creating A Project](https://guides.github.com/activities/hello-world/)
* [Git basics](http://rogerdudler.github.io/git-guide/) - will show you most common git operations
* [Git branches explained](https://www.youtube.com/watch?v=JTE2Fn_sCZs) - a relatively good summary of why and how to use Git branches, which is needed for working in a team but also awesome if you’re the only contributor
* [Learn Git Branching](https://learngitbranching.js.org/) - this will help you practice branching

Once you learn how to create repositories, prepare commits, push your code into local and remote repositories, and create Pull Requests (known as PRs) to merge your code into the master branch—it’s time to move on to the actual content.

### Getting Over The Fear Of Sharing Your Work In Progress With The World

If you are anything like me, you may cringe internally at the thought of showing anything other than absolute perfection to any human beings. I’ve got great news for you—that’s a [personality trait](https://en.wikipedia.org/wiki/Perfectionism_(psychology)) and you don’t have to be a slave of it for the rest of your life. Go read some self-help book and get that cruel master over the board of your life’s ship and go back to push some code. And then make some commits with fixes for bugs, typos, missing tests, missing files, etc.

Check out this experienced software developer's post saying that [it’s OK for your open source library to be a bit shitty](https://www.drmaciver.com/2015/04/its-ok-for-your-open-source-library-to-be-a-bit-shitty/). We’re all human—even the best programmers have bugs and typos in their work. If you don’t believe me, have a look at this [commit made by the author of Python in which he fixes a typo](https://github.com/gvanrossum/500lines/commit/aff34bb8b6ed8d5cfe6da5cc0ce3438f72d34522). We’re all in this life to improve as we go—iteratively. (And in most cases you can [rewrite git history](https://stackoverflow.com/questions/8981194/changing-git-commit-message-after-push-given-that-no-one-pulled-from-remote) if needed).

The whole point of using a VCS like Git is to be able to build your projects chunk by chunk. By adding a few functions here, a few tests there, then removing some code which is no longer needed, and fixing mistakes made in the past, you help your projects grow. What you want to avoid is trying to build a perfect project, and only then pushing it to a remote repository for others to see.

An additional benefit to being able to work with Git and GitHub is the improved chance to get help with your code from mentors—or sometimes even random, kind strangers of the interwebs. You can easily create a Pull Request in your repository and reviewers can post their comments directly in it. It’s much easier for someone else to have a look at the repository to understand what you’re trying to achieve, than go through random code snippets sent using [GitHub gists](https://gist.github.com/) or [Pastebin](https://pastebin.com/).

## Things Typical For Projects Versioned With Git And Pushed To GitHub

When it comes a GitHub repository, there’s a bunch of things that will speak volumes of who you are, how you think about problems, and what is your work routine, apart from your actual code:

### GitHub Flow

Do you know how to use branches in git? Do you know how to write [descriptive commit messages](https://chris.beams.io/posts/git-commit/)? Can you create a Pull Request, or do you push code straight into the master branch? Do you care about the code development lifecycle even if you work by yourself?

Creating Pull Requests, and going through the process of a [code review](https://smartbear.com/learn/code-review/what-is-code-review/) before your code gets deployed to production is an important way of avoiding introducing obvious bugs, a chance for you to learn from your colleagues, and ultimately write higher quality code. It also shows that you know Git enough to onboard into a team project faster—your new team won’t have to explain to you how to create and merge branches into master.

### Documentation

Does the project include a [README file](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-readmes)? Does the README include information on how to get started using the project? Are the instructions correct and easy to follow, so people can try them to play with your project on their machine? Is it written using a common format like [Markdown](https://guides.github.com/features/mastering-markdown/)? Are there any descriptions of repositories? Does the code itself include [comments that explain the why of the code](https://blog.codinghorror.com/code-tells-you-how-comments-tell-you-why/)? Does the author show that they care about users’ experience with their code?

You will spend [more time reading your own code than writing it](https://www.goodreads.com/quotes/835238-indeed-the-ratio-of-time-spent-reading-versus-writing-is). Your colleagues will read your code when you work on the same code base. **Working with people who care about writing documentation means working with people who care about others**. That’s the kind of people you want to be around, particularly when you’re just starting your career.

So go and read this [Beginners Guide To Docs](https://www.writethedocs.org/guide/writing/beginners-guide-to-docs/) and make the world a better place by writing some god damn docs!

### Tests

Do you know anything about code testing? Does your project include tests? Do you have at least some basic [unit tests](http://softwaretestingfundamentals.com/unit-testing/)? Is it clear from the documentation how to run the tests, so that potential contributors to your project know if their changes broke the existing code? And a question for 10 cookie points—have you heard of, and can you work using [Test Driven Development](https://www.freecodecamp.org/news/test-driven-development-what-it-is-and-what-it-is-not-41fa6bca02a2/)? Then comes a question for 50 cookie points—can you [automate testing](https://smartbear.com/learn/automated-testing/what-is-automated-testing/)?

Putting the effort to write tests matters when you work on creating software—in the long run, it [helps you be more productive](https://medium.com/@richbray/why-should-you-write-tests-910a3175d33c) and create more reliable products. People who test show that they care about the quality and reliability of their work. And you want to learn from people who do.

## How Do You Structure Your Work

Browsing through Git commits, reading commit messages and checking out the history of your project is a great way to see how you think about your work. Do you pick a convention and follow it? Do you break your work down into logical chunks? Do you pay attention to detail when it comes to administration of your project, not just programming?

You can expect such questions to come up in interviews, and actually thinking them through before you even apply for jobs makes sense. And having your decisions speak for themselves through Git history is a great way to showcase your way of thinking to other people.

## Summary

GitHub profile can be used as a portfolio of your work. It shows much more than just your programming skills. Ultimately, **it shows how ready you are to collaborate with other people to build great stuff, and continuously learn and improve your work**. Use this opportunity to show other people how you think and work.

_**Daria**_

---

P.S. Many thanks to [Honza Javorek](https://honzajavorek.cz/) for his review and suggestions which enriched this post.

P.P.S. When doing some research for this article I found out that indeed—there’s a nontrivial amount of studies related to personality types and GitHub. My favorite example is this bachelor’s thesis on the [exploration of personality traits of GitHub Developers as expressed in GitHub issues](https://elib.uni-stuttgart.de/handle/11682/10641).

It starts off by highlighting that “Software engineering is a highly collaborative process [...]. Whenever collaboration is a factor, personality of participants can affect the outcome, especially due to the nature of software development practices in which single people can hold tremendous decision making power and many developers work on definitive areas within the software itself.”

Looking at the table of contents I have to admit, though, that I get alarmed every time someone drags Freud into an innocent conversation.

![Banner](/images/dg-tcp.jpeg)
