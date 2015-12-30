# React Towel

Rapid React Prototyping

React Towel brings together babel-standalone, react, react-dom, and throw-in-the-towel to make it dead simple to start using React with JSX and ES6.

1. Include this script in your html page
2. Write es6 scripts in `<script type="text/babel"></script>` tags
3. View the page
5. Profit?

Checkout an example by viewing the source for: [react-towel.surge.sh](http://react-towel.surge.sh)

```es6
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
    <script src="https://npmcdn.com/react-towel/umd/react-towel.js" charset="utf-8"></script>
    <script type="text/babel">
      const Winner = () => <h1>winning?</h1>
      ReactDOM.render(
        <Winner />,
        document.getElementById('root')
      )
    </script>
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>
```
