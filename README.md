![ ](https://media.discordapp.net/attachments/1033015592036343841/1120428670310424697/Screenshot_2023-06-16_232014.png?width=1766&height=307)
# **RedditPirate**
___
**RedditPirate**<br>
Is an All-In-One solution, from account creation, posts creation, comment posting, upvoting/downvoting, RedditPirate is very simple Reddit Bot that will make reddit easier for you.<br>

# Attention<br>

RedditPirate is currently released as a BETA product. More features will get added as time goes by.
---
![ ](https://cdn.discordapp.com/attachments/1033015592036343840/1120921583922454679/Screen_Shot_2023-06-20_at_8.39.12_PM.png)
<br>

<p align="center">
  <img src="[https://cdn.discordapp.com/attachments/1033015592036343840/1120921583922454679/Screen_Shot_2023-06-20_at_8.39.12_PM.png]" />
</p>

### Accounts
- Account Management with options to Auto Login, automatically tracks account status and their karma and profile picture.
- Export is available in custom format
- Every account is assigned one static proxy
- Keep Alive requests for IDLE accounts, so they don't get logged out.
- Import your own accounts - we automatically assign an unique user agent and pick proxy one time from imported proxies.
- Each account is realtime updated, busy accounts are not available to be used with other tasks, before previous task is finished
- Automatic Shadowban Checker
- Cookie Management
- Clear Traces of an account
- Realtime session tokens updating per request
- Cookie storage - cookies are stored, bot does not need to login everytime on startup, unless cookies are expired
---
### Shadowban Remover
- We will try to remove shadowban via using some common methods
- Supports both IMAP emails and Temporary mails
- Does not work with every account, success rate is not 100%
- Option per account or bulk action
- Supports even accounts with no email set (usually bought accounts without original email)

*This method will not work for flagged accounts or suspended accounts - This means, if you make an account, start spamming and then try to unshadowban it 20 minutes later, it will not work.*
---
### Account Creation
- Proxy Support with Http, Socks4, Socks4a & Socks5 protocols
- Proxy Fraud Detection - Checks automatically if proxy is good or not
- Auto Profile Picture setting
- Automatic Profile Update with BIO and NSFW tag
- Custom IMAP Support - You can configure your own IMAP hosts to use with our account creator, or you can ignore this feature and use inbuilt temp-mail service
- Use Reddit Suggested usernames
- Each Account gets its own proxy, its own unique user agent and fingerprint
- WebRequest based, we are not using Selenium for account creation
  *Do not use rotating proxies for Reddit Accounts*
---
### Post Creation
- Currently supporting Image and Text posts
- Option to automatically add a comment after creating new post
- Automatic tracking of post status (upvotes, ...)
- Spintax for text is supported
- NSFW marking supported
- Spoiler marking supported
- Flair Selection
- Automatic flair selection if subreddit requires it and you didn't specify any
- Flair selection by priority
- Post to multiple subreddits at once
- Option to join subreddit before making a post
---
### Comment Posting
- Importing of URLS
- Importing of Comments
- Spintax support
- Select accounts that should make the comments or leave blank to use any
---
### Upvoting / Downvoting
- Supports both posts and comments
- Supports both absolute URL's or only comment/thread id
- Editable amount or just use maximum
---
### Subreddit Joiner
- Join subreddits with as many accounts as you want
- Threaded or single thread mode
- Used to grow community of your own
___

### Custom IMAP

RedditSuite allows you to configure your own settings for imap. You can setup for example gmail.com IMAP, enter all the info and then when RedditSuite picks an e-mail account from email list and finds that it belongs to gmail.com, it will use those settings + credentials from email list to connect to that IMAP provider. You can use any provider as long as IMAP access is allowed.<br>

---
### Image Cleaning

RedditSuite automatically cleans every image that is being uploaded, we automatically clean and update EXIF data and change pixel variations by small margin, to avoid MD5 detection of images or EXIF scans.
___
### Other features
- Automatic Startup with Windows
- Automatic login on all accounts with startup
- Automatically moves shadowbanned profiles to different directory and does not use them
- User-Agent override
- Custom Timeouts
- Randomized Delays between tasks and requests




