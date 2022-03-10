# Css 선택자 알아보기 Part2
___

* 가상 클래스 선택자
* 가상 요소 선택자
* 속성 선택자
___
# ex) HTML
```html
<div class="fruits">
  <span>딸기</span>
  <span>수박</span>
  <div>사과</div>
  <p>감</p>
  <h2>오렌지</h2>
</div>
```
___
#Pseudo-Classes

### hover : 선택자 a 요소에 마우스 커서가 올라가 있는동안 선택
```
a:hover {}
```
___
### active : 선택자 a 요소에 마우스를 클릭하고 있는동안 선택
``` 
a:active {}
```
___
### focus : 선택자 input 요소에 포커스되면 (선택되면)
```
input:focus {}
```
___
### first-child : 선택자 .fruits span 이 형제 요소 중 첫째 라면 선택
```
.fruits span:first-child{}
```
___
### list-child : 선택자 .fruits h2 이 형제 요소 중 막내 라면 선택
```
.fruits h2:first-child{}
```
___
### nth-child(n) : 선택자 .fruits 가 형제 요소중 (n) 번 째라면 선택

```
.fruits *:first-child{2}
```
___
# Pseudo-Elements

### before : 선택자 ABC 요소의 내부 앞에 내용을 삽입
### after : 선택자 ABC 요소의 내부 뒤에 내용을 삽입
___
# Attribute 

### 속성을 선택 : [typy="password"]
```
<input type="password" value="aaa">
```
