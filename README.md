# DMeloper's 3D Block Pet — Test Releases

[Download test builds](https://github.com/oup030416/dmelopers-3d-block-pet-test/releases)

Windows 11 24H2 or newer, x64. Current test builds use manual NSIS installation:
EXE plus its dedicated test signature. No automatic installer or rollback runs.
Test builds read this repository's `badges/badge-data.json` using the same
validator and producer as the official app. The highest canonical stable version
is selected; prereleases and non-version tags are excluded. The publisher refreshes badges after each deployment. Automatic scheduled refresh
is not enabled; metadata expires after 24 hours and must then be refreshed. App checks reuse successful
results for six hours and failed attempts for ten minutes.

New test releases are mutable: the maintainer can explicitly replace assets at
the same version. Compare current SHA-256 checksums and signatures when downloading.
Historical immutable releases remain unchanged. `updates` is retired historical
evidence and is not used by current builds. There is no app source mirror here;
main contains this notice and the shared badge producer only.

Test builds share normal product settings, presets and skins. Close an existing
app before manual installation. Passing these tests is not official release or
antivirus approval. The official app continues to default to the
[official repository](https://github.com/d-meloper/dmelopers-3d-block-pet).

---

# 테스트 릴리스

[테스트 빌드 다운로드](https://github.com/oup030416/dmelopers-3d-block-pet-test/releases)

Windows 11 24H2 이상 x64용입니다. 현재 테스트 빌드는 EXE·테스트 전용 서명으로
구성되며 수동 설치합니다. 자동 설치·자동 복구는 수행하지 않습니다.
공식 앱과 같은 배지 생성·검증 코드를 사용해 이 저장소에서 가장 높은 정식 버전을
확인합니다. 배지는 배포 도구로 갱신합니다. 자동 주기 갱신은 구성되지 않았으며, 24시간이
지난 메타데이터는 다시 갱신해야 합니다. 앱은 성공 결과를
6시간 재사용하며 실패 후에는 10분 뒤 재시도합니다.

새 테스트 릴리스는 같은 버전으로 첨부파일을 교체할 수 있습니다. 다운로드 시
현재 SHA-256과 서명을 확인하세요. 과거 immutable 릴리스와 `updates` 브랜치는
기록으로 보존하며 현재 앱은 해당 설치 피드를 사용하지 않습니다. 앱 소스는
공개하지 않고 이 안내·배지 생성 코드만 운영합니다.

테스트 빌드는 기존 앱의 설정·프리셋·스킨을 공유합니다. 기존 앱을 종료하고 직접
설치하세요. 테스트 배포는 공식 출시 또는 백신 검사 통과를 의미하지 않습니다.
이 프로젝트는 비공식이며 Mojang 또는 Microsoft의 승인·제휴를 받지 않았습니다.
