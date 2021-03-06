# input

React component for Input

## Usage

### Install
```
npm i @react-ag-components/input --save
```
### Use in your project
```
import Input from '@react-ag-components/input'
```

```
<Input
  label="Weight amount"
  id="weight-amount"
  value={this.state.weightAmount}
  onChange={this.onChange('weightAmount')} />
```

### Properties

| Property        | Default| Description  |
| -------- |:-------------:|-------------:|
| id       | same as label |              |
| type     | "text"        |              |
| value    | ""            |              |
| onBlur   |               | function     |
| onChange |               | function     |
| label    | ""            |              |
| error    | ""            |              |

## Contributing

Get the repository
```
git clone https://github.com/alphillips/input.git
```

Update dependencies
```
npm install
```

Run the project
```
npm start
```

### Deploy to npm
#### Build
`npm run build -- --copy-files`

#### Publish
`npm publish --access public`
