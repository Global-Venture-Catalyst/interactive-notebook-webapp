# interactive-notebook-webapp

This is an example notebook that shows how to turn jupyter notebooks into webapps deployed on Heroku, using Voila.

The notebooks provided are from [voila](https://github.com/voila-dashboards/voila/tree/master/notebooks).


## Getting Started

### Locally
```
pip install requirements.txt
voila notebooks
```

### Deploying to Heroku

Ensure you have the heroku CLI installed.
```
heroku login
heroku create YOUR_APP_NAME
heroku push origin main
```

Check out the deployed app at [https://interactive-notebook-webapp.herokuapp.com/](https://interactive-notebook-webapp.herokuapp.com/)


### References
- https://github.com/voila-dashboards/voila
- https://towardsdatascience.com/creating-interactive-jupyter-notebooks-and-deployment-on-heroku-using-voila-aa1c115981ca
- https://devcenter.heroku.com/articles/creating-apps
