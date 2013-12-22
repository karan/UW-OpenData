UW Open Data
============

![UW Open Data](https://raw.github.com/karan/UW-OpenData/master/UW.png)

An open API for [UW Course Catalog](http://www.washington.edu/students/crscat/).

Start
=====

	$ git clone https://github.com/karan/UW-OpenData.git
	$ cd UW-OpenData
    $ pip install -r requirements.txt
    ...
    $ python app.py

Deploying on Heroku
=======

- Install [Heroku Toolbelt](https://toolbelt.heroku.com/)
- `$ heroku login`
- `$ foreman start` to run the API server locally
- `$ heroku create` will create a new app in your account
- `$ git push heroku master` will deploy the API to the app

More detailed instruction are [available at Heroku](https://devcenter.heroku.com/articles/getting-started-with-python).

Usage
==========

**Output:** JSON

### `/<course code>`

Returns all courses for the requested code.

### Example:

    $ python app.py
    $ curl -i http://localhost:5000/cse


![](https://blockchain.info/Resources/buttons/donate_64.png)
=============

If UW Open Data has helped you in any way, and you'd like to help the developer, please consider donating.

**- BTC: [19dLDL4ax7xRmMiGDAbkizh6WA6Yei2zP5](http://i.imgur.com/bAQgKLN.png)**

**- Flattr: [https://flattr.com/profile/thekarangoel](https://flattr.com/profile/thekarangoel)**

**- Dogecoin: DGJxQkPqfxGkPYazHdPpAfatyagpDdG4qJ**

Contribute
========

If you want to add any new features, or improve existing ones, feel free to send a pull request!