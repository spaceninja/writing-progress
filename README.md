# writing-progress

[![NPM version](http://img.shields.io/npm/v/@spaceninja/writing-progress.svg)](https://www.npmjs.org/package/@spaceninja/writing-progress)

A web component for authors to track progress towards a word count goal.

- [Demo](https://writing-progress.netlify.app/)

## How Does It Work?

Add the `<writing-progress>` element to your page with a `word-count` attribute, and it will calculate the progress towards your goal.

## Installation

```shell
npm install @spaceninja/writing-progress
```

## Usage

```html
<writing-progress word-count="19873"></writing-progress>

<script type="module" src="writing-progress.js"></script>
```

### Attributes

You can configure the component by setting any of the following attributes on the `<writing-progress>` element.

| attribute    | default value             |
| ------------ | ------------------------- |
| `word-count` | none                      |
| `goal`       | `100000`                  |
| `round`      | none                      |
| `start-date` | first day of current year |
| `end-date`   | last day of current year  |
