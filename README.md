## tarc

```javascript
  import Taro, { Component } from '@tarojs/taro'
  import { View, Text } from '@tarojs/components'
  
  class Test extends Component {
    constructor(props) {
      super(props)
    }

    config = {,
      navigationBarTitleText: ''
    }

    componentWillMount() {}

    componentDidMount () {}

    componentDidShow () {}

    componentDidHide () {}

    componentCatchError () {}

    render() {
      return (
        <View>
          <Text> Test </Text>
        </View>
      )
    }
  }

  export default Text
```

## tarcr
```javascript
  import Taro, { Component } from '@tarojs/taro'
  import { connect } from '@tarojs/redux'
  import { View, Text } from '@tarojs/components'

  class Test extends Component {
    constructor(props) {
      super(props)
    }

    config = {,
      navigationBarTitleText: ''
    }

    componentWillMount() {}

    componentDidMount () {}

    componentDidShow () {}

    componentDidHide () {}

    componentCatchError () {}

    render() {
      return (
        <View>
          <Text> Test </Text>
        </View>
      )
    }
  }

  const mapState = () => ()

  const mapDispatch = dispatch => ()

  export default connect(mapState, mapDispatch)(Test)
```
