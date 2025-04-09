# Dart 비동기 프로그래밍

## ✅ 1. 동기
- 한 작업이 끝나야 다음 작업을 실행함
- 작업들이 순차적으로 실행됨
- `blocking`방식 -> 이전 작업이 끝날 때까지 기다림.
```dart
void main() {
  print('A');
  print('B');
  print('C');
}
```

## ✅ 2. 비동기
- 시간이 오래 걸릴 수 있는 작업을 미뤄두고, 다음 작업을 먼저 실행함
- 대표적인 비동기 작업 : API 호출, 파일 읽기, 타이머 등
- `Future`, `async`, `await` 키워드를 통해 구현
![Sync vs Async](./sync-vs-async.png)


