# Hello World JS Action

This action prints "Hello World" or "Hello" + the name of a person to greet to the log.

## Inputs

### `who`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `date`

The date we greeted you.

## Example usage

```yaml
uses: bk-lopes/helloworld-js-action@main
with:
  who: 'Mona the Octocat'
```