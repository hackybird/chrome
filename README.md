# Filter & Sort your twitter feed with HackyBird ! 


## Features : 
- Filter out tweets by keywords 
- Sort a timeline / feed / search results by retweets & likes
- Assign weights to users (for sorting)
- Mark tweets as "read"
- No signup required !


## Usage : 
- Go to twitter home page or a timeline or search results in your browser
- Click ![Hackybird](http://i.imgur.com/XXtSQm1.png) to filter / sort
- You can load more tweets & click the icon again to filter / sort
- You can also hide tweets that have been sorted (see options)


## Options : 
###### Right click ![Hackybird](http://i.imgur.com/XXtSQm1.png) to select options

## Filter by keywords
- You can enter comma separated keywords. Any tweet containing these keywords would be hidden when you click the hackybird icon.
![](http://i.imgur.com/Md6hnSU.png)
- Alternately, you can download popular keywords from https://mute.life by clicking "mute.life" button

## Sort by popularity
- Click "enable sort"
![](http://i.imgur.com/IrEegiK.png)
- Adjust the weight percentage for retweets & likes (for estimating popularity of a tweet, for sorting). E.g. `100% retweet` and `0% like` means sorting would consider retweet count only. 
- You can choose to normalize the count of retweets & likes by the tweet's age (e.g. to see what's hot)
- You can mark the tweets as "read". Tweets once sorted will be hidden from subsequent sort operations. Simply uncheck the box or reload the page to undo that. 

## User weights
- Hover over a username (on twitter.com) to adjust a user's weight (used for sorting). Default weight is `1`
![](http://i.imgur.com/MtRsJP2.png)
- Non-default weights are visible under options
![](http://i.imgur.com/SqeIa75.png)


## Why would I use this
- You follow anywhere from a dozen to a few hundred people on twitter
- You don't want to miss out on the important stuff & don't have to sift through the drivel
- You want to fine tune & re-arrange your timeline
- You dislike "magic" sorting. You want predictability & control


## FAQ
**Q** : Do I need to signup or authorize with my twitter account ? 
**A** : No. Just open your twitter timeline or search anything on twitter or go to any user's feed & click the extension to sort. 

**Q** : Are my settings sync'd in the cloud or with my google account ? 
**A** : Currently no. All settings are saved in your browser's local storage. 

**Q** : How do I unhide the tweets (that were marked as read)
**A** : Either reload the page OR uncheck the "Mark as read" option 

**Q** : What is "user weight" ? 
**A** : Higher weight => tweets & retweets from the user would be shown higher up. 
    Default is 1. Any other value is multiplied to the count of retweets & likes. 
    So a user weight of 1.5 with 100 retweets & 20 likes has a score = 1.5 x (100 + 20)

**Q** : How do I change the "user weight" ? 
**A** : After you've sorted your timeline (i.e. clicked on the extension), you can simply hover over the username of either the tweeter or the retweeter. 
    A small floating box will show up with either the default weight (i.e. 1) or whatever value you've stored in the past. 
    Just enter a new value & you should be done. 

**Q** : What is "Normalize" in options ? 
**A** : If checked, the count of retweets & likes is divided by the age of the tweet (in seconds). Otherwise absolute count is used.

