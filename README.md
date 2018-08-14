#### Install

```
npm install ivuel-loader --save-dev
```
#### Setting

```js
module: {
    rules: [
        {
            test: /\.vue$/,
            use: [
                {
                    loader: 'vue-loader',
                    options: {

                    }
                },
                {
                    loader: 'ivuel-loader',
                    options: {
                        prefix: false
                    }
                }
            ]
        }
    ]
}
```
