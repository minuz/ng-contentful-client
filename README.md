# ng-contentful-client
Under the hood, contentful.js uses Axios as HTTP Client. When using Angular Universal, the async calls are not completed prior to the rendering. This repository is based on contentful.js, but uses the native angular http client instead, which allows the SSR to run properly.
