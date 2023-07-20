# Hello world docker action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

## `who-to-greet`

**Required** The name of person to greet. Default "World".

## Outputs

## `time`

The time we greeted you.

## Example Usage

uses: actions/hello-world-docker-action@v2
with:
  who-to-greet: 'Mona the Octocat'