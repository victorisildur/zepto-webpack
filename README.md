# Install
Since webpack ProvicePlugin can only be used when $ is directly derived from a module,
current modules can't be used conviently in webpack since their exports.$ is what we got.

To install, only type:

```npm install npm-webpack```

# Usage

```javascript
plugins: [
    new webpack.ProvidePlugin({
        $: 'npm-webpack'
    })
]
```

