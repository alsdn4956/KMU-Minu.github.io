![image](https://user-images.githubusercontent.com/84303574/146312456-cd62974a-f593-4d94-9ab9-cfc4be176013.png)

# My Github Page
-------------------------------------------
### 목차

#### My profile

#### Markdown

#### Jekyll

#### Git & Github

#### Google Analytics
-----------------------------------


### 1. My profile
<br/>
<br/>

블로그를 만든 기념으로 작성해 본 포스트이다. <br/>
간단하게 인스타 아이디와 Github 주소를 올렸다.
<br/>
xxminuxx_  <br/>
https://github.com/kmu-Minwoo <br/>
<br/>
<br/>
<br/>

### 2. Markdown
<br/>
<br/>
Markdown은 일반 텍스트 문서의 양식을 편집하는 문법이다.<br/>
README 파일이나 온라인 문서, 혹은 일반 텍스트 편집기로 문서양식을 편집할 때 사용한다.<br/>
쉽게 HTML문서 형태로 변환이 가능하다는 장점이 있다.<br/>
<br/>
이처럼 Markdown이 무엇인지 설명하고, Markdown 문법에 대해 소개하였다.
<br/>
주의깊게 알아볼 문법은 #의 개수이다.<br/>
개수에 따라 문서의 크기를 바꿀 수 있는데 1~6개 순으로 크기가 점점 작아진다.
깃허브에서 바꾸지 않고 콘솔창에서도 바꿀 수 있다.
<br/>
<br/>
<br/>

### 3. Jekyll
<br/>
<br/>
Jekyll 은 텍스트 변환 엔진이다.<br/>
정적 사이트를 만들기 때문에, PHP 등의 소프트웨어가 필요없다.<br/>
매우 빠르고 가볍다는 장점이 있다.<br/>
<br/>
<br/>
https://rubyinstaller.org/downloads/ <br/>
위 페이지에서 윈도우용 루비 + 개발자킷(DevKit) 설치 프로그램을 다운로드 후 완료되면,
Start Command Promp with Ruby를 실행

![image](https://user-images.githubusercontent.com/84303574/146314535-ba1b8fef-7636-4dac-b5bb-64a3d7fe0fa7.png) <br/>
를 입력해 패키지 설치
jekyll -v 를 입력해 설치 확인

![image](https://user-images.githubusercontent.com/84303574/146315535-83742b20-ee13-4303-84b7-92eafe6a9689.png) <br/>
자신의 블로그를 생성하고  <br/>
![image](https://user-images.githubusercontent.com/84303574/146315586-59eeab08-980d-48e2-8d01-4df39bbaa908.png) <br/>
블로그 디렉터리로 이동한다.<br/>
위의 과정들을 통해 Jekyll 환경을 구성하였다.
<br/>
<br/>
<br/>

### 4. Git계정 & Repository 생성하기
<br/>
<br/>
Git이 무엇인지 설명하고 Git을 개인과 팀이 사용하였을 때의 각각 장점을 작성하였다.
<br/>
먼저 Git을 설치한다.
그 다음 Github 계정을 생성한다.<br/>
<br/>

![image](https://user-images.githubusercontent.com/84303574/146313986-b75caa9f-4f91-49ef-b587-b788850a4cf2.png)
Repository name을 설정해야 한다. <br/>
<username.github.io>로 지정한다.<br/>
kmu-Minwoo.github.io  <- 이렇게 말이다.
<br/>
만약 원격저장소와 로컬저장소를 연결하고 싶다면 clone 명령어를 통해 연결할 수도 있다.
<br/>


### 5. Google Analytics


#### [View Demo](http://brianmaierjr.com/long-haul)

[![Netlify Status](https://api.netlify.com/api/v1/badges/bd29f13b-3754-46d7-9a39-48db2e174b99/deploy-status)](https://app.netlify.com/sites/long-haul/deploys)

## Features

- Minimal, Type Focused Design
- Built with GULP + SASS + BROWSERSYNC + AUTOPREFIXER
- SVG Social Icons
- Responsive Nav Menu
- XML Feed for RSS Readers
- Contact Form via Formspree
- 5 Post Loop with excerpt on Home Page
- Previous / Next Post Navigation
- Estimated Reading Time for posts
- Stylish Drop Cap on posts
- A Better Type Scale for all devices
- Comments powered by Disqus
- [Dark Mode support](https://github.com/brianmaierjr/long-haul/blob/master/preview-dark.png) via [prefers-color-scheme](https://developer.mozilla.org/en-US/docs/Web/CSS/@media/prefers-color-scheme) 

## Setup

1. [Install Jekyll](http://jekyllrb.com)
2. Fork the [Long Haul repo](http://github.com/brianmaierjr/long-haul)
3. Clone it
4. [Install Bundler](http://bundler.io/)
5. Run `bundle install`
6. Install gulp dependencies by running `npm install`
7. Run Jekyll and watch files by running `bundle exec gulp`
8. Customize and watch the magic happen!

## Site Settings

The main settings can be found inside the `_config.yml` file:

- **title:** title of your site
- **description:** description of your site
- **url:** your url
- **paginate:** the amount of posts displayed on homepage
- **navigation:** these are the links in the main site navigation
- **social** diverse social media usernames (optional)
- **google_analytics** Google Analytics key (optional)

### Header Option

If you'd like your header to be larger then you can use the option below in you `config.yml` to make it take up half of the vertical space on screens 800px wide and up. *Preview image below.*

- **header:** large

![preview Long Haul](/preview-large.png)

## License

This is [MIT](LICENSE) with no added caveats, so feel free to use this Jekyll theme on your site without linking back to me or using a disclaimer.
