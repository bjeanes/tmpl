# A Project

A description...

## Developing

This application uses a follower of the application that serves addon

* To set up app, run `bin/setup` (e.g. after a pull).
* To run all tests, run `bin/tests`.
* To run a specific test, run `ruby -Itest test/path/to/the_test.rb`
* To boot app, run `foreman start` (or `forego start`).

## Delivering

Run the tests against each commit in your feature branch:

```
bin/run-each bin/tests
```

## Deploying

Pushes/merges to the `master` branch will cause a CI run that will result in a
staging deploy.

## Contributing

See the [contribution guideline](CONTRIBUTING.md).

## License

See [full license](LICENSE).
