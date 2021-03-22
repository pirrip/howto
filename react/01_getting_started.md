### install nvm

[NVM for Windows GIT](https://github.com/coreybutler/nvm-windows/releases)

```shell
nvm -v
# book recommendation
nvm install 8.10.0
# LTS
nvm install 14.16.0
# current
nvm install 15.12.0

# 버전 체크
nvm use 14.16.0
node -vㅜ프
npm -v
```

### react앱 생성

```shell
# yarn 설치
npm install -g yarn
# create-react-app 설치
yarn global add create-react-app
# react 앱 생성
npx create-react-app doits
# 실행
yarn start
```

### VSCode Plugin

[Reactjs code snippets](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
[Prettier](https://prettier.io/docs/en/options.html)

### Prettier 포맷 적용

`.prettierrc` 파일 작성

```json
{
	"trailingComma": "es5",
	"tabWidth": 2,
	"printWidth": 240,
	"jsxBracketSameLine": true,
	"proseWrap": "never",
	"htmlWhitespaceSensitivity": "ignore",
	"endOfLine": "lf",
	"semi": true,
	"singleQuote": false,
	"jsxSingleQuote": false
}
```

### VSCode Hot Key

`ctrl`+`shift`+`p` - preference
`ctrl`+`,` - settings
`alt`+`shift`+`f` - format
