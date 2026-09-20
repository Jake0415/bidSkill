# Generation evidence

Generated recommendations are PROPOSED and require human review. Source statuses below are unchanged; interactions were not verified.

[
  {
    "evidence_id": "1182156e-0f1b-4248-acca-bbc06c1b9278",
    "hash": "85ca9d8c3d87c3706ddb3ef928ec5f5af72bff68e3501d6fa1062a9ba025f77a",
    "title": "대시보드 — 본문 미표시",
    "screen_type": "other",
    "source": "USER_SUPPLIED",
    "observation_status": "UNVERIFIED",
    "notes": [
      "OBSERVED: CUA_BROWSER_OBSERVED; 직접 URL 접근과 관제패널 대시보드 버튼을 통한 진입 모두 확인했다.",
      "OBSERVED: 상단 헤더·좌측 메뉴·열린 화면 탭은 표시되지만 본문은 비어 있다. 직접 URL 접근에서는 서버 오류 토스트가 나타났다.",
      "LIMITATION: 정상 대시보드 레이아웃, KPI, 차트 또는 업무 기능을 관찰하지 못했다. 완료된 대시보드 참조로 사용하지 않는다."
    ]
  },
  {
    "evidence_id": "50fc9846-1bed-42f9-b114-d7e20b2eff61",
    "hash": "d4a917d3042ba90fabb9abab46279f0f9d38cfc020b816bc94252de936a43be6",
    "title": "스마트 안전장비 — 개별장비",
    "screen_type": "list",
    "source": "USER_SUPPLIED",
    "observation_status": "OBSERVED",
    "notes": [
      "OBSERVED: CUA_BROWSER_OBSERVED; 현재 위치→제목→개별장비/장비세트 탭→다중 조건 검색→건수/액션→표 구조.",
      "OBSERVED: 지역본부, 시도, 현장, 장비유형, 장비 세부유형, 배정상태, 가동상태, 자산상태, 연도, S/N·모델명 검색 필터가 표시된다. 일부 종속 필터는 비활성 상태다.",
      "OBSERVED: 초기화·조회·신규 장비 등록·Excel 내보내기 버튼이 보인다. 쓰기/내보내기는 실행하지 않았다.",
      "OBSERVED: 표 헤더는 NO, S/N, 장비유형, 장비 세부유형, 제조사, 모델명, 현장 배정 현장, 보유 지역본부, 배정상태, 가동상태, 자산상태, 도입일.",
      "OBSERVED: DOM counts: tables=1, inputs=1, buttons=24.",
      "LIMITATION: 상세 화면과 필터 실제 동작은 검증하지 않았다. 표 본문은 제외했다."
    ]
  },
  {
    "evidence_id": "7328cb3e-325b-4dd9-ad9d-ce9c2d320977",
    "hash": "2941efc5258f7c9b6d0984caced3c33e0e431ce4b1a9305ce06f8183c04ef026",
    "title": "현장지원사업",
    "screen_type": "list",
    "source": "USER_SUPPLIED",
    "observation_status": "OBSERVED",
    "notes": [
      "OBSERVED: CUA_BROWSER_OBSERVED; 공통 헤더·좌측 메뉴 아래 제목→다중 조건 검색→건수/액션→표 구조.",
      "OBSERVED: 검색 조건은 지역본부, 시도, 현장, 지원유형, 운영단계, 공종 대분류, 년도, 현장명/주소 검색이다. 초기화·조회 버튼이 보인다.",
      "OBSERVED: 신규 등록과 Excel 내보내기 버튼은 보이지만 실행하지 않았다.",
      "OBSERVED: 표 헤더는 NO, 지역본부, 현장명, 지원유형, 운영단계, 지원기간, 공사기간, 공종, 전체 지원장비, 발생 이벤트, 안전관리수준점수, 관리.",
      "OBSERVED: DOM counts: tables=1, inputs=1, buttons=34.",
      "LIMITATION: 표 본문과 운영 레코드를 저장하지 않았다. 검색·등록·내보내기 동작은 검증하지 않았다."
    ]
  },
  {
    "evidence_id": "c69ca635-9bca-4b54-99ae-3019fc309fbe",
    "hash": "ad5b097b7f048357bb8c56f211539f1694a13fb88c435230aaf376de7df5001b",
    "title": "이벤트 관리 — CCTV 이벤트",
    "screen_type": "list",
    "source": "USER_SUPPLIED",
    "observation_status": "OBSERVED",
    "notes": [
      "OBSERVED: CUA_BROWSER_OBSERVED; /events는 /events/cctv로 이동한다.",
      "OBSERVED: 현재 위치와 제목 아래 CCTV 이벤트·알림 이력·CSI 연동정보 탭, 전체 건수, 그리드/리스트 보기 선택이 표시된다. 초기 선택은 리스트 보기다.",
      "OBSERVED: 표 헤더는 NO, 이벤트 ID, 발생 시각, 장비 S/N, 이벤트 유형, 지역본부, 현장명, 발생 위치, 조치상태, 조치자, 조치일시.",
      "OBSERVED: DOM counts: tables=1, inputs=0, buttons=13.",
      "LIMITATION: 조치 등록, 상세 레코드, 보기 전환 동작은 검증하지 않았다. 개인 및 운영 데이터는 제외했다."
    ]
  },
  {
    "evidence_id": "de72c9be-b176-4428-a6ee-8ec183c5b1c5",
    "hash": "2d04dc9fe91748ee3b9efd6e99daf5be9d4fe3d3afadc7627d5014b0c89691fa",
    "title": "통합관제",
    "screen_type": "main",
    "source": "USER_SUPPLIED",
    "observation_status": "OBSERVED",
    "notes": [
      "OBSERVED: CUA_BROWSER_OBSERVED; original public app rendered without entering credentials.",
      "OBSERVED: 상단 전역 헤더, 좌측 주 메뉴, 열린 화면 탭, 지도 중심 본문, 접이식 좌측 관제패널 및 우측 실시간알림 패널.",
      "OBSERVED: 지역 필터, 지도/항공 보기, 확대/축소, 날씨 상세 및 AI 도우미 진입 버튼이 보인다. 내 위치 버튼은 클릭하지 않았다.",
      "OBSERVED: 좌측 패널을 펼치면 관제현황/대시보드 전환, 지원사업 현황, 지역별 분포, 스마트 안전장비 관리현황, 안전관리수준 요약 블록이 표시된다.",
      "OBSERVED: DOM counts at initial view: buttons=16, links=8, nav=2, tables=0, forms=0, inputs=0.",
      "OBSERVED: Noto Sans KR 14px; white body; text rgb(30,33,36); navigation background rgb(244,245,246); typical button radius 4px.",
      "LIMITATION: 일부 API 오류 알림이 관찰되었다. 화면 구조만 확인했으며 실제 관제 데이터 정확성, 지도 타일 및 실시간 갱신 정상 여부는 검증하지 않았다."
    ]
  }
]