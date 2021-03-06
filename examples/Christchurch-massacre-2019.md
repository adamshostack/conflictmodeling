This is an example of how we can use a conflict modeling engineering repository (such as this one) to inform responses to a horrific event such as the [Christchurch Mosque shootings](https://en.wikipedia.org/wiki/Christchurch_mosque_shootings).  Before he began, the murderer sent out a manifesto via Twitter, 8Chan and email, and he livestreamed the murders.  There are questions of why each one was hard to surpress.

# Livestream video
The video obviously violates the terms of service of Facebook Live.  However, taking down copies of videos is not as easy as it initially seems.  Facebook removed over 1.5 million versions of the attack; 1.2 million at upload. [Facebook Newsroom tweet](https://twitter.com/fbnewsroom/status/1107117981358682112) They also chose to remove all edited versions that "do not show graphic content" [Followup tweet](https://twitter.com/fbnewsroom/status/1107117981828431872).  Facebook has posted a "[A Further Update on New Zealand Terrorist Attack](https://newsroom.fb.com/news/2019/03/technical-update-on-new-zealand/)," which discusses many of the challenges they faced.

## Content Identification via fingerprinting or machine learning.
Pros: The Content ID technology exists.

Cons: 
* Systems like ContentID routinely flag the wrong content.
* Machine learning would have many false positives on video game streams.

Challenges:
* It would be trivial to add a few seconds of random other video to the start, overlay a chyron, or to simply re-encode it as you upload a copy.  These changes would break the ContentID technology (See [Stamos twitter thread](https://threadreaderapp.com/thread/1106650393902104578.html) and "[Inside YouTube’s struggles to shut down video of the New Zealand shooting — and the humans who outsmarted its systems](https://www.washingtonpost.com/technology/2019/03/18/inside-youtubes-struggles-shut-down-video-new-zealand-shooting-humans-who-outsmarted-its-systems/)")  Facebook reported finding "over 800 visually-distinct variants of the video."
* ContentID is dependent on a copyright owner asserting that a video is theirs. In this case, the video owner wanted it shared. Who should be authorized to stop a video?  (See also pre-authorization)



## Pre-authorize live streaming
There were also calls for putting controls on who can live stream video, or turning off video upload for events of some magnitude.

Pro: Fewer people live streaming makes monitoring of abuse easier.

Cons: 
* Raises concerns for activists who use livestreams to record abuse by police.  (See [Bonnie Boyd](https://twitter.com/BonnieCeit/status/1106755184695361536) comment.) This is obviously a concern that also impacts those who live under repressive regimes.
* Once the video has streamed anywhere, a non-live version can be uploaded to YouTube, Vimeo and other video sharing platforms, and is not longer "live."

## Flagging systems
Facebook [reports](https://newsroom.fb.com/news/2019/03/technical-update-on-new-zealand/) that it was first notified 12 minutes after the live broadcast ended.

# Block the manifesto
It seems obvious that text matching for the content of the manifesto could allow it to be controlled.

Pros: Don't spread the word

Cons: 
* What about journalists quoting it?  What ratio of words is acceptable?  Is it ok to say "This trash speaks for itself?"  
* (The entire free speech debate; who gets to make the call; what scope their calls have)
