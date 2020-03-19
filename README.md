# AIIA Lab 주간 목표 관리 ⚡️
개인별 주간 목표를 설정하고 관리하도록 합니다. 서로 부족한 부분을 알아보고 도와줄 수 있습니다. Github에서 제공하는 Project management 관련 기능을 적극 활용합니다!

## 1. Issue ‼️
* 개인별 계획을 작성하고 진행 상황은 스레드로 관리합니다.
* 계획의 추가/변경/진행에 대한 기록을 comment를 통해 남깁니다.
## 2. Milestone 🏁
* 주간 일정은 Milestone으로 관리됩니다.
* Milestone은 매 주 월~금을 기준으로 합니다.

# FAQ
* Q1. 왜 Github 이슈를 사용해야 하죠? 적응하기 불편해요
  * A. Github의 프로젝트 관리 도구는 웹 접근성 뿐만 아니라 이미 수 많은 프로젝트 진행으로 증명된 되었으며 주간 계획과 같은 주기적인 과업 관리에도 알맞습니다. 따라서 적응하기 불편한 것은 익숙하지 않아서 입니다. 잠시 마음을 열고 딱 두 번만 해보시면 잘 사용할 것입니다. 시도 할 가치가 있습니다 도전하세요!
* Q2. 이슈에 라벨은 왜 붙여야 하죠?
  * A. 라벨은 색으로 잘 구분되기 때문에 이슈에 붙어있는 색으로 이슈를 올린 사람을 쉽게 구분할 수 있습니다. 또한 Github에서는 라벨별 검색을 지원하기 때문에 추후 자료 찾기에 유용합니다.
* Q3. 계획 진행 대한 모든 기록을 남겨야 하나요?
  * A. 개인에 따라 다릅니다. 세세히 남기는 분도 있을 것이고, 자료를 만들어 업로드 하시는 분들도 있을 것으로 보입니다. 다만 주간 계획 공유의 목적에 맞춰 주시면 될 것 같습니다.
* Q4. [TODO] TBU

# 사용 Guide 📜
사용 가이드를 잘 읽어주시고 양식에 맞춰 사용해 주세요. 통일된 양식은 인지적인 피로를 낮춰줘서 효율적으로 내용을 탐색할 수 있도록 도와줍니다. 이렇게 조금씩 시간을 아껴봐요.☀️

## 1. 주간 계획의 Lifecycle
### 1. 주간 계획의 수립시
> RULE: 다음 주의 주간 계획은 이번 주 금요일 저녁까지 작성합니다.
* 다음 주의 주간 계획은 본인이 새로운 Issue를 생성한 후 작성합니다.
* Issue의 제목은 아래와 같은 형식을 유지해야 합니다.
  * 이름 [시작YYMMDD]~[종료YYMMDD]
  * 예) 홍길동 200101~200106
* 생성한 Issue는 오른쪽 탭에서 해당 주차의 Milestone을 지정해야 합니다.
  * 만일 해당 주차의 Milestone이 아직 생성되지 않은 경우 생성한 후 지정합니다.
* 새로운 Issue는 미리 설정된 양식에 맞추어 작성합니다.
#### < 작성 예시 >
  * 제목 : 홍길동 200101~200106
    * 내용 : (양식에 따라 작성), 마일스톤과 라벨 Check; 라벨은 모아보기를 위해서 사용
* ![이슈 작성](https://user-images.githubusercontent.com/32090903/77050492-35536b80-6a0d-11ea-904d-e1c506a04945.png)


### 2. 주간 계획 진행시
> RULE: 
* 계획 진행에 따라 Comment를 통해 상황을 기록합니다.
#### < 작성 예시 >
* Comment : (요일) (작업내용) 완료
* ![이슈 진행에 따른 코멘트](https://user-images.githubusercontent.com/32090903/77050583-54ea9400-6a0d-11ea-82bf-94bcade96f35.png)
* 기타 사항 : 
    1) 할일이 미뤄진 경우 : 사유을 적을 것 (완료한뒤에 Close)
    2) 시행불가인 경우 : 사유을 적을 것 (그대로 Close 가능)
    ~~~
    목표에 대한 책임감을 위해 할일을 모두 완료해야만 Close하는 걸로 정했음. 
    필치못할 사정은 제외함.
    ~~~
* ![image](https://user-images.githubusercontent.com/32090903/77051126-21f4d000-6a0e-11ea-8eba-0f3638d2764b.png)

### 3. 주간 계획 완료시
> RULE: 이슈의 close는 자기 스스로 합니다.
* 주간 계획을 모두 완료하는 경우 다음과 같은 Comment를 남긴 후 해당 이슈를 Close 합니다.
  * "모든 주간 계획을 완료하였으므로 이 이슈를 close 합니다"
* 주간 계획을 모두 완료하지 못하는 경우 상황을 설명하는 Comment를 남긴 후 해당 이슈를 Close 합니다. 아래는 예시입니다.
  * "구현 작업을 계획하였으나 문서 작업에 투입되며 완료하지 못했음. 다음 주차 계획에 반영하여 마무리하겠음. 따라서 이 이슈를 close 합니다"

## Ref. 마일스톤 생성/Close
 * 누구나 쉽게 생성하고 Close시킬수 있기 때문에 주간계획을 먼저 올리는 사람이 시행합니다
 
 * Issue -> Milestones -> New milestorne/Close
![image](https://user-images.githubusercontent.com/32090903/77047754-a2b0cd80-6a08-11ea-9ab1-0212580e08d2.png)
![image](https://user-images.githubusercontent.com/32090903/77047891-df7cc480-6a08-11ea-9b8f-399c7a8042e5.png)