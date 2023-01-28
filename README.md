# Atom

[![Build status](https://dev.azure.com/github/Atom/_apis/build/status/Atom%20Production%20Branches?branchName=master)](https://dev.azure.com/github/Atom/_build/latest?definitionId=32&branchName=master)

> Atom 및 Atom 관련 모든 리포지토리는 2022년 12월 15일에 보관됩니다. [공식 발표](https://github.blog/2022-06-08-sunsetting-atom/)에서 자세히 알아보세요.

Atom은  [Electron](https://github.com/electron/electron)에 기반하고, 좋아하는 편집기들에서 우리가 사랑하는 모든것에 기반한 21세기 해킹가능한 텍스트 편집기 입니다. 우리는 사용자 정의가능 하도록 설계 했습니다, 그러나 여전히 기본 설정을 사용하여 접근 가능 합니다. 


![Atom](https://user-images.githubusercontent.com/378023/49132477-f4b77680-f31f-11e8-8357-ac6491761c6c.png)

![Atom Screenshot](https://user-images.githubusercontent.com/378023/49132478-f4b77680-f31f-11e8-9e10-e8454d8d9b7e.png)

좀 더 배우기 위해서 [atom.io](https://atom.io) 또는  [Atom 게시판에](https://github.com/atom/atom/discussions)에 방문하십시오.

중요한 공지를 요해서 트위터의 [@AtomEditor](https://twitter.com/atomeditor)를 팔로우 하십시오.


이 프로젝트는 기여자 서약[행동 강령](CODE_OF_CONDUCT.md)을 준수합니다.

참여시에 귀하는 규칙을 지킬것으로 생각 됩니다. 지켜 지지 않는 경우 atom@github.com 으로 연락 주십시오.

## 문서화

당신이 Atom 사용하는 것이나, 아톱에서 개발 패키지를 개발 하는 것에 관한 것을 일고 싶다면, [Atom 비행 매뉴얼](https://flight-manual.atom.io)은 무료이고, 온라인상에서 가능하다. 당신은 [atom/flight-manual.atom.io](https://github.com/atom/flight-manual.atom.io)에서 매뉴얼을 위한 소스를 찾을 수 있다. 

개발 패키지를 위한 [API 참조](https://atom.io/docs/api)는 역시 Atom.io에 문서화 했다.

## 설치

### 필요한 것들
- [Git](https://git-scm.com)

### 맥OS

최신버전을 다운로드 하십시오. [Atom 배포](https://github.com/atom/atom/releases/latest).

Atom will automatically update when a new release is available.

아톰은 새 배포가 가능 할때 자동으로 업데이트 될 것입니다. 

### 윈도우즈

최신버전을 다운로드 하십시오. [Atom 설치관리자](https://github.com/atom/atom/releases/latest). `AtomSetup.exe`는 32비트용 입니다. 64비트 시스템은 `AtomSetup-x64.exe`을 다운로드 하십시오.

아톰은 새 배포가 가능 할때 자동으로 업데이트 될 것입니다. 

당신은 [배포 페이지](https://github.com/atom/atom/releases/latest)에서  `atom-windows.zip` (32-bit) 또는 `atom-x64-windows.zip` (64-bit)도 다운로드 할 수 있습니다.
`.zip` 버전은 자동 업데이트를 제공하지 않는다. 

[Chocolatey](https://chocolatey.org)를 이용하십니까? Atom의 최신 버전을 설치하기 위해서 `cinst Atom`를 실행 하십시오.

### 리눅스

Atom 은 리눅스 시스템에서 64비트만 가능 합니다. 

Configure your distribution's package manager to install and update Atom by following the [Linux installation instructions](https://flight-manual.atom.io/getting-started/sections/installing-atom/#platform-linux) in the Flight Manual.  You will also find instructions on how to install Atom's official Linux packages without using a package repository, though you will not get automatic updates after installing Atom this way.

#### 아카이브 추출 / Archive extraction

An archive is available for people who don't want to install `atom` as root.

This version enables you to install multiple Atom versions in parallel. It has been built on Ubuntu 64-bit,
but should be compatible with other Linux distributions.

1. Install dependencies (on Ubuntu):
```sh
sudo apt install git libasound2 libcurl4 libgbm1 libgcrypt20 libgtk-3-0 libnotify4 libnss3 libglib2.0-bin xdg-utils libx11-xcb1 libxcb-dri3-0 libxss1 libxtst6 libxkbfile1
```
2. Download `atom-amd64.tar.gz` from the [Atom releases page](https://github.com/atom/atom/releases/latest).
3. Run `tar xf atom-amd64.tar.gz` in the directory where you want to extract the Atom folder.
4. Launch Atom using the installed `atom` command from the newly extracted directory.

리눅스 버전은 자동 업데이트를 지원하지 않기 때문에 새 버전에서도 동일 작업을 반복 해야 합니다. 

## 컴파일(배포파일 만들기)

* [리눅스](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-linux)
* [맥OS](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-mac)
* [윈도우즈](https://flight-manual.atom.io/hacking-atom/sections/hacking-on-atom-core/#platform-windows)

## 토론

* [GitHub 토론](https://github.com/atom/atom/discussions)에서 에톰을 이야기 하십시오.

## 라이센스

[MIT](https://github.com/atom/atom/blob/master/LICENSE.md)

아톰 또는 Github 로고들을 사용할때는 [GitHub 로고 가이드](https://github.com/logos)를 따라 주십시오.
