github-api
==========
Simple GitHub API bindings.

Usage
=====
* First: `(require github-api)`
* Then create an identity: `(github-identity type data)`
* Finally, initiate the bindings: `(define api-req (github-api github-identity))`
* Now do your request: `(github-create-gist api-req files)`

For more detailed usage information and examples, see the included documentation.

Installation
============
Run `raco pkg install git://github.com/eu90h/racket-github-api` or use DrRacket.

To remove, execute `raco pkg remove racket-github-api`

A Note on Testing
=================
To run the functional tests require a valid GitHub username & personal-access-token/password. If you wish to run the tests, edit the credentials in `functional_tests/identity.rkt`.
