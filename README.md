# prettier-config

Prettier is the key to keeping all your codes in a consistent style and format, and no more asking your teammates to set the tab width to 2.

## Getting Started
1. Install the package.
```
pnpm i @tekminewe/prettier-config
```
2. Create `.prettierrc` in the root of your project with following content.
```
"@tekminewe/prettier-config"
```
3. Add the script in your `package.json`.
```
  "scripts": {
    // Your other scripts
    "prettier": "npx prettier --write ."
  }
```
4. Run `prettier` and enjoy your pretty codes.
```
npm run prettier
```