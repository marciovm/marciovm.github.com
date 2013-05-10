---
layout: page
title: "We need a Github of Science"
date: 2011-04-21 17:05
comments: true
sharing: true
footer: true
permalink: /i-want-a-github-of-science/
---            

{% img /images/profzi_scheme.gif "Piled Higher and Deeper" by Jorge Cham %}

["Piled Higher and Deeper" by Jorge Cham](http://www.phdcomics.com)


** Summary **

- Publishing is central to Academia, but its publishing system is outclassed by what Open Source software developers have in GitHub

- GitHub's success is not just about openness, but also a prestige economy that rewards valuable content producers with credit and attention

- Open Science efforts like arXiv and PLoS ONE should follow GitHub's lead and embrace the social web                      

**Publish or Perish**

I am postdoctoral fellow, and [my academic department][20] is currently
running a junior faculty search.  We are interviewing four candidates, each of
whom will present a job talk attended by the entire department.  Before each
talk, I'll receive each candidate's application packets, and my eyes will scan
the "publications" section of their resume.  The presence of a first-author
article in the ultra-prestigious academic journals Science or Nature would all
but guarantee an offer.  Multiple publications in top-tier journals would
indicate a strong application.  If those are missing, meaning the publication
history is weak, I'll wonder how that person got an interview in the first
place.  Cultural fit, letters of reference and other credentials certainly
matter, but beyond publications, everything is secondary.

   [20]: http://dbmi.ucsd.edu/confluence/display/BMI/Division+of+BioMedical+Informatics

To anyone involved in academia, this overwhelming focus on publications is a
given.  Publishing is so central to scientists that their academic value can
be measured by adding the relative worth of their publications.  After many
years, citations preferentially accumulate towards publications of
significance, and by extension, their authors.  Ranking importance by
citations received is a powerful concept, and incidentally is the basis for
[Google's search algorithm][21].  But at the beginning of an academic's
career, before citations accumulate, reputation rests largely on what journals
they have published in.

   [21]: http://en.wikipedia.org/wiki/PageRank

Getting a paper accepted into an academic journal requires passage through the
often opaque process of peer-review. Scientists make a big deal of peer-
review, because it is supposed to be the filter that separates mere opinions
from trusted, citable sources. However, the peer-review process in science has
close analogs in any "old-media" field, such as TV or radio. Like academic
journals, these are mediums of limited capacity, and there are always more
submissions (or ideas for submissions) than there are openings.  Selecting
content worthy enough for distribution is made by the field's establishment,
which effectively silences what they don't choose. This is especially true of
peer-review as practiced in prestigious journals, defined as the ones that get
their contributors faculty jobs.

Having editorial decisions made by established experts makes sense, since they
draw on judgement born from years of experience. But this exposes the system
to vulnerabilities common to any decision by committee -- especially semi-
secret committee -- such as lack of agility, an aversion to disruptive
innovation, and the tendency of committee members (and their friends) to be
more equal in their own eyes than anyone else.  Because publishing affects
scientists so deeply, the strengths and weaknesses of this system inevitably
affect the makeup and character of science as a whole.  Which makes one
wonder, is there a better way?

 

**GitHubbing**

My training has spanned biology, engineering, and computer science.  My latest
project, [Instant Q&A for Physician Communities][22], relies heavily on open
source code and led me to [GitHub][23] and [Git][24].  The Linux community
[developed Git][25], a distributed version control system, to coordinate work
on the Linux code repository among thousands of programmers. Git is itself
open source, and has become widely adopted for many software projects (open
source and not).  GitHub is a cloud service that hosts [over 1 million][26]
Git repositories.  Since its launch in 2008, GitHub has quickly become the _de
facto_ platform for publishing open source code, whose popularity is changing
the world.  If you've ever been astonished at how quickly the web world seems
to move, the primary reasons are 1) it's not dominated by Microsoft, so we
have competition instead of a monopoly, and 2) open source code, widely shared
through a multitude of email lists in the past and now centralized at GitHub
[[1][27]].  How has GitHub become so successful?

   [22]: http://secure.dokbot.com/
   [23]: http://www.github.com/
   [24]: http://git-scm.com/
   [25]: http://progit.org/book/ch1-2.html
   [26]: http://techcrunch.com/2010/07/24/github-one-million/
   [27]: http://marciovm.com/i-want-a-github-of-science#f1n

