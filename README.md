# 쇼핑 리스트 앱

간단하고 직관적인 쇼핑 리스트 웹 애플리케이션입니다.

## 🌐 데모

👉 [https://templar0.github.io/shopping-listapp/](https://templar0.github.io/shopping-listapp/)

## ✨ 기능

- **아이템 추가**: 텍스트 입력 후 추가 버튼 클릭 또는 Enter 키로 아이템 추가
- **아이템 삭제**: 각 아이템 우측의 × 버튼으로 삭제
- **완료 체크**: 체크박스를 클릭하여 구매 완료 표시
- **다크 모드**: 라이트/다크 테마 전환 지원
- **데이터 저장**: localStorage를 활용하여 브라우저를 닫아도 데이터 유지
- **진행 상황 표시**: 총 아이템 수와 완료된 아이템 수 표시

## 🚀 사용 방법

1. 입력 필드에 구매할 아이템 이름을 입력합니다
2. `추가` 버튼을 클릭하거나 `Enter` 키를 누릅니다
3. 구매를 완료한 아이템은 왼쪽 체크박스를 클릭하여 표시합니다
4. 아이템을 삭제하려면 오른쪽의 `×` 버튼을 클릭합니다
5. 우측 상단의 🌙/☀️ 버튼으로 다크/라이트 모드를 전환할 수 있습니다

## 🛠️ 기술 스택

- HTML5
- CSS3 (CSS Variables, Flexbox, Gradient)
- Vanilla JavaScript (ES6+)
- localStorage API

## 📁 프로젝트 구조

```
shopping-listapp/
├── index.html    # 메인 애플리케이션 (HTML, CSS, JS 통합)
└── README.md     # 프로젝트 설명
```

## 🔒 보안

- XSS(Cross-Site Scripting) 공격 방지를 위한 HTML 이스케이프 처리

## 📱 반응형 디자인

모바일, 태블릿, 데스크톱 등 다양한 화면 크기에서 최적화된 UI를 제공합니다.

## 📄 라이선스

MIT License
