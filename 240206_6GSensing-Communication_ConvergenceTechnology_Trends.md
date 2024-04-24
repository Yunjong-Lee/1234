---
date: 2024-02-06 09:20:30
layout: post
---

# [6G 센싱-통신 융합 서비스의 기술 개발 동향](https://ettrends.etri.re.kr/ettrends/206/0905206003/)

## 센싱-통신 융합기술
- 단일 시스템으로 두가지 기능 동시 동작
  + 무선 통신 기지국이나 Access Point와 같은 통신 기반 시설을 활용하여 통신용 전파를 센싱의 용도로 사용(사물을 비롯한 주변 환경과 사람 센싱 및 정보 추출/가공)  
  + 센싱과 통신의 융합으로 주파수 스펙트럼과 에너지의 효율성 증가 가능(동일 전파 사용, 통신용 HW & SW 공유 등)

  + 센싱-통신 융합 서비스의 Key Performance Index  
  |분류 | 서비스 | 최대 거리 | 최대 속도 | 거리해상도 | 도플러 해상도 |
  |-|-|-|-|-|-|
  | 사물 | 주행 차량 감지 | 250~300 | 70 | 7~30 | 0.1~0.8 |
  | 사물 | 주차 차량 감지 | ~5 | 0 | 0.5 | - |
  | 사물 | 드론 모니터링  | ~500 | ~40 | 1.0 | ~5.0 |
  | 주변 환경 | 날씨 예측 | ~500 | - | ~5.0 | - |
  | 주변 환경 | 대기오염 모니터링 | ~500 | - | ~5.0 | - |
  | 주변 환경 | 공장환경 모니터링 | ~200 | 9 | ~0.01 | 0.5 |
  | 주변 환경 | 교통량 모니터링 | ~200 | 70 | 0.5~1.0 | 0.5 |
  | 사람 | 보행자 감지 | ~5 | 3 | ~0.01 | - |
  | 사람 | 동작 감지 | 0.01~1 | 10 | ~0.01 | ~0.3 |
  | 사람 | 사람 유무 감지 | ~20 | ~2 | ~0.01 | ~0.1 |
  | 사람 | 낙상 모니터링 | ~10 | ~3 | ~0.01 | ~0.3 |

## IEEE 802.11bf, SENS(WLANSensing)
- 무선랜 센싱을 통한 실내(방 안) 사람/동물의 유무, 어떤 자세를
취하고 있는지 알 수 있고, 사람의 생체 신호 추출 or 사물의 이동 경로 추적
- SENS 기능 요구사항
| 항목 | 내용 |
|-|-|
|센싱 기능 | 장치 기능 정의 |
|| - 1) SENS 기능 알림 |
|| - 2) SENS 측정을 위한 전송 요청 및 셋업 |
|| - 3) 특정 전송이 SENS를 위한 것임을 표시 |
|| - 4) SENS 피드백 및 정보 교환 |
|| 요청 및 비요청 전송에 기반한 SENS 동작 정의 |
|| SENS 측정을 요청하고 관련 정보 수집을 위한 MAC 서비스 인터페이스 정의 |
| 동작대역|1GHz~7.125GHz와 45GHz 이상의 면허 불필요 대역(License-exempt spectrum)|
| PHY | 1) SENS 동작을 위한 DMG(Directional Multi Gigabit)과 EDMG(Enhanced DMG)에 대한 규격 수정 |
|  | 2) HT(High Throughput), VHT(Very High Throughput), HE(High  Efficiency), EHT(Extremely High Throughput) 내용 수정 |
| MAC | SENS 동작을 위한 MAC 기능 수정 |

- 표준화 주요 이슈
