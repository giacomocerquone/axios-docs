---
id: axios-instance
title: Creating an axios instance
---

### Creating an instance

You can create a new instance of axios with a custom config.

##### axios.create([config])

```js
const instance = axios.create({
  baseURL: 'https://some-domain.com/api/',
  timeout: 1000,
  headers: {'X-Custom-Header': 'foobar'}
});
```

### Instance methods

The available instance methods are the same you can find in the [default axios object](the-axios-object.md) plus the one listed below. The specified config will be merged with the instance config.

##### axios#getUri([config])
