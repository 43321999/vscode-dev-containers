# hub-template
## Frequently used Terminal settings:
```bash
# git
git clone
## .gitignore
echo -e "node_modules\n" > .gitignore
# package.json
npm init
# nodemon
npm install --save-dev nodemon
## nodemon.json
> nodemon.json
# eslint
npx eslint --init
## airbnb
npx install-peerdeps --dev eslint-config-airbnb-base
## .eslintrc.json
echo -e '{\n\t"env": {\n\t\t"browser": true,\n\t\t"es2021": true,\n\t\t"node": true\n\t},\n\t"extends": [\n\t\t"eslint-config-airbnb-base",\n\t\t"plugin:vue/vue3-recommended"\n\t],\n\t"parserOptions": {\n\t\t"ecmaVersion": 12,\n\t\t"sourceType": "module"\n\t},\n\t"plugins": [\n\t\t"vue"\n\t],\n\t"rules": {\n\t}\n}\n' > .eslintrc.json
## .eslintignore
echo -e "node_modules\n" > .eslintignore
# docker

## .dockerignore
echo -e "node_modules\n" > .dockerignore
# .vscode workspace settings
mkdir .vscode
echo -e '{\n\t"files.exclude": {\n\t\t"node_modules":true,\n\t\t".vscode":true,\n\t\t"package-lock.json":true,\n\t\t".eslintrc.json":true,\n\t\t".gitignore":true,\n\t\t"eslintignore":true,\n\t}\n}' > ./.vscode/settings.json
# workspace
## folders
mkdir browser node test
```
