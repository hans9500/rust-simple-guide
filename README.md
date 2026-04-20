# Rust Simple Guide

Rust 핵심 개념을 주제별로 정리한 독립형 HTML 가이드 모음입니다.

- 외부 의존성 없는 독립형 HTML (인라인 CSS + 바닐라 JS)
- VS Code Dark Modern 테마 코드 하이라이팅
- 모든 예제 [Wandbox](https://wandbox.org) 연동 즉시 실행
- 라이트 / 다크 테마 토글
- 사이드바 + 스크롤 감지 TOC

## 🔗 GitHub Pages

**[hans9500.github.io/rust-simple-guide](https://hans9500.github.io/rust-simple-guide)**

---

## 📚 가이드 목록

### ⭐ Main Guide

| 파일 | 제목 | 내용 |
|------|------|------|
| [rust_java-developer.html](https://hans9500.github.io/rust-guide-for-java-developer) | Java 개발자를 위한 Rust | Java · C++ · Rust 단계별 전환 가이드 |

---

### 🧠 소유권 & 메모리

| 파일 | 제목 | 내용 |
|------|------|------|
| rust_smart-pointer.html | 스마트 포인터 · 소유권 | Box · Rc · Arc · 소유권 이전 · Drop |
| rust_lifetime.html | 라이프타임 | dangling 방지 · 생략 규칙 · 'static · struct 라이프타임 |
| rust_variable-lifecycle.html | 변수 라이프사이클 | 스코프 · Drop · move · borrow 흐름 |
| rust_mutable-variables.html | 뮤터블 변수 | mut · interior mutability · Cell · RefCell |

---

### 🔷 타입 시스템

| 파일 | 제목 | 내용 |
|------|------|------|
| rust_trait.html | 트레이트 | trait 정의 · 구현 · 기본 메서드 · 트레이트 객체 |
| rust_impl-guide.html | impl 패턴 | struct · impl · 빌더 패턴 · 메서드 체이닝 |
| rust_expression.html | 표현식 | 모든 것이 표현식 · if/match/block 반환값 |

---

### 🎯 패턴 & 제어 흐름

| 파일 | 제목 | 내용 |
|------|------|------|
| rust_pattern-matching.html | 패턴 매칭 | match · if let · while let · let-else · 구조분해 |
| rust_matching-option.html | 매칭 · Option | Option · Result · ? 연산자 · 에러 처리 |
| rust_closure_basic.html | 클로저 기초 | 클로저 기본 문법 · 캡처 · 활용 패턴 |
| rust_closure.html | 클로저 | 캡처 방식 · Fn/FnMut/FnOnce · move · 고차함수 |

---

### 📚 컬렉션 & 함수형

| 파일 | 제목 | 내용 |
|------|------|------|
| rust_iterator.html | Iterator · 함수형 | map · filter · fold · chain · Iterator 직접 구현 |
| rust_hashmap.html | 해시맵 | HashMap · entry API · BTreeMap · 컬렉션 비교 |

---

### 📁 모듈 & 구조

| 파일 | 제목 | 내용 |
|------|------|------|
| rust_module-system.html | 모듈 시스템 | mod · use · pub · crate · 파일 구조 |

---

## 🛠 기술 스택

- **언어**: HTML · CSS · JavaScript (순수 바닐라, 프레임워크 없음)
- **코드 실행**: [Wandbox](https://wandbox.org) API (rust-1.82.0)
- **테마**: VS Code Dark Modern 기반 커스텀 하이라이터
- **폰트**: Consolas · Courier New (코드), 시스템 폰트 (본문)

## 📄 License

MIT