GitHub is a social network of code, the first  platform for sharing validated
knowledge native to the social web [[2][28]].  This is a big deal.  I believe
it represents a demonstrably superior way of distributing validated knowledge
than academic publishing.  How are these even related?  Software developers
rarely write applications from scratch.  Instead, they often start with
various modular bundles of open source code.  Within Ruby (the programming
language underlying the popular web application framework Ruby on Rails
[[3][29]]) these bundles are called gems.  My current project employs 34 gems.
Each one is responsible for a specific task, such as [logging in users][30],
[interfacing with cloud storage][31], or making [fancy-looking buttons][32].
Science operates in a similar way.  Scientists never begin a research project
from an intellectual vacuum.  They stand on the shoulders of giants, building
on the knowledge contained in previous publications to form a new, coherent
finding.  For example, the [article][33] in which I published the bulk of my
PhD thesis cites 38 others.

   [28]: http://marciovm.com/i-want-a-github-of-science#f2n
   [29]: http://marciovm.com/i-want-a-github-of-science#f3n
   [30]: https://github.com/plataformatec/devise
   [31]: https://github.com/marcel/aws-s3
   [32]: https://github.com/imathis/fancy-buttons
   [33]: https://s3.amazonaws.com/marcios/Marciovm+et+al+Analytical+Chem.pdf

Gems are typically developed, distributed, and promoted through GitHub, and
therein lies the connection.  GitHub has evolved to solve the same general
problem that scientific publishing does: making modular, validated units of
knowledge easily usable by a global community, with mechanisms that
efficiently allocate prestige to proven contributors.  GitHub has the
advantage of doing this with 21st century technology, the social web, while
academic publishing is based on the printing press.  This suggests an
opportunity for the scientific community to evolve its publishing practices by
assimilating mechanisms proven to work for GitHub.

 

**Published Versus Prestigious**

The existing peer-review process [arose from the limited carrying capacity of physical journals][34].  Prioritization had to happen before publication,
because journals were limited in size to what could be economically printed
and shipped.  If you were born before 1990, you may recall the prestige
formerly associated with being "a published author".  However, in the times we
are living in, distributing media is basically free.  Anyone can start a blog
and deliver content worldwide in minutes.  Clay Shirky has made a career of
[deftly explaining][35] how this has fundamentally changed the media equation,
with such unexpected consequences as YouTube videos that [get more views][36]
than Super Bowl commercials.

   [34]: http://www.timeshighereducation.co.uk/story.asp?sectioncode=26&storycode=414579&c=2
   [35]: http://www.amazon.com/gp/product/1594202532/ref=as_li_ss_tl?ie=UTF8&tag=marciovm-20&linkCode=as2&camp=1789&creative=390957&creativeASIN=1594202532
   [36]: http://www.youtube.com/watch?v=_OBlgSz8sSM&feature=player_embedded

Individuals still have a limited capacity for consuming and evaluating
content, so prioritization and authentication remain necessary, but look
different.  These functions are now disconnected from publication.  Google
prioritizes web pages by analyzing utility _after_ publication, by tracking
citations in the form of inbound links.  Similarly, anyone can publish a gem
to GitHub, and published gems are prioritized by the numbers of developers
"watching" for updates or "[forking][37] " new development lines.  This is the
social web at work, where the audience gets to decide what and whom to pay
attention to all by itself, without requiring assistance from all-powerful
editorial committees.  One can complain that lowering barriers to publication
leads to content that on average is of lower quality.  But the abundance of
non-significant projects in GitHub does not detract from its usability,
because those projects are never brought to anyone's attention [[4][38]].

   [37]: http://en.wikipedia.org/wiki/Fork_(software_development)
   [38]: http://marciovm.com/i-want-a-github-of-science#f4n

Prestige is really about having an engaged audience that follows and
recognizes your activities.  This formerly required publication through
established venues, but that's no longer needed since your audience can use
the social web to recognize and engage with you directly.

 

**The Market for Prestige**

Gems on GitHub are not just code.  They also have authors whose relative
contributions are automatically catalogued by Git, as shown in this [impact graph][39] for the popular and open source jQuery project.  If you've visited
a web application recently, chances are you've benefitted from jQuery, which
makes it easy for a web engineer to turn static web sites into responsive web
applications (think interactions with buttons instead of navigation through
links).  This impact graph can let you know precisely which developers are
responsible for this awesome-ness. In this way, GitHub acts as an efficient,
incorruptible "central bank" of the prestige supply. Furthermore, unlike in
Google, great contributions in GitHub bring prestige to their creators, not
their domain names.  If you wanted to hire a contractor to work on a web
application, GitHub can let you know who has publicly demonstrated the skills
you'd need.  It's thus not surprising that [GitHub profiles are supplanting traditional resume items][40], such as a CS degree, for discerning employers
looking to hire top talent.

   [39]: https://github.com/jquery/jquery/graphs/impact
   [40]: http://blog.stackoverflow.com/2011/03/careers-2-0-now-does-github/

