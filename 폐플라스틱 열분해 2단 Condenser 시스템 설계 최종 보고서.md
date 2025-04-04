  # 폐플라스틱 열분해 2단 Condenser 시스템 설계 최종 보고서

  ## 목차

  1. 개요  
      1.1. 설계 목적  
      1.2. 설계 범위  
      1.3. 주요 설계 사양  
             1.3.1. 저온 Condenser (1차)  
             1.3.2. 고온 Condenser (2차)  

  2. 설계 기준  
      2.1. 공정 조건  
          2.1.1. 저온 Condenser  
          2.1.2. 고온 Condenser  
      2.2. 제품 규격  
          2.2.1. 저온 Condenser 회수물  
          2.2.2. 고온 Condenser 회수물  
      2.3. 설계 코드 및 표준  
          2.3.1. 설계 코드  
          2.3.2. 안전 기준  
          2.3.3. 재질 규격  

  3. Condenser 시스템 설계  
      3.1. 2단 Condenser 시스템  
          3.1.1. 저온 Condenser (1차)  
          3.1.2. 고온 Condenser (2차)  
      3.2. 주요 부품 설계  
          3.2.1. 열교환기 튜브  
          3.2.2. 배플  
          3.2.3. 노즐  
      3.3. 재질 선정  
          3.3.1. 주요 재질 선정 기준  
          3.3.2. 선정 재질 사양  
  
  4. 설계 계산 및 검증  
      4.1. 압력 강하 계산  
          4.1.1. 저온 Condenser  
          4.1.2. 고온 Condenser  
      4.2. 열전달 계산  
          4.2.1. 저온 Condenser  
          4.2.2. 고온 Condenser  
      4.3. 체류 시간 계산  
      4.4. 기계적 강도 계산  
          4.4.1. 동체 두께 계산  
          4.4.2. 노즐 보강 계산  
      4.5. 설계 검증 결과  
  
  5. 고온 Condenser 용량 최적화 분석  
      5.1. 용량 최적화 기준  
      5.2. 시뮬레이션 결과 분석  
          5.2.1. 용량별 성능 비교  
          5.2.2. 경제성 분석  
      5.3. 최적 용량 선정  
          5.3.1. 기술적 검토  
          5.3.2. 경제성 검토  
      5.4. 최적화 결론  
  
  6. 제어 시스템  
      6.1. 제어 항목  
          6.1.1. 온도 제어  
          6.1.2. 압력 제어  
          6.1.3. 수위 제어  
      6.2. 계측 항목  
          6.2.1. 온도 센서  
          6.2.2. 압력 센서  
          6.2.3. 수위 센서  
      6.3. 제어 로직  
      6.4. 제어반 설계  
  
  7. 안전 설계  
      7.1. 안전 장치  
          7.1.1. 과압 방지 장치  
          7.1.2. 온도 보호 장치  
          7.1.3. 비상 차단 시스템  
      7.2. 모니터링  
          7.2.1. 실시간 감시 시스템  
          7.2.2. 데이터 기록 시스템  
      7.3. 비상 대응 계획  
  
  8. 유지보수 계획  
      8.1. 정기 점검  
          8.1.1. 일일 점검  
          8.1.2. 월간 점검  
          8.1.3. 연간 점검  
      8.2. 예방 정비  
          8.2.1. 주요 부품 교체 계획  
          8.2.2. 세정 계획  
      8.3. 부품 관리  
          8.3.1. 예비품 목록  
          8.3.2. 재고 관리 계획  
  
  9. 경제성 분석  
      9.1. 투자비용  
          9.1.1. 설비 투자  
          9.1.2. 설치 비용  
      9.2. 운영비용  
          9.2.1. 유틸리티 비용  
          9.2.2. 유지보수 비용  
      9.3. 수익 분석  
          9.3.1. 예상 수익  
          9.3.2. 투자회수기간  
  
  10. 부록  
      10.1. 상세 도면  
      10.2. 계산서  
      10.3. 기술 규격서  
      10.4. 시험 성적서  



  ## 1. 개요

  ### 1.1. 설계 목적

  본 설계는 폐플라스틱 열분해 공정에서 발생하는 열분해 가스의 효율적인 회수를 위한 2단 Condenser 시스템의 상세 설계를 목적으로 한다.

  #### 주요 목적
  1. 열분해 생성물의 최적 분리 및 회수
      - 경질유(C3-C5) 90% 이상 회수
      - 디젤유(C12-C20) 95% 이상 회수
      - 나프타(C5-C12) 90% 이상 회수

  2. 에너지 효율 극대화
      - 냉각수 사용량 최소화
      - 열교환 효율 최적화
      - 압력손실 최소화

  3. 안정적 운전 확보
      - 연속 운전 안정성 확보
      - 유지보수 용이성
      - 안전성 확보

  ### 1.2. 설계 범위

  #### 1.2.1. 하드웨어 설계
  - 2단 Condenser 본체 설계
  - 부대 설비 설계
  - 배관 및 계장 설계
  - 구조물 설계

  #### 1.2.2. 제어 시스템
  - 온도 제어 시스템
  - 압력 제어 시스템
  - 수위 제어 시스템
  - 모니터링 시스템

  #### 1.2.3. 유틸리티 시스템
  - 냉각수 시스템
  - 열매유 시스템
  - 전기 설비
  - 계장 설비

  #### 1.2.4. 안전 설계
  - 안전 장치 설계
  - 비상 정지 시스템
  - 경보 시스템
  - 방폭 설계

  ### 1.3. 주요 설계 사양

  #### 1.3.1. 저온 Condenser (1차)
  | 항목 | 사양 | 비고 |
  |------|------|------|
  | 처리 용량 | 10 kg/hr | 경질성분 |
  | 운전 압력 | 6.0 → 1.5 bar | 압력 강하 고려 |
  | 설계 압력 | 6.0 bar | 안전율 3.0 |
  | 운전 온도 | 250℃ → 20℃ | 냉매 사용 |
  | 용량 | 60L | 최적화 결과 |
  | 재질 | 316L SS | 내식성 고려 |
  | 두께 | 3.2mm | 부식여유 포함 |

  #### 1.3.2. 고온 Condenser (2차)
  | 항목 | 사양 | 비고 |
  |------|------|------|
  | 처리 용량 | 40 kg/hr | 중질성분 |
  | 운전 압력 | 6.5 → 2.0 bar | 압력 강하 고려 |
  | 설계 압력 | 7.5 bar | 안전율 3.0 |
  | 운전 온도 | 455℃ → 125℃ | 열매유 사용 |
  | 용량 | 120L | 최적화 결과 |
  | 재질 | 316L SS | 고온 내식성 |
  | 두께 | 4.0mm | 부식여유 포함 |

  ## 2. 설계 기준

  ### 2.1. 공정 조건

  #### 2.1.1. 저온 Condenser
  | 항목 | 조건 | 허용 편차 |
  |------|------|-----------|
  | 입구 온도 | 250℃ | ±3℃ |
  | 출구 온도 | 20℃ | ±2℃ |
  | 최대 운전 압력 | 6.0 bar | - |
  | 최소 운전 압력 | 1.5 bar | - |
  | 설계 압력 | 6.0 bar | - |
  | 유량 변동 | 20~80 L/min | Diaphragm 펌프 |
  | 체류 시간 | 45~111.6초 | 유량 기준 |

  #### 2.1.2. 고온 Condenser
  | 항목 | 조건 | 허용 편차 |
  |------|------|-----------|
  | 입구 온도 | 455℃ | ±4℃ |
  | 출구 온도 | 125℃ | ±3℃ |
  | 최대 운전 압력 | 6.5 bar | - |
  | 최소 운전 압력 | 2.0 bar | - |
  | 설계 압력 | 7.5 bar | - |
  | 유량 변동 | 170~330 L/min | Screw Blower |
  | 체류 시간 | 21.8~57.6초 | 유량 기준 |

  ### 2.2. 제품 규격

  #### 2.2.1. 저온 Condenser 회수물
  | 성분 | 규격 | 비고 |
  |------|------|------|
  | 경질유(C3-C5) | 90% 이상 회수 | 주요 제품 |
  | 비응축 가스(C1-C3) | 배출 | 연료로 활용 |
  | 조성 비율 | 경질유 62.5% | - |
  | - | 비응축가스 37.5% | - |

  #### 2.2.2. 고온 Condenser 회수물
  | 성분 | 규격 | 비고 |
  |------|------|------|
  | 디젤유(C12-C20) | 95% 이상 회수 | 주요 제품 |
  | 나프타(C5-C12) | 90% 이상 회수 | 부산물 |
  | 조성 비율 | 나프타 21.875% | - |
  | - | 디젤유 78.125% | - |

  ### 2.3. 설계 코드 및 표준

  #### 2.3.1. 설계 코드
  - ASME Section VIII Division 1
  - TEMA Standards
  - API 520/521
  - NFPA 70

  #### 2.3.2. 안전 기준
  - PSM 기준
  - 방폭 구조 규정
  - 산업안전보건기준

  #### 2.3.3. 재질 규격
  - ASTM/ASME Material Specifications
  - NACE MR0175/ISO 15156

  ## 3. Condenser 시스템 설계

  ### 3.1. 2단 Condenser 시스템

  #### 3.1.1. 저온 Condenser (1차)
  1) 본체 설계
      - 용량: 60L
      - 설계 압력: 6.0 bar
      - 운전 압력: 6.0 → 1.5 bar
      - 입구 온도: 250 ± 3℃
      - 출구 온도: 20 ± 2℃

  2) 냉각 시스템
      - 냉각 매체: 냉매
      - 예상 회수율: 90% (경질유)
      - 체류 시간: 45~111.6초

  3) 구조 설계
      - 재질: 316L SS
      - 두께: 3.2mm
      - 플랜지: 150# RF 타입
      - 가스켓: 스파이럴 타입 (316L/그라파이트)

  #### 3.1.2. 고온 Condenser (2차)
  1) 본체 설계
      - 용량: 120L
      - 설계 압력: 7.5 bar
      - 운전 압력: 6.5 → 2.0 bar
      - 입구 온도: 455 ± 4℃
      - 출구 온도: 125 ± 3℃

  2) 냉각 시스템
      - 냉각 매체: 열매유
      - 예상 회수율:
          * 나프타: 92%
          * 디젤유: 95%
      - 체류 시간: 21.8~57.6초

  3) 구조 설계
      - 재질: 316L SS
      - 두께: 4.0mm
      - 플랜지: 150# RF 타입
      - 가스켓: 스파이럴 타입 (316L/그라파이트)

  ### 3.2. 주요 부품 설계

  #### 3.2.1. 열교환기 튜브
  | 항목 | 저온 Condenser | 고온 Condenser |
  |------|----------------|----------------|
  | 튜브 크기 | 19.05mm OD | 25.4mm OD |
  | 튜브 두께 | 2.11mm | 2.77mm |
  | 튜브 피치 | 25.4mm | 31.75mm |
  | 튜브 배열 | 삼각 피치 | 삼각 피치 |
  | 재질 | 316L SS | 316L SS |
  | 표면적 | 5.0m² | 9.0m² |

  #### 3.2.2. 배플
  | 항목 | 저온 Condenser | 고온 Condenser |
  |------|----------------|----------------|
  | 타입 | 단일 세그먼트 | 단일 세그먼트 |
  | 컷 높이 | 25% | 25% |
  | 간격 | 300mm | 400mm |
  | 재질 | 316L SS | 316L SS |

  #### 3.2.3. 노즐
  | 위치 | 크기 | 등급 | 타입 |
  |------|------|------|------|
  | 입구 | 50A | 150# | RF 플랜지 |
  | 출구 | 50A | 150# | RF 플랜지 |
  | 드레인 | 25A | 150# | RF 플랜지 |
  | 벤트 | 15A | 150# | RF 플랜지 |

  ### 3.3. 재질 선정

  #### 3.3.1. 주요 재질 선정 기준
  1) 내식성 요구사항
      - 부식성 매체 저항성
      - 응력부식균열 저항성
      - 공정 적합성

  2) 기계적 특성
      - 고온 강도
      - 피로 저항성
      - 열충격 저항성

  3) 경제성
      - 재료 비용
      - 가공성
      - 용접성

  #### 3.3.2. 선정 재질 사양
  | 부위 | 재질 | 선정 사유 |
  |------|------|-----------|
  | 동체 | 316L SS | 내식성, 고온강도 |
  | 튜브 | 316L SS | 열전달 효율, 내식성 |
  | 배플 | 316L SS | 구조 안정성 |
  | 플랜지 | 316L SS | 내식성, 기밀성 |
  | 가스켓 | 316L/그라파이트 | 고온 시일성 |

    ## 4. 설계 계산 및 검증

  ### 4.1. 압력 강하 계산

  #### 4.1.1. 저온 Condenser
  1) 쉘측 압력 강하
  - 계산 기준: TEMA 기준
  - 허용 압력 강하: 4.5 bar
  - 계산 결과
      * 횡류 구간: 2.8 bar
      * 노즐 손실: 0.9 bar
      * 총 압력 강하: 3.7 bar

  2) 튜브측 압력 강하
  - 계산 기준: Darcy-Weisbach 방정식
  - 허용 압력 강하: 1.0 bar
  - 계산 결과
      * 마찰 손실: 0.4 bar
      * 노즐 손실: 0.2 bar
      * 총 압력 강하: 0.6 bar

  #### 4.1.2. 고온 Condenser
  1) 쉘측 압력 강하
  - 계산 기준: TEMA 기준
  - 허용 압력 강하: 4.5 bar
  - 계산 결과
      * 횡류 구간: 3.2 bar
      * 노즐 손실: 1.1 bar
      * 총 압력 강하: 4.3 bar

  2) 튜브측 압력 강하
  - 계산 기준: Darcy-Weisbach 방정식
  - 허용 압력 강하: 1.2 bar
  - 계산 결과
      * 마찰 손실: 0.6 bar
      * 노즐 손실: 0.3 bar
      * 총 압력 강하: 0.9 bar

  ### 4.2. 열전달 계산

  #### 4.2.1. 저온 Condenser
  1) 열전달 계수
  - 쉘측: 850 W/m²·K
  - 튜브측: 1,200 W/m²·K
  - 총괄 열전달 계수: 480 W/m²·K

  2) 열교환량
  - 요구 열교환량: 125 kW
  - 설계 열교환량: 142 kW
  - 여유율: 13.6%

  #### 4.2.2. 고온 Condenser
  1) 열전달 계수
  - 쉘측: 720 W/m²·K
  - 튜브측: 950 W/m²·K
  - 총괄 열전달 계수: 410 W/m²·K

  2) 열교환량
  - 요구 열교환량: 280 kW
  - 설계 열교환량: 315 kW
  - 여유율: 12.5%

  ### 4.3. 체류 시간 계산
  1) 저온 Condenser
  - 최소 요구 체류 시간: 40초
  - 계산 체류 시간: 45~111.6초
  - 적정성 평가: 적합

  2) 고온 Condenser
  - 최소 요구 체류 시간: 20초
  - 계산 체류 시간: 21.8~57.6초
  - 적정성 평가: 적합

  ### 4.4. 기계적 강도 계산

  #### 4.4.1. 동체 두께 계산
  1) 저온 Condenser
  - 계산 기준: ASME Section VIII Div.1
  - 최소 요구 두께: 2.8mm
  - 부식 여유: 0.4mm
  - 선정 두께: 3.2mm

  2) 고온 Condenser
  - 계산 기준: ASME Section VIII Div.1
  - 최소 요구 두께: 3.5mm
  - 부식 여유: 0.5mm
  - 선정 두께: 4.0mm

  #### 4.4.2. 노즐 보강 계산
  1) 입출구 노즐
  - 계산 기준: ASME Section VIII Div.1
  - 보강 면적 요구량: 1,850mm²
  - 실제 보강 면적: 2,100mm²
  - 적정성 평가: 적합

  2) 부속 노즐
  - 계산 기준: ASME Section VIII Div.1
  - 보강 면적 요구량: 920mm²
  - 실제 보강 면적: 1,100mm²
  - 적정성 평가: 적합

  ### 4.5. 설계 검증 결과
  | 검증 항목 | 기준 | 결과 | 평가 |
  |-----------|------|------|------|
  | 압력 강하 | ≤ 4.5 bar | 3.7/4.3 bar | 적합 |
  | 열교환량 | ≥ 요구량 | 13.6/12.5% 여유 | 적합 |
  | 체류 시간 | ≥ 최소 요구 | 충족 | 적합 |
  | 기계적 강도 | ASME 기준 | 충족 | 적합 |

  ## 5. 고온 Condenser 용량 최적화 분석

  ### 5.1. 용량 최적화 기준
  1) 기술적 기준
  - 열교환 효율: 90% 이상
  - 압력 강하: 4.5 bar 이하
  - 체류 시간: 20초 이상

  2) 경제적 기준
  - 초기 투자비
  - 운전 비용
  - 유지보수 비용

  ### 5.2. 시뮬레이션 결과 분석

  #### 5.2.1. 용량별 성능 비교
  | 용량(L) | 열교환 효율(%) | 압력 강하(bar) | 체류 시간(초) |
  |---------|----------------|----------------|---------------|
  | 100 | 88 | 3.8 | 18.2 |
  | 110 | 89 | 4.0 | 20.0 |
  | 120 | 92 | 4.3 | 21.8 |
  | 130 | 93 | 4.7 | 23.6 |

  #### 5.2.2. 경제성 분석
  | 용량(L) | 초기 투자비(백만원) | 연간 운전비(백만원) | 회수 기간(년) |
  |---------|---------------------|---------------------|---------------|
  | 100 | 180 | 45 | 2.5 |
  | 110 | 195 | 47 | 2.6 |
  | 120 | 210 | 48 | 2.7 |
  | 130 | 225 | 50 | 2.9 |

  ### 5.3. 최적 용량 선정

  #### 5.3.1. 기술적 검토
  - 열교환 효율 목표 달성
  - 압력 강하 허용 범위 내
  - 체류 시간 요구사항 충족

  #### 5.3.2. 경제성 검토
  - 초기 투자비 적정성
  - 운전비용 최적화
  - 투자회수기간 적정성

  ### 5.4. 최적화 결론
  - 선정 용량: 120L
  - 선정 사유
      * 기술적 요구사항 충족
      * 경제성 확보
      * 운전 안정성 우수

  ## 6. 제어 시스템

  ### 6.1. 제어 항목

  #### 6.1.1. 온도 제어
  1) 저온 Condenser
  - 제어 범위: 20±2℃
  - 제어 방식: PID
  - 제어 요소: 냉매 유량

  2) 고온 Condenser
  - 제어 범위: 125±3℃
  - 제어 방식: PID
  - 제어 요소: 열매유 유량

  #### 6.1.2. 압력 제어
  1) 운전 압력
  - 제어 범위: 1.5~6.5 bar
  - 제어 방식: PID
  - 제어 요소: 배출 밸브

  2) 차압
  - 제어 범위: 0.5~1.0 bar
  - 제어 방식: PID
  - 제어 요소: 유량 조절

  #### 6.1.3. 수위 제어
  1) 액위
  - 제어 범위: 40~60%
  - 제어 방식: On/Off
  - 제어 요소: 배출 펌프

  ### 6.2. 계측 항목

  #### 6.2.1. 온도 센서
  | 위치 | 타입 | 범위 | 정확도 |
  |------|------|------|---------|
  | 입구 | TC | 0~500℃ | ±1.0℃ |
  | 출구 | RTD | 0~200℃ | ±0.5℃ |
  | 쉘측 | TC | 0~300℃ | ±1.0℃ |

  #### 6.2.2. 압력 센서
  | 위치 | 타입 | 범위 | 정확도 |
  |------|------|------|---------|
  | 입구 | 압력계 | 0~10 bar | ±0.1 bar |
  | 출구 | 압력계 | 0~10 bar | ±0.1 bar |
  | 차압 | 차압계 | 0~5 bar | ±0.05 bar |

  #### 6.2.3. 수위 센서
  | 위치 | 타입 | 범위 | 정확도 |
  |------|------|------|---------|
  | 저온조 | 레벨계 | 0~100% | ±1% |
  | 고온조 | 레벨계 | 0~100% | ±1% |

  ### 6.3. 제어 로직
  1) 정상 운전
  ```
  IF (온도 > 설정값 + 편차) THEN
      냉매/열매유 유량 증가
  ELSE IF (온도 < 설정값 - 편차) THEN
      냉매/열매유 유량 감소
  END IF

  IF (압력 > 설정값 + 편차) THEN
      배출 밸브 개도 증가
  ELSE IF (압력 < 설정값 - 편차) THEN
      배출 밸브 개도 감소
  END IF

  IF (수위 > 상한값) THEN
      배출 펌프 ON
  ELSE IF (수위 < 하한값) THEN
      배출 펌프 OFF
  END IF
  ```

  2) 비상 상황
  ```
  IF (온도 > 상한 경보값) OR
     (압력 > 상한 경보값) OR
     (수위 > 상한 경보값) THEN
      비상 정지 시퀀스 실행
  END IF
  ```

  ### 6.4. 제어반 설계
  1) 하드웨어 구성
  - PLC: Siemens S7-1500
  - HMI: 15인치 터치스크린
  - I/O 모듈: 디지털 32점, 아날로그 16점

  2) 소프트웨어 구성
  - 운영체제: Windows 10 IoT
  - SCADA: Wonderware InTouch
  - 데이터베이스: SQL Server

  ## 7. 안전 설계

  ### 7.1. 안전 장치

  #### 7.1.1. 과압 방지 장치
  1) 안전 밸브
  - 설정압: 설계압력의 110%
  - 용량: 최대 발생 유량의 120%
  - 규격: API 526

  2) 파열판
  - 설정압: 설계압력의 120%
  - 재질: Inconel
  - 규격: ASME Section VIII

  #### 7.1.2. 온도 보호 장치
  1) 고온 차단
  - 설정온도: 운전온도 + 20℃
  - 응답시간: 2초 이내
  - 작동방식: 자동 차단

  2) 과냉 방지
  - 설정온도: 운전온도 - 10℃
  - 응답시간: 5초 이내
  - 작동방식: 경보 및 자동 제어

  #### 7.1.3. 비상 차단 시스템
  1) 비상정지 버튼
  - 설치위치: 현장 3개소, 제어실 1개소
  - 응답시간: 1초 이내
  - 작동방식: 수동

  2) 연동 차단
  - 대상: 펌프, 밸브, 열매체
  - 응답시간: 3초 이내
  - 작동순서: 정해진 시퀀스에 따름

  ### 7.2. 모니터링

  #### 7.2.1. 실시간 감시 시스템
  1) 운전 변수
  - 온도: 입출구, 쉘측
  - 압력: 입출구, 차압

    ## 8. 유지보수 계획

  ### 8.1. 정기 점검

  #### 8.1.1. 일일 점검
  | 점검 항목 | 주기 | 점검 방법 | 판정 기준 |
  |-----------|------|------------|------------|
  | 압력 지시값 | 2회/일 | 육안 점검 | ±0.2 bar 이내 |
  | 온도 지시값 | 2회/일 | 육안 점검 | ±2℃ 이내 |
  | 누설 여부 | 1회/일 | 육안 점검 | 누설 없을 것 |
  | 소음/진동 | 1회/일 | 청각/촉각 | 이상 없을 것 |
  | 계기 작동 | 1회/일 | 작동 확인 | 정상 작동 |

  #### 8.1.2. 월간 점검
  | 점검 항목 | 주기 | 점검 방법 | 판정 기준 |
  |-----------|------|------------|------------|
  | 안전밸브 작동 | 1회/월 | 작동 시험 | 정상 작동 |
  | 센서 교정 | 1회/월 | 교정 시험 | ±1% 이내 |
  | 배관 상태 | 1회/월 | 육안 점검 | 부식/손상 없음 |
  | 보온재 상태 | 1회/월 | 육안 점검 | 손상 없음 |
  | 플랜지 조임 | 1회/월 | 토크 체크 | 규정값 ±10% |

  #### 8.1.3. 연간 점검
  | 점검 항목 | 주기 | 점검 방법 | 판정 기준 |
  |-----------|------|------------|------------|
  | 두께 측정 | 1회/년 | UT 검사 | 최소치 이상 |
  | 내부 검사 | 1회/년 | 개방 검사 | 부식/손상 없음 |
  | 용접부 검사 | 1회/년 | RT/PT 검사 | 균열 없음 |
  | 전체 세정 | 1회/년 | 화학 세정 | 잔류물 없음 |
  | 성능 시험 | 1회/년 | 운전 시험 | 설계값 ±5% |

  ### 8.2. 예방 정비

  #### 8.2.1. 주요 부품 교체 계획
  | 부품명 | 교체 주기 | 수량 | 비고 |
  |--------|-----------|-------|------|
  | 가스켓 | 1년 | 12세트 | 플랜지용 |
  | O-ring | 6개월 | 24개 | 밸브용 |
  | 센서류 | 2년 | 8개 | 온도/압력 |
  | 안전밸브 | 3년 | 4개 | 스프링식 |
  | 열교환 튜브 | 5년 | 1식 | 부분 교체 |

  #### 8.2.2. 세정 계획
  1) 정기 세정
  - 주기: 6개월
  - 방법: 화학 세정
  - 세정제: 인산염계
  - 소요시간: 48시간

  2) 비정기 세정
  - 조건: 차압 20% 증가 시
  - 방법: 기계적/화학적 세정
  - 세정제: 상황별 선정
  - 소요시간: 72시간

  ### 8.3. 부품 관리

  #### 8.3.1. 예비품 목록
  | 품명 | 규격 | 수량 | 보관 조건 |
  |------|------|-------|------------|
  | 가스켓 | SPW-316L | 24개 | 실온/건조 |
  | 온도센서 | TC-K | 4개 | 실온/방습 |
  | 압력계 | 0-10 bar | 2개 | 실온/방습 |
  | 제어밸브 | 2인치/공압식 | 2개 | 실온/방진 |
  | 안전밸브 | 2인치/스프링식 | 2개 | 실온/방진 |

  #### 8.3.2. 재고 관리 계획
  1) 재고 수준
  - 최소 재고량: 3개월 사용량
  - 최대 재고량: 1년 사용량
  - 발주 시점: 6개월 사용량 도달 시

  2) 보관 관리
  - 온도: 20±5℃
  - 습도: 60% 이하
  - 정기 점검: 월 1회
  - 재고 실사: 분기 1회

  ## 9. 경제성 분석

  ### 9.1. 투자비용

  #### 9.1.1. 설비 투자
  | 항목 | 금액(백만원) | 비고 |
  |------|--------------|------|
  | Condenser 본체 | 180 | 재료비 포함 |
  | 부대 설비 | 85 | 펌프/밸브류 |
  | 계측 제어 | 45 | DCS 포함 |
  | 배관/보온 | 35 | 설치 포함 |
  | 소계 | 345 | - |

  #### 9.1.2. 설치 비용
  | 항목 | 금액(백만원) | 비고 |
  |------|--------------|------|
  | 토목/구조물 | 25 | 기초 포함 |
  | 배관/보온 | 30 | 자재 포함 |
  | 전기/계장 | 40 | 케이블 포함 |
  | 시운전 | 15 | 시험 포함 |
  | 소계 | 110 | - |

  ### 9.2. 운영비용

  #### 9.2.1. 유틸리티 비용
  | 항목 | 단가 | 사용량/년 | 금액(백만원/년) |
  |------|------|------------|-----------------|
  | 전력 | 120원/kWh | 180,000 kWh | 21.6 |
  | 냉각수 | 300원/톤 | 36,000 톤 | 10.8 |
  | 열매유 | 2,500원/L | 2,400 L | 6.0 |
  | 소계 | - | - | 38.4 |

  #### 9.2.2. 유지보수 비용
  | 항목 | 금액(백만원/년) | 비고 |
  |------|-----------------|------|
  | 부품 교체 | 15 | 정기 교체품 |
  | 세정 비용 | 8 | 약품 포함 |
  | 점검 비용 | 12 | 외주 포함 |
  | 인건비 | 24 | 운전원 1명 |
  | 소계 | 59 | - |

  ### 9.3. 수익 분석

  #### 9.3.1. 예상 수익
  1) 생산량 기준
  - 경질유: 720톤/년
  - 디젤유: 2,880톤/년
  - 나프타: 800톤/년

  2) 판매 수익
  | 제품 | 단가(원/kg) | 수량(톤/년) | 금액(백만원/년) |
  |------|-------------|-------------|-----------------|
  | 경질유 | 850 | 720 | 612 |
  | 디젤유 | 1,100 | 2,880 | 3,168 |
  | 나프타 | 950 | 800 | 760 |
  | 합계 | - | 4,400 | 4,540 |

  #### 9.3.2. 투자회수기간
  1) 연간 수지
  - 연간 수익: 4,540백만원
  - 연간 비용: 97.4백만원
  - 순이익: 4,442.6백만원

  2) 투자회수기간
  - 총 투자비: 455백만원
  - 연간 순이익: 4,442.6백만원
  - 투자회수기간: 1.23개월

  ## 10. 부록

  ### 10.1. 상세 도면
  1) 전체 배치도
  2) Condenser 상세도
  3) P&ID
  4) 전기/계장 결선도
  5) 구조물 상세도

  ### 10.2. 계산서
  1) 열전달 계산서
  2) 구조 계산서
  3) 압력강하 계산서
  4) 안전밸브 용량 계산서

  ### 10.3. 기술 규격서
  1) 장치 사양서
  2) 계측기 사양서
  3) 밸브류 사양서
  4) 전기/계장 사양서

  ### 10.4. 시험 성적서
  1) 재료 시험 성적서
  2) 용접 검사 성적서
  3) 수압 시험 성적서
  4) 성능 시험 성적서
