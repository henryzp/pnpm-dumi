---
nav:
  title: TextArea
  path: /components
---

## TextArea

Demo:

```tsx
import React from 'react';
import { TextArea } from '@dzg/dawn';

class Demo extends React.Component {
  state = {
    value: '',
  };
  onChange = (e: any) => {
    this.setState({
      value: e.target.value,
    });
  };
  render() {
    return <TextArea value={this.state.value} onChange={this.onChange} />;
  }
}

export default () => {
  return <Demo />;
};
```

<API></API>
