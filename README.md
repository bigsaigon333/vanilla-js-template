# javascript-package-initial-settings

1. yarn을 이용하여 package 초기화

```shell
$ yarn init
```

2. prettier 설치 및 설정

```shell
$ yarn add prettier --dev --exact

# 별도로 옵션을 설정하지 않고 기본 설정 그대로 사용
$ echo {} > .prettierrc.json

```

3. eslint를 설치한다

```shell
$ yarn add eslint --dev

$ yarn eslint --init
yarn run v1.22.10
✔ How would you like to use ESLint? · problems
✔ What type of modules does your project use? · esm
✔ Which framework does your project use? · none
✔ Does your project use TypeScript? · No / Yes
✔ Where does your code run? · browser
✔ What format do you want your config file to be in? · JSON
Successfully created .eslintrc.json file
Done in 13.17s.
```

- airbnb JS style 적용

```shell
$ npx install-peerdeps --dev eslint-config-airbnb-base
```

[참고자료- Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)

- eslint-config-prettier 설치

```shell
$ yarn add eslint-config-prettier --dev
```

[참고자료 - Prettier vs. Linters](https://prettier.io/docs/en/comparison.html)

- cypress 및 eslint-plugin-cypress 설치

```shell
$ yarn add cypress --dev

$ yarn add eslint-plugin-cypress --dev

```

4. editorconfig 설정 및 editorconfig for vs code extension 설치

[EditorConfig](https://editorconfig.org/)
[EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

5. vscode settings 추가
