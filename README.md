# Scout_Robot

> A two-wheel scouting robot built with Arduino Uno, NRF24L01, BLDC motors, and ESP32-CAM based remote vision support.

![Scout Robot Front](전면.jpg)

## Overview
Scout_Robot은 아두이노 우노와 NRF24L01 무선 통신을 기반으로 제작한 2륜 정찰 로봇입니다. BLDC 모터 구동과 원격 제어를 중심으로 설계했으며, 전면 카메라에는 ESP32-CAM을 적용해 현장 상황을 확인할 수 있도록 구성했습니다. 하드웨어 제작과 제어 코드 구현을 함께 수행한 캡스톤 프로젝트입니다.

## Project Context
| Item | Details |
| --- | --- |
| Event | 2022 디지텍 캡스톤디자인 경진대회 |
| Period | 2022.07 ~ 2022.10 |
| Result | 제1회 2022 전국 디지텍 캡스톤 디자인 경진대회 은상 |
| Scope | 2륜 정찰 로봇 설계, 제어 로직 구현, 원격 시야 확보 |

## My Role
- 팀장으로서 작품 동작 제어와 시스템 통합을 담당했습니다.
- Arduino 기반 주행 제어 코드와 무선 제어 흐름을 구현했습니다.
- ESP32-CAM 연동과 전원 조건을 포함한 현장 동작 구성을 정리했습니다.

## Tech Stack
`Arduino Uno`, `C/C++`, `NRF24L01`, `BLDC Motor`, `ESP32-CAM`

## Key Contributions
- 아두이노 우노와 NRF24L01을 활용한 원격 제어 구조 구현
- BLDC 모터 기반 2륜 구동부 제어
- ESP32-CAM을 적용한 전면 영상 확인 구성
- 작품 시연을 위한 하드웨어 배치 및 동작 안정화

## Implementation Notes
- `Dron_main.ino`: 본체 제어와 전체 동작 로직
- `Dron_controller.ino`: 무선 조종기 입력 및 제어 신호 처리
- ESP32-CAM은 별도 오픈소스 구성을 활용하며 5V 인가가 필요합니다.

## Images / Demo
| Front | Side |
| --- | --- |
| ![Scout Robot Front](전면.jpg) | ![Scout Robot Side](측면.jpg) |

<details>
<summary>Legacy Notes</summary>

### Team
| Name | Role |
| --- | --- |
| 이성욱 | 작품 동작 제어 |
| 이용진 | 작품 동작 제어 |
| 이경현 | 하드웨어 제작 |

기존 README의 상세 설명과 수상 이력은 위 내용에 통합해 정리했습니다.

</details>
