about@ Ying
> What is the result?
```js
class HelloMessage extends React.Component {
  render() {
    return (
      <div>
        Hello {this.props.name}
      </div>
    );
  }
}

ReactDOM.render(
  <HelloMessage name="World" />,
  document.getElementById('hello-example')
);
```
- "Hello World"
- "Hello"
- "HelloWorld"
- "Hello HwlloMessage"