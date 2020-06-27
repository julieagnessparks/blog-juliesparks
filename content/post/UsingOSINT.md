+++
author = "Hugo Authors"
title = "Using Open Source Intelligence to Discover My Digital Footprint"
date = "2019-10-10"
description = "Using OSINT on myself to understand my public presence."
+++

As much as I’ve read about OSINT, or open source intelligence gathering, I’ve only done some research for various work projects. I wanted to gain more practice using OSINT techniques and what’s a better way than to practice on yourself?

I am going to explain my process and what I discovered in my attempt to build a profile on myself using only my name, birth date, and state of residence. I consider myself a person who is very private online but I did grow up in a world with computers and I’ve made way more accounts than I ever could remember.

All the following research was completed by me with publicly available tools. While I have experience with security, no specific security concepts were necessary in my research.

**What is OSINT?**

OSINT, according to Wikipedia, is data collected from publicly available sources to be used in an intelligence context.

**How did I begin?**

I started by doing Google searches which can be quite painful as there are *many* Julie Sparks’ in the world. From a combination of Google and Google Image searches I was able to find my LinkedIn and Twitter profile, including Twitter mentions from various friends over the years. One of my crowning moments online in high school was getting tweeted at by the original Olive Garden account.

![img](https://lh4.googleusercontent.com/Hlrlt3NJ6vrZ_WethkbulmaqrvD-XK2patLvKPr0U7tn4BiMBf1eWVb6wiTSb7Ip2Rd-sxfPjHfZOL_nCTvuUZpExLZcG6T2HdvKQzLqRIPamCUn9EWoJu7fXSJnfuE3qA1dtnVK)

I also found my personal website and other sites in which I was featured or was listed as an author such as [Rollins College](https://www.rollins.edu) and [Cloudflare](https://blog.cloudflare.com/author/julie/). After discovering my personal website, I scanned it for website vulnerabilities, just in case.

Many of the platforms I used for searches gave me no results, such as Global File Search, Getty Images, Pastebin, and Facebook. [Stalkture](https://stalkture.com/), an Instagram scraping tool, found my profile and suggested followers which included two family members but little else due to my high privacy settings. I searched through pages of Youtube for mentions of “Julie A. Sparks” and I found I have a doppelganger who loves posting monologues. And then I stumbled upon my middle school Youtube account including a cringe worthy alternate username I used before turning 18. Pivoting off this username I found numerous other accounts--not mine--in which I found someone else had branded themselves using this username, and is incredibly popular on DeviantArt. In the fluidity of identity and creativity, their adoption of my username captures the ease and flexibility built into the Internet.

In my now known association to Rollins College as an undergraduate student, I scraped their website for mentions of me which included a photo I submitted to a photo contest, my place on the cross country team, a field study to Greece, and the President’s List. From this information you could make a good profile on the type of student I am; however, all of this is also on my LinkedIn profile. Learning of my time on the cross country team, I looked at public track and field records on [FLRunners](https://fl.milesplit.com/). FLRunners has a profile on my athletic history from high school through college. Discovering my high school, I then searched Google extensively for mentions of “Julie Sparks” that tie me to the school. I found various community newsletters announcing scholarship grants, involvement in track & field, current outreach, and PTA notes from my elementary school.

[NameCheckr](https://www.namecheckr.com/) is a great tool that further drilled down into popular website I may have accounts, showing my Github and Spotify profiles. [HaveIBeenPwned](https://haveibeenpwned.com/) lists several websites where I had an account and information was breached--an interesting attack vector for a potential hacker. Of all the tools I used, [SpiderFoot](https://github.com/smicallef/spiderfoot) gave the most comprehensive scan with options for various inputs and level of scanning. For my school email, I gained 83+ potential websites which had an account associated with that email.

All of this is a decent amount of information but that didn’t prepare me for the next part of my search.

**Are you a Florida resident?**

Florida’s Sunshine Law, passed in 1991, ensures free public access to Florida’s government documents and proceedings including police arrest records. This law is one reason that the popular [Florida Man meme](https://twitter.com/hashtag/floridaman?lang=en) exists. However, what that means for its residents is many of their personal details are available online in digitized free to use databases. Beginning at Florida State Records, it takes less than 60 seconds to find my records including my age, locations I’ve lived, and my parents with their respective ages.

Next I moved on to Florida Voters, an open listing of my voting records including address, voter ID, date of registration, and my party affiliation. Included on those records were my last voting address, when I submitted my absentee ballot, located in Ireland. Just from my voting records I grabbed a list of all my addresses--even my apartment abroad. What about my parents? Florida Voters shows my father has never registered to vote in Florida and it gives similar detail for my mother’s registration.

Next repository for public records is the County Clerk Office. Luckily I have no records tied to my name but knowing my parents populated dozens of records on their marriage, divorce, house purchase, IRS claims, tax records, and wage garnishment payments. The culmination of Florida public records is enough to build a timeline of my life with my family growing up including financial hardships, school districts, and party affiliation.

**What are my next steps?**

- Lock down my data
- Understand what others can learn about me online
- Be careful about where and how my data is used moving forward

**Where can you start?**

- This [article](https://medium.com/@Peter_UXer/osint-how-to-find-information-on-anyone-5029a3c7fd56) by Petro Cherkasets gave me a lot of resources.
- [OSINT Link](https://osint.link/)
- Check out various resources I’ve linked throughout the post.

**Takeaways**

What surprised me most was how locked down my Facebook account seemed. Perhaps because a lot of women named Julie Sparks have a Facebook, or because I hardly use, or because I have the highest privacy settings. It was refreshing to see that was not the source of all my information online.

I discovered several tools that bordered on the side of scary but represent the real gravity of personal data and an individual’s metadata. [Facebook Sleep Stats](https://github.com/sqren/fb-sleep-stats) uses social media data to estimate your sleep schedule and map how you spent your day. [Apply Magic Sauce](https://applymagicsauce.com/demo) uses social media data to build a “psycho-demographic profile.” These are just some examples of why it’s important to adopt high privacy settings.

I was inspired to undertake this project after I finished [Permanent Records](https://www.amazon.com/Permanent-Record-Edward-Snowden/dp/1250237238/ref=asc_df_1250237238/?tag=hyprod-20&linkCode=df0&hvadid=385115590018&hvpos=1o1&hvnetw=g&hvrand=13413343038602256677&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=&hvtargid=pla-817635065886&psc=1&tag=&ref=&adgrpid=78287769493&hvpone=&hvptwo=&hvadid=385115590018&hvpos=1o1&hvnetw=g&hvrand=13413343038602256677&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=&hvtargid=pla-817635065886) and watched [The Great Hack](https://www.imdb.com/title/tt9358204/) on Netflix. Understanding how your data is used is something that is vital to your security and privacy moving forward. I firmly believe data rights are a fundamental human right.
