Ruby on Rails Tutorial sample application
=========================================
This is the sample application for [*Ruby on Rails Tutorial: Learn Web
Development with Rails*][Ruby on Rails Tutorial] (6th Edition) by
[Michael Hartl].

License
-------
All source code in the [Ruby on Rails Tutorial] is available jointly
under the MIT License and the Beerware License.

Getting started
---------------
To get started with the app, clone the repo and then install the needed
gems:

    bundle install --without production

Next, migrate the database:

    rails db:migrate

Finally, run the test suite to verify that everything is working
correctly:

    rails test

If the test suite passes, you'll be ready to run the app in a local
server:

    rails server

For more information, see the [*Ruby on Rails Tutorial* book].

[Michael Hartl]: https://www.michaelhartl.com/
[Ruby on Rails Tutorial]: https://www.railstutorial.org/
[*Ruby on Rails Tutorial* book]: https://www.railstutorial.org/book
