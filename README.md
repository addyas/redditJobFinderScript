## Reddit Job Scraper

This script takes a reddit username, and returns comments that may detail the user's occupation, by searching for keywords like "job", and "work".

### Why?

The internet is creepy. Embrace it. 



### How?
```markdown
import praw

 reddit = praw.Reddit(user_agent='Comment Extraction (by /u/USERNAME)',
                     client_id='CLIENT_ID', client_secret="CLIENT_SECRET",
                     username='USERNAME')
```

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)


For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
