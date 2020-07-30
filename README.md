# Project-Gulliver
![logo](/img/gull.png)

**Project Gulliver** is a open source initiative to detect, flag and report sites utilizing ads which go against AdSense usage policies. 

This project focuses more towards Google AdSense since it’s the most widely used (legal online ad platform) present right now. It pay well for (good) content. 

### Adsense specifically has several ways for showing ads including:

> As stated: 
* (Original) Adsense for website’s and YouTube.
* Admob: Analyze, monetise and promote mobile apps.


Some of the Ad types include text, display, rich media. All in all, it is a platform where majority of advertisers put their stake (and $$$) on to get potential customers.

AdSense as such is the majority profit maker for Google with billions in annual turnover.


For displaying ads with AdSense for content, publishers receive 68% of the revenue recognized by Google in connection with the service. For AdSense for search, publishers receive 51% of the revenue recognized by Google. (https://support.google.com/adsense/answer/180195)

That’s a generous chunk of cash, compared to other ad platforms. Here is where the catch is, click fraud and malicious revenue generation. 

*[ClickGuardian](https://www.clickguardian.co.uk/click-fraud-statistics/) states that estimated $27..2+ billion in estimated revenue was lost to click fraud in the year 2018.*


Google Ads pay for both PPC(Pay per Click) and CPM (Cost per thousand impressions).PPC gets more revenue than CPM. There are a lot of ad fraud schemes using bots, manual pay per click etc going around from years. Thankfully Google has procedures in place using deeplearning and other internal tools to detect and flag such activities. 

## What is the goal of this project?

One thing which I personally disliked about Google is its Adsense approval process. I once used to be a blogger, who got dismayed by Google for approving low quality blogs, pirated movie sites. Google fails to verify properly several sites which pushes low quality content and host hoard of ads on it. It requires a lot of manual verification to find and suspend such sites from the program and is usually time consuming .

Unfortunately, there is only a one way possible email communication (https://support.google.com/adsense/troubleshooter/119050) which gives a place to report such violating sites.

This results in :
1. Advertisers losing genuine customers.
2. Truthful and genunine content creators getting less chance for better ads.
3. Siphoning of revenue from Google to violating webmasters practising such frauds .

You can read more about Terms and conditions of Google Adsense [here.](https://support.google.com/adsense/answer/23921)


***Project Gulliver aims at creating a shorter interaction time with Google moderators and takedown sites having pirated , spammy, clickbait content which runs Google AdSense and may have not yet been detected by Google review team.***

This will fast-track taking down ads from such sites and give better opportunities for genuine content creators.

## How you can help?

If you find sites violating Google TOC and still have adSense enabled, issues a pull request to **site.md** with a screenshot of the running ad. You may also add the Publisher id of site: ca-pub-12650550879054xxx (which can found at the page source, usually within <head> tags; around the script which gets called to place Google Ads.
  
A moderator will review it,  approve and then report the violation to Google Support Team.
We will hold frequent review to ensure if the site has been stripped off from the AdSense program. If so, the site will be moved onto **banned.md** .

## Calling out:
* Programmers for building automated tools.
* Bloggers who believe in success of genuine content creators and help find Ad fraud sites .
* Security researchers to detect and find sites employing Google ads in malicious ways.


## Goal and future:
We want this repo to be a go to place where the Google Team comes , take a look, verify and immediately ban such sites from the Adsense platform. Being well aware that there are tools and filters in place to flag many such sites, still internet is a vast ocean; there is good chance for drops to leak out from filters, and we are exactly here for that.

## Communication:
If you are from Google/ or have any ideas feel free  to issue a pull request to contact me. 

*Disclaimer: This project is not associated to Google or its partners nor has any backing. This is my personal endeavour to correct problems I faced when I was a blogger and which I feel can help change as a Security Researcher now.* 
