# Hello world javascript action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `time`

The time we greeted you.

## Example usage

uses: AlexAntn/test_actions@v1
with:
  who-to-greet: 'Mona the Octocat'

![](https://github.com/AlexAntn/test-actions/workflows/.github/workflows/main.yml/badge.svg)
