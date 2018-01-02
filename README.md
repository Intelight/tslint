# @intelight/tslint
TSLint rules at Intelight.

## Installation

`yarn add @intelight/tslint --dev` or `npm install @intelight/tslint --save-dev`

## Usage

To use these this preset, use configuration inheritance via the extends keyword. Here's a sample configuration where `tslint.json` lives adjacent to your `node_modules` folder:

```
{
	"extends": ["@intelight/tslint"],
	"rules": {
		// if you want to make some adjustments
		// you can override preset rules here
	}
}
```

Then run `tslint --project ./tsconfig.json 'src/**/*.{ts,tsx}'`
