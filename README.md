# react-github-calendar

[![Greenkeeper badge](https://badges.greenkeeper.io/philipwhiuk/react-github-calendar.svg)](https://greenkeeper.io/)

[github-calendar](https://github.com/IonicaBizau/github-calendar) wrapper component for react

## History

* Forked from https://github.com/axetroy/react-github-calendar

## Install

```bash
yarn add @philipwhiuk/react-github-calendar
```

## Usage

```jsx harmony
import React, { Component } from 'react';
import ReactGithubCalendar from '@philipwhiuk/react-github-calendar';

class App extends Component {
  render() {
    return (
      <div>
        hello world
        <ReactGithubCalendar name="axetroy" />
      </div>
    );
  }
}
```

## Props

- name: string

> Github name

## Run the Demo

```bash
git clone https://github.com/philipwhiuk/react-github-calendar.git
yarn
yarn start
```

### License

The [MIT License](https://github.com/philipwhiuk/react-github-calendar/blob/master/LICENSE)
