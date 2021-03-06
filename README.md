# MEAN Stack Authorization App
Sample MEAN stack app (MongoDB-Express-Node-Angular6) deployed on Heroku

Ref: Traversy Media's YouTube "MEAN Stack Front To Back"

### Requirements

- Heroku account
- mLab account
- Locally installed Git

### Pre-Upload to Heroku

Update confi/database.js for the database in mLab, i.e.

```
mongoURI: 'mongodb://abcdefg:abcdefg@ds123456.mlab.com:56789/meanauth-dev'
```

### Upload to Heroku

```
git init
git add .
git commit -am "initial commit"
heroku create
git push heroku master
```

### Live App

[URL: https://infinite-springs-40564.herokuapp.com](https://infinite-springs-40564.herokuapp.com)
