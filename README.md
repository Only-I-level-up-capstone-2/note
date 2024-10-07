# note

/lib
│
├── main.dart                   # Firebase 초기화 및 앱 실행
├── screens                     # UI 화면 관련 파일들
│   ├── login_screen.dart        # 로그인 및 회원가입 화면
│   ├── home_screen.dart         # 메인 화면 (Drawer 포함)
│   ├── calendar_screen.dart     # 달력 화면
│   ├── diary_screen.dart        # 일기 작성 화면
│   ├── answer_list_screen.dart  # 내가 답한 질문 목록 화면
│   ├── profile_screen.dart      # 사용자 정보 수정 화면
│
├── services                    # Firebase 및 기타 서비스 로직
│   ├── auth_service.dart        # 로그인 및 회원가입 로직
│   ├── firestore_service.dart   # Firestore 데이터 관련 로직
│   └── emotion_analysis.dart    # 감정 분석 로직
│
└── models                      # 데이터 모델
    └── diary_model.dart         # 일기 데이터 모델
