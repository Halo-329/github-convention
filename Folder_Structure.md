📁 my-project/
├── 📁 backend/                      # 백엔드(Spring Boot 전체)
│   ├── 📁 src/
│   │   ├── 📁 main/
│   │   │   ├── 📁 java/com/example/project/
│   │   │   │   ├── config/
│   │   │   │   ├── domain/
│   │   │   │   ├── repository/
│   │   │   │   ├── service/
│   │   │   │   ├── controller/
│   │   │   │   └── ProjectApplication.java
│   │   │   └── 📁 resources/
│   │   │       ├── 📁 static/             # JS, CSS, 이미지 등 정적 자원
│   │   │       │   ├── css/
│   │   │       │   ├── js/
│   │   │       │   └── images/
│   │   │       ├── 📁 templates/          # Thymeleaf HTML 템플릿
│   │   │       │   └── *.html
│   │   │       └── application.yml
│   │   └── 📁 test/
│   └── build.gradle 또는 pom.xml
│
├── 📁 docs/                         # 기획 문서
│
├── 📁 infra/                        # Docker, nginx, CI/CD 등
│
├── 📁 scripts/                      # 배포 스크립트
│
├── .gitignore
├── README.md
└── LICENSE
