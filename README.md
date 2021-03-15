# forum-discussion-scrapping

a web scrapper for scrapping the hottest and latest political discussions in Chinese from one mainland China (bbs.tianya.cn), two Hong Kong based discussion forums (discussion.com.hk, uwants.com)

\*\*\*still under constructions, doesn't work properly\*\*\*

There exsists a few well-organized Chinese online forums for all sorts of discussions. The users will find discussions threads by clicking on general, pre-defined catorgies, such as food, travel, politics, etc., which is different from websites like reddit and quora where users are fed with recommended threads and the topics are more random. This allows easy access to chunks of hottest and latest discussions.

On the threads board at those websites, usually the number of replies are displayed. The scrapper simply find threads with larger number of replies (how large is large is decided based on heuristics for now) and the top n threads (again the value of n is based on heuristics for now). Heuristically, you can find discussions within 1h from discussion.com.hk, within 1 days from bbs.tianya.cn, and within a month from uwants.com

Have fun!