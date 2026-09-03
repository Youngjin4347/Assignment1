# Assignment1 - 자기소개

## 설명
AI를 활용하여 만든 자기소개 웹.
전공, 취미, 관심 분야 등을 소개합니다.

## Vercel 배포 URL
assignment1-omega-ebon.vercel.app

## index.html
https://assignment1-omega-ebon.vercel.app/index.html

## index2.html
https://assignment1-omega-ebon.vercel.app/index2.html

## Key Learning: 이번 주 배운 핵심 내용 3가지
1. html의 기본적인 뼈대와 제목을 표시하는 법, 단락과 목록 등을 표시하는 법을 배웠다.
2. 내가 쓴 코드를 git을 이용하여 버전관리를 하는 것, git hub에 commit하고(내 코드가 하나의 버전으로 저장됨) push(커밋 후 내 컴퓨터의 git에만 있는 것을 git hub에 업로드)하는 법에 대해 알게 되었다.  
3. vercel을 사용하며 git hub에 저장된 프로젝트를 배포하는 방법에 대해 알게 되었다.
## Development Flow: VS Code → Git → GitHub → Vercel 흐름
1. VS Code에서 코드를 작성한다.
2. 작성한 코드를 commit하여 내 컴퓨터의 git에 저장한다(현재 코드의 버전을 기록).
3. 그 commit한 버전을 push하여 git hub에 올린다.
4. git hub와 연동된 vercel이 저장소의 변동을 감지하고 변경된 코드를 배포하여 웹사이트에 자동으로 반영한다.
## Code Modification: index.html에서 index2.html로 변경한 주요 내용
1. 처음 AI가 생성한 불필요한 이미지 파일을 지웠다.
2. 택스트 옆에 영어로도 설명을 추가했다.
3. 웹의 배경 색상을 변경했다.
4. 마지막 링크를 구글에서 히즈넷으로 변경했다.
5. 감사인사 단락을 추가했다.
## Problem & Solution: 실습 중 발생한 문제와 해결 방법 1가지
파워쉘에서 git clone 을 사용할 때 계속 Git hub의 프로젝트 파일이 복사되다가 지워지는 에러가 생겼다. 확인해보니 다른 Git hub 계정이 하나 더 있었는데 지금 사용하는 계정이 아닌 예전의 Git hub계정이 자동 로그인 되어 그 계정의 프로젝트 파일이 복사되어서 생긴 문제였다. 
지금 사용하는 Git hub계정으로 로그인을 따로 해주니 해결되었다.
## Reflection: 새롭게 알게 된 점 또는 궁금한 점 1가지
 index2 완성 후 vercel에서 도매인 주소로 들어가도 계속 처음 AI가 만든 index가 나와서 왜그런지 몰라서 TA세션에 가보았는데 다른 학우들도 나와 동일한 문제를 겪고 있었다. TA님의 답변으로는 도매인 주소는 대표 주소의 개념이라 그대로고 https://xxxxx.vercel.app/index2.html이런 식으로 직접 index2.html을 추가하면 내가 수정한 웹으로 들어갈 수 있다는 것을 알게 되었다. 