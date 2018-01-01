# eslint-plugin-radargun

Adds an environment to ESLint for the [`radargun`](https://www.npmjs.com/package/radargun) benchmarking utility.

## Usage

Install the plugin as a `devDependency`:

```sh
$ npm install eslint-plugin-radargun -D
```

Add an `.eslintrc` file to the directory that contains all of your `radargun` benchmarking scripts:

```json
{
  "env": {
    "radargun/bin": true
  }
}
```

This configuration ensures that the `bench()` function is recognized as a global when the script is run by `radargun`.
