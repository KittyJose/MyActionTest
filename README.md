# some action script

This action prints action payload.

## Inputs

### `who-to-greet`

**Required** The name of the person to greet. Default `"World"`.

## Outputs

### `payloadOp`

the payload

## Example usage

uses: actions/hello-world-javascript-action@v1.1
with:
  who-to-greet: 'Kitty Jose'
