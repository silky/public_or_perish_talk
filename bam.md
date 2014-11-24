Collaboration and Openess Everywhere!
==


-- TODO: Maybe use the "HoTT" book
-- TODO: Mention the outputs of HoTT and the Polynmath project
-- TODO: Explain repository; try not to mention any jargon
-- TODO: Explain tests/builds
-- TODO: Mention why being public and open is a good idea
-- TODO: Reproducibility studies
-- TODO: Tell what you'll say, say it, then summarise it
-- TODO: 


Imagine waking up on Christmas morning. You run downstairs, rush to the tree
and you see a present with your name on it! Awesome! You open it up,

***---- Click ----***


and inside, is this ...

***---- Click ----***


<!-- http://iml.univ-mrs.fr/~girard/mustard/page1.html -->

![](http://i.imgur.com/jtbuoyr.png)

whereas maybe you were hoping it would be this ...


***Surprise!***


I claim this reflects the current sophistication of the dominant form of
scientific publishing today. I believe that, *right now*, the tools and
technologies exist to change the research process into an interactive, open,
system where we can achieve the fundamental goal of sharing understanding,
solving interesting problems, having fun, and just generally working together
to make the world a better place.

In the following we will explore two topics:

    - Collaboration and openness, and
    - Interactivity and reproducibility.


***---- Click ----***


First idea: `Collaboration and openness`
--

<!--
        Key idea: Share everything, work with anyone.

        Examples:
            - Git/GitHub
            - Polymath Project
-->

This is Paul Erdös; and some other Australian mathematician ... I'm not sure
what became of him. (Joke: That is, of course, Terry Tao.) A quote
Erdös is "My brain is open".

***---- Click ----***


Erdös is famous for being intensely collaborative - he would show up on
doorsteps of mathematicians, and announce "My brain is open". Subsequently,
they would collaborate on some work, and Erdös would leave to go
work with someone else.

Terry Tao, also, is doing excellent work in collaborative mathematics, with
the "Polymath Project".

***---- Click ----***


The Polymath project is a platform for collaboration on research-level
mathematical problems, with a very small number of projects being actively
worked on (< 10, say).

Polymath8 was about reducing the "prime gap" number, that was first set at 70
million by Yitang Zhang last year.

This is cool. Let's look at another example.

***---- Click ----***


This is the Homotopy Type Theory book - or "HoTT" for short. It was
collaboratively written in 2012/13, partly by people working at the IAS.

The interesting thing about this book (other than it's inherent interestingness)
is that it was written largely online, in the public - completely openly.

They did this using a website called "GitHub",

***---- Click ----***


and a software package called "Git". "Git" is what's referred to as a "version
control system" or "source control system". We won't get into details here; but
this program - Git - lets you work on the same files as other people, i.e.
a particular TeX file, or piece of code, or presentation, and share the changes
you make in a structured way.

This "GitHub" website is the place where changes are sent to, and grabbed from,
by all members of the team. If you're familiar with "Dropbox", you can think of
GitHub is a more-structured version of that.

While with Dropbox you sync folders, with GitHub you sync "repositories". The HoTT
book is a GitHub repository, and it looks like this,

***---- Click ----***


at a glance you can see it contains folders and files, updated at different
times by perhaps different people.

This collaboration was recognised as groundbreaking by Wired, and other news
agencies.

***---- Click ----***

Okay, so we can see that there is a scale of openness. The least "awesome" is
simply publishing finished products in existing journals. On the other hand, we
can imagine doing all the work of research - workings/journals/ideas - in the
public, and inviting collaborations by being completely open.

To get a sense of this; let's go back to Paul Erdös, and bring him into the
modern world.

***---- Click ----***


Here's a modern take on how Paul Erdös might've gone about life today.

***GitHub Paul Edrös***

Each paper Erdös has is a "repository" - a collection of all the files
related to the particular work.

Notice also that he is contributing to other repositores, and note
further that all these repositories are publically accessible. Anyone
can contribute, and submit what are called "pull requests" - which are
a formal mechanism for suggesting changes; and everything is tracked
by the version control system.

So let's look in a bit of detail at the possibilities here.

***---- Click ----***


We can simply just stick to what we do currently - work largely in private,
and publish in journals, or we can tend towards being more awesome - more
Erdös/Tao/etc-like - and be as open as possible.

We can show all our workings, we can mainain online journals about what we are
working on (what Terry Tao does with his blog), and,

***---- Click ----***


we can list the topics we'd like to research.

Anyone can comment on these issues. They can see what I am interested in,
and maybe if someone else is interested in the same things, they can contact
me and we would work together on a thing.

Imagine being able to see such a list for your friends. Your colleagues,
your supervisor; the leading people in your field - Everyone!

***---- Click ----***


And finally we can submit our finished pieces to completely open "journals"
- my personal favourite being the *arXiv*, which can be accessed through
*SciRate* - probably my favourite website of all time.


For an example of this happening for a research-level work, consider the HoTT
book, which was written collaboratively on GitHub,

***---- Click ----***



Note that a lot of these sites have a social aspect. On GitHub, you can
"follow" people, in order to stay up to date with what they are doing. You
can comment on their work, and - as mentioned - submit changes. On SciRate
you can see what other researchers in your field are interested in, and
you can see which papers are popular (this may or may not be a feature).

We can go further.

***---- Click ----***


There are several companies working on document authoring online. Authorea
is one that I happen to like because it is backed by "Git" - the version
control system that "GitHub" also uses, and there is a way to connect the two.

Furthermore, they are attempting to add an element of interactivity
into the papers, which is undeniably good.

Another example of this idea is the Sage Math Cloud.

***---- Click ----***


This is a picture of a Sage worksheet that Christian Perfect (blogs
for the "Aperiodical" website) put up. He was attempting to verify some conclusions
drawn by an article about the relationship between salaries and programming languages.
The details aren't what I want to talk about here - only to observe that this
is a document that anyone (on the SageMathCloud) can view, and use to check Christian's
workings. I.e. instead of providing *only* a graph, he provided the actual code
used to generate the graph; and not only that - it's provide on a platform that
allos me to *run it immediately*.


So let's now talk a bit about reproducibility and interactivity.

The point here is to observe that openness facilitates collaboration. But
openness alone isn't enough. We need tools to make the process easy and
intuitive.
 
<!-- ???: More ramblings? -->


***---- Click ----***

Second idea: `Reproducibility and interactivity`
--

<!--
        Key idea: You need to make everything public, it should
            all "work" together; i.e. it should pass tests, be
            installable, etc.
-->

Reproducibility is necessary.

The idea is; given some particular work, can you re-derive all the results
that they have obtained?

In pure maths, it generally means following proofs. In say applied maths,
it might mean obtaining the same running times for particular algorithms. In
physics it could mean being able to actually build a device that matches the
expected operating specifications.

In a world where everything is open - i.e. all source code is available, all
data is available, etc, we might imagine a notion of "immediate
reproducibility". This would mean that we are simply trying to run, on our own
computers/labs/environments, the understandings we have obtained from the given
work.

So on one hand, while we require "reproducibility", we can actually produce our
work in ways to make this easier, for anyone else reading it.

Here's an example.

***---- Click ----***


This website is quite recent, and it represents the work of a few people,
who have read some specific papers, and their attempts at verifying the
results obtained.

Here's an example.

***---- Click ----***


On the left we have an "IPython Notebook". This is, if you like, an open
source version of Mathematicas notebooks.

On the right you have the paper. 

Note here that because the left hand side is simply *reproducing* the work of
the right hand side, it doesn't contain explanations. Note that the right hand
side contains explanations, but no working.

These two things can, infact, be merged.

Indeed, this idea is actually very old!

--- Click ---


Probably the worlds most famous living computer scientist - Donald Knuth - advocated
strongly an idea he calls "Literate Programming".

The key idea is to write explanations with the code that accompanies their
implementation. This is naturally applicable to papers insofaras they almost entirely
consist of explanations, and no implementations.

Mathematica - probably software everyone here is familiar with - adopts this
idea in a ambitious way. To refresh your memory, a very basic example is this.

***---- Click ----***


Note that on the one hand we have TeX explanation, and immediately below that we
have executable code. The two modes can be interspersed.

IPython is the same idea, but instead of Mathematica code it is Python code.

***---- Click ----***


Observe here that images can also be embedded.

So infact an entire *paper* can be written this way - such that it's actually
interactive, as well as explanatory. We can provide implementations of our ideas;
or little exploratory tools that people can use to explore our proofs and
definitions.

**This** is the future that I want to see for academic research.

Where, when a paper may provide a series of definitions, there could also be
an interactive example that let's you see how these definitions work together.
Where each paper supplying an algorithm or technique comes equipped with a
working implementation - right there in the paper itself - and the data that it
used to generate it. These things are possible with the IPython/Mathematica/Notebook
environments.

Going back to the Erdös example,

***---- Click ----***


The new standard for a "paper" could look like this:

    1. A repository

***---- Click ----***


where inside we have:

    1. The paper itself, as an IPython notebook,
    2. Tests and a build, to make sure the code works,
    3. A license so people know how to use it,
    4. Talks related to the paper (maybe?)

and also perhaps a "Release" of a PDF version, (which can be automatically
generated from the IPython notebook),

***---- Click ----***


So now we have this.

The old imperative was "publish or perish". That's out now.

The new imperative is this.

***---- Click ----***


***Public or perish!***


