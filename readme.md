# npm init
```
npm init -y
```

# typescript 설치
```
npm i -D typescript
```

# tsconfig 셋팅
```
{
    "include": [
        "src"
    ], // 타입스크립트 필요한 폴더.
    "compilerOptions": {
        "outDir": "build", // 컴파일하여 자바스크립트 파일이 생성될 디렉터리.
        "target": "ES6" // js 버전 지정
    }
}
```

package.json 에서 scripts 셋팅

```
"scripts": {
    "build": "tsc"
  },
```
  
## ts build 설정
```
npm run build
```







