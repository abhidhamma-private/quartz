## 1. 하는 일
> 중복을 없애준다 

## 2. 용법
### 1)  선언
> set 자료구조는 {}모양이지만 그냥 {}라고 하면 딕셔너리가 된다
```python
a = set() # {}
```

### 2) 내장함수
>
```python
#추가
a.add(1) # {1}
a.add(2) # {1, 2}

#삭제
a.remove(1) # {2}

#리스트로 업데이트하기
a.update([3,4]) # {2, 3, 4}


```

## 3.예제
>
   ex) 
```python
a = set([1,2,3,4])
b = set([3,4,5,6])

a & b # {3, 4} (교집합)
a | b # {1, 2, 3, 4, 5, 6} (합집합)
a - b # {1, 2} (차집)
```