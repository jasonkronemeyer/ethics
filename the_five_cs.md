The Five Cs
===========

What does it take to build a good data product or service? Not just a
product or service that's useful, or one that's commercially viable, but
one that uses data ethically and responsibly.

We often talk about a product's technology or its user experience, but
we rarely talk about how to build a data product in a responsible way
that puts the user in the center of the conversation. Those products are
badly needed. News that people "don't trust" the data products they
use---or that use them---is common. While Facebook has received the most
coverage, lack of trust isn't limited to a single platform. Lack of
trust extends to nearly every consumer internet company, to large
traditional retailers, and to data collectors and brokers in industry
and government.

Users lose trust because they feel abused by malicious ads; they feel
abused by fake and misleading content, and they feel abused by "act
first, and apologize profusely later" cultures at many of the major
online companies. And users ought to feel abused by many abuses they
don't even know about. Why was their insurance claim denied? Why weren't
they approved for that loan? Were those decisions made by a system that
was trained on biased data? The slogan goes, "Move fast and break
things." But what if society is broken?

Data collection is a big business. Data is valuable: "the new oil," as
the [Economist proclaimed](http://econ.st/2CmpboL). We've known that for
some time. But the public provides the data under the assumption that
we, the public, benefit from it. We also assume that data is collected
and stored responsibly, and those who supply the data won't be harmed.
Essentially it's a model of trust. But how do you restore trust once
it's been broken? It's no use pretending that you're trustworthy when
your actions have proven that you aren't. The only way to get trust back
is to be trustworthy, and regaining that trust once you've lost it takes
time.

There's no simple way to regain users' trust, but we'd like to suggest a
"golden rule" for data as a starting point: "treat others' data as you
would have others treat your own data." However, implementing a golden
rule in the actual research and development process is
challenging---just as it's hard to get from short, pithy oaths and
pledges to actual practice.

What does it mean to treat others' data as you would treat your own? How
many data scientists have actually thought about how their own data
might be used and abused? And once you know how you'd like to see your
data (and others' data) respected, how do you implement those ideas? The
golden rule isn't enough by itself. We need guidelines to force
discussions with the application development teams, application users,
and those who might be harmed by the collection and use of data.

Five framing guidelines help us think about building data products. We
call them the five Cs: consent, clarity, consistency, control (and
transparency), and consequences (and harm). They're a framework for
implementing the golden rule for data. Let's look at them one at a time.

Consent
-------

You can't establish trust between the people who are providing data and
the people who are using it without agreement about what data is being
collected and how that data will be used. Agreement starts with
obtaining consent to collect and use data. Unfortunately, the agreements
between a service's users (people whose data is collected) and the
service itself (which uses the data in many ways) are binary (meaning
that you either accept or decline) and lack clarity. In business, when
contracts are being negotiated between two parties, there are multiple
iterations (redlines) before the contract is settled. But when a user is
agreeing to a contract with a data service, they either accept the terms
or they don't get access. It's nonnegotiable.

For example, when you check into a hospital you are required to sign a
form that gives them the right to use your data. Generally, there's no
way to say that your data can be used for some purposes but not others.
When you sign up for a loyalty card at your local pharmacy, you're
agreeing that they can use your data in unspecified ways. Those ways
certainly include targeted advertising (often phrased as "special
offers"), but may also include selling your data (with or without
anonymization) to other parties. And what happens to your data when one
company buys another and uses data in ways that you didn't expect?

Data is frequently collected, used, and sold without consent. This
includes organizations like Acxiom, Equifax, Experian, and Transunion,
that collect data to assess financial risk, but many common brands also
collect data without consent. In Europe, [Google collected
data](https://tcrn.ch/2LwZZ2Z) from cameras mounted on cars to develop
new mapping products. [AT&T and Comcast](http://bit.ly/2LlkRO7) both
used cable set top boxes to collect data about their users, and
[Samsung](http://bit.ly/2uBxqLs) collected voice recordings from TVs
that respond to voice commands. There are many, many more examples of
nonconsensual data collection. At every step of building a data product,
it is essential to ask whether appropriate and necessary consent has
been provided.


Clarity
-------

Clarity is closely related to consent. You can't really consent to
anything unless you're told clearly what you're consenting to. Users
must have clarity about what data they are providing, what is going to
be done with the data, and any downstream consequences of how their data
is used. All too often, explanations of what data is collected or being
sold are buried in lengthy legal documents that are rarely read
carefully, if at all. Observant readers of Eventbrite's user agreement
[recently discovered that listing an event gave the company the right to
send a video team, and exclusive copyright to the
recordings](http://bit.ly/2Ltk4uk). And the only way to opt out was by
writing to the company. The backlash was swift once people realized the
potential impact, and Eventbrite removed the language.

Facebook users who played Cambridge Analytica's "This Is Your Digital
Life" game may have understood that they were giving up their data;
after all, they were answering questions, and those answers certainly
went somewhere. But did they understand how that data might be used? Or
that they were giving access to their friends' data behind the scenes?
That's buried deep in Facebook's privacy settings.

Even when it seems obvious that their data is in a public forum, users
frequently don't understand how that data could be used. Most Twitter
users know that their public tweets are, in fact, public; but [many
don't understand that their tweets can be collected and used for
research](http://bit.ly/2mx5jsD), or even that they are [for
sale](https://developer.twitter.com/en/pricing.html). This isn't to say
that such usage is unethical; but as [Casey
Fiesler](http://caseyfiesler.com/) points out, the need isn't just to
get consent, but to inform users what they're consenting to. That's
clarity.

It really doesn't matter which service you use; you rarely get a simple
explanation of what the service is doing with your data, and what
consequences their actions might have. Unfortunately, the process of
consent is often used to obfuscate the details and implications of what
users may be agreeing to. And once data has escaped, there is no
recourse. You can't take it back. Even if an organization is willing to
delete the data, it's very difficult to prove that it has been deleted.

There are some notable exceptions: people like John Wilbanks are
[working](http://bit.ly/2JEEFqx) to develop models that help users to
understand the implications of their choices. Wilbanks' work helps
people understand what happens when they provide [sensitive medical and
health data to a service](http://bit.ly/2JE5I5x).


Consistency and Trust
---------------------

Trust requires consistency over time. You can't trust someone who is
unpredictable. They may have the best intentions, but they may not honor
those intentions when you need them to. Or they may interpret their
intentions in a strange and unpredictable way. And once broken,
rebuilding trust may take a long time. Restoring trust requires a
prolonged period of consistent behavior.

Consistency, and therefore trust, can be broken either explicitly or
implicitly. An organization that exposes user data can do so
intentionally or unintentionally. In the past years, we've seen many
security incidents in which customer data was stolen: Yahoo!, Target,
Anthem, local hospitals, government data, data brokers like Experian,
and the list grows longer each day. Failing to safeguard customer data
breaks trust---and safeguarding data means nothing if not consistency
over time.

We've also seen frustration, anger, and surprise when users don't
realize what they've agreed to. When Cambridge Analytica used Facebook's
data to target vulnerable customers with highly specific advertisements,
Facebook initially claimed that this was not a data breach. And while
Facebook was technically correct, in that data was not stolen by an
intruder, the public's perception was clearly different. This was a
breach of trust, if not a breach of Facebook's perimeter. Facebook
didn't consistently enforce its agreement with its customers. When the
news broke, Facebook became unpredictable because most of its users had
no idea what it would or wouldn't do. They didn't understand their user
agreements, they didn't understand their complex privacy settings, and
they didn't understand how Facebook would interpret those settings.


Control and Transparency
------------------------

Once you have given your data to a service, you must be able to
understand what is happening to your data. Can you control how the
service uses your data? For example, Facebook asks for (but doesn't
require) your political views, religious views, and gender preference.
What happens if you change your mind about the data you've provided? If
you decide you're rather keep your political affiliation quiet, do you
know whether Facebook actually deletes that information? Do you know
whether Facebook continues to use that information in ad placement?

All too often, users have no effective control over how their data is
used. They are given all-or-nothing choices, or a convoluted set of
options that make controlling access overwhelming and confusing. It's
often impossible to reduce the amount of data collected, or to have data
deleted later.

A major part of the shift in data privacy rights is moving to give users
greater control of their data. For example, Europe's [General Data
Protection Regulation](http://bit.ly/2BnbBUF) (GDPR) requires users'
data to be provided to them at their request and removed from the system
if they so desire.


Consequences
------------

Data products are designed to add value for a particular user or system.
As these products increase in sophistication, and have broader societal
implications, it is essential to ask whether the data that is being
collected could cause harm to an individual or a group. We continue to
hear about unforeseen consequences and the "unknown unknowns" about
using data and combining data sets. Risks can never be eliminated
completely. However, many unforeseen consequences and unknown unknowns
could be foreseen and known, if only people had tried. All too often,
unknown unknowns are unknown because we don't want to know.

Due to potential issues around the use of data, laws and policies have
been put in place to protect specific groups: for example, the
[Children's Online Privacy Protection Act](http://bit.ly/2zYrL7q)
(COPPA) protects children and their data. Likewise, there are laws to
protect specific sensitive data sets: for example, the [Genetic
Information Nondiscrimination Act](http://bit.ly/2LzvRV1) (GINA) was
established in 2008 in response to rising fears that genetic testing
could be used against a person or their family. Unfortunately, policy
doesn't keep up with technology advances; neither of these laws have
been updated. Given how rapidly technology is being adopted by society,
the Obama administration realized that the pace of the regulatory
process couldn't keep up. As a result, it created the roles of the US
chief technology officer and chief data scientist. The Obama
administration also established more than 40 chief data officers and
scientists across the federal government. The result has been to make
sure the regulatory process fosters innovation while ensuring the
question of potential of harm is asked regularly and often.

Even philanthropic approaches can have unintended and harmful
consequences. When, in 2006, AOL released anonymized search data to
researchers, it proved possible to "de-anonymize" the data and identify
specific users. In 2018, [Strava opened up their
data](http://bit.ly/2uR6Ptd) to allow users to discover new places to
run or bike. Strava didn't realize that members of the US military were
using GPS-enabled wearables, and their activity exposed the locations of
bases and patrol routes in Iraq and Afghanistan. Exposure became
apparent after the product was released to the public, and people
exploring the data started talking about their concerns.

While Strava and AOL triggered a chain of unforeseen consequences by
releasing their data, it's important to understand that their data had
the potential to be dangerous even if it wasn't released publicly.
Collecting data that may seem innocuous and combining it with other data
sets has real-world implications. Combining data sets frequently gives
results that are much more powerful and dangerous than anything you
might get from either data set on its own. For example, data about
running routes could be combined with data from smart locks, telling
thieves when a house or apartment was unoccupied, and for how long. The
data could be stolen by an attacker, and the company wouldn't even
recognize the damage.

It's easy to argue that Strava shouldn't have produced this product, or
that AOL shouldn't have released their search data, but that ignores the
data's potential for good. In both cases, well-intentioned data
scientists were looking to help others. The problem is that they didn't
think through the consequences and the potential risks.

It is possible to provide data for research without unintended
side-effects. For example, the US Internal Revenue Service (IRS), in
collaboration with researchers, opened a similar data set in a [tightly
controlled manner](http://bit.ly/2zXsjum) to help understand economic
inequality. There were no negative repercussions or [major policy
implications](https://nyti.ms/2LkEnKH). Similarly the Department of
Transportation releases data about [traffic
fatalities](http://bit.ly/2mxsPWl). The [UK
Biobank](http://www.ukbiobank.ac.uk/data-showcase/) (one of the largest
collections of genomic data) has a sophisticated approach to opening up
different levels of data. Other companies have successfully [opened up
data for the public benefit](http://bit.ly/2uAIJDK), including
[LinkedIn's Economic Graph project](https://economicgraph.linkedin.com/)
and [Google Books' ngram viewer](http://bit.ly/2JKo4C4).

Many data sets that could provide tremendous benefits remain locked up
on servers. Medical data that is fragmented across multiple institutions
limits the pace of [research](http://bit.ly/2LbS9Qr). And the data held
on traffic from ride-sharing and GPS/mapping companies could transform
approaches for traffic safety and congestion. But opening up that data
to researchers requires careful planning.


Implementing the Five Cs
------------------------

Data can improve our lives in many ways, from the mundane to the
amazing. Good movie recommendations aren't a bad thing; if we could
consolidate medical data from patients around the world, we could make
some significant progress on treating diseases like cancer. But we won't
get either better movie recommendations or better cancer treatments if
we can't ensure that the five Cs are implemented effectively. We won't
get either if we can't treat others' data as carefully as we'd treat
our own.

Over the past decade, the software industry has put significant effort
into improving user experience (UX). Much of this investment has been in
user-centric approaches to building products and services that depend on
the data the collective user base provides. All this work has produced
results: using software is, on the whole, easier and more enjoyable.
Unfortunately, these teams have either intentionally or unintentionally
limited their efforts to providing users with immediate gratification or
the ability to accomplish near-term goals. "Growth hacking" focuses on
getting people to sign up for services through viral mechanisms. We've
seen few product teams that try to develop a user experience that
balances immediate experience with long-term values.

In short, product teams haven't considered the impacts of the five Cs.
For example, how should an application inform users about how their data
will be used, and get their consent? That part of user experience can't
be swept under the rug. And it can't mean making it easy for users to
give consent, and difficult to say "no." It's all part of the total user
experience. Users need to understand what they are consenting to and
what effects that consent might have; if they don't, the designer's job
isn't done.

Responsibility for the five Cs can't be limited to the designers. It's
the responsibility of the entire team. The data scientists need to
approach the problem asking "what if" scenarios that get to all of the
five C's. The same is true for the product managers, business leaders,
sales, marketing, and also executives.

The five Cs need to be part of every organization's culture. Product and
design reviews should go over the five Cs regularly. They should
consider developing a checklist before releasing a product to the
public. All too often, we think of data products as minimal viable
products (MVPs: prototypes to test whether the product has value to
users). While that's a constructive approach for developing and testing
new ideas, even MVPs must address the five Cs. The same is true for
well-established products. New techniques may have been developed that
could result in harm in unforeseen ways. In short, it's about taking
responsibility for the products that are built. The five Cs are a
mechanism to foster dialogue to ensure the products "do no harm."
