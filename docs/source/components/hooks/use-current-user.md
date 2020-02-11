---
title: useCurrentUser
summary: Hook that returns the current user.
---

## Example

```jsx
import React, { useState } from 'react';
import { useCurrentUser } from '@availity/hooks';

const MyComponent = () => {
  const [user = {}, loading] = useCurrentUser();

  return <div>{loading ? 'Loading...' : user.id}</div>;
};
```
