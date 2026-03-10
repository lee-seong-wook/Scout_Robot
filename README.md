# Scout_Robot

> A two-wheel scouting robot built with Arduino Uno, NRF24L01, BLDC motors, and ESP32-CAM based remote vision support.

![Scout Robot Cover](https://github.com/lee-seong-wook/Scout-robot/assets/130055880/b68b02d7-d178-4002-bdfd-8e31bb057739)

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

## Project Gallery
### Prototype Views
| Cover | Overall |
| --- | --- |
| ![Scout Robot Front](전면.jpg) | ![Scout Robot Overall](https://github.com/lee-seong-wook/RCDRON/assets/130055880/8121e0d7-88e0-4139-a412-5459c465ba40) |
| ![Scout Robot Side](측면.jpg) | ![Scout Robot Side View](https://github.com/lee-seong-wook/Scout-robot/assets/130055880/b68b02d7-d178-4002-bdfd-8e31bb057739) |

### System Diagram
![Scout Robot Diagram](https://github.com/lee-seong-wook/RCDRON/assets/130055880/3310ffb0-054b-402b-a69f-f347e549025f)

### Project Explanation
| Explanation 1 | Explanation 2 | Explanation 3 |
| --- | --- | --- |
| ![Scout Robot Detail 1](https://github.com/lee-seong-wook/RCDRON/assets/130055880/3a8c3af4-3ae0-4a03-9f23-3bf9e3c38968) | ![Scout Robot Detail 2](https://github.com/lee-seong-wook/RCDRON/assets/130055880/0967211f-8fb1-43c3-9ff7-0f1b2e8b0695) | ![Scout Robot Detail 3](https://github.com/lee-seong-wook/RCDRON/assets/130055880/a4b32d67-bca0-4186-89fa-79431bae1229) |

<details>
<summary>Team</summary>

| Name | Photo | Role |
| --- | --- | --- |
| 이성욱 | ![이성욱](https://github.com/lee-seong-wook/Scout-robot/assets/130055880/7ae2e5fc-7500-48b0-97be-c1608f7e8ce4) | 작품 동작 제어 |
| 이용진 | ![이용진](https://github.com/lee-seong-wook/Scout-robot/assets/130055880/4c32d976-9147-466d-9799-5c14cd2903be) | 작품 동작 제어 |
| 이경현 | ![이경현](https://github.com/lee-seong-wook/Scout-robot/assets/130055880/e22a55b8-2aeb-4d5c-a9b9-73a9e3b08f25) | 하드웨어 제작 |

</details>
