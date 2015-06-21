# React Style to CSS (string)
A heavily cropped, simplified version of the style to css string logic in [react-style][]. Used by react-static-jsx.

example:

    var React = require('react')
    var styleToCssString = require('style-to-css')

    var styles = {
        color: 'red',
        backgroundColor: 'white'
    };

    class HelloWorld extends React.Component{
      render() {
        return <div style={styleToCssString(styles)}>Hello, world!</div>
      }
    }

License
---
MIT

[react-style]: https://github.com/js-next/react-style
