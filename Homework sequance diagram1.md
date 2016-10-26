#การบ้าน 
Sequance diagram1
Code
```
@startuml

title Facebook

User -> Websitfacebook : Register
Websitfacebook -> System : Send information
System -> User : ID and Password
User-> Websitfacebook : Login

Websitfacebook -> System : information verification

Websitfacebook -> Websitfacebook : [fault] Enter new code 
Websitfacebook -> System : information verification
System -> Websitfacebook : Go to Profile

@enduml
```
<img src="http://www.plantuml.com/plantuml/img/dP2z2i9048JxVOfz0LyWXQJm1y4YA68X5fTaBonURk5kO_3jFM90CS72TcTsFcRog2Perpe0PNM46rDHAN83E4KAk5ZYcSh8QiSxPdYWXgDIW2ybUO-F9BJ9SoHV8tiheJNAuc5KacV8pN2tGfCyXOcnbr0Fk3dQNXhsy8lrWS4x1RPSlPWpJvFuYpMTqokkVMg4ddgif2RyY_VkEC5i1LMm26BP4K2UvacZFm40">

Sequance diagram2
Code

```
@startuml

title Computer Word

Com -> Keyboard : command
Keyboard -> Word :Type the Characters 
Word -> Com : Show
Com -> Keyboard : PressKey
Keyboard -> Print : [Ctrl + P]
@enduml

```
<img src="http://www.plantuml.com/plantuml/img/ROwz2i9048JxVOhfnHUuGW8fRGuKBCJYp2rSu7x2tWR9sxkn40JBcM_ucA5h45rB9j9PCsDiPLcL1RScaSWYZYUSUNks814EKoibr4ZVol2-XRjk2qEJELAGC9caWpx89hl8uPBQwu_J2_Tk-KVgPQvgy3wgP1pW7pHmZVRr3G00">

Sequence diagram 3 
Code 

```
@startuml

title Hotel

Customer -> Service : ask information
Service -> Customer : Welcome
Customer -> Service : Check in 
Service -> Computer : information verification 
Computer -> Service : Room
Service -> Customer : explain
Customer -> Service : Ok pay money
Service -> Customer : Give key to Customer
Customer -> Room : Go to room 
Customer -> Service : Check out
Customer -> Service : Give key to Service
Service -> Room : cleaning
@enduml
```
<img src="http://www.plantuml.com/plantuml/img/VL4x3i8m3Drp2b-02tH0bJh0XWG3SnHSi9h4LUfKxUr9e5Jj4BOy-_sir8Fe8D5PfOJ48fnPC84c3i8E0noESCCmaa6eG0yTa6yvE2t4NlqsYRGAAhYZDUbPy6XUQB8BxDJi-YWVzSOVHWpKala2jP9sVbTcLoY2Ksyr-KAHImUzdi6nnxbWSA8HeSCPXDVnpYs7PnvdHiZWxzKSfR3V9YtJRQSbnrZKdlnJrUWVwTFU">

Sequence diagram 4 
Code 
```
@startuml

title Electric Train

Customer -> Service : Buy Ticket
Service -> Customer : Call stations
Customer -> Service : Pay Money
Service -> Customer : Give Ticket
Customer -> TheCheckCard : check card
 TheCheckCard -> Customer : Get Card
 Customer -> Train : Go to Train
 Train -> Train : Open - Close the door
 Train -> Station : Stop
 Train -> Train : Open - Close the door
 Customer -> TheCheckCard : check card
TheCheckCard -> TheCheckCard : Store cards
@enduml

```
<img src="http://www.plantuml.com/plantuml/img/ZP512eCm44NtESLSe1TmKQIXT5LQq0k4E60mPcGo2jw-qMfHeU0kC__nXa_oA8QbRxrIuiGZt3rQOMUXPEE2KhgFGYqoNAvG80_E8cHmwqSedMrGrBfC-O_DG1ll8Rd5KOX_96ypmfC2ZdyS3pVWUcLhA6lKDTf66wuIPgSts3IeVNImeO2UePrhQZcb149BvsMvILyTfXcqfuWWDK95n1kk-1PDP27KdHUSQtKiTI3JISQPZ2h7KANF_000">

Sequence diagram 5 
Code 
```
@startuml

title Microwave

Mom -> Microwave : Open 
Mom -> Microwave : Food
Mom -> Microwave : Close
Mom -> Timer : Time
Timer -> Microwave : set time
Microwave -> Microwave : Food Time
Timer -> Microwave : Full time
Microwave -> Mom : Bell 
Mom -> Microwave : Open
Mom -> Microwave : get food
Mom -> Microwave : Close

@enduml

```

<img src="http://www.plantuml.com/plantuml/img/SoWkIImgAStDuU8goIp9ILNmpKmkoYzFB4lbulBDprNGjKE8A5Wf-1UavYbWat3Bpq_19kwSar-S2fC8oSnDBG8AWcWk20TDUN5gYK89I1OXYCKYF0QubURaO3C1w00h1QTKe2GkRs4JJmSw9mslpxWSKlDIWC470000">
