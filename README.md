
# LGD-Production-Quality-Report

<img width="985" height="795" alt="깃허브 사진" src="https://github.com/user-attachments/assets/70338e62-345e-49e4-8aae-b1ae528e6413" />

# LG Display 생산·품질 업무 보고서

**날짜:** 09월 14일

## 사용 라이브러리

* Python
* Flask
* HTML / CSS / JavaScript
* Three.js
* OrbitControls
* Cloudflared
* JSON

## 설명

LG Display 생산 현장을 가정하여 제작한 **교육용 생산·품질 업무 보고서 웹 서비스**입니다.

생산라인과 조회 기간을 선택하여 LOT별 생산 및 품질 데이터를 확인하고, 생산 목표 대비 달성률과 검사 수량, 불량 수량, 불량률을 확인할 수 있도록 구현했습니다.

또한 Three.js를 활용하여 패널 검사·이송 설비를 3D로 구현하였으며, 설비의 정상 및 온도 주의 상태를 시각적으로 확인할 수 있습니다.

조회한 생산·품질 데이터와 설비 사건을 기반으로 업무 보고서 초안을 생성하고, 사용자가 내용을 검토·수정한 뒤 저장할 수 있도록 구성했습니다. 저장된 보고서는 TXT 형식으로, 보고서의 근거 데이터는 JSON 형식으로 다운로드할 수 있습니다.

Google Colab 환경에서 Flask 서버를 실행하고 Cloudflared를 이용하여 외부에서 웹 서비스에 접속할 수 있도록 구현했습니다.

## 주요 기능

* 기간 및 생산라인별 생산·품질 데이터 조회
* LOT별 목표수량 / 생산수량 / 검사수량 / 불량수량 확인
* 생산 목표 달성률 및 불량률 자동 계산
* 일자별 불량률 시각화
* 설비 사건 이력 조회
* Three.js 기반 패널 검사·이송 설비 3D 시각화
* 생산·품질 업무 보고서 초안 생성
* 보고서 수정 및 검토 상태 저장
* 보고서 TXT 다운로드
* 보고서 근거 데이터 JSON 다운로드
* Cloudflared를 활용한 외부 접속

## 참고 문헌

* Three.js Documentation
* Flask Documentation
* Cloudflare Tunnel Documentation
* MDN Web Docs
* LG Display K-뉴딜 아카데미 교육자료

※ 본 프로젝트에서 사용된 생산·품질 데이터와 설비 정보는 실습을 위한 **교육용 가상 데이터**입니다.
