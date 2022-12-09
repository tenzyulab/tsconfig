# @tenzyu/tsconfig

## Installation

```sh
pnpm i -D @tenzyu/tsconfig
```

## Usage

use extends field in yout tsconfig.json

```json
{
  "extends": "@tenzyu/tsconfig/lib.json",
  "compilerOptions": {
    "outDir": "lib"
  },
  "include": ["src/**/*.ts"],
  "exclude": ["src/**/*.test.ts"]
}
```

## License

MIT

## Author

[@tenzyu](https://github.com/tenzyu)
