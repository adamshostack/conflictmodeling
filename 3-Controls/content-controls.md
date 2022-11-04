# Managing Potentially Problematic Content

Choices you have include, but are not limited to:


1. Automated Response - AI/ML & Business Logic
2. UI Cues & Controls
3. Behaviour based controls
4. Banned word lists
5. Threat Hunting (proactive) 
6. Reporting systems (Reactive)
7. Rate limiting
8. Content dependent vs content oblivious strategies

**NOTE:** The problem with this page is that these controls can also be used on combination to each other and not just individual seperate controls. They have to be part of a cohesive strategy. One description of a strategy is in Zuckerman's description of Front Porch (2020). Mike Masnick describes the [content moderation learning curve](https://www.techdirt.com/2022/11/02/hey-elon-let-me-help-you-speed-run-the-content-moderation-learning-curve/) in relation to Musk's takeover of Twitter.



## Automated Response - AI/ML & Business Logic
With billions of users one thing that needs to be factored in is automation and business logic that balances user experience with, with the identification of fake/harmeful content.

The objective is to feed an ML model various signals in order to react to specific content i.e. either tag content for further review or provide soft challenges (rate throtteling / captcha / ID&V etc..) or preventative controls - banning account, blocking content, etc... There's a 2018 [A Survey on Automatic Detection of Hate Speech in Text](https://dl.acm.org/doi/10.1145/3232676). 

Various aspects can be factored in such as political turmoil or upcomming elections as some of these issues changes depending on the date. In May 2021, the Center for Democracy and Technology released an extensive report, [Do You See what I See](https://cdt.org/wp-content/uploads/2021/05/2021-05-18-Do-You-See-What-I-See-Capabilities-Limits-of-Automated-Multimedia-Content-Analysis-Full-Report-2033-FINAL.pdf), outlining issues with automated content analysis tools. It covers how matching and predictive models have limitations including robustness, data quality, lack of context, measurability, and explainability.

Content does not have to be viewed in a vacuum.  There are signals in not only content and publisher, but also the relationships between content, publisher and promotors.  See [Shu19](https://blog.acolyer.org/2019/02/13/beyond-news-contents-the-role-of-social-context-for-fake-news-detection/)

## UI Cues & Controls
Provide transparency and visibility to the users of content authenticity and challenges to false narratives. Also the user to request to make these cues more (or less) visibile. This includes providing visibile cues that the content of verious categories e.g. the ability to distinguish if the content is from an official news source, a promoted ad, an opinion piece etc..  
**NOTE:** I personally would like to know if the content I am seeing is an untampered news article, an opinion piece (which news sites do a poor job at tagging consistently) Official public Statements (press releases) vs. public/user generated content.

## Controls applied to contact requests
Instagram has [applied](https://about.instagram.com/blog/announcements/introducing-new-tools-to-protect-our-community-from-abuse) a different set of controls to DM requests (that is, people who are not already your contacts), claiming they are a frequent source of abuse.

## Behaviour Based Controls
Analysis of user behaviour of the account posting the content, added as a signel to either an ML model or for an analyst to investigate.


## Banned word lists
Pros: Simple, predictable

Cons: 
* Real life is not so simple.  See [Zunger17](https://medium.com/@yonatanzunger/asking-the-right-questions-about-ai-7ed2d9820c48) and search for Jay-Z
* You will be accused of censorship.  

**NOTE:** You could alter / tag content based on word list(s) to help further controls i.e. a silent trigger for a soft challenge or a feature to pass on for behavioural / ML analyaisis.

## Threat Hunting 
Setting up operations to proactivly monitor volatile sisuations or important events (elections) and practively take steps (what steps?) to monitor, investage and limit the dissemination of fake content.

## Reporting systems
Reporting systems range from Twitter/Facebook-style "flag this content" buttons to DMCA-style reporting.

## Rate limiting
Pros: Stop the spread of fake news.

Cons: Stop activists from organizing the next Arab Spring.  Suddenly popular accounts may be popular for positive reasons.

## Content-dependent vs content oblivious
In [Content-Oblivious Trust and Safety Techniques: Results from a Survey of Online Service Providers](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3920031) Riana Pfefferkorn reports on a survey of 14 online service providers, and finds that in late 2021, abuse reporting systems are used more than other techniques.

