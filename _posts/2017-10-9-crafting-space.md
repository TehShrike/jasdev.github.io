---
layout: post
title: Crafting Space to Be Ourselves
permalink: crafting-space
---

One of my all-time favorite quotes from [Rainer Maria Rilke](https://en.wikipedia.org/wiki/Rainer_Maria_Rilke) is

> “Where I create, there I am _true_.”

I certainly feel this way about writing. Committing thoughts to prose is easily one of the [most _vulnerable_ and rewarding things I do](https://www.instagram.com/p/BPk28P5AIGj)<sup>1</sup>. Moreover, hammering away at my keyboard on [idle Saturdays](https://www.instagram.com/p/BZ9El9pAVTj) gives me space to be my true self.

Recently, I’ve been ramping up two junior engineers on [my team](https://www.instagram.com/p/BYeoOX6HFwJ), which got me thinking about crafting spaces that harbor psychological safety. As one of the more senior engineers in the group, the onus is on me to make sure teammates can comfortably pose questions, ask for help, be their true selves, and feel welcome. Below are a few ways I try to accomplish this, capping off with a variation on 1x1s I plan on using as a future manager.

## Not Being Afraid to Say “I Don’t Know“

While interning, one of the most reassuring statements to hear from my mentor was “I don’t know.” It reminded me that we’re all human and a competitive advantage for knowledge workers isn’t what you know _internally_, but rather the ability to sift through the noise on the Internet in finding an answer. I’ve tried to do the same for my mentees<sup>2</sup>. A good suffix to this phrase is “let’s research this __together__.” 

<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">As a senior engineer or a technical team lead, it&#39;s perfectly okay to say &quot;I don&#39;t know, let&#39;s research this together.&quot;</p>&mdash; Celestine Omin (@cyberomin) <a href="https://twitter.com/cyberomin/status/915222080647548928?ref_src=twsrc%5Etfw">October 3, 2017</a></blockquote> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## Collective Code Ownership

[Sarah Mei](https://twitter.com/sarahmei) wrote a [great thread](https://twitter.com/sarahmei/status/892180578753142784) on our industry’s tendency to conflate code authorship and ownership (and ultimately responsibility). That is, if person _X_ wrote the code that caused a production issue, the (internal) limelight is _often_ placed on _X_ instead of their larger team (in the absence of sound company values). Doing so is a failure to realize that “[most non-trivial issues come from a confluence of problems and usually are driven by misunderstandings at multiple points in the process](https://twitter.com/sarahmei/status/892158909107982337).” A way to mitigate this is being [explicit about collective ownership](https://twitter.com/sarahmei/status/892158909107982337). Just because _X_ shows up in `git blame` doesn’t mean the “blame” is on them. To reinforce a sense of group ownership, I’ve made it a point to prefix code review comments with “let’s”.

![An example of a GitHub code review comment that uses “let’s”](/public/images/lets_1.png)

![An example of a GitHub code review comment that uses “let’s”](/public/images/lets_2.png)

![An example of a GitHub code review comment that uses “let’s”](/public/images/lets_3.png)

“Let’s” is a subtle reminder that although I’m not committing the code, we’re crafting it _together_ and should treat any downstream fallouts as such. Scoping out, this might hint at the unfortunate [power of the phrase](/peeling-labels) “ownership” and connotation of `git blame`. [I don’t seem to be the only one who feels this way](https://twitter.com/mb/status/883515108927909889).

- Blameless postmortems (learning reviews)

## Asking questions publicly

- I always err on the side of asking questions to my team in public channels, as opposed to DMs. This better normalizes asking for help, regardless of seniority (in addition to better sharing knowledge).

## Being transparent about goofiness

- [This is one of the best definitions I’ve seen of a senior engineer](https://twitter.com/jasdev/status/870339296649248768). Just because we’re surrounded by skilled colleagues, doesn’t mean we have to be uptight (or “with it“) all the time. It’s okay to be [open about the derpier moments](https://twitter.com/iano/status/870333996366016515). They remind us that we’re all human.

## Accounting for _future_ teammates

- At Peloton, we’ve recently started having the client teams review OpenAPI docs, prior to server-side implementation. During these reviews, I’ve often found myself pushing to have the team write down our assumptions, avoid temporary codenames, and other hurdles that would make on-boarding difficult for new hires. Similarly, even though our iOS team of three engineers and one manager is all-male at the moment (:/), I’ve made strides—albeit nuanced—to make sure our [culture](https://twitter.com/jasdev/status/849648790307037185) and [code](https://twitter.com/jasdev/status/883349603508211713) are welcoming to anyone.

## Interviews

- Letting the candidate use their own editors and toolchain

## Management

- Walking 1x1s (side-by-side)

---

Special thanks to () for reading early drafts of this essay and to [Ryan](https://twitter.com/ryan_nayr_) for [motivating me](https://twitter.com/ryan_nayr_/status/888158199701848064) to write about this topic.

## Footnotes and Related Links

<sup>1</sup>: Shout-out to [Jacob](https://twitter.com/fat) for this phrasing in the context of [building Bootstrap](https://medium.com/@fat/twitter-bootstrap-b95033c270af).

<sup>2</sup>: I use “mentor” and “mentee” in this essay [in a bidirectional manner](https://twitter.com/jasdev/status/804002682969145344). [Knowledge transfer](https://www.instagram.com/p/BY_iquag_oN) isn’t exclusively top-down, it’s probably more like a graph.

⇒ I was lucky enough to attend the [Recurse Center](https://www.recurse.com) back in the fall of 2015. Many of the techniques mentioned in this essay are second-order effects of their fantastic [social rules](https://www.recurse.com/manual#sub-sec-social-rules). These carefully selected rules [make RC a refreshing escape](http://blog.annharter.com/2017/09/16/What-I-Learned-at-RC.html) from the often-imperfect tech industry.

![Poster with the following contents: “Social Rules: No Feigning Surprise, No Well-Actually’s, No Backseat Driving, No Subtle -isms”. Below the poster are signs that read “Help me!” and “BUSY, but I still love you <3”](/public/images/social_rules.jpg)
