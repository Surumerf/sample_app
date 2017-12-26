# Ruby on Rails Tutorial sample application

This is the reference implementation of the sample application for the 4th edition of [*Ruby on Rails Tutorial: Learn Web Development with Rails*](http://www.railstutorial.org/) by [Micheal Hartl](http://www.michaelhartl.com/).

## License

All sources code in the [Ruby on Rails Tutorial](http://www.railstutorial.org/) is available jointly under the MIT License and the Beerware License. See [LICENSE.md](LICENSE.md) for more details.

## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ git clone https://github.com/Surumerf/sample_app.git
$ cd sample_app
$ bundle install --without production
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in local server:

```
$ rails server
```

For more information, see the [*Ruby on Rails Tutorial* book](http://www.railstutorial.org/book).