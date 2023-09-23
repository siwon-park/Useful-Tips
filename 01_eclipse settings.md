# 01_eclipse settings

이클립스 관련 세팅 정리

아마 버전마다 메뉴 탭이 다를 것이지만, 그래도 큰 흐름상 설정하는 방법은 같음

<br>

## 1. 플러그인 설치

이클립스에서 플러그인 설치하는 방법

`[help] - [Eclipse Marketplace]`에서 필요한 플러그인을 설치하면 된다.

만약 본인이 원하는 커스텀 컬러 테마를 설치하고 싶다면, 사전에

- Eclipse Color Theme
- Darkest Dark Theme with DevStyle

을 설치하면 된다.

<br>

## 2. 폰트 및 컬러 테마 변경

이클립스에서 폰트 및 컬러 테마 변경하기

`[Window] - [Preferences] - [General] - [Appearance]`

### 1) 폰트

`[Colors and Fonts]`의 `Basic` 부분의 `Text Font`를 Edit하여 원하는 스타일 및 크기의 폰트를 설정할 수 있다.

- 나의 세팅: Consolas 16

### 2) 컬러 테마

- DevStyle 플러그인을 설치했을 경우엔 DevStyle 탭에서 원하는 컬러 테마를 선택한 후 변경 Apply
- 그렇지 않을 경우에도 Appearance 안에 있는 메뉴에서 Color Themes에서 원하는 테마를 선택한 후 변경 가능

### 3) 설정 적용

분명히 설정을 바꿨음에도 불구하고 Eclipse를 재시작하면 설정이 초기화되어 있는 것을 볼 수 있는데, 이럴 때는 `[Window] - [Preferences] - [Oomph] - [Setup Tasks]`에 있는 `Preference Recorder`를 선택하여 모든 설정을 전부 다 체크하고 적용 후 저장하면 된다.

<br>

