# Material components for React
[![Maintenance Status][status-image]][status-url] [![NPM version][npm-image]][npm-url] [![License][license-image]][license-url] 

React components based on styles from [Material Design Components Web project][mdc-web]. Components are written in React.js. Doesn't use MDC JS sources.

## Installation
```sh
npm i --save react-mdc-web
```

## Usage
```jsx
import React, { Component } from 'react'
import {Card, CardHeader, CardTitle, CardText, CardActions, Button} from 'react-mdc-web/lib';

class MyComponent extends Component {
  render() {
    return (
        <Card>
          <CardHeader>
            <CardTitle>
              Title goes here
            </CardTitle>
          </CardHeader>
          <CardText> 
            Lorem ipsum dolor sit amet, sint adipiscing ius eu, qui eu aliquid minimum imperdiet. In ridens impedit vis, an habeo accumsan dissentiunt eam, id cum elitr putant voluptatibus. Congue admodum mentitum per no, harum inimicus contentiones pri an. Sea eius modus adipiscing ei, his erat erroribus intellegebat cu.
          </CardText>
          <CardActions>
            <Button compact>Save</Button>
            <Button compact accent>Remove</Button>
          </CardActions>
        </Card>
    );
  }
}

```

## License
MIT, see [LICENSE](/LICENSE) for details
[status-image]: https://img.shields.io/badge/status-maintained-brightgreen.svg
[status-url]: https://github.com/kradio3/react-mdc-web

[npm-image]: https://img.shields.io/npm/v/react-mdc-web.svg
[npm-url]: https://www.npmjs.com/package/react-mdc-web

[license-image]: https://img.shields.io/badge/license-MIT-blue.svg
[license-url]: https://raw.githubusercontent.com/kradio3/react-mdc-web/master/LICENSE