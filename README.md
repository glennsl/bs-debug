
# bs-debug

BuckleScript bindings to [debug](https://github.com/visionmedia/debug).

## Example

```ml
let debug = Debug.make "debug:example"

let () = debug "log me an A" [@bs]
```

## Installation

```sh
npm install --save bs-debug
```

Then add `bs-debug` to `bs-dependencies` in your `bsconfig.json`:
```js
{
  ...
  "bs-dependencies": ["bs-debug"]
}
```