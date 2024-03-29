# Threat Modeling for Disinformation and Conflict
A place to gather and organize information about using threat modeling
frameworks to deal with social conflict in online systems.  Businesses
are named here soley to make discussion concrete, not to criticise
their choices.

## Frame 

It is very obvious that there are many problems with the way
people behave online, which various people have approached with names
like "social threat modeling," or "conflict modeling."  This site is
intended as a frame for thinking about and collaborating around
building blocks to help us understand such conflict, and to engineer
ways to address it. Since I started tracking these ideas in 2017, an industry frame around "trust and safety" has emerged.

A brief example may help illustrate.  When a business is in the news
and Yelp detects that people are reviewing it based on the news rather
than their experience with the business, they put up an interstitial
which tells visitors that they're aware of the problem, what a good
review is, and promising to look at the reviews that have been posted
for quality.  **These are engineering decisions around conflict.**
They put up an interstitial page.  They implement a review queue.
They might instead lock the business relative to new reviews.  They
might keep a secret what they look for in moderation.  Each of these
involves tradeoffs, and my goal in starting this site is to collect
the tools that are being used, discuss the tradeoffs, and offer a
resource for engineers and managers taking on these complex
descisions.

Shown below are two screenshots from Yelp, the first from 2020 (Four Seasons Total Landscape)

![A 2020 screenshot from Yelp](https://raw.githubusercontent.com/adamshostack/conflictmodeling/master/images/yelp-2.png)

The second from 2018 (Red Hen Restaurant)

![A 2018 screenshot from Yelp](https://raw.githubusercontent.com/adamshostack/conflictmodeling/master/images/RedHen.png)

## Threat Modeling

Threat modeling is a collection of techniques that help us bring
structure to analysis of systems to anticipate what might go wrong and
address it earlier in the engineering process.

This site is organized along the lines of the 4-question frame for
technology threat modeling:

1. What are we working on?
2. What can go wrong?
3. What are we going to do about it?
4. Did we do a good job?

Amanda Levendowski has made a convincing case that the hardest part of threat
modeling conflict is figuring out what to do about the issues that you
find. Evelyn Douek has a long article, [Content Moderation as Systems Thinking](https://harvardlawreview.org/2022/12/content-moderation-as-systems-thinking/). This site aims to track pros and cons of possible methods. 

## Ways to Contribute
1. There's a lot of information in the references.  It would be great to mine and organize into the 4 question framework.
2. There are lots of ways to address it which we need to model and discuss.  For example, there's plenty of enthusiasm for and criticism of real name policies.  Can we pull that information together to be a better resource to help engineers, product managers, executives and advocates to have richer discussions?
