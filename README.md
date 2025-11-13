<h1 align="center">
  <a href="https://github.com/jcubic/tsdocu">
    <img src="https://github.com/jcubic/tsdocu/blob/master/.github/logo.svg?raw=true" />
  </a>
</h1>

Simple tsdoc Markdown documentation generator

## Usage

```bash
npx -y tsdocu
```

## Config

Create a file named `tsdocu.json`, here is example content:

```json
{
  "path": "snapp",
  "include": ["src/**/*.{ts,tsx}"],
  "exclude": ["**/*.test.{tsx,ts}", "node_modules/**"],
  "output": "docs"
}
```

* `path` (string) - an entry point
* `include` (`string | string[]`) - glob of the files you want to include
* `exclude` (`string | string[]`) - glob of the files to exclude
* `output` (`string`) - output directory

## License

Copyright (c) 2025 [Jakub T. Jankiewicz](https://jakub.jankiewicz.org)

Released under [MIT](http://opensource.org/licenses/MIT) license
