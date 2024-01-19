---
title: React 프로젝트 만들기
date: 2024-01-18 17:57
categories: [React, 서브카테고리]
tags: [React]
pin: false
image: 
img_path:
---

## Node.js 설치하기

터미널에서 homebrew를 이용해 npm과 Node.js를 설치해줍니다.

```bash
    brew install nvm
```

환경변수 설정을 위해 vi편집기로 이동합니다.

```bash
    vim ~/.zshenv
```

아래 환경변수를 설정해줍니다.
```bash
export NVM_DIR="$HOME/.nvm"
[ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
[ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
```

환경변수를 적용해줍니다.

```bash
source ~/.zshenv 
```

이제 nvm으로 node.js를 설치할 수 있습니다.

ls-remote 명령어로 버전을 체크한뒤,
```bash
nvm ls-remote
```

LTS 버전을 다운받아줍니다.

```bash
nvm install v20.11.0
```

버전을 체크하여 다운로드를 체크합니다.
```bash
node --version
```

## React 프로젝트 만들기

이제 React프로젝트를 생성할 수 있습니다. <br/><br/>

프로젝트를 만들고싶은 폴더에 터미널을 열어 준 후, 아래 명렁어로 프로젝트를 생성합니다. <br>
위 명령어로 생성이 잘 되지 않을 시, sudo를 붙여 관리자권한을 준 뒤 실행합니다.

```bash
npx create-npx-react-app <projectName>

sudo npx create-npx-react-app <projectName>
```

 + node_modules : 라이브러리 보관함
 + public : static 파일 보관함
 + src : 소스코드 보관함. 여기서 코드를 짤 수 있습니다.


 ### 만든 프로젝트 내에서 저장이 안되는경우

 ```bash
 sudo chmod -R 777 <프로젝트 경로>
 ```

터미널에서 위 명령어로 해결할 수 있습니다.