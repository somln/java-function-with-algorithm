# 알고리즘 문제 풀이에서 자주 쓰이는 자바 함수 정리

## [ Data Type ]

## String
#### 형 변환
* toCharArray(): 문자열을 char형 배열으로 변환
* String.valueOf(str) : 지정된 값을 String으로 변환

#### 대소문자
* toLowerCase() : 문자열을 소문자로 변환
* toUpperCase() : 문자열을 대문자로 변환

#### 문자열 나누기
* charAt(index): 해당 인덱스의 문자를 char형으로 반환
* split(String regex): 문자열을 특정 문자를 기준으로 나누어 배열으로 반환
* substring(index, {end index}) : index 위치를 포함하여 그 이후의 문자열 반환

#### 탐색
* indexOf(str, {시작 위치}): 특정 문자열이 대상 문자열의 몇 번째 인덱스에 위치하는지 반환
* equal(str) : String 문자열 값 비교

* length() : 문자열의 길이를 반환


<br>


## [ Wrapper ]

## Charcter
* toLowerCase(c): 문자열을 소문자로 변환
* toUpperCase(c): 문자열을 대문자로 변환
* isAlphabetic(c): c가 알파벳이면 true, 아니면 false 반환

## Array
* length : 배열의 크기를 반환


<br>

## [ Collection Framework ]

## List 
* add(obj): 리스트 끝에 원소 추가  
