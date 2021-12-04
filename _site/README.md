### 1.0 repo 만들기
github 에 snacktime81.github.io repository만듦

### 1.1 로컬 저장소 연결
git clone을 하여 내 노트북에 local repo 를 연결함

### 2.0 index.html 생성
html을 이용하여 index.html파일을 생성

### 3.0 jekyll을 repo에 다운
404.html, Gemfile, Gemfile.lock, _config.yml, _posts/, about.markdown, index.markdown을 생성하고
<br>index.html을 삭제

### 4.0 introduce-myself post 작성
introduce-myself 포스트를 _posts 레포 아래에 생성함

### 5.0 Theme 적용
kasper Theme을 다운 받고 현재 repo에 Gemfile, Gemfile.lock, posts를 제외한 파일들을 수정함'

### 5.1 _config.yml 수정
name과 meata_description을 수정함

### 6.0 disqus 다운
disqus를 introduce81 사이트를 생성

### 6.1 _config.yam 에 disqus 추가
_config.yam에 disqus정보 추가

### 6.2 introduce-myself comments 수정 및 disqus 연결
introduce-myself 포스트에 comments를 true로 설정
<br> post.html에 disqus를 설

### 7.0 SW2-Adproject post 작성
SW2-Adproject post 작성

### 7.1 disqus 연결
comments = true로 하여 댓글 기능 가능하게 설정

### 8.0 Markdown post작성
Markdonw post 작성

### 8.1 disqus 설정 해재
comments = false 로 설정하여 댓글 기능 비활성화

### 9.0 google analytics 가입
google analytics가입 후 측정 ID값을 받아옴

### 9.1 google analytics 연결
_config.yam에 측정 ID 기입

### 9.0 favicon 이미지 추가
assets/logo.ico 안에 favicon 이미지 저장

### 9.1 favicon 코드 작성
_layout/default.html의 <head>태그 아래에 코드를 작성