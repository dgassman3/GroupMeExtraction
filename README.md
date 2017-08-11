# GroupMeExtraction

Youyanggu wrote a great python script that utilizes a GroupMe access token to pull messages and information from the GroupMe API. His scripts can be found here: https://github.com/youyanggu/groupme_stats

One issue for my utilization that I noticed is the "name" from a single message was used. As users in the GroupMe app can change their name whenever they want, one user may have infinite names. This poses a bit of an identity problem, depending on the end goal.
My version has simply added in a "user_id" column, which is a 1-to-1 relationship with a GroupMe account and facilitates easier identification of who sent a particular message.
