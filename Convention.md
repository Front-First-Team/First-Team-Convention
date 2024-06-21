
#Team Convention 

-----


### if문
    '''
     if (true) {
        return true;
    }
    '''

### 화살표 함수
    '''
    const foo = () => {
        return "Hello World";
    }
    '''
### 문장 종료
* 반드시 세미콜론을 사용

### 상수는 영문 대문자, 스네이크 표기법을 사용

'''
const NAME_ROLE;
'''

### 변수 및 함수는 카멜케이스를 사용

###  배열: 복수형 이름으로 사용

'''
const datas = [];
'''

###  정규표현식: 'r'로 시작

'''
const = rName = /.*/;
'''

###  이벤트 핸들러: 'on'으로 시작

'''
const onClick = () => {};
const onChange = () => {};
'''

###  반환 값이 불린인 경우: 'is'로 시작

'''
const isLoading = false;
'''

###  Fetch함수: method(get, post, put, del)로 시작

'''
const getEnginList = () => {…}
'''

###  블록 구문

*한 줄짜리 블록일 경우라도 {}를 생략하지 않고, 명확히 줄 바꿈 하여 사용한다

'''
if(true){
  return 'hello'
}
'''

###  함수는 함수 표현식을 사용하며, 화살표 함수를 사용한다.

'''
const fnName = () => {};
[1,2,3].map(x => x);
'''

###  바로 return 하는 경우 중괄호 생략 X

'''
const foo = () => { return "bar"; }
'''

### 태그 네이밍

1.Styled-component태그 생성 시 아래 네이밍 규칙을 준수하여 의미 전달을 명확하게 한다.
2.태그명이 길어지더라도 의미 전달의 명확성에 목적을 두어 작성한다.
*전체 영역: Container
*영역의 묶음: {Name}Area
*의미없는 태그: <>

### 폴더 네이밍

* 카멜 케이스를 기본으로 한다. 컴포넌트 폴더일 경우에만 파스칼 케이스로 사용한다.
###  카멜 케이스
* camelCase
###  파스칼 케이스
* PascalCase

### 파일 네이밍
1.컴포넌트일 경우만 .jsx 확장자를 사용한다. (그 외에는 .js)
2.customHook을 사용하는 경우 : use + 함수명

### 이벤트 핸들러 네이밍
1.Props의 경우: on (onClick 등등)
2.함수인 경우: handle (handleClick 등등)

'''
<MyComponent onclick={this.handleClick} />
'''
