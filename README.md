# Newman CircleCI Orb test

A test repository to run [`newman`][_newman] tests in CircleCI using the [`newman` CircleCI orb][_orb].

## Running with `newman`

Install newman:

```
$ npm install -g newman
```

Run the collection in the `tests` directory:

```
$ newman run ./tests/CircleCI\ newman\ orb\ test.postman_collection.json
```

## Running in CircleCI

Add your repository as a project in CircleCI. See [./circleci/config.yml](circleci/config.yml) for an example.

[_newman]: https://learning.getpostman.com/docs/postman/collection_runs/command_line_integration_with_newman
[_orb]: https://circleci.com/orbs/registry/orb/postman/newman