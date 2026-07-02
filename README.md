Syntax highlighting for JavaScript and TypeScript for the GNU nano text editor.

## Installation

1. Clone the repository:

```bash
git clone https://github.com/nousantx/javascript-nanorc.git
```

2. Open your nano configuration file:

```bash
nano ~/.nanorc
```

3. Add the following lines (adjust the path to where you cloned the repository):

```sh
include ~/javascript-nanorc/js.nanorc
include ~/javascript-nanorc/ts.nanorc
```

## Supported File Types

- `.js` - JavaScript
- `.mjs` - ES Module JavaScript
- `.cjs` - CommonJS
- `.jsx` - JavaScript with JSX
- `.json` - JSON
- `.ts` - TypeScript
- `.tsx` - TypeScript with JSX

## Usage

After installation, open any JavaScript or TypeScript file in nano:

```bash
nano myfile.js
nano myfile.ts
```

Syntax highlighting will be applied automatically based on the file extension.
