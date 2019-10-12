## tarc

```javascript
  import Taro from '@tarojs/taro'
  import { View } from '@tarojs/components'
  
  class Test extends Taro.Component {
    constructor(props) {
      super(props)
    }

    static options = {
      addGlobalClass: true
    }

    config = {
      navigationBarTitleText: ''
    }

    componentWillMount() {}

    componentDidMount () {}

    componentDidShow () {}

    componentDidHide () {}

    componentCatchError () {}

    render() {
      return (
        <View> test </View>
      )
    }
  }

  export default Text
```

## tarcr
```javascript
  import Taro from '@tarojs/taro'
  import { connect } from '@tarojs/redux'
  import { View } from '@tarojs/components'

  class Test extends Taro.Component {
    constructor(props) {
      super(props)
    }

    config = {
      navigationBarTitleText: ''
    }

    componentWillMount() {}

    componentDidMount () {}

    componentDidShow () {}

    componentDidHide () {}

    componentCatchError () {}

    render() {
      return (
        <View> test </View>
      )
    }
  }

  const mapState = () => ({})

  const mapDispatch = () => ({})

  export default connect(mapState, mapDispatch)(Test)
```
