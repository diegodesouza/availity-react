---
title: Feedback
summary: Availity feedback with smiley faces react component.
---

## Installation

### NPM

```bash
$ npx install-peerdeps @availity/feedback --save
```

### Yarn

```bash
$ yarn add @availity/feedback
```

## Example

```jsx live=true viewCode=true
import Feedback from '@availity/feedback';

<div className="w-100 d-flex flex-column justify-content-around align-items-start">
  <Feedback
    appName="Payer Space"
    prompt="Please provide some feedback"
    color="primary"
  >
    Provide Feedback
  </Feedback>
</div>;
```
