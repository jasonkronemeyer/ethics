Of Oaths and Checklists
=======================

> "Oaths? We don't need no stinkin' oaths." (With apologies to
> Humphrey Bogart in *Treasure of the Sierra Madre*.)

Over the past year, there has been a great discussion of data ethics,
motivated in part by discomfort over "fake news," targeted advertising,
algorithmic bias, and the effect that data products have on individuals
and on society. Concern about data ethics is hardly new; the
[ACM](http://ethics.acm.org/code-of-ethics),
[IEEE](https://www.ieee.org/about/compliance.html), and the [American
Statistical Association](http://bit.ly/2zWQAk0) all have ethical codes
that address data. But the intensity with which we've discussed ethics
shows that something significant is happening: data science is coming of
age and realizing its responsibilities. A better world won't come about
simply because we use data; data has its dark underside.

The recent discussion frequently veers into a discussion of [data
oaths](http://bit.ly/2zRvEe8), looking back to the ancient [Hippocratic
Oath](http://bit.ly/2A4QiYA) for doctors. Much as we appreciate the work
and the thought that goes into oaths, we are skeptical about their
value. Oaths have several problems:

-   They're one-shots. You take the oath once (if at all), and that's
    it. There's no reason to keep it in the front of your
    consciousness. You don't recite it each morning. Or evaluate
    regularly whether you're living up to the ideals.

-   Oaths are a set of very general and broad principles. Discussions of
    the Hippocratic Oath begin with the phrase "First, do no harm,"
    words that don't actually appear in the oath. But what does "do no
    harm" mean? For centuries doctors did very little but harm (many
    people died because doctors didn't believe they needed to wash their
    hands). The doctors just didn't know they were doing harm. Nice
    idea, but short on the execution. And data science (like medicine)
    is all about execution.

-   Oaths can actually give cover to people and organizations who are
    doing unethical work. It's easy to think "we can't be unethical,
    because we endorsed this oath." It's not enough to say "don't be
    evil." You have to not be evil.

-   Oaths do very little to connect theories and principles to practice.
    It is one thing to say "researchers must obtain informed consent";
    it's an entirely different thing to get informed consent at
    internet scale. Or to teach users what "informed consent" means.

We are not suggesting that the principles embodied in oaths aren't
important, just that they don't get us to the endpoint we want. They
don't connect our ideas about what's good or just to the practices
that create goodness and justice. We can talk a lot about the importance
of being fair and unbiased without knowing about how to be fair and
unbiased. At this point, the oath actually becomes dangerous: it becomes
a tool to convince yourself that you're one of the good guys, that
you're doing the right thing, when you really don't know.

Oaths are good at creating discussion---and, in the past year, they have
created quite a lot of discussion. The discussion has been tremendously
helpful in making people aware of issues like algorithmic fairness. The
discussion has helped software developers and data scientists to
understand that their work isn't value-neutral, that their work has real
impact, both good and bad, on real people. And there has been a vigorous
debate about what self-government means for data scientists, and what
guiding principles would last longer than a few years. But we need to
take the next step, and connect these ideas to practice. How will we do
that?

In 2009, Atul Gawande wrote *The Checklist Manifesto* (Macmillan), a
short book on how not to make big mistakes. He writes a lot about his
practice as a surgeon. In a hospital, everyone knows what to do.
Everyone knows that you're supposed to scrub down before the surgery.
Everyone knows that you're not supposed to amputate the wrong leg.
Everyone knows that you're not supposed to leave sponges and other
equipment in patients when you close the incision.

But mistakes are made, particularly when people are in stressful
environments. The surgeon operates on the wrong leg; the sponge is left
behind; and so on. Gawande found that, simply by creating checklists for
basic things you shouldn't forget, these mistakes could be eliminated
almost completely. Yes, there were some doctors who found the idea of
checklists insultingly simple; they were the ones who continued making
mistakes.

Unlike oaths, checklists connect principle to practice. Everyone knows
to scrub down before the operation. That's the principle. But if you
have to check a box on a form after you've done it, you're not likely
to forget. That's the practice. And checklists aren't one-shots. A
checklist isn't something you read once at some initiation ceremony; a
checklist is something you work through with every procedure.

What would a checklist for data science and machine learning look like?
The [UK Government's Data Ethics Framework](http://bit.ly/2NvJ0ik) and
[Data Ethics Workbook](http://bit.ly/2O69wjh) is one approach. They
isolate seven principles, and link to detailed discussions of each. The
workbook asks a number of open-ended questions to probe your compliance
with these principles. Our criticism is that their process imposes a lot
of overhead. While anyone going through their entire process will
certainly have thought carefully about ethical issues, in practice,
asking developers to fill out a workbook with substantive answers to 46
questions is an effective way to ensure that ethical thought doesn't
happen.

We believe that checklists are built around simple, "have we done this?"
questions---and they are effective because they are simple. They don't
leave much room to wiggle. Either you've analyzed how a project can be
abused, or you haven't. You've built a mechanism for gathering consent,
or you haven't. Granted, it's still possible to take shortcuts: your
analysis might be inadequate and your consent mechanism might be flawed,
but you've at least gone on record for saying that you've done it.

Feel free to use and modify this checklist in your projects. It covers
most of the bases that we've seen discussed in various data oaths. Go
over the checklist when starting a project so the developers know what's
needed and aren't surprised by a new set of requirements at the last
minute. Then work through it whenever you release software. Go through
it, and actually check off all the boxes before your product hits the
public.

Here's a checklist for people who are working on data projects:

❏ Have we listed how this technology can be attacked or abused?

❏ Have we tested our training data to ensure it is fair and
representative?

❏ Have we studied and understood possible sources of bias in our data?

❏ Does our team reflect diversity of opinions, backgrounds, and kinds of
thought?

❏ What kind of user consent do we need to collect to use the data?

❏ Do we have a mechanism for gathering consent from users?

❏ Have we explained clearly what users are consenting to?

❏ Do we have a mechanism for redress if people are harmed by the
results?

❏ Can we shut down this software in production if it is behaving badly?

❏ Have we tested for fairness with respect to different user groups?

❏ Have we tested for disparate error rates among different user groups?

❏ Do we test and monitor for model drift to ensure our software remains
fair over time?

❏ Do we have a plan to protect and secure user data?

Oaths and codes of conduct have their value. The value of an oath isn't
the pledge itself, but the process you go through in developing the
oath. People who work with data are now having discussions that would
never have taken place a decade ago. But discussions don't get the hard
work done, and we need to get down to the hard work. We don't want to
talk about how to use data ethically; we want to use data ethically.
It's hypocritical to talk about ethics, but never do anything about it.
We want to put our principles into practice. And that's what checklists
will help us do.

---

##### This work was forked from:

**Original Repository:** [Ethics and Data Science](https://resources.oreilly.com/examples/0636920203964)

**Authors:** Mike Loukides, Hilary Mason, and DJ Patil, O'Reilly Media, Inc.

**Recommended Citation:** Loukides, M., Mason, H., & Patil, D. J. (n.d.). Ethics and Data Science. O'Reilly Media, Inc. Retrieved from https://resources.oreilly.com/examples/0636920203964/ 

**Forked Repository:** [Ethics](github.com/jasonkronemeyer/ethics)

**Modifications:** As of March 1, 2024, the only revisions that have been made are the internal links to the forked repository and the correct reference links in the origin repository.

**Date of Fork:** March 1, 2021

### &copy; 2024 O’Reilly Media, Inc. All rights reserved.
