# welcome-for-cli

> Welcome header for Node.js CLI software.

<br>

## Installation

### npm

```sh
npm install welcome-for-cli
```

### Yarn

```sh
yarn add welcome-for-cli
```

## Usage

```js
import welcome from 'welcome-for-cli';

// Use it.
welcome({ title: `Welcome CLI`, tagLine: `by csalam07` });

// OR with all the options set like this:
welcome({
  title: `Welcome CLI`,
  tagLine: `by csalam07`,
  bgColor: `#FADC00`,
  color: `#000000`,
  bold: true,
  clear: true,
  version: `v1.0`,
});
```

<br>

## API

### welcome(options)

#### ❯ options

Type: `object`<br>
Default: `{}`

You can specify the options below.

#### ❯ title

Type: `string`

CLI title with background color highlight.

#### ❯ tagLine

Type: `string`

CLI tag line in front of the title without highlight but dimmed.

#### ❯ description

Type: `string`

CLI description below the title.

#### clear

Type: `boolean`<br>
Default: `true`

Clear console.

#### bold

Type: `boolean`<br>
Default: `true`

Bold heading text.

#### bgColor

Type: `string`<br>
Default: `#ffffff`

Background color highlight for `heading`.

#### color

Type: `string`<br>
Default: `true`

Text color for `heading`.

#### version

Type: `string`<br>
Default: `(empty string)`

Print version text.

<br>

## License

- MIT © [cslam07](https://twitter.com/CSALam12/)
