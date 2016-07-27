# The Bluest Lie

Join the campaign to fight the 'Blue Lives Matter' ordinance that would make negative interactions with the police a hate crime. Find out more [here](http://blackyouthproject.com/the-bluest-lie-campaign-fights-efforts-to-make-violence-against-police-a-hate-crime/)

## Running locally

``` bash
git clone https://github.com/byp100/bluest-lie.git
cd bluest-lie

#install gems
gem install bundler
bundle install

# to run locally
jekyll serve -w
```

navigate to http://localhost:5000/

# Web dependencies

Data comes from the [Google Civic Information API](https://developers.google.com/civic-information/).

We used the following open source tools:

* [Bootstrap](http://getbootstrap.com/) - Responsive HTML, CSS and Javascript framework
* [jQuery Address](https://github.com/asual/jquery-address) - javascript library creating RESTful URLs
* [Google Civic Information API](https://developers.google.com/civic-information/) - API for looking up elected representatives in the USA

## Credits

Forked with permission from https://github.com/datamade/my-reps

Copyright (c) 2016 BYP100. Released under the [MIT License](https://github.com/byp100/bluest-lie/blob/master/LICENSE).
