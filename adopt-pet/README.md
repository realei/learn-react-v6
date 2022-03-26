## Project shotcuts

### prettier
**Install:**

`npm install -D prettier`

**Command:**
`npm run format`

```
"scripts": {
	"format": "prettier --write \"src/**/*.{js,jsx}\""
}
```

### ESLint

**Install**

`npm install -D eslint eslint-config-prettier`

**Command:**

```
Worth adding three things here:

* With npm scripts, you can pass additional parameters to the command if you want. Just add a -- and then put whatever else you want to tack on after that. For example, if I wanted to get the debug output from ESLint, I could run npm run lint -- --debug which would translate to eslint **/*.js --debug.

* We can use our fix trick this way: npm run lint -- --fix.

* We're going to both JS and JSX.

```

### Parcel

`npm run dev`

```
"scripts" {
  "dev": "parcel src/index.html"
}
```
