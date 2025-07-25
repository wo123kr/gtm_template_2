# Thinking Engine GTM Template

This repository contains the Google Tag Manager Custom Template for the Thinking Engine SDK.

## Template: Thinking Engine - 커스텀 이벤트 및 유저 속성 (Custom Events and User Properties)

이 태그 템플릿은 이전에 설정한 "Thinking Engine - 초기화" 태그에 의해 로드된 SDK를 사용하여, 다양한 종류의 데이터를 Thinking Engine 서버로 전송하는 역할을 합니다.

This template corresponds to the `template.tpl` file.

### Features
- 다양한 이벤트 타입 지원:
    - Track (일반 이벤트)
    - Track First (최초 이벤트)
    - Track Update (이벤트 수정)
    - Track Overwrite (이벤트 덮어쓰기)
- 유저 속성 관리 기능:
    - User Set (유저 속성 설정)
    - User Set Once (유저 속성 최초 설정)
    - User Add (유저 속성 증감)
    - User Unset (유저 속성 제거)
    - User Append (유저 속성 배열 추가)
    - User Delete (유저 삭제)
- 로그인/로그아웃 이벤트 처리:
    - Login (로그인)
    - Logout (로그아웃)
- 공통 속성 (Super Properties) 관리:
    - Set Super Properties (공통 속성 설정)
    - Clear Super Properties (공통 속성 초기화)
- 이벤트 타이머 시작 (Time Event)
- SDK 디버그 로그 활성화/비활성화 옵션
- 여러 SDK 인스턴스 지원

## How to use in GTM

1.  In Google Tag Manager, navigate to the "Templates" section of your container.
2.  Click the "New" button in the "Tag Templates" box.
3.  Click the three-dots menu in the top-right corner and select "Import".
4.  Select the `template.tpl` file from this repository.
5.  Save the template. You can now use it as a new tag.

## License

This project is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for details.
