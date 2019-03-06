# @sophek/use-filter-words

This is a custom react hook to filter bad words from a string.

## Install

```
$ npm install @sophek/use-filter-words
```

## Usage

```js
const [words, setWords] = useFilterWords("What the hell is this?");

//=> "What the **** is this?!"

```
