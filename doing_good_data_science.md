
Doing Good Data Science
=======================

The hard thing about being an ethical data scientist isn't understanding
ethics. It's the junction between ethical ideas and practice. It's doing
good data science.

There has been a lot of healthy discussion about data ethics lately. We
want to be clear: that discussion is good, and necessary. But it's also
not the biggest problem we face. We already have good standards for data
ethics. The [ACM's code of ethics](http://bit.ly/2zUY4E7), which dates
back to 1993, and is currently being updated, is clear, concise, and
surprisingly forward-thinking; 25 years later, it's a great start for
anyone thinking about ethics. The [American Statistical
Association](http://bit.ly/2mzaMPw) has a good set of ethical guidelines
for working with data. So, we're not working in a vacuum.

And we believe that most people want to be fair. Data scientists and
software developers don't want to harm the people using their products.
There are exceptions, of course; we call them criminals and con artists.
[Defining "fairness" is
difficult](http://bit.ly/problem-build-fair-sys), and perhaps
impossible, given the many crosscutting layers of "fairness" that we
might be concerned with. But we don't have to solve that problem in
advance, and it's not going to be solved in a simple statement of
ethical principles, anyway.

The problem we face is different: how do we put ethical principles into
practice? We're not talking about an abstract commitment to being fair.
Ethical principles are worse than useless if we don't allow them to
change our practice, if they don't have any effect on what we do
day-to-day. For data scientists, whether you're doing classical data
analysis or leading-edge AI, that's a big challenge. We need to
understand how to build the software systems that implement fairness.
That's what we mean by doing good data science.

Any code of data ethics will tell you that you shouldn't collect data
from experimental subjects without informed consent. But that code won't
tell you how to implement "informed consent." Informed consent is easy
when you're interviewing a few dozen people in person for a psychology
experiment. Informed consent means something different when someone
clicks an item in an online catalog (hello, Amazon), and ads for that
item start following them around *ad infinitum*. Do you use a pop-up to
ask for permission to use their choice in targeted advertising? How many
customers would you lose if you did so? Informed consent means something
yet again when you're asking someone to fill out a profile for a social
site, and you might (or might not) use that data for any number of
experimental purposes. Do you pop up a consent form in impenetrable
legalese that basically says "we will use your data, but we don't know
for what"? Do you phrase this agreement as an opt-out, and hide it
somewhere on the site where nobody will find it?

That's the sort of question we need to answer. And we need to find ways
to share best practices. After the ethical principle, we have to think
about the implementation of the ethical principle. That isn't easy; it
encompasses everything from user experience design to data management.
How do we design the user experience so that our concern for fairness
and ethics doesn't make an application unuseable? Bad as it might be to
show users a pop-up with thousands of words of legalese, laboriously
guiding users through careful and lengthy explanations isn't likely to
meet with approval, either. How do we manage any sensitive data that we
acquire? It's easy to say that applications shouldn't collect data about
race, gender, disabilities, or other protected classes. But if you don't
gather that data, you will have trouble testing whether your
applications are fair to minorities. Machine learning has proven to be
very good at figuring its own proxies for race and other classes. Your
application wouldn't be the first system that was unfair despite the
best intentions of its developers. Do you keep the data you need to test
for fairness in a separate database, with separate access controls?

To put ethical principles into practice, we need space to be ethical. We
need the ability to have conversations about what ethics means, what it
will cost, and what solutions to implement. As technologists, we
frequently share best practices at conferences, write blog posts, and
develop open source technologies---but we rarely discuss problems such
as how to obtain informed consent.

There are several facets to this space that we need to think about.

Foremost, we need corporate cultures in which discussions about
fairness, about the proper use of data, and about the harm that can be
done by inappropriate use of data can be considered. In turn, this means
that we can't rush products out the door without thinking about how
they're used. We can't allow "internet time" to mean ignoring the
consequences. Computer security has shown us the consequences of
ignoring the consequences: many companies that have never taken the time
to implement good security practices and safeguards are now paying with
damage to their reputations and their finances. We need to do the same
when thinking about issues like fairness, accountability, and unintended
consequences.

We particularly need to think about the unintended consequences of our
use of data. It will never be possible to predict all the unintended
consequences; we're only human, and our ability to foresee the future is
limited. But plenty of unintended consequences could easily have been
foreseen: for example, Facebook's "Year in Review" that [reminded people
of deaths and other painful events](http://bit.ly/2JJBaPI). Moving fast
and breaking things is unacceptable if we don't think about the things
we are likely to break. And we need the space to do that thinking: space
in project schedules, and space to tell management that a product needs
to be rethought.

We also need space to stop the production line when something goes
wrong. This idea goes back to Toyota's
[Kanban](https://en.wikipedia.org/wiki/Kanban): any assembly line worker
can [stop the line](https://en.wikipedia.org/wiki/Autonomation) if they
see something going wrong. The line doesn't restart until the problem is
fixed. Workers don't have have to fear consequences from management for
stopping the line; they are trusted, and expected to behave responsibly.
What would it mean if we could do this with product features? If anyone
at Facebook could have said "wait, we're getting complaints about Year
in Review" and pulled it out of production until someone could
investigate what was happening?

It's easy to imagine the screams from management. But it's not hard to
imagine a Toyota-style "stop button" working. After all, Facebook is the
poster child for continuous deployment, and they've often talked about
how new employees push changes to production on their first day. Why not
let employees pull features out of production? Where are the tools for
instantaneous undeployment? They certainly exist; continuous deployment
doesn't make sense if you can't roll back changes that didn't work. Yes,
Facebook is a big, complicated company, with a big complicated product.
So is Toyota. It worked for them.

The issue lurking behind all of these concerns is, of course, corporate
culture. Corporate environments can be hostile to anything other than
short-term profitability. That's a consequence of poor court decisions
and economic doctrine, particularly in the US. But that inevitably leads
us to the biggest issue: how to move the needle on corporate culture.
Susan Etlinger has suggested that, in a time when public distrust and
disenchantment is running high, [ethics is a good
investment](http://bit.ly/2O4Iuc1). Upper-level management is only
starting to see this; changes to corporate culture won't happen quickly.

Users want to engage with companies and organizations they can trust not
to take unfair advantage of them. Users want to deal with companies that
will treat them and their data responsibly, not just as potential profit
or engagement to be maximized. Those companies will be the ones that
create space for ethics within their organizations. We, the data
scientists, data engineers, AI and ML developers, and other data
professionals, have to demand change. We can't leave it to people that
"do" ethics. We can't expect management to hire trained ethicists and
assign them to our teams. We need to live ethical values, not just talk
about them. We need to think carefully about the consequences of our
work. We must create space for ethics within our organizations. Cultural
change may take time, but it will happen---if we are that change. That's
what it means to do good data science.

---

##### This work was forked from:

**Original Repository:** [Ethics and Data Science](https://resources.oreilly.com/examples/0636920203964)

**Author:** Mike Loukides, Hilary Mason, and DJ Patil, O'Reilly Media, Inc.

**Forked Repository:** [Ethics](github.com/jasonkronemeyer/ethics)

**Modifications:** As of March 1, 2024, the only revisions that have been made are the internal links to the forked repository and the correct reference links in the origin repository.

**Date of Fork:** March 1, 2021
