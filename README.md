# AURA Platform Technical Test

Write an application in a language of your choice which covers the deatils below. It will be evaluated according to categories at the bottom of the this readme.

## Application Details

Your application should be a simple, small, operable web-style API service. It should implement the following items:

- a simple root endpoint which responds in a simple manner; "hello world" or some such
- a health endpoint which returns an appropriate response code
- a metadata endpoint which returns basic information about your application; example:

```json
"myapplication": [
  {
    "version": "1.0",
    "description" : "technical test",
    "lastcommit": "c0484c"
  }
]
```

- tests or a test suite; the type of testing is up to you

## Finish

Once the application has been written, continue with the following additions:

- provide a means of packaging your application as a single deployable artifact which encapsulates its dependencies
- create a pipeline that builds your application on each commit; Travis or similar, for example
- describe or demonstrate any risks associated with your application/deployment
- write a clear and understandable `README` which explains your application and its deployment steps

## Submission format
Preferred option is a link to public git repository with your solution. Alternatively a [git-bundle](https://git-scm.com/docs/git-bundle) or zip archive are acceptable.

## How the submission will be evaluated 

The solution and documentation will be rated against the following categories:

- Simplicity
- Code / documentation layout
- Ease of deployment
- Idempotency
- Security
- Anti-fragility

The documentation is as important as the code. We are looking to understand why you chose a certain solution and what trade offs it has. Be prefered to answer any question about your solution at the next interview stage.
