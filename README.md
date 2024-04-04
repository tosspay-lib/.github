# tosspay-lib
사업자 등록증 없이 결제를 할수있게 도와주는 라이브러리입니다.

## 예상문법
```rs
tp = Tosspay("toss-id")
tp.addEvent(Event.Send, 핸들러함수(이름: str, 설명: str, 금액: str))

tp = Tosspay("toss-id")
tp.payment(결제금액: int, 핸들러함수 { 코드가 같을때 실행할꺼 })
```
