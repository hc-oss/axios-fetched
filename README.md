# axios-fetched

> **info** This is a fork of https://github.com/developit/redaxios with interceptor PR changes added (since it's more then 2 years and it's unlikely that this PR will be merged)

[Axios] has a great API that developers love. axios-fetched provides that API in **800 bytes**, using native `fetch()`.

For those searching for ways to shave a few kilobytes off of their bundles, that's less than 1/5th of the size. This is made possible by using the browser's native [Fetch API][fetch], which is [supported in all modern browsers](https://caniuse.com/#feat=fetch) and polyfilled by most tools including Next.js, Create React App and Preact CLI.

### Can I just use Axios?

Yes! Axios is an excellent module and you should use it! axios-fetched exists so that you can use that same API in cases where it's difficult to justify the dependency. Instead of having to choose between Axios and Fetch, axios-fetched provides a middle-ground between the two.

[axios]: https://github.com/axios/axios
[fetch]: https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch

### Usage

```js
import axios from 'axios-fetched';
// use as you would normally
```

Refer to the [Axios Documentation](https://github.com/axios/axios#axios-api).
