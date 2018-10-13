# Scrape Onions

**DESCRIPTION:** App that scrapes recent political articles from the Onion and allows users to leave their comments.

**USER EXPERIENCE**

* Upon loading of the app, all articles will load from the mongoose Articles collection.
* If the collection is empty, the user will have the option of making the first scrape by clicking the scrape button.
* By hovering over an article tab, an Onion logo button will appear that can redirect the User to the actual article.
* By clicking anywhere on the article tab except the logo button, the comment thread for that article will load.
* The user has the ability to post a comment by leaving their name along with their comment.
* At anytime, the user can click "Refresh Results" to scrape for any new articles on the Onion.


**PROGRAMMING / FUNCTIONALITY**

* App is built using the following languages/technologies:
  - *HTML* 
  - *CSS* 
  - *JavaScript*
  - *jQuery*
  - *Handlebars*
  - *Node.js*
  - *MongoDB*
  - *Mongoose*
  - *Express*
  
* Web scraping is facilitated using Cheerio and Axios middleware.


**FILE STRUCTURE**

```

├── models
│   ├── article.js
│   ├── comment.js
│   └── index.js
├── public
│   └── assets
│       ├── css
│       │   ├── reset.css
│       │   └── style.css
│       ├── images
│       │   └── favicon.png
│       │   
│       └── javascript
│           └── functions.js
├── views
│   ├── articles.handlebars
│    └── layouts
│       └── main.handlebars
│
├── package-lock.json
├── package.json
│
├── README.md
│
└── server.js
       
```