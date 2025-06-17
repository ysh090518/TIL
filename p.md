# python
python은 다른 언어들과 문법이 조금씩 다름
; 을 붙이지 않아도 되고 {} 대신 : 을 씀
숫자를 입력할 때 제한이 없음

- 출력 방법
```python
print("Hello")
print(12)
```
- 변수 선언
```python
birth = 0518
name = seohyon
```
변수 키워드 없이 변수이름과 값만 정해줌
- 함수
```python
def name():
    print("seohyon")
```
- 클래스
```python
class Animal:
    def dog(self):
        print("멍멍")
    def _init_(self)
animal = Animal()
animal.dog()
```
class 안에 property와 method를 추가할 수 있음
- 배열
```python
arr=[1,2,3,4]
arr[1] = 'one'
```
- 딕셔너리
```python
dic = {'key1'=1, 'key2'=2}
```
딕셔너리는 key,value로 구성됨.
key는 변할 수 없지만 value는 변할 수 있음
- 조건문 if
```python
if num > 1:
    print("1보다 큼")
```
- 반복문 for
```python
for i in range(3):
    print(for)
```
- 반복문 while
```python
i = 0
while i < 3:
    print(while)
    i = i + 1
```
- 주석처리
```python
#한줄주석
'''여
러
줄
주
석'''
```