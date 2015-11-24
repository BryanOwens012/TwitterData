# TwitterData
This is where I store all the gathered Twitter data.

### Conversion process:
1. Take a txt from folder `ids_raw`, then use included `TwitterIDToName.jar` to convert the IDs to screen names
2. Place the resulting txt of converted screen names into folder `names`
3. Take that txt, then use [`TwitterUserTweets.jar`](https://github.com/BryanOwens012/TwitterUserTweets/releases) to convert the screen names to txts of tweets
(For each txt of screen names, create a subfolder in folder `tweets` to hold the tweets of those users)

#### Note:
- `popular_users_followers_ids.txt` used to be called `newids.txt`
- `popular_users_followers_names.txt` used to be called `newids_out.txt`

Thanks to **zhangxiaoxuan1** and **Bovey Qin** for contributing!
