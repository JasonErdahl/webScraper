# webScraper
In this assignment, you'll create a web app that lets users view and leave comments on the latest news. But you're not going to actually write any articles; instead, you'll flex your Mongoose and Cheerio muscles to scrape news from another site.

db.getCollection('articles').find({})
db.getCollection('notes').find({})
db.articles.remove({})
db.notes.remove({})


https://webscraper-digg2018.herokuapp.com/
https://jasonerdahl.github.io/
https://github.com/JasonErdahl/webScraper


FIX FOR HEROKU CONNECTION
PATH="$PATH:/c/Program Files/Heroku/bin"
heroku logs

npm i dotenv