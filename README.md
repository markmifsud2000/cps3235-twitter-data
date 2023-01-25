**Note:** Due to poor time management, the data collection script was only run once before the initial deadline.
That data is available on the main branch.
After the deadline, the collection script was run daily, between 26/12/2022 and 22/01/2023.
This larger data set has been uploaded to this branch, and will be used for any remaining tasks. 


# Twitter Data for CPS3235 Assignment

The included csv files contain the data collected for the CPS3235 assignment.
Data was collected starting from user `@elonmusk`.

## Tweet.csv

`Tweet.csv` contains the data on each tweet collected.

This includes all tweets created by Elon Musk (including replies, retweets and quotes),
as well as any tweets referenced by Elon Musk (such as tweets he replied to or retweeted).

Certain data (public metrics, referenced tweets, entities) was only collected for tweets made by Elon Musk,
and not for tweets that he referenced.

Elon Musks Tweets can be obtained by selecting the entries with `Author_id=44196397`.

## User.csv

`User.csv` contains the data on all users collected.

This includes any user who authored a collected tweet, any user mentioned by Elon Musk in a tweet,
and accounts following/followed by Elon Musk.

## Followers.csv

`Followers.csv` represents all FOLLOWING relations between users.

Elon Musk's Follower's can be obtained by selecting those entries where 'user=elonmusk'.
Any accounts he follows can be obtained by selecting those entries where 'follower=elonmusk'.

## Collected By

```
Mark Mifsud
0382200L
mark.mifsud.18@um.edu.mt
```
