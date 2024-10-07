# note

/lib <br>
│ <br>
├── main.dart                   # Firebase 초기화 및 앱 실행 <br>
├── screens                     # UI 화면 관련 파일들 <br>
│   ├── login_screen.dart        # 로그인 및 회원가입 화면 <br>
│   ├── home_screen.dart         # 메인 화면 (Drawer 포함) <br>
│   ├── calendar_screen.dart     # 달력 화면 <br>
│   ├── diary_screen.dart        # 일기 작성 화면 <br>
│   ├── answer_list_screen.dart  # 내가 답한 질문 목록 화면 <br>
│   ├── profile_screen.dart      # 사용자 정보 수정 화면 <br>
│ <br>
├── services                    # Firebase 및 기타 서비스 로직 <br>
│   ├── auth_service.dart        # 로그인 및 회원가입 로직 <br>
│   ├── firestore_service.dart   # Firestore 데이터 관련 로직 <br>
│   └── emotion_analysis.dart    # 감정 분석 로직
│ <br>
└── models                      # 데이터 모델 <br>
    └── diary_model.dart         # 일기 데이터 모델 <br>
