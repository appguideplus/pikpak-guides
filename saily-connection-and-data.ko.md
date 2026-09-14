# Saily 인터넷이 안 될 때: 회선·로밍·데이터 추가

Saily eSIM을 설치하고 목적지에 도착했는데 연결이 안 되는 상황을 다룹니다. 플랜의 국가와 유효기간을 먼저 보고, 실제 모바일 데이터에 Saily 회선이 선택됐는지 살펴보세요.

[Saily](saily.ko.md) · [전체 가이드](README.md) · [웹에서 보기](https://appguideplus.com/ko/saily/connection-and-data/)

## iPhone에서 회선과 로밍 확인

1. 설정 → 셀룰러(또는 모바일 서비스) → Saily eSIM에서 이 회선 켜기를 활성화합니다.
2. Saily eSIM의 데이터 로밍을 켭니다. 기존 통신사 회선의 로밍과 혼동하지 않도록 회선 이름을 봅니다.
3. 셀룰러 → 셀룰러 데이터에서 Saily를 선택합니다.
4. Wi-Fi를 잠시 끄고 웹페이지를 열어 이동통신 연결을 확인합니다.

출처: [Saily iPhone 연결 문제](https://support.saily.com/hc/en-us/articles/13357933521436-How-to-fix-iOS-network-connection-issues)

## Android에서 데이터 회선 선택

제조사마다 이름이 조금 다릅니다. 아래는 공식 안내에 제시된 Connections 메뉴 기준입니다.

1. 설정 → 연결(Connections) → SIM 관리자(SIM manager)에서 Saily eSIM을 켭니다.
2. 모바일 데이터(Mobile data)에서 Saily eSIM을 선택합니다.
3. 연결 → 모바일 네트워크(Mobile networks)에서 데이터 로밍을 켭니다. 모바일 데이터 회선이 Saily인지 다시 봅니다.
4. APN이 보이지 않으면 Saily 앱을 최대 5분 정도 열어 두어 자동 구성을 기다립니다.
5. Wi-Fi를 끈 상태에서 다시 연결을 시도합니다.

출처: [Saily Android 연결 문제](https://support.saily.com/hc/en-us/articles/13338388172828-How-to-fix-Android-no-net-issue) · [APN 자동 구성과 활성화 확인](https://support.saily.com/hc/en-us/articles/12823108536476-How-to-check-if-my-Saily-eSIM-is-activated)

## APN을 직접 넣어야 하는 경우

APN은 이동통신 데이터 접속 주소입니다. 회선과 플랜이 맞는데 연결이 안 될 때 아래 공식 기기별 안내와 대조해서 설정합니다.

| 기기 | 입력 위치와 값 |
| --- | --- |
| iPhone | Saily eSIM → Mobile Data Network에서 Mobile Data와 LTE Setup의 APN에 wbdata. 다른 필드는 빈칸. |
| Android | 연결 → 모바일 네트워크 → 액세스 포인트 이름 → Saily eSIM → 추가. 이름과 APN에 wbdata 입력 후 저장하고 새 APN 선택. |

출처: [Saily iPhone 연결 문제](https://support.saily.com/hc/en-us/articles/13357933521436-How-to-fix-iOS-network-connection-issues) · [Saily Android 연결 문제](https://support.saily.com/hc/en-us/articles/13338388172828-How-to-fix-Android-no-net-issue)

## 데이터를 다 썼다면 add data

1. Saily 앱에서 사용 중인 eSIM을 선택합니다.
2. add data → 여행 국가 또는 지역 → 필요한 용량을 선택합니다.
3. continue를 눌러 기간과 금액을 읽은 뒤 구매를 진행합니다.
4. 앱에서 새 플랜을 확인하고 Saily 회선을 켠 상태로 유지합니다.

출처: [같은 eSIM에 데이터 추가](https://support.saily.com/hc/en-us/articles/12823150321052-What-happens-when-I-run-out-of-data-on-my-eSIM)

## 추가 구매 전에 한 번 더 확인

유효기간이 끝나면 잔여 데이터도 만료됩니다. 새 플랜을 추가하는 add data와 별도 eSIM을 만드는 Add new eSIM은 다릅니다.

회선·로밍·APN까지 맞으면 오류 화면과 여행 국가, 기기 모델을 정리해 Saily 지원에 전달하세요. 전체 네트워크 초기화는 저장한 네트워크 설정에도 영향을 주므로 첫 단계로 권하지 않습니다.

출처: [Saily Android 연결 문제](https://support.saily.com/hc/en-us/articles/13338388172828-How-to-fix-Android-no-net-issue) · [같은 eSIM에 데이터 추가](https://support.saily.com/hc/en-us/articles/12823150321052-What-happens-when-I-run-out-of-data-on-my-eSIM) · [데이터 플랜 관리](https://support.saily.com/hc/en-us/articles/21484628749084-Saily-data-plan-management) · [별도 eSIM 추가](https://support.saily.com/hc/en-us/articles/20269649356828-How-do-I-get-an-additional-Saily-eSIM)

## 함께 볼 안내

- [Saily eSIM 사용법: 구매 전 기기 확인부터 설치까지](saily.ko.md)
- [Saily eSIM 설치와 출국 전 확인](saily-installation.ko.md)

## 출처와 확인일

- [Saily iPhone 연결 문제](https://support.saily.com/hc/en-us/articles/13357933521436-How-to-fix-iOS-network-connection-issues)
- [Saily Android 연결 문제](https://support.saily.com/hc/en-us/articles/13338388172828-How-to-fix-Android-no-net-issue)
- [APN 자동 구성과 활성화 확인](https://support.saily.com/hc/en-us/articles/12823108536476-How-to-check-if-my-Saily-eSIM-is-activated)
- [같은 eSIM에 데이터 추가](https://support.saily.com/hc/en-us/articles/12823150321052-What-happens-when-I-run-out-of-data-on-my-eSIM)
- [데이터 플랜 관리](https://support.saily.com/hc/en-us/articles/21484628749084-Saily-data-plan-management)
- [별도 eSIM 추가](https://support.saily.com/hc/en-us/articles/20269649356828-How-do-I-get-an-additional-Saily-eSIM)

내용 확인일: 2026-09-14. GitHub판 편집일: 2026-09-14.

AppGuide+가 작성한 독립적인 이용 안내이며, 각 서비스의 공식 고객지원 문서는 아닙니다.