By contrast, current Open Science [efforts][41] that ask scientists to "[share all your data][42]" have not become mainstream, because they do not
appropriately reward knowledge producers.  They are all free-distribution and
no prestige, solving a different half of the problem than traditional journals
but not the whole enchilada.  Put another way, when anything can be published,
there is no prestige associated with being published, so prestige must be
introduced in other ways.  Evangelists for Open Science should focus on
promoting new, post-publication prestige metrics that will properly
incentivize scientists to focus on the utility of their work, which will allow
them to start worrying less about publishing in the right journals.

   [41]: http://openwetware.org/wiki/Main_Page
   [42]: http://figshare.com/

The biomedical world is increasingly permeated by code and data [[5][43]],
which should be very amenable to GitHub style metrics since they are by nature
tied to networked computers.  Scientists in fields like genomics and
biomedical informatics are being held to the same publication expectations as
their peers, but this makes little sense.  An article describing a genomic
database is nowhere near as useful as an open API for accessing it.  We need
trusted ways to quantify just how useful that API and associated code are to
the scientific community, which can be listed on a scientist's profile and
utilized by committees making hiring and funding decisions [[6][44]].

   [43]: http://marciovm.com/i-want-a-github-of-science#f5n
   [44]: http://marciovm.com/i-want-a-github-of-science#f6n

 

**Challenges and Current Efforts**

Of course, there are fundamental differences between publishing software code
and publishing science.  Copying code results in an exact replica and does not
affect the original.  By contrast, duplicating a research finding may require
significant expenses just to recreate experimental conditions.  Code is
structured by the strict syntax of programming languages, while most
scientific research is not.  For this reason and others, academic articles and
journals are not going to disappear, but they should not be the only way for a
scientist to accumulate prestige.

Unfortunately, energy that could be spent developing these new solutions is
instead tied up with the older struggle of open-access.  Universities still
pay outrageous sums to journal publishers to allow them access to the
knowledge they just produced, reviewed, and edited on their own dime
[[7][45]].  Broadly speaking, traditional journals are being reduced to rent-
takers on brand names with reputational inertia.  [arXiv][46], which provides
open access to pre-prints in many quantitative disciplines, is a notable and
[long-running][47] example of the scientific community's workaround to this
problem.  The arXiv is amazing, but why remain dependent on a system it could
be replacing [[8][48]]?

   [45]: http://marciovm.com/i-want-a-github-of-science#f7n
   [46]: http://www.arxiv.org/
   [47]: http://www.sciencemag.org/content/259/5099/1246
   [48]: http://marciovm.com/i-want-a-github-of-science#f8n

[PLoS][49] is at the cutting edge of both open-access and [rethinking the functions of a journal][50].  [PLoS One][51] comes closest to what I am
describing, in that their peer-review process screens only for scientific
rigour, not perceived impact, meaning they will publish content considered
unsexy and let future citations determine importance.  But they have not yet
embraced the social web, as the lack of scientist profiles (with associated
prestige metrics) in their website demonstrates.  In programmer jargon, PLoS
ONE needs to become a web application, not a website that hosts content.  One
problem might be that they still consider themselves a journal first, [and journals have editorial boards][52], while [social web is all about *not* having editors][53].  There is no editorial board at GitHub.

   [49]: http://www.plos.org/about/principles.php
   [50]: http://www.slideshare.net/dduin/rethinking-the-functions-of-a-journal-some-case-studies-from-plos-by-mark-patterson
   [51]: http://www.plosone.org/
   [52]: http://www.plosone.org/static/edboard.action
   [53]: http://www.poynter.org/latest-news/top-stories/110111/why-the-new-york-times-eliminated-its-social-media-editor-position/

When I discuss this with current faculty, a typical reaction is that I'm
pining for a social network of scientists.  That seems reasonable, and it is
[being tried][54], but may not be bold enough.  GitHub did not succeed by
being a social network of programmers.  It succeeded by being a social network
of code.  We need a social network of science, meaning scientific bundles of
knowledge must be structured and accessible by API, with the connections among
those bundles and appropriate utility metrics being what connects and
prioritizes scientists.

   [54]: http://www.academia.edu/

