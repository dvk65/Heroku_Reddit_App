# Heroku_Reddit_App
App takes url from user and predicts the flare using that url. The code is used to crawl the r/India Reddit page.

Clone the code by copying the link to clone.

The python code is written using jupyter notebook.

Run the redditWebScrapingApp code first.

Then use the other two codes and use git bash to run the following commands:
$ cd my-project/
$ git init
$ heroku git:remote -a ml-deployment-app
$ git add .
$ git commit -am "adding files"
$ git push heroku master

This should give you a functioning app.

References:
https://towardsdatascience.com/deploying-a-deep-learning-model-on-heroku-using-flask-and-python-769431335f66
https://www.programcreek.com/python/example/100060/datetime.datetime.combine
https://praw.readthedocs.io/en/latest/code_overview/models/redditor.html
