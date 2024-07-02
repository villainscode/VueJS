# VueJS
VueJS Tutorial 


## Project setup
## Node 설치 
```shell
$ brew install nvm
$ brew install node 
```


## 환경변수 등록
```shell
$ vi ~/.zshrc

export NVM_DIR="$HOME/.nvm"
[ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
[ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion

$ :wq!
```

## 변경사항 적용 
```shell
$ source ~/.zshrc
$ node -v
$ nvm -v 
```

## Vue CLI 설치
```shell
$ npm install -g @vue/cli

$ vue --version 
```

## project 생성
```javascript
$ vue create . // 프로젝트 생성  
$ npm install   // 의존성 설치 
$ npm run serve // 프로젝트 실행
```

## 접근 
```javascript
http://localhost:8080
```
