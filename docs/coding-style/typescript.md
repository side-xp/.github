# TypeScript coding style for Node projects

We use *Biome* as our main linting & formatting tool.

We created a dedicated `npm` package from which you can inherit to use the same rules.

Create a `biome.json` file at the root of your Node project and add:

```json
{
  "extends": ["@side-xp/biome-config/biome.json"]
}
```

See the [@side-xp/biome-config](https://www.npmjs.com/package/@side-xp/biome-config) package for more details about the code rules.