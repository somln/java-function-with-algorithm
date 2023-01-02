# 알고리즘 자바 함수 정리

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

#### 치환
* replace(beforeStr, afterStr) : 특정 문자열을 새로운 문자열로 치환
* replaceAll(pattern, afterStr) : 정규식에 일치하는 문자를 새로운 문자열로 치환

<br>

## Array
* length : 배열의 크기를 반환

<br>

## [ Wrapper ]

## Charcter

#### 대소문자
* toLowerCase(c): 문자를 소문자로 변환
* toUpperCase(c): 문자를 대문자로 변환
* isLowerCase(c): c가 소문자이면 true, 아니면 false 반환
* isUpperCase(c): c가 대문자이면 true, 아니면 false 반환

#### 문자 종류
* isAlphabetic(c): c가 알파벳이면 true, 아니면 false 반환
* isDibit(c): c가 숫자면 true, 아니면 false 반환

<br>

## Integer

* parseInt(str): 문자열을 int로 변환

<br>

## [ Collection Framework ]

## List 
* add(obj): 리스트 끝에 원소 추가  
