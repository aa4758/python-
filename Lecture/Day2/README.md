# 주피터 노트북
- Anaconda prompt -> jupyter-notebooke 입력

# TYPE
- '가나다': String 문자열
- 123: int 숫자
- True, False: bool 불린
- (): tuple 투플
- {}: dict 딕셔너리
- []: list 리스트

# 연산자
- +: 더하기
- -: 빼기
- *: 곱하기
- /: 나누기
- %: 나머지
- //: 정수만 나오도록 나누기
- ** : 제곱
- A += B: A에 B를 더해서 나온 값
- A -= B: A에 B를 빼고 나온 값
- A *= B: A에 B를 곱해서 나온 값
- A /= B: A에 B를 나누고 나온 값
- A //= B: A에 B를 나누고 나온 값
- A %= B: A에 B를 나누고 나온 나머지 값

# .format()
"내 이름 {}, 주소{}, 나이{}" .format(AAA, BBB, CCC)
-> 내이름 AAA, 주소 BBB, 나이CCC 출력
"내 이름 {0}, 주소{2}, 나이{1}" .format(AAA, CCC, BBB)
-> 내이름 AAA, 주소 BBB, 나이CCC 출력

fruit = 'apple'
cost = '$3'
f'{fruit} cost {cost}'
-> 'apple cost $3' 출력

# 문자열 객체
