##  Estado

Gestion _controlado_ del estado.

```js
class FormComponent extends React.Component {
  state = { checked: false }
  handleClick = e => this.setState( ( { checked } ) => ( { checked: !checked } ) );

  render() {
    return (
      <form>
        <label htmlFor="cb">Checkbox</label>
        <input
          id="cb"
          type="checkbox"
          onClick={ this.handleClick }
          checked={ this.state.checked }
        />
      </form>
    )
  }
}
```
