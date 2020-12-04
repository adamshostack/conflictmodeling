Selecting controls is often tricky.  They involve known-tradeoffs.  Over time, this page will grow to cover how those tradeoffs work, so you can engineer from an understanding of them, rather than re-inventing.

# Approaches and Tradeoffs

## Rules vs Principles
In [Warzel19](https://www.nytimes.com/2019/06/08/opinion/technology/youtube-crowder-vox-harassment-debate.html) Charlie Warzel and Sarah Jeong discuss principle-based and rule-based moderation, and Jeong says "The end result is that YouTube loses all trust, makes almost nobody happy and basically only empowers the worst actors by giving them more reason to have grievances. Even when YouTube does try to explain the logic to its rules, as it eventually did this week, it inadvertently lays out a map for how bad actors can sidestep takedowns, giving bad faith creators workarounds to harass or profit off bigotry. You know you’re in a real dark place when the good decisions YouTube makes are equally troubling."


## Incentives
[Warzel19](https://www.nytimes.com/2019/06/08/opinion/technology/youtube-crowder-vox-harassment-debate.html) also discusses how the YouTube incentive system plays a part in the problem, as creators are incented to create viral content, which can often be viral because it's offensive in some way.

## Testing
Google has released datasets for testing voice cloning and deepfake video.  ([Advancing research on fake audio detection](https://www.blog.google/outreach-initiatives/google-news-initiative/advancing-research-fake-audio-detection/) refers to a discipline of automatic speaker verification; [Contributing Data to Deepfake Detection Research](https://ai.googleblog.com/2019/09/contributing-data-to-deepfake-detection.html) is their dataset & blog on deepfakes.)

## Reducing Bias in ML
Amazon has released an interesting approach in [Mitigating social bias in knowledge graph embeddings](https://www.amazon.science/blog/mitigating-social-bias-in-knowledge-graph-embeddings) (Fisher, 2020)
