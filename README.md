# hub-template
## Frequently used Terminal settings:
```bash
# git
git clone
## .gitignore
echo -e "node_modules\n" > .gitignore
# package.json
npm init -y
# nodemon
npm install --save-dev nodemon
## nodemon.json
echo -e '{
	\n\t"ignore": [
	\n\t]
\n}' > .nodemon
# prettier
npm install --save-dev eslint-config-prettier
## shield
echo "[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)" >> README.md
## .prettierrc
> .prettierrc
# eslint
npx eslint --init
## airbnb
npx install-peerdeps --dev eslint-config-airbnb-base
## .eslintrc
echo -e '{
	\n\t"env": {
		\n\t\t"browser": true,
		\n\t\t"es2021": true,
		\n\t\t"node": true
	\n\t},
	\n\t"extends": [
		\n\t\t"eslint-config-airbnb-base",
		\n\t\t"plugin:vue/vue3-recommended",
	\n\t\t"prettier"\n\t],
	\n\t"parserOptions": {
		\n\t\t"ecmaVersion": 12,
		\n\t\t"sourceType": "module"
	\n\t},
	\n\t"plugins": [
		\n\t\t"vue"
	\n\t],
	\n\t"rules": {
	\n\t}
\n}' > .eslintrc
## .eslintignore
echo -e "node_modules\n" > .eslintignore
# mocha
mkdir tests
# docker

## .dockerignore
echo -e "node_modules\n" > .dockerignore
# .vscode workspace settings
mkdir .vscode
echo -e '{
	\n\t"files.exclude": {
		\n\t\t"node_modules":true,
		\n\t\t".vscode":true,
		\n\t\t"package-lock.json":true,
		\n\t\t".prettierrc": true,
		\n\t\t".eslintrc":true,
		\n\t\t".gitignore":true,
		\n\t\t".eslintignore":true,
		\n\t\t"nodemon.json":true
		\n\t}
	\n}
\n' > ./.vscode/settings.json
# workspace
## folders
mkdir browser node test log
```
