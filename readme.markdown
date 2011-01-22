# aspect-status

With this project I aim to present a view of how well I, as a person, am operating.
I was inspired to do this after seeing how beautifully [Google Apps Dashboard](http://www.google.com/appsstatus#hl=en) presents a view of how their systems have been operating.
The things I find impressive about it, and aim to steal, are:

* It doesn't just show how things are today. because most of the time I know how things are today.
* It doesn't go too far into the past, at least in its initial view.
  I dwell on the past enough as it is.
* It isn't overly free-form.
  I think Google's structured approach is better, at least for internal use, than simply posting notes to a blog.
* It shows a lot of fields in a small amount of space.

The main difference is that instead of automatically collecting data, data will need to be entered in by a human.
As I learned in the first chapter of [Beautiful Data](), this can be challenging.
My initial strategy will be to remind me to use it, but only if I don't use it on my own.

## Status

* I haven't implemented this project yet.
* I'm doing [README-driven development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html).
* [I know kung fu.](http://www.youtube.com/watch?v=EmEPXXJ4sKw)


## Getting Started (DRAFT)

*   Have a working Ruby setup with Bundler
*   Be logged into your [Cloudant](https://cloudant.com/) account
*   Sign up for a Heroku account and install the Heroku gem
*   Clone this repo
*   run `heroku create <<appname>>`
*   Set up a CouchDB database
    *   Create a database
    *   Create an API key
    *   Give that API key read, write, delete permissions on the database
*   run `heroku config COUCH\_URL <<database url>>` 
    (CLOUDANT\_URL also works, as a fallback, if you decide to use Cloudant's Heroku add-on)

Running locally and deploying to other services is left as an exercise for the reader.

## TODO

* Deploy to Heroku
* Force SSL in production
* Set up database (Cloudant)
* Add javascript libraries (jQuery, backbone.js, icanhazjs)
* Get fake data in database
* Implement viewing
* Implement editing
* Implement notifications

