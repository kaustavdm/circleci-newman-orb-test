# Newman CircleCI Orb test

A test repository to run [`newman`][_newman] tests in CircleCI using the [`newman` CircleCI orb][_orb].

[_newman]: https://learning.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman
[_orb]: https://circleci.com/orbs/registry/orb/postman/newman

## Running with `newman`

Install newman:

```
$ npm install -g newman
```

Run the collection in the `tests` directory:

```
$ newman run ./tests/CircleCI\ newman\ orb\ test.postman_collection.json
```