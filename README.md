# dezling-ui

#### Its a UI Library for React script

> A Magic ui for react and react nextjs to make your website s

[![NPM](https://img.shields.io/npm/v/dezling-ui.svg)](https://www.npmjs.com/package/dezling-ui) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)![Code style](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)

## Install

```bash
//nmp install
npm install --save dezling-ui

//yarn install
yarn add dezling-ui
```

## Adding Stylesheet to Ui

#### add this line to your index.js or App.js

```bash
import "dezling-ui/src/styles.css";

```

## Usage

```jsx
import React, { Component } from 'react'
import {Wrapper,Row,Col, Button} from 'cloud-ui'

class Example extends Component {
  render () {
    return (
      <Wrapper>
      <Row>
      <Col>
      First column
      </Col>
      <Col>
      Second column
      </Col>
      <Col>
      Third column
      <Button outline color='primary'>Hit me here</Button>
      </Col>
      </Row>
      <Wrapper/>
    )
  }
}
```

## Documentation

Check out our documentation website.

## Change Log

Recently Updated? Please read the changelog.

#### Its under construction

## License

This project is licensed under the terms of the [MIT license](https://github.com/dezlingroof/dezling-ui/#license).
