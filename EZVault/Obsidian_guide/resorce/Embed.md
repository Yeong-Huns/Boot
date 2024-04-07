```plantuml
title 일상 생활

actor 와이프 as user

box "나"
participant 집 as home
participant 회사 as company
end box

user -> home : 일해라
home -> home : 출근 준비
home -> company : 출근
note right
	8시간
end note
company --> home : 퇴근
home --> user : 밥줘

```




```plantuml
class example{
	- String name
	- int age
	..Getter..
	+ getName()
	+ getAge()
}
abstract abstract 
abstract class "abstract class"
example<|--abstract



```
^myBlock
