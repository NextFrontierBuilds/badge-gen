# badge-gen

Generate README badges for npm packages. One command, instant shields.io badges.

[![npm version](https://img.shields.io/npm/v/badge-gen.svg?style=flat-square)](https://www.npmjs.com/package/badge-gen) [![npm downloads](https://img.shields.io/npm/dm/badge-gen.svg?style=flat-square)](https://www.npmjs.com/package/badge-gen) [![license](https://img.shields.io/npm/l/badge-gen.svg?style=flat-square)](https://www.npmjs.com/package/badge-gen)

## Install

```bash
npm install -g badge-gen
```

Or use directly with npx:

```bash
npx badge-gen <package-name>
```

## Usage

```bash
# Generate badges for any npm package
badge-gen ai-pdf-builder

# Append badges to a README file
badge-gen web-qa-bot --output README.md
```

## Output

```markdown
[![npm version](https://img.shields.io/npm/v/ai-pdf-builder.svg?style=flat-square)](https://www.npmjs.com/package/ai-pdf-builder) [![npm downloads](https://img.shields.io/npm/dm/ai-pdf-builder.svg?style=flat-square)](https://www.npmjs.com/package/ai-pdf-builder) [![license](https://img.shields.io/npm/l/ai-pdf-builder.svg?style=flat-square)](https://www.npmjs.com/package/ai-pdf-builder) [![node](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg?style=flat-square)]()
```

Renders as:

[![npm version](https://img.shields.io/npm/v/ai-pdf-builder.svg?style=flat-square)](https://www.npmjs.com/package/ai-pdf-builder) [![npm downloads](https://img.shields.io/npm/dm/ai-pdf-builder.svg?style=flat-square)](https://www.npmjs.com/package/ai-pdf-builder) [![license](https://img.shields.io/npm/l/ai-pdf-builder.svg?style=flat-square)](https://www.npmjs.com/package/ai-pdf-builder) [![node](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg?style=flat-square)]()

## Badges Generated

| Badge | Description |
|-------|-------------|
| Version | Current npm version |
| Downloads | Monthly download count |
| License | Package license |
| Node | Required Node.js version |

## Options

```
--output, -o <file>   Append badges to file instead of stdout
--help, -h            Show help message
```

## Why?

Manually creating badge markdown is tedious. This tool fetches live data from npm and generates consistent, copy-paste ready badges.

## License

MIT
