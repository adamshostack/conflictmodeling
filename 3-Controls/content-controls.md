# Managing Potentially Problematic Content

Choices you have include, but are not limited to:


1. Automated Response - AI/ML & Business Logic
2. UI Cues & Controls
3. Behaviour based controls
4. Banned word lists
5. Threat Hunting (proactive) 
6. Reporting systems (Reactive)
7. Rate limiting

**NOTE:** The problem with this page is that these controls can also be used on combination to each other and not just individual seperate controls. They have to be part of a cohesive strategy.



## Automated Response - AI/ML & Business Logic
With billions of users one thing that needs to be factored in is automation and business logic that balances user experience with, with the identification of fake/harmeful content.

The objective is to feed an ML model various signals in order to react to specific content i.e. either tag content for further review or provide soft challenges (rate throtteling / captcha / ID&V etc..) or preventative controls - banning account, blocking content, etc..

Various aspacts should be factored in such as political turmoil or upcomming elections as some of these issues changes depending on the date.

## UI Cues & Controls
Provide transparency and visibility to the users of content authenticity and challenges to false narratives. Also the user to request to make these cues more (or less) visibile. This includes providing visibile cues that the content of verious categories e.g. the ability to distinguish if the content is from an official news source, a promoted ad, an opinion piece etc..  
**NOTE:** I personally would like to know if the content I am seeing is an untampered news article, an opinion peice (which news sites do a poor job at tagging consistently) Official public Statements (press releases) vs. public/user generated content.

## Behaviour Based Controls
Analysis of user behaviour of the account posting the content, added as a signel to either an ML model or for an analyst to investigate.


## Banned word lists
Pros: Simple, predictable

Cons: 
* Real life is not so simple.  See [Zunger17](https://medium.com/@yonatanzunger/asking-the-right-questions-about-ai-7ed2d9820c48) and search for Jay-Z
* You will be accused of censorship.  

**NOTE:** You could alter / tag content based on word list(s) to help further controls i.e. a silent trigger for a soft challenge or a feature to pass on for behavioural / ML analyaisis.

## Threat Hunting 
Setting up operations to proactivly monitor volitalie sisuations or important events (elections) and practively take staps to monitor, investage and limit the decemination of fake content.

## Reporting systems
Reporting systems range from Twitter/Facebook-style "flag this content" buttons to DMCA-style reporting.

## Rate limiting
Pros: Stop the spread of fake news.
Cons: Stop activists from organizing the next Arab Spring.  Suddenly popular accounts may be popular for positive reasons.



