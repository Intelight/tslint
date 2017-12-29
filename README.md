# tslint-intelight
TSLint rules for Intelight projects.

## Installation

`yarn add tslint-intelight --dev` or `npm install tslint-intelight --save-dev`

## Usage

To use these this preset, use configuration inheritance via the extends keyword. Here's a sample configuration where tslint.json lives adjacent to your node_modules folder:

```
{
	"extends": ["tslint-intelight"],
	"rules": {
		// if you want to make some adjustments
		// you can override preset rules here
	}
}
```
