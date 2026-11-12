# https-test.com
창작자 피드백 분석 및 심리적 부담 완화를 위한 AI
webtoon-comment-bert/
│
├── data/
│   └── webtoon_comments_sample.csv    # 회차별 독자 댓글 수집 데이터
├── models/
│   └── bert_classifier.py             # 트랜스포머(BERT) 기반 미세조정 분류 모델
├── utils/
│   ├── preprocessor.py                # 중복 및 개인정보 제거 전처리기
│   └── visualizer.py                  # 막대그래프 및 원그래프 시각화 모듈
├── main.py                            # 전처리 -> BERT 분석 -> 시각화 -> 회차별 리포트 파이프라인
├── requirements.txt                   # 필수 라이브러리 목록
└── README.md                          # 연구 배경 및 시스템 구조 설명 문서
