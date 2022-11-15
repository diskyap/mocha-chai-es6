## Configuration ES6 mocha babel

### Step by Step --
### 1. npm init -y
### 2. npm i --save-dev supertest mocha chai @babel/cli @babel/core @babel/node @babel/register @babel/preset-env
### 3. create .babelrc
### 4. add 
```
{
    "presets": ["@babel/preset-env"]
}
```
### 5. create .mocharc.yaml
### 6 add
```
require: '@babel/register'
```
### 7. add html reporter : npm i --save-dev mochawesome
