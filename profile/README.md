## AddForYou



![image](https://user-images.githubusercontent.com/96874318/223017193-3f18c09b-eb92-405b-b1dc-aa6e029482fe.png)


## 🧑🏼‍💻 소개

지금 이순간에도 수천만명의 사람이 YouTube 플랫폼을 이용합니다. <br>
YouTube 는 다양한 컨텐츠를 제공하며 인종,성별, 국적 어느 것도 상관 없이 지구촌에 YouTube 를 이용하는 이용자라면 누구든지 이어줍니다. <br>
YouTube 의 **'엔진'** 역할을 하는 유튜버(YouTuber) 는 자신이 제작한 영상을 업로드하고 해당 영상은 시청자에게 유익하고 재밌는 컨텐츠로 전달됩니다. <br>
이때 유튜버는 회사로부터 특정 제품의 광고를 받고 상업적인 목적으로 광고를 업로드 하여 자신의 구독자들에게 제품을 소개합니다.

바쁜 하루를 살아가는 현대인들에게 이러한 광고 컨텐츠는 놓치지 쉬운 컨텐츠가 될 수 있습니다. <br>
만약 해당 광고 컨텐츠가 정말 필요로 하는 제품이였다면 정말 아쉽겠죠? 😅 <br>
`AddForYou` 서비스는 현대인들을 위해 자신이 관심있어하는 유튜버 혹은 제품의 광고를 한눈에 검색할 수 있으며 알람 서비스를 받아볼 수 있습니다. <br>
`AddForYou` 서비스를 이용하여 삶의 질을 향상시켜보세요! 🔥




<br>

## 👩🏼‍💻 팀원 소개

<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/choidongkuen"><img src="https://avatars.githubusercontent.com/u/96874318?v=4" width=100px; alt=""/><br /><sub><b>BE 팀원 : 최동근 </b></sub></a><br /></td>
      <td align="center"><a href=""><img src="https://user-images.githubusercontent.com/96874318/223997059-25b33b01-e502-4e2f-925e-29bf00509f8b.jpeg" width="100px; alt=""/><br /><sub><b>FE 팀원 : 유안지 </b></sub></a><br /></td>
    </tr>
  </tbody>
</table>
        
       
<br>
        
        
 <hr>
        
##  ✒️ 브랜치 전략 : Git Flow 전략
        
- Git Flow 전략을 따르되, Develop, Feature, Hotfix 브랜치로 운영합니다.
- develop 브랜치를 Default 브랜치로 운영합니다.
- develop 브랜치에서 기능 단위의 feature 브랜치를 생성합니다.
- feature 브랜치의 이름은 feature/이슈 번호로 합니다.
        
ref : https://velog.io/@choidongkuen/Git-Git-Flow%EA%B9%83-%ED%94%8C%EB%A1%9C%EC%9A%B0-%EB%9E%80
 
<hr>
     
        


## ✏️ 커밋 컨벤션 : 유다시티 스타일의 커밋 메세지 컨벤션

유다시티 스타일의 커밋 메세지는 크게 **제목, 본문, 꼬리말** 세가지 파트로 나뉩니다.
또한 각 파트는 빈줄을 두어서 구분합니다 🧑🏼‍💻

> type : subject (제목) <br>
> <br>
>  body : (본문) <br>
> <br>
> footer : (꼬리말)<br>

- type : 어떤 의도로 커밋했는지를 type 에 명시합니다.
- subject : 최대 50글자가 넘지 않도록 하고 마침표는 찍지 않습니다. 
영문으로 표기하는 경우 동사(원형)을 가장 앞에 두고 첫 글자는 대문자로 표기합니다.
- body : 긴 설명이 필요한 경우에 작성합니다. 무엇을 왜 했는지를 중점으로 작성합니다.
최대 75자를 넘기지 않도록 합니다.
- footer : issue tracker ID를 명시하고 싶은 경우에 작성합니다.


#### ✏️ 제목은 어떻게 작성하는가?

#### 📕 타입(Type) 
👉 어떤의도로 커밋했는지는 타입에 명시합니다. 
유다시티에서는  7개의 타입 중 하나로 쓸 것을 권장 합니다.

|타입 이름| 설명 |
|:--:|:--:|
|feat|새로운 기능 추가|
|fix|버그 수정|
|docs|문서 수정|
|style|들여쓰기, 세미 콜론등을 변경하였을때|
|refactor|코드 리팩토링을 했을 때|
| test | test 코드의 작성 및 수정이 이루어졌을 때|
| chore | 외부 라이브러리 임포트 등의 작업을 완료했을 때 |


#### 📕 제목(Subject)
👉 타입 : 제목 형식으로 사용합니다.
 앞에서 설명한 바와 같이 대문자로(영어인 경우) 시작하는 명령형 문장이며 50자를 넘지 않도록 합니다. 
또한, 개조식 구문으로 작성합니다 -> 완전한 서술형 문장 x

> Feat[type] : 추가 조회 메소드 추가[subject]

<hr>

#### ✏️ 본문은 어떻게 작성하는가?

👉 본문은 한 줄 당 72자 내로 작성합니다.
👉 본문 내용은 제목과 달리 양에 구애받지 않고 최대한 상세히 작성합니다.
👉 무엇을 왜 변경했는지를 설명합니다.


> Feat[type] : 추가 조회 메소드 추가[subject]
> < 한줄 띄우고 >
> 로그인 API 개발[body]

<hr>

#### ✏️ 꼬리말은 어떻게 작성하는가?

👉 꼬리말은 선택 사항이고 이슈 트래커 ID 를 작성합니다.
👉 꼬리말은 "유형 : # 이슈 번호" 형식으로 사용합니다.
👉 여러 개의 이슈 번호를 적을 때는 쉼표(,) 로 구분합니다.
 
| 이슈 트래커 유형| 설명|
| --- | --- |
| Fixes | issue 수정중( 아직 해결 안됨 )
| Resolves| issue 해결 완료 |
| Ref | 참고할 issue 존재 시 |
| Related to | 해당 커밋에 관련된 이슈 번호( 아직 해결 안됨 )

> Feat[type] : 추가 조회 메소드 추가[subject]
> 
> 로그인 API 개발[body]
> 
> Resolves: #123 [footer]
> Ref: #456
> Related to : #100 
        
#### ref : https://velog.io/@choidongkuen/Git-%EC%BB%A4%EB%B0%8B-%EC%BB%A8%EB%B2%A4%EC%85%98-%EC%9C%A0%EB%8B%A4%EC%8B%9C%ED%8B%B0%EC%9D%98-%EC%8A%A4%ED%83%80%EC%9D%BC
