Ember Library Template
======================

A template to get started when writing a new Ember.js template. This template is based on [interline/ember-skeleton](https://github.com/interline/ember-skeleton).

Get started
-----------

    $ git clone git@github.com:pangratz/ember-library-template.git
    $ cd ember-library-template
    $ bundle install

Change LIBRARYNAME in `Rakefile` to the name of your library

    $ bundle execute rake init

This initializes your library. Afterwards delete the `init` task in the `Rakefile`.

Now the template is initialized. Next: change the name of your library. To do this, update the value of the `APPNAME` variable in `Rakefile` and `Assetfile`.

Run the tests
-------------

    $ bundle exec rake test

or

    $ bundle exec rackup && open http://localhost:9292/tests/index.html

or

    $ bundle exec guard

Develop your library
--------------------

Implement your awesome library in `app/lib/library.js` and don't forget to add tests in `app/tests/library_test.js`.

Upload latest version of your library to GitHub
-----------------------------------------------

Invoke `rake upload_latest` to upload the latest version of your library to GitHub Downloads.