# 미국공시 수집기

SEC EDGAR 의 공시·재무 자료를 조회해 엑셀로 받습니다.

회계사가 만들어 무료로 공개하는 회계·공시 실무 도구입니다. 회원가입과 결제가 없습니다. 이미 공시된 자료를 읽어 엑셀로 옮기는 쪽이며, 공시를 작성해 제출하는 도구가 아닙니다.

| | |
|---|---|
| 넣는 것 | 회사·서식·기간 조회 조건 |
| 나오는 것 | 엑셀 워크북(.xlsx) |
| 쓰는 곳 | 윈도우, 설치 과정 없음 |
| 값 | 무료 |

## 받기

- **내려받기** — <https://github.com/kongsist/kongsist-sec-collector/releases/latest>
- 판마다 무엇이 달라졌는지 — <https://kongsist.com/run/sec-collector>

## 쓰는 법

절차는 화면과 함께 사이트에 정리해 두었습니다.

- [SEC EDGAR 자료를 엑셀로 받는 방법 — 미국공시 수집기](https://kongsist.com/docs/sec-collector)
- [SEC EDGAR 재무데이터 엑셀 조회 — 미국공시 수집기 기능설명](https://kongsist.com/features/sec-collector)

## 자료 취급

인증키와 조회 조건은 자료를 받아 오기 위해 미국 SEC EDGAR(`www.sec.gov`) 로 전송됩니다. 받아 온 결과는 이용자의 컴퓨터에서만 처리되며, 만든 이에게는 인증키도 조회 내용도 가지 않습니다. 그 밖에 프로그램이 보내는 것은 켤 때 한 번 새 판이 나왔는지 묻는 `kongsist.com/version.json` 요청뿐입니다.

## 이 저장소에 있는 것

배포 파일(릴리스)만 둡니다. 서명하지 않은 실행 파일을 사이트가 직접 내주면 일부 사내망 보안 장비가 도메인 전체를 막아 버려서, 배포는 GitHub 릴리스로 옮겼습니다.

---

만든 곳 · 다른 도구 — <https://kongsist.com>  
문의 — <https://kongsist.com/contact>