APIs for science already exist, and some are incredibly useful, but they have
ignored authorship and prestige implications which have prevented them from
achieving their potential.  For example, biophysicists have the [RCSB Protein Data Bank][55], which stores experimentally determined protein structures.
This database is a tremendous asset to the field, but it could represent much
more, as a story from my younger days illustrates.  In 2004, as an undergrad,
I spent a summer writing Python code to download and analyze all existing RCSB
structures.  That program built a database of "real" structures to train a
scoring algorithm, which subsequently scored computationally generated
structures to see how "real" they seemed [[9][56]].  Unfortunately, my results
were not compelling enough to be published in a prestigious academic journal,
and therefore not interesting to my research adviser.  Open-sourcing and
publishing that code might have saved someone's time, spurred new thinking, or
at the very least marked a tangible reward for my work.  But the incentives to
my adviser weren't there, so he did not suggest it.  That idea did not even
occur to me, because I was not a good enough programmer to know about
[SourceForge][57], a less-social precursor to GitHub, so the code went
nowhere.

   [55]: http://www.pdb.org/pdb/home/home.do
   [56]: http://marciovm.com/i-want-a-github-of-science#f9n
   [57]: http://sourceforge.net/

 

**Hey Mr. Gates**

It may be that the activation energy required to initiate changes won't arise
within the system.  In that case, an outside push might do the job, and the
best place for this push to come from may be a nimble funding agency.  For
example, a request for proposals could specify that phase II funding decisions
would be based on the impact of online resources developed in phase I, as
measured by specific metrics developed with community feedback.  Nothing makes
a scientist contemplate change faster than a new source of grant money, and
the only thing better than a faculty applicant with a paper in Science may be
one bringing in a multimillion dollar grant.

 

**Further reading:**

[Collective knowledge systems: Where the Social Web meets the Semantic Web
][58](Tom Gruber)

   [58]: http://www.sciencedirect.com/science?_ob=MImg&_imagekey=B758F-4R9GGVW-1-7&_cdi=12925&_user=4429&_pii=S1570826807000583&_origin=gateway&_coverDate=02%2F29%2F2008&_sk=999939998&view=c&wchp=dGLzVzb-zSkzk&md5=84599c163a5b359195c25f6fd5449c2b&ie=/sdarticle.pdf

[Peer Review in Academic Promotion and Publishing: Its meaning, locus and
future][59] (Diane Harley and Sophia Krzy)

   [59]: http://cshe.berkeley.edu/publications/publications.php?id=379

[Mechanisms for (Mis)Allocating Scientific Credit.][60] (Jon Kleinberg and
Sigal Ore)

   [60]: http://www.cs.cornell.edu/home/kleinber/stoc11-credit.pdf

[The Life Scientists room on Friendfeed][61]

   [61]: http://friendfeed.com/the-life-scientists

 

**Notes**

<a name="f1n">1</a> "The combination of the Internet and open source transformed the
functionality in modern programming tools, increasing developer productivity
10 fold" - [Ben Horowitz][62], formerly of Netscape.

   [62]: http://voices.allthingsd.com/20110323/bubble-trouble-i-dont-think-so/

<a name="f2n">2</a> "Native" in the sense [eloquently explained by USV][63] (the VCs who funded
Twitter): "Native opportunities are the ones that make use of unique
capabilities of [new] platforms".  The social web is the new platform.

   [63]: http://www.usv.com/2009/06/the-mobile-chal.php

<a name="f3n">3</a> For example, Twitter, Groupon, and GitHub itself run on Ruby on Rails.

<a name="f4n">4</a> I speculate that many gems are also discovered through technical blogs
(found through Google) or the programmer Q&A site [StackOverflow][64].

   [64]: http://stackoverflow.com/

<a name="f5n">5</a> Biomedical research is also huge - funding has been [squeezed lately][65],
but is still on the order of ~$100B annually.  Therefore the potential market
is large enough to be worthwhile to build for.

   [65]: http://jama.ama-assn.org/content/303/2/137.full

<a name="f6n">6</a> The unique requirements of the scientific community probably mean GitHub
itself can't do the job.

<a name="f7n">7</a> Or more accurately, on the federal government or philanthropic organizations
that fund them. Journals do not compensate their editors or peer reviewers.

<a name="f8n">8</a> The peer-review process [has been hacked via arXiv before][66], by Grigori
Perelman.  But to appreciate how unusual Grigori's motivations are, consider
that he also refused to accept the Fields Medal and its $1M cash prize.

   [66]: http://www.news.cornell.edu/stories/Sept06/library_arXiv.html

<a name="f9n">9</a> Computing protein structure from amino acid sequence is known as "the
protein folding problem" and is one of the [holy grails of science][67].

   [67]: http://mail.cmu.edu.tw/~ythuang/the_holy_grail.htm

 

**Thanks to** [Sean Ahrens][68], Sean Carroll, Manuel Cebrian, Wendy Chapman, Lawrence David, Lucila Ohno-Machado, Carlos von Muhlen, Denise von Muhlen, and Ryan Weald for reading drafts and helpful discussions.

   [68]: http://seanahrens.net
