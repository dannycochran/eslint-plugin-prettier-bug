### Steps to reproduce

1. Install dependencies.

```sh
yarn
```

or 

```
npm o
```

2. Run lint from `actualApp`

```
cd actualApp
yarn lint
```

You will see an error noting that the semi-colon should be removed, because one directory up, there's a `.prettierrc.js` file that specifies no semi-colons.