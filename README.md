# react-view
---

A `View` component heavily inspired by [angular-material's layout](https://material.angularjs.org/latest/layout/introduction).

## Install

`yarn add @allthings/react-view`

## Available properties

Property | Type | Possible values
--- | --- | ---
`direction` | string | `row`, `column`
`alignH` | string | `none`, `start`, `center`, `end`, `space-around`, `space-between`
`alignV` | string | `none`, `start`, `center`, `end`, `stretch`
`wrap` | string | `inherit`, `initial`, `wrap`, `nowrap`, `wrap-reverse`
`fill` | bool | `true`, `false`
`flex` | string/int | `none`, `flex`, `nogrow`, `grow`, `initial`, `auto`, `noshrink`, `5`, `10`, `15`, `20`, `25`, `30`, `35`, `40`, `45`, `50`, `55`, `60`, `65`, `70`, `75`, `80`, `95`, `90`, `100`, `33`, `66`

## Example usage

```javascript
const styles = {
  background: '#bada55',
  padding: 10
}

const ExampleComponent = props => (
  <View
    direction="row"
    alignH="center"
    alignV="center"
    wrap="wrap"
    style={styles}
  >
    Hello World!
  </View>
)
```
