---
title: useSpacesContext
---

If you are using a function component, you can subscribe to the spaces by using this hook.

## Example

```jsx
import React from 'react';
import { useSpacesContext } from '@availity/spaces';

const SpacesComponent = () => {
  const { spaces, loading, error } = useSpacesContext();

  return loading ? <p>Loading...</p> : <div>Content to display</div>;
};
```
