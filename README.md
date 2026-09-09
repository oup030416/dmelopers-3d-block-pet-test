# DMeloper's 3D Block Pet — Test Releases

This repository contains test distribution fixtures for
[DMeloper's 3D Block Pet](https://github.com/d-meloper/dmelopers-3d-block-pet).
Test builds target Windows 11 24H2 or newer, x64.

The [Releases](https://github.com/oup030416/dmelopers-3d-block-pet-test/releases)
exercise installation, signed updates and recovery. A current stable fixture
contains an NSIS installer, its signature, `stable.json` and its signature.
Empty non-version and prerelease fixtures exercise release selection. Published
tags and assets remain fixed.

Test builds default to this repository and a dedicated test signing key for
later updates. The `updates` branch carries the signed feed; the default branch
contains only this notice. There is no source mirror or badge automation here.
Passing a test does not approve an official release or its security checks.

In an installed app, edit
`%APPDATA%/com.dmeloper.blockpet3d/update-source.json` to
`{"repository":"oup030416/dmelopers-3d-block-pet-test"}` for test updates, or
use `d-meloper/dmelopers-3d-block-pet` for official updates. The exact GitHub
repository URL is also accepted. The next update check reads the change; a
rebuild is unnecessary. Only these two repositories and their built-in signing
keys are accepted. Invalid settings block updating.

Use an isolated test installation. Test builds retain the product's normal
settings, presets and skins, so they can interact with an existing installation
under the same Windows account. Follow the official repository for ordinary
product releases.

This project is unofficial and is not approved by or associated with Mojang or
Microsoft.

---

# DMeloper's 3D Block Pet — 테스트 릴리즈

이 저장소는
[DMeloper's 3D Block Pet](https://github.com/d-meloper/dmelopers-3d-block-pet)의
테스트 배포 fixture를 보관합니다. 테스트 빌드는 Windows 11 24H2 이상 x64를
대상으로 합니다.

[릴리즈](https://github.com/oup030416/dmelopers-3d-block-pet-test/releases)를 통해
설치, 서명된 업데이트와 복구를 검증합니다. 현재 stable fixture에는 NSIS 설치
파일, 설치 파일 서명, `stable.json`과 피드 서명이 포함됩니다. 버전 형식이 아닌
빈 릴리즈와 prerelease는 선택 로직 검증에 사용합니다. 게시한 태그와 첨부파일은
고정하여 보존합니다.

테스트 빌드는 후속 업데이트의 기본값으로 이 저장소와 테스트 전용 서명 키를
사용합니다.
`updates` 브랜치는 서명된 피드를 제공하고 기본 브랜치에는 이 안내만 둡니다.
소스 미러와 배지 자동화는 운영하지 않습니다. 테스트 통과가 공식 출시나 보안
검사 통과를 의미하지 않습니다.

설치한 앱에서 `%APPDATA%/com.dmeloper.blockpet3d/update-source.json`을
`{"repository":"oup030416/dmelopers-3d-block-pet-test"}`로 편집하면 테스트
업데이트를 선택합니다. 공식 업데이트는 `d-meloper/dmelopers-3d-block-pet`을
사용하십시오. 해당 GitHub 저장소의 정확한 URL도 허용합니다. 다음 업데이트
확인부터 반영되며 앱을 다시 빌드할 필요가 없습니다. 이 두 저장소와 내장된
각 서명 키만 허용하며, 잘못된 설정은 업데이트를 차단합니다.

격리된 테스트 설치 환경을 사용하십시오. 테스트 빌드는 제품의 기존 설정,
프리셋과 스킨을 유지하므로 같은 Windows 계정의 기존 설치에 영향을 줄 수
있습니다. 일반 제품 릴리즈는 공식 저장소를 이용하십시오.

이 프로젝트는 비공식이며 Mojang 또는 Microsoft의 승인이나 제휴를 받지
않았습니다.
