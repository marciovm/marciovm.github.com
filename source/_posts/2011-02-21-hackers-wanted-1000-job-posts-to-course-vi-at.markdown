---
layout: post
title: "hackers-wanted-1000-job-posts-to-course-vi-at"
date: 2011-02-21 17:58
comments: false
categories: 
---
**Tried to hire a hacker lately?**

Hacker talent is highly non-commoditized, and the ROI at the top end of the
market more closely resembles professional sporting leagues than traditional
engineering career fields. [[1,2][19]] I have a theory that [Paul Graham][20]
is the [Scott Boras][21] of this marketplace, which I'll write about in the
future.  The ability to scout and hire great hackers before other market
participants (GOOG = Yankees?) can be extremely valuable.

   [19]: http://marciovm.com/hackers-wanted-1000-job-posts-to-course-vi-at#f1n
   [20]: http://paulgraham.com/
   [21]: http://en.wikipedia.org/wiki/Scott_Boras

The mailing list for Course VI at MIT is an interesting place to see what
people who are (presumably) looking to hire great hackers are saying in
"hackers wanted" posts. [[3][22]] Many years ago, my friend Fergus at
[PicBounce][23] tipped me off that it's a great resource to capture trends and
vocabulary in the tech entrepreneurship world. [[4][24]] It's also good for a
few laughs. [[5][25]]  To brush off my python skills, I performed basic word
count analyses on last semester's posts; I figured the results might be
interesting to others so I'm sharing them here.

   [22]: http://marciovm.com/hackers-wanted-1000-job-posts-to-course-vi-at#f3n
   [23]: http://picbounce.com/
   [24]: http://marciovm.com/hackers-wanted-1000-job-posts-to-course-vi-at#f4n
   [25]: http://marciovm.com/hackers-wanted-1000-job-posts-to-course-vi-at#f5n

Updated 01-18-11: The administrator of this list contacted me and asked me to
clarify details of who maintains the list.  It's not the EECS Department's
list, but rather a personal list maintained by Anne Hunter, who can be reached
at anneh@eecs at MIT's domain name.  Thanks Anne for keeping this very useful
list going, and my apology for not crediting you when I first posted this.

{% img /images/hacker_posts_word_count.png %}

**Methods**

I extracted 944 messages sent to the announcement list from July to December
2010 to a text file using Automator on Snow Leopard.  Using python, I parsed
messages into message objects containing date, subject, and body.  I ignored
date and subject and looked only at body text.  I then stripped punctuation
(except # and +), split() to tokenize strings, and built a wordDict with
key/value pairs of {word: wordCount}.  To filter non-job posts like course
announcements, I ignored messages that contained any of a list of words
usually used by the department. [[6][28]]  I then merged all the individual
wordDicts into a globalDict.  I dropped words commonly used in English.
[[7][29]]  I did something similar for two-word phrases, to capture terms like
"social networking" (data used for figures B and C).  I'm reporting average
word count in the globalDict -- total word count divided by number of posts.
The number of posts analyzed was 905 (thus 39 were scored as being department
announcements).

   [28]: http://marciovm.com/hackers-wanted-1000-job-posts-to-course-vi-at#f6n
   [29]: http://marciovm.com/hackers-wanted-1000-job-posts-to-course-vi-at#f7n

**Results**

The most common word was "experience".  Lots of generic technology words show
up in the top-50 (figure A), as expected.  I figured a more interesting plot
might be the occurrence of words that I thought _a priori_ were interesting,
which I call "programmer vocabulary" (figure B).  This is subject to my own
biases of what I think is important, so sorry if I didn't include your
favorite.  The winner there was "web", followed closely by "mobile".  The
prevalence of buzzwords like "rockstar", "ninja" and "guru" was smaller than I
expected.  Finally I looked at locations (figure C).  The sum of the SF Bay
Area terms was 0.067, which I didn't place in the figure because it would have
been the only multi-term aggregate.

Any thoughts on how I can improve this analyses?  I'll do this again in 6
months if enough people find this interesting (email me and I'll send you the
update when it's ready).

Disclaimers:  This is a relatively small sample size subject to outlier
effects (i.e. a single message that contains "mobile" twenty times).  I used
an arbitrary exclusion list to filter department announcements and it might be
incomplete (i.e. these results may include department announcements that were
not job posts).

**Notes**

<a name="f1n">1</a> Hacker as in "person who builds things with computer code", as opposed to
the more common definition of "16 year old who does bad things with
computers".

<a name="f2n">2</a> Just look at the size of signing bonuses.  Paul Buchheit's was up there with
Lebron James's when he was [acqui-hired][30] by Facebook via Friendfeed (there
were additional engineers in this trade deal).

   [30]: http://www.readwriteweb.com/archives/facebook_just_bought_friendfeed.php

<a name="f3n">3</a> Course VI is MIT-speak for Department of Electrical Engineering and Computer
Science.

<a name="f4n">4</a> A great complement to [Hacker News][31].

   [31]: http://news.ycombinator.com/

<a name="f5n">5</a> A real email from Fall 2010, identities redacted to protect the guilty:

>Subject: Coder Needed for Social Network Website
>
>Greetings,
>
>My name is [*redacted*] and I am looking for a very experienced coder. My team
>and I are looking to build a social networking site, very similar to facebook,
>that has extreme potential. We plan on 95 percent of all college students
>becoming active users within 4-8 months from the launch date. My partners
>[*redacted*], [*redacted*], and I are marketing and promotions specialists
>with a great outreach to the college market. We are searching for an
>unbelievably talented coder, who is ready and willing to PARTNER UP on this
>college based website project to make history. We are very serious about our
>business venture so we are looking for someone who really feels confident that
>they are capable of handling a project like this.
>
>Please email all your contact info as well as a resume/portfolio with sample
>projects.
>
>I look forward to hearing from anyone who's up for this challenge. Lets Make
>History.
>
>Best,
>
>[*redacted*]
>
>[*redacted*]@gmail.com

<a name="f6n">6</a> Words that appear in department posts: 'ta', 'lecture', 'course
description', 'grad school', 'correction', 'announcement', 'websis'.

<a name="f7n">7</a> Common words in English: 'a', 'able', 'about', 'across', 'after', 'all',
'almost', 'also', 'am', 'among', 'an', 'and', 'any', 'are', 'as', 'at', 'be',
'because', 'been', 'but', 'by', 'can', 'cannot', 'could', 'dear', 'did', 'do',
'does', 'either', 'else', 'ever', 'every', 'for', 'from', 'get', 'got', 'had',
'has', 'have', 'he', 'her', 'hers', 'him', 'his', 'how', 'however', 'i', 'if',
'in', 'into', 'is', 'it', 'its', 'just', 'least', 'let', 'like', 'likely',
'may', 'me', 'might', 'most', 'must', 'my', 'neither', 'no', 'nor', 'not',
'of', 'off', 'often', 'on', 'only', 'or', 'other', 'our', 'own', 'rather',
'said', 'say', 'says', 'she', 'should', 'since', 'so', 'some', 'than', 'that',
'the', 'their', 'them', 'then', 'there', 'these', 'they', 'this', 'tis', 'to',
'too', 'twas', 'us', 'wants', 'was', 'we', 'were', 'what', 'when', 'where',
'which', 'while', 'who', 'whom', 'why', 'will', 'with', 'would', 'yet', 'you',
'your'.