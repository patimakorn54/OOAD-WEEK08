# OOAD-WEEK08 นายปฏิมากร บุญเปลี่ยน 57030190

ส่งการบ้าน USE CASE Diagram

ภาพที่ 1 ดูทีวีและทานอาหาร
```
Code
```
```
@startuml
:Patimakorn: --> (Watch Television)
:Patimakorn: -> (Eat Food)
@enduml
```





ภาพที่ 2 การพิมพ์เอกสาร
```
Code
```
```
@startuml
:Patimakorn: -left-> (Upload File Data) 
:Patimakorn: -right-> (Search Data From Internet) 
:Patimakorn: -up-> (Print Data)
:Patimakorn: -down-> (Copy Data for Edit in word)
@enduml
```



ภาพที่ 3 ร้านกาแฟ
```
Code
```
```
@startuml
left to right direction
skinparam packageStyle rect
actor Cashier
actor Customer
actor Barista
rectangle Cafe {
  Customer --> (Order Coffee)
  Cashier --> (Order Coffee)
  Cashier --> (Tell Order Coffee)
  Barista --> (Tell Order Coffee)
  Barista --> (Make Coffee)
  Barista --> (Give Coffee to Cashier)
  Cashier --> (Give Coffee to Cashier)
  Cashier --> (Pay For Coffee)
  Customer --> (Pay For Coffee)
  
}
@enduml
```


ภาพที่ 4 วงดนตรี
```
Code
```
```
@startuml
'default
top to bottom direction
user1 --> (Vocal)
user2 --> (Play Guitar)
user3 --> (Play Bass)
user4 --> (Play Drum)

@enduml
```
![]


ภาพที่ 5 เล่นกีฬา
```
Code
```
```
@startuml
:user: --> (Play Tennis)
:user: -> (Drink Water)
@enduml
```
![]

