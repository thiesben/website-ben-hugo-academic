---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Walking Through Twitter: How to Mine a National Follow Network"
event: "AoIR Flashpoint Symposium 2019"
event_url: "https://sites.google.com/uniurb.it/dms-week/aoir-symposium"
location: "University of Urbino Carlo Bo, Urbino, Italy"
address: 
  street: Via Aurelio Saffi 2
  city: Urbino
  region: Puglia
  postcode: 61029
  country: Italy
summary:
abstract: "Twitter is used by individuals, grassroots movements, and political and social elites to directly communicate to the public and influence opinion. The platform appears relatively accessible to researchers because the majority of accounts post publicly and its API remains comparably open. However, after Twitter introduced restrictive rate limits in 2012 (Puschmann & Burgess, 2012), the global follow network stopped being accessible to the majority of researchers (for exceptions, see e.g., Myers, Sharma, Gupta, & Lin, 2014).
<br><span style='padding-left:3em'>
This development results in a lack of independent research on a key mechanism for information diffusion and a global infrastructure for influence. While it is widespread research practice to address this lack by using proxies for networks of attention on Twitter, such as mention, co-hashtag, or retweet networks (e.g., Himelboim, Smith, Rainie, Shneiderman, & Espina, 2017), all of these rely on active communication. Therefore, silent listening may be underrepresented.</span>
</span><br><span style='padding-left:3em'>
This situation is aggravated by a change in how Twitter assigns account IDs. Until recently, its consecutive numbering scheme allowed a few independent, technically and monetarily costly projects such as the Australian Tracking Infrastructure for Social Media Analysis (TrISMA) (Bruns et al., 2016) to collect details of public accounts globally. Based on this, national follow networks could be captured and analysed (e.g., Bruns & Enli, 2018; Bruns, Moon, Münch, & Sadkowsky, 2017). However, Twitter closed this possibility by assigning account IDs at random, undermining further data mining efforts following this collection strategy.
</span><br><span style='padding-left:3em'>
Therefore, we present a large-scale test of a new sampling technique, building on the rank-degree method (Salamanos, Voudigari, & Yannakoudakis, 2017). As this walk-based technique only requires local information to sample a graph, we were able to adapt it as a data mining method for the follow networks of influential Twitter users, using the cost-free standard Twitter API. This approach has been tested on an ongoing collection of influential accounts in the German-speaking Twittersphere. So far, we have compiled a network of more than 200,000 accounts and 840,000 edges.
</span><br><span style='padding-left:3em'>
First results indicate that this network sample is suitable for investigating large-scale functional and topical communication structures in the Twittersphere. For example, we can detect topical clusters of prominent and influential accounts, or identify bridges between rather disconnected groups. Further, descriptive statistics show that the sample exhibits similar distribution patterns for indicators of influence and activity as a near-complete collection of German-speaking Twitter accounts from 2016. This is evidence that our sample represents an influential backbone of the German Twittersphere.
</span><br><span style='padding-left:3em'>
In light of the growing restrictions on the Twitter API, this shows that our new technique for gathering and analysing selected network samples is a valuable alternative to more brute-force approaches. Even though Twitter has made it almost impossible for independent researchers to capture comprehensive, large-scale follow networks, our method works around these restrictions to produce a robust perspective on the overall structure of these networks, for the German Twittersphere and other contexts. The code for this approach will be published under an open-source licence.</span>"

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: 2019-06-23T15:10:00+02:00
date_end: 2019-06-23T15:30:00+02:00
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: 2019-07-12T20:07:31+02:00

authors: ["Felix Victor Münch", "Ben Thies", "Cornelius Puschmann", "Axel Bruns"]
tags: ["Twitter", "Quantitative Methods", "Network Science"]

# Is this a featured talk? (true/false)
featured: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Top"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

# Optional filename of your slides within your talk's folder or a URL.
url_slides:  https://www.slideshare.net/FelixVictorMnch/walking-through-twitter-sampling-a-languagebased-follow-network-154303762

url_code:
url_pdf:
url_video: https://www.youtube.com/watch?v=qsnGTl8d3qU&feature=youtu.be&t=21822

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## References
Bruns, A., Burgess, J., Banks, J., Tjondronegoro, D., Dreiling, A., Hartley, J., … Sadkowsky, T. (2016). TriSMA: Tracking infrastructure for Social Media Analysis. Retrieved from https://trisma.org/

Bruns, A., & Enli, G. (2018). The Norwegian Twittersphere: structure and dynamics. *Nordicom Review*, 1–20. http://doi.org/10.2478/nor-2018-0006.1

Bruns, A., Moon, B., Münch, F. V., & Sadkowsky, T. (2017). The Australian Twittersphere in 2016: mapping the follower/followee network. *Social Media + Society*, 3(4). http://doi.org/10.1177/2056305117748162

Himelboim, I., Smith, M. A., Rainie, L., Shneiderman, B., & Espina, C. (2017). Classifying Twitter topic-networks using social network analysis, 1–38. http://doi.org/10.1177/2056305117691545

Myers, S. A., Sharma, A., Gupta, P., & Lin, J. (2014). Information network or social network? The structure of the Twitter follow graph. *WWW’14 Companion*, 493–498. http://doi.org/10.1145/2567948.2576939

Puschmann, C., & Burgess, J. (2014). The Politics of Twitter Data. In K. Weller, A. Bruns, J. Burgess, C. Puschmann, & M. Mahrt (Eds.), *SSRN* (pp. 43–54). New York: Peter Lang. Retrieved from https://eprints.qut.edu.au/67127/1/Puschmann_%26_Burgess_politics_of_Twitter_data.pdf 

Salamanos, N., Voudigari, E., & Yannakoudakis, E. J. (2017). Deterministic graph exploration for efficient graph sampling. *Social Network Analysis and Mining*, 7(1), 24. http://doi.org/10.1007/s13278-017-0441-6"


