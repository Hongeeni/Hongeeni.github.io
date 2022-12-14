# 프로젝트명 : Mirroring (개발자 : 윤홍인)

<br><br>

## [목차]
### 1. [컨셉](#1)
### 2. [관련 이미지 & 동영상](#2)
### 3. [대표 이미지](#3)
### 4. [컨셉 & 대표 이미지 기반 작품 묘사](#4)
### 5. [Mirroring 구성 요소](#5)
### 6. [게임 시스템 디자인](#6)
### 7. [개발 요구사항 & 흐름도](#7)
### 8. [스토리보드](#8)
### 9. [프로토타입 개발 요구사항 (6주 개발)](#9)
### 10. [프로토타입 개발작업 일정 (6주 개발)](#10)

<br>

***
***

<br><br>

## [컨셉]<a name='1'></a>
### 메인컨셉 :: 불확실성
- 러브크래프트는 인간의 뇌가 불확실한 것에 대해 취약하다는 것을 알고 있었고 그는 "가장 오래되고 강력한 두려움은 미지의 것에 대한 두려움"이라고 말했습니다.
불확실성에 대한 공포가 인간이 경험하는 모든 공포의 근본적인 원인 이라는 것을 토대로 게임의 분위기를 형성하여 플레이어로 하여금 알 수 없는 불안감에서 오는 공포를 경험할 수 있는 게임을 제작하고자 합니다.

### 서브 컨셉 1 :: 정보
- 완벽하지 않은 정보는 때로 난항을 격게 만드는 원인이 되기도 합니다. 게임 진행에 중요하게 작용하는 스토리 혹은 기믹의 정보를 부분적으로만 플레이어에게 제공하여 메인 컨셉을 보조하는 역할을 할 것입니다.

### 서브 컨셉 2 :: 충격
- 게임 진행에 따라 알게 되는 게임의 스토리로 하여금 플레이어에게 새로운 충격을 주어 흥미를 유발할 수 있도록 할 것입니다.

### 서브 컨셉 3 :: 의미
- 플레이어가 불확실성에서 벗어나기 위해 수행하는 행동에 의미를 부여하여 게임의 분위기를 자연스럽게 형성할 수 있도록 할 것입니다.

### 서브 컨셉 4 :: 성찰
- 사회적 문제나 평소 도덕성과 이익의 갈등 등 다양한 문제들을 게임 속에 내포하여 플레이어로 하여금 스스로의 행동에 대해 성찰할 수 있는 기회를 제공할 것입니다.

### 서브 컨셉 5 :: 희열
- 플레이어가 문제를 해결했을 때, 희열을 느끼고 다음 챕터로 넘어갈 수 있는 원동력을 제공할 것입니다.

<br><br>

## [관련 이미지 & 동영상]<a name='2'></a>

- 이미지  
  ![게임 컨셉 이미지](./img/게임컨셉이미지_01.jpg)
  
  <br>
  
- 동영상
  [![동영상 미리보기 이미지](./img/게임컨셉이미지_02.png)](https://youtu.be/YKe3znDCEMY)

<br><br>

## [대표 이미지]<a name='3'></a>

![게임 대표 이미지](./img/게임플레이이미지_02.png)

<br><br>

## [컨셉 & 대표이미지 기반 작품묘사]<a name='4'></a>

> ### 시작 화면 :
> - 전체적으로 어둡게 화면을 구성하여 플레이어에게 공포감을 주고 있습니다.
> - 좌측 하단에는 게임의 조작법을 볼 수 있게 하였고 우측 하단에는 게임을 시작하는 버튼과 게임을 종료하는 버튼을 두어 사용자의 선택에 의해 게임이 시작될 수 있도록 하였습니다.
> - 현재 상황에서 'ESC'키를 사용하여 사용자 메뉴를 이용할 수 있습니다.
![시작 화면 이미지](./img/시작화면.png)

<br>

> ### 게임 화면 :
> - 전체적으로 UI를 최소화하여 사용자가 게임의 상황에 쉽게 몰입할 수 있는 환경을 조성하였습니다.
> - 좌측 단에 현재 플레이어가 소지한 아이템이 표시됩니다.
> - 'ESC'키를 이용하여 사용자 메뉴를 이용할 수 있습니다.
> - 마우스를 이용하여 플레이어 캐릭터의 시아를 변경하며, 'F'키를 이용해 사물과 상호작용 할 수 있습니다.
![게임 화면 이미지 1](./img/게임플레이이미지_01.png)
![게임 화면 이미지 2](./img/게임플레이이미지_02.png)

<br>

### 게임 진행에 적용된 컨셉 :

> 주인공이 침대에서 일어나면서 게임이 시작됩니다. 그리고 침대 옆에 있는 거울을 보았습니다. 거울에 비친 자신의 모습과 방 안이 보입니다.

- 서브컨셉_정보, 서브컨셉_의미, 메인컨셉_불확실성

> 창문과 침대 사이의 서랍 위에는 기괴한 피아노 건반 사진이 올려져 있습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 메인컨셉_불확실성

> 그리고 그 서랍은 열쇠로 잠겨 열리지 않습니다. 창문 반대편에는 책상과 금고, 책장이 있습니다.

- 서브컨셉_정보

> 책상 위에 작은 상자를 발견하고 상자를 열기 위해 비밀번호가 필요하다는 것을 알게 된 주인공은 단서를 찾습니다.

- 서브컨셉_정보, 서브컨셉_의미

> 주변을 훑어보던 중 책상 서랍 안에 일기장의 한 페이지를 발견합니다. 그곳에는 고통스러운 일기가 적혀있었습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 메인컨셉_불확실성

> 다음으로 책장을 확인해보니 주인공이 다녔던 고등학교의 2018년 졸업 앨범이 있었습니다.

- 서브컨셉_정보, 서브컨셉_의미

> 졸업 앨범을 보던 중 앨범에서 일기장의 일부분이 또 나왔습니다. 이곳에도 마찬가지로 고통스러운 일기의 내용이 적혀있습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 서브컨셉_희열, 메인컨셉_불확실성

> 하지만 아직 상자의 비밀번호를 알 수 있는 단서는 없는 것 같아서 주변에 아직 보지 않은 물건이 있는지 확인합니다. 주인공은 문 옆에 커다란 액자를 발견하고 액자를 건드렸습니다.

- 서브컨셉_정보

> 액자가 떨어지자 그 뒤에는 알 수 없는 문양이 있었습니다.

- 서브컨셉_정보, 서브컨셉_의미, 메인컨셉_불확실성

> 주인공은 이 문양을 보고 피아노의 건반 사진이 떠올라 피아노 건반 사진에 쓰여있는 숫자와 문양의 모양을 맞추어 비밀번호(9608)를 입력합니다.

- 서브컨셉_정보, 서브컨셉_희열, 메인컨셉_불확실성

> 비밀번호를 입력하니 책상 위에 상자가 열리고 그 안에서 작은 열쇠가 하나 나옵니다.

- 서브컨셉_정보,서브컨셉_희열, 메인컨셉_불확실성

> 그 열쇠로 방안에 열쇠를 넣을 수 있는 구멍에 넣어 보던 중 침대 옆에 서랍이 열리게 되고 그 안에서 입학식 날에 관한 이야기가 쓰여있는 일기장을 발견합니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 서브컨셉_희열, 메인컨셉_불확실성

> 책장의 졸업 앨범과 서랍 안의 입학식 일기, 금고에 붙어있는 메모지를 본 주인공은 금고에 입학식 년도(2015)를 입력하자 금고가 열리고 그 안에 열쇠가 모습을 보였습니다.

- 서브컨셉_정보, 서브컨셉_의미, 서브컨셉_희열, 메인컨셉_불확실성

> 주인공은 그 열쇠로 방문을 열어 다음 방으로 넘어갑니다.

- 서브컨셉_희열

> 그리고 충격적인 사실을 알게 됩니다. 처음 침대 옆에 창문은 밖이 아니라 그림을 사이에 둔 창문이였고 그 반대편에는 첫 번째 방을 확인할 수 있는 공간(두 번째 방)이 있었던 것 이였습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 메인컨셉_불확실성

> 주인공은 두 번째 방을 탈출하기 위해 방을 훑어보던 중 창문 앞 책상 위에 나침반과 "죽어버려"가 적힌 종이 그리고 소파를 발견합니다.

- 서브컨셉_정보, 서브컨셉_의미, 메인컨셉_불확실성

> 곧바로 소파에 가까이 가서 밀어보니 소파 밑에서 일기장의 일부분을 찾게 됩니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미,서브컨셉_성찰, 메인컨셉_불확실성

> 그리고 일기장의 내용 중 “오른쪽”의 부분이 빨간색 볼 팬으로 쓰여져 있는 것을 본 주인공은 책상 위에 있는 나침반을 보고 동쪽 벽에 있는 책장을 옆으로 밀게 됩니다.

- 서브컨셉_정보, 서브컨셉_의미, 서브컨셉_희열, 메인컨셉_불확실성

> 책장을 밀자 금고가 하나 나왔고 첫 번째 방에 있던 금고의 비밀번호가 입학식 년도(2015)였던 것을 떠올려 졸업식 년도(2018)를 입력합니다.

- 서브컨셉_정보, 서브컨셉_의미, 메인컨셉_불확실성

> 그러자 금고의 문이 열리고 안에는 열쇠와 누군가에 의해 찢어진 신문의 일부분이 보입니다.

- 서브컨셉_정보, 서브컨셉_의미

> 신문에 내용을 본 주인공은 지금에 상황이 왕따를 당한 피해자가 복수를 하는 상황임을 인지하게 됩니다. 주인공은 혼란스러운 감정을 추스르며 열쇠가 들어갈 구멍을 찾기 위해 다시 주변을 둘러보기 시작합니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 메인컨셉_불확실성

> 밀려져 있는 책장 옆에 작은 서랍을 발견한 주인공은 서랍에 열쇠를 넣어봅니다.

- 서브컨셉_희열

> 열쇠가 열리고 서랍 안에는 알 수 없는 문제가 있었습니다. 첫 번째 방 침대 서랍의 힌트와 두 번째 방의 "죽어버려"가 적힌 종이를 보고 문제 풀고 방 문의 비밀번호를 알아냅니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 메인컨셉_불확실성

> 두 번째 방의 강철로 된 문이 열리고 복도가 보입니다. 바로 보이는 복도에는 두 개의 방이 있고 각 방에는 화병(花甁)이 두 개씩 있습니다. 왼쪽으로 뻗은 복도에도 두 개의 문이 있고 주인공과 가까운 방의 문은 잠겨서 열리지 않습니다.

- 서브컨셉_정보, 메인컨셉_불확실성

> 가장 안쪽의 방의 문을 열자 바닥에는 피가 묻어있는 무언가를 덮은 천과 깨끗한 천이 섞여서 나열 되어 있습니다. 그리고 가장 안쪽에는 금고가 하나 있습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 메인컨셉_불확실성

> 방에 무언가 덮여있는 피 묻은 천 위에는 주인공의 이름과 주인공의 고등학교 동창들의 이름이 적혀 있습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 메인컨셉_불확실성

> 두 번째 방의 신문과 천들을 보고 금고를 열었더니, 금고 안에는 붉은 열쇠와 일기장이 있습니다. 주인공 붉은 열쇠로 잠겨있던 복도의 문을 열었습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 서브컨셉_희열, 메인컨셉_불확실성

> 방 안에는 책상이 있고 책상 위에는 일기장, 문제가 적힌 종이, 그리고 네 송이의 색이 다른 꽃이 있습니다.

- 서브컨셉_정보, 서브컨셉_충격, 서브컨셉_의미, 서브컨셉_성찰, 메인컨셉_불확실성

> 책상 위에 문제를 보고 주인공은 꽃을 각각 위치에 맞게 화병에 옮기니, 방 밖에서 문이 열리는 소리가 들립니다.

- 서브컨셉_희열, 메인컨셉_불확실성

> 주인공이 방 밖으로 나가보니, 복도의 문이 열려있고 건물 밖이 보입니다.

- 서브컨셉_희열

> 게임이 끝납니다.

<br><br>

## [Mirroring의 구성 요소]<a name='5'></a>

- 모든 일은 자신에게 되돌아 온다.

- 자료 : [게임 구성 요소 PDF](./pdf_data/게임구성요소.pdf)

<br>

### 1. 메커니즘

[도전 과제]

1. 모든 방의 문제를 해결하고 탈출하는 것.
2. 방에 흩어져 있는 정보를 수집하여 주인공이 여기에 오게 된 이유를 파악하는 것.

[재미 요소]

1. 물체와의 상호작용 : 상호작용을 통하여 플레이어가 능동적으로 문제의 힌트
혹은 게임 스토리의 정보를 습득할 수 있도록 하여 탐색의 흥미를 자아냄.
2. 힌트 : 문제의 해결 방식을 유추할 수 있는 힌트 혹은 문제 자체를 힌트의 형식으로
제공하여 플레이어가 방안에 숨겨진 문제들을 찾고 해결할 수 있도록 함.
3. 문제 : 방을 탈출하기 위한 수단으로 하나의 문제를 여러 과정들로 분리하여
게임의 난이도를 높이고 사용자에게 게임의 몰입감을 제공함.
4. BGM 및 효과음 : 현실적인 사운드를 이용하여 사용자에게 현실감을 주어
게임 속 공간에 있는 것 같은 몰입감을 제공함.

<br>

### 2. 이야기

[만들게 된 배경]

개인주의적 성향이 유행하고 있는 현재 사회에서 개인주의와 이기주의를
혼동하여 살아가는 사람들이 많아지고 있고 개인주의와 이기주의의 측면으로
접근하지 않더라도 사회적 동물로써 상호관계 간 최소한의 배려 및 존중조차
하지 않는 잘못된 이념이 문제없이 적용되고 있는 단체들이 존재한다.
주변에서 흔하게 볼 수 있는 예시로써 왕따 문제가 있다.
우리는 게임을 통해 원활하고 완만한 인간관계가 서로 간의 존중과
배려에서 비롯하고 자신의 사소한 행동이 때로는 상대방에서 정신적,
신체적으로 크게 영향을 끼칠 수 있다는 경각심을 게임을 통해 상기시키고자
한다.

[참신함]

- 주변에서 실제로 일어나고 있는 사회적 문제를 주제로 하여
플레이어에게 문제의식을 상기시킴.

- 스스로의 행동에 대하여 성찰하는 기회를 제공하여
게임의 의미와 깊이를 더함

[카메라 관점]  

1. 1인칭 시점을 채택하여 플레이어에게 몰입감과 현실감을 제공함.
2. 화면 UI를 간소화하여 플레이어가 게임 속 상황에 몰입할 수 있는 환경을 제공함.
3. 좌측 하단에 플레이어가 획득한 아이템을 아이콘으로 보여주어 시각적으로 확인할 수 있도록 함.

<br>

### 3. 미적요소

[디자인]

캐릭터 : 주변에서 볼 수 있는 건장한 20대 남성의 모델을 사용.

오브젝트 : 현실에 실제로 존재할 것 같은 디자인의 물건(책장, 탁자, 액자, 시계) 모델을 사용.

상호작용 : 물체들의 중력작용과 캐릭터의 움직임 등이 현실성 있게 작용하여 실제처럼 구현.

[컬러]

캐릭터 : 대한민국 20대 남성을 모티브로 하고 있으므로 살구색 피부의 검정머리 남성으로 구현.

오브젝트 및 주변환경 : 허름한 집, 정리가 안된 창고의 분위기를 자아내기 위해 어둡고 얼룩진 색상으로 표현.

[음향]  

캐릭터 : 걷거나 상호작용할 때, 무겁고 둔탁한 음향을 사용하여 으스스한 분위기 조성.

오브젝트 및 주변환경 : 바람이 새는 소리와 물건이 떨어지는 소리, 문이 천천히 열리는 소리 등 으스스한 분위기를 조성할 수 있는 음향을 활용.

<br>

### 4. 기술

1. 물체의 상호작용에 물리엔진을 적용하여 현실적인 물체의 움직임을 구현.
2. 음향의 싱크를 맞춰 캐릭터와 물체의 움직임에 현실성을 더함.

<br><br>

## [게임 시스템 디자인]<a name='6'></a>

### 1. 게임 오브젝트 분해

|번호|오브젝트 이름(영문이름)|이미지|
|:---:|:---:|:---:|
|1|AdmissionPhoto|![입학식_이미지](./img/AdmissionPhoto.jpg)|
|2|GraduatePhoto|![졸업식_이미지](./img/GraduatePhoto.jpg)|
|3|Bed|![침대_이미지](./img/Bed_Obj.png)|
|4|MagicMirror|![매직미러_이미지](./img/MagicMirror_Obj.png)|
|5|Drawer_1, Drawer_2|![서랍_이미지](./img/Drawer_Obj.png)|
|6|PictureOfPiano|![더러운피아노건반_이미지](./img/piano_blood.png)![깨끗한피아노건반_이미지](./img/piano_number.png)|
|7|HintPaper|![힌트_이미지](./img/PaperHint.PNG)|
|8|Table|![책상_이미지](./img/Table_Obj.png)|
|9|Safe_1, Safe_2|![금고_이미지](./img/Safe_Obj.png)|
|10|BookShelf_1, BookShelf_2|![책장_이미지](./img/BookShelf_Obj.png)|
|11|LittleBox|![작은상자_이미지](./img/LittleBox_Obj.png)|
|12|Diary_1, Diary_2, Diary_3, Diary_4|![일기장1_이미지](./img/Diary_1.png)![일기장2_이미지](./img/Diary_2.png)![일기장3_이미지](./img/Diary_3.png)![일기장4_이미지](./img/Diary_4.png)|
|13|AlbumOfGraduation|![졸업앨범_이미지](./img/Album_Obj.png)|
|14|Frame|![액자_이미지](./img/Frame_img.png)|
|15|KeyOfDrawer_1, KeyOfDrawer_2, RoomKey|![열쇠_이미지](./img/Key_img.png)|
|16|Door, IronDoor|![첫번째방_문](./img/Door_Obj.png)![두번째방_문](./img/IronDoor_Obj.png)|
|17|Compass|![나침반_이미지](./img/Compass_img.jpg)|
|18|Sofa|![소파_이미지](./img/Sofa_Obj.png)|
|19|Newspaper|![신문_이미지](./img/NewsPaper.png)|
|20|QuestionPaper|![문제_이미지 1](./img/PaperQuiz.png)![문제_이미지 2](./img/PaperQuiz02.png)|
|21|DeadBodyCloth|![시체 이미지](./img/DeadBody_img.png)|
|22|Vase|![검은 화병 이미지](./img/Vase1_img.png)![흰 화병 이미지](./img/Vase2_img.png)|
|24|Flower|![빨간꽃 이미지](./img/빨간장미.png)![노란 꽃 이미지](./img/노란장미.png)![파란 꽃 이미지](./img/파란장미.png)![하얀 꽃 이미지](./img/하얀장미.png)|

<br>

***

<br>

### 2. 플레이어 캐릭터 속성 (파라미터)

|속성|영문 명칭|설명|비고|
|:---:|:---:|:---:|:---:|
|캐릭터 이동속도|PlayerSpeed|플레이어 캐릭터의 이동속도 값을 설정합니다.||
|카메라 회전속도|RotateSpeed|플레이어의 카메라 회전속도 값을 설정합니다.||
|소지품|Items|플레이어가 소지한 아이템의 리스트를 저장합니다.||
|클리어 스테이지|Clear Stage|플레이어가 클리어한 있는 스테이지를 저장합니다.||
|클리어 확인|Clear Check|플레이어가 현재 진행하고 있는 스테이지의 목표를 달성했는지 확인합니다.||

<br>

***

<br>

### 3. 오브젝트 속성 (파라미터)

#### 1) 오브젝트 이름 : 문 Door

|속성|영문 명칭|설명|비고|
|:---:|:---:|:---:|:---:|
|잠금 확인|OpenDoor|문이 현재 열 수 있는 상태인지 확인합니다.||

#### 2) 오브젝트 이름 : 금고 Safe

|속성|영문 명칭|설명|비고|
|:---:|:---:|:---:|:---:|
|잠금 확인|OpenSafe|금고가 현재 열 수 있는 상태인지 확인합니다.||

#### 3) 오브젝트 이름 : 책상 Table

|속성|영문 명칭|설명|비고|
|:---:|:---:|:---:|:---:|
|잠금 확인|OpenTable|책상의 서랍이 현재 열 수 있는 상태인지 확인합니다.|열쇠가 필요한 책상 서랍과 필요 없는 책상 서랍이 있습니다.|

#### 4) 오브젝트 이름 : 서랍 Drawer

|속성|영문 명칭|설명|비고|
|:---:|:---:|:---:|:---:|
|잠금 확인|OpenDrawer|서랍이 현재 열 수 있는 상태인지 확인합니다.|열쇠가 필요한 서랍과 필요 없는 서랍이 있습니다.|

#### 5) 오브젝트 이름 : 액자 Frame

|속성|영문 명칭|설명|비고|
|:---:|:---:|:---:|:---:|
|낙하 확인|DropCheck|액자와의 상호작용 여부를 저장합니다.|액자는 최초 1회만 상호작용하는 오브젝트입니다.|

<br>

***

<br>

### 4. 플레이어 캐릭터의 행동

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|앞으로 이동|Walk_Forward|플레이어 캐릭터를 앞으로 이동합니다.|
|뒤로 이동|Walk_Back|플레이어 캐릭터를 뒤로 이동합니다.|
|오른쪽으로 이동|Walk_Right|플레이어 캐릭터를 오른쪽으로 이동합니다.|
|왼쪽으로 이동|Walk_Left|플레이어 캐릭터를 왼쪽으로 이동합니다.|
|상호작용 하기|Interaction|'F'키를 눌러 게임 오브젝트와 상호작용합니다.|
|시아 변경|Looking|마우스를 이용하여 시아를 변경합니다.|

<br>

***

<br>

### 5. 게임 오브젝트의 행동

#### 1) 오브젝트 이름 : 첫 번째 방의 문 Door

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|열쇠 확인|DoorKeyCheck|플레이어가 열쇠를 가지고 있는지 확인하고 OpenDoor의 값을 수정합니다.|

#### 2) 오브젝트 이름 : 두 번째 방의 문 IronDoor

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|비밀번호 확인|DoorOpenCheck|플레이어가 입력한 비밀번호가 옳은지 확인하고 OpenDoor의 값을 수정합니다.|

#### 3) 오브젝트 이름 : 금고 Safe

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|비밀번호 확인|PasswordCheck|플레이어가 입력한 비밀번호가 옳은지 확인하고 OpenSafe의 값을 수정합니다.|

#### 4) 오브젝트 이름 : 책상 Table

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|열쇠 확인|TableKeyCheck|플레이어가 열쇠를 가지고 있는지 확인하고 OpenTable의 값을 수정합니다.|

#### 5) 오브젝트 이름 : 서랍 Drawer

|행동|영문 명칭|설명|
|열쇠 확인|DrawerKeyCheck|플레이어가 열쇠를 가지고 있는지 확인하고 OpenDrawer의 값을 수정합니다.|

#### 6) 오브젝트 이름 : 액자 Frame

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|상호작용 확인|InteractionCheck|DropCheck의 값을 확인하고 액자와 상호작용합니다.|

#### 7) 오브젝트 이름 : 열쇠 Key

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|획득 확인|GetKey|열쇠 오브젝트를 게임에서 비활성화하고 플레이어의 소지품 리스트에 추가합니다.|

#### 8) 오브젝트 이름 : 종이 및 사진 오브젝트 Paper or Picture Items

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|상호작용 확인|InteractionCheck|해당 물체와 상호작용 하였을 때, 해당 종이 또는 사진이 플레이어의 화면에 확대되어 표출되도록 합니다.|

#### 9) 오브젝트 이름 : 소파 Sofa

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|상호작용 확인|InteractionCheck|해당 물체와 상호작용 하였을 때, 해당 물체의 위치가 이동하도록 합니다.|

#### 10) 오브젝트 이름 : 첫 번째 방의 책장 First Room BookShelf

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|상호작용 확인|InteractionCheck|해당 물체와 상호작용 하였을 때, 책장 안의 책이 나오고 플레이어 화면에 일기장 이미지가 확대되어 표출되도록 합니다.|

#### 11) 오브젝트 이름 : 두 번째 방의 책장 Second Room BookShelf

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|상호작용 확인|InteractionCheck|해당 물체와 상호작용 하였을 때, 일정 횟수 동안 주인공의 대사가 나오고 이후 책장의 위치가 이동하도록 합니다.|

#### 12) 오브젝트 이름 : 꽃 Flower

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|상호작용 확인|InteractionCheck|해당 물체와 상호작용 하였을 때, 해당 오브젝트가 비활성화 되고 사용자의 인벤토리 UI에 꽃 이미지를 활성화합니다.|

#### 13) 오브젝트 이름 : 화병 Vase

|행동|영문 명칭|설명|
|:---:|:---:|:---:|
|상호작용 확인|InteractionCheck|플레이어가 꽃 아이템을 소지하고 있는 상태에서 해당 물체와 상호작용 하였을 때, 해당 꽃의 오브젝트가 화병에 놓이게 됩니다.|
|정답 확인|AnswerCheck|플레이어가 꽂은 꽃이 해당 화병에 알맞은 꽃인지 확인하여 모든 화병에 알맞은 꽃을 꽂았을 경우, 복도의 문이 열립니다.|


<br>

***

<br>

### 6. 플레이어 캐릭터의 상태

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|모든 상태 중(예외. 상호작용 중)|앞으로 이동합니다.|'W'키를 누릅니다.|
|모든 상태 중(예외. 상호작용 중)|뒤로 이동합니다.|'S'키를 누릅니다.|
|모든 상태 중(예외. 상호작용 중)|오른쪽으로 이동합니다.|'D'키를 누릅니다.|
|모든 상태 중(예외. 상호작용 중)|왼쪽으로 이동합니다.|'A'키를 누릅니다.|
|모든 상태 중(예외. 상호작용 중)|플레이어의 시아를 변경합니다.|마우스를 움직입니다.|
|모든 상태 중|Ray에 맞은 오브젝트와 상호작용합니다.|상호작용 하고자하는 오브젝트에 CrossHair를 두고 'F'키를 누릅니다.|

<br>

***

<br>

### 7. 게임 오브젝트의 상태

#### 1) 오브젝트 이름 : 첫번째 방의 문 Door

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(잠김 상태)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(잠김 상태)|열쇠가 필요하다는 내용의 자막을 표출합니다.|문의 열쇠가 없는 상태에서 문과 상호작용합니다.|
|기본 상태(잠김 상태)|열림 상태|문의 열쇠를 소지한 상태에서 문과 상호작용합니다.|
|열림 상태|기본 상태(잠김 상태)|문이 열려있는 상태에서 문과 상호작용합니다.|

#### 2) 오브젝트 이름 : 두번째 방의 문 IronDoor

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(잠김 상태)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(잠김 상태)|비밀번호가 맞지 않다는 내용의 자막을 표출합니다.|문의 비밀번호를 틀립니다.|
|기본 상태(잠김 상태)|열림 상태|문의 비밀번호를 맞춥니다.|
|열림 상태|기본 상태(잠김 상태)|문이 열려있는 상태에서 문과 상호작용합니다.|

#### 3) 오브젝트 이름 : 금고 Safe

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(잠김 상태)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(잠김 상태)|비밀번호가 맞지 않다는 내용의 자막을 표출합니다.|금고의 비밀번호를 틀립니다.|
|기본 상태(잠김 상태)|열림 상태|금고의 비밀번호를 맞춥니다.|

#### 4) 오브젝트 이름 : 책상 Table

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(잠김 상태)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(잠김 상태)|열쇠가 필요하다는 내용의 자막을 표출합니다.|책상서랍의 열쇠가 없는 상태에서 책상과 상호작용합니다.|
|기본 상태(잠김 상태)|열림 상태|책상서랍의 열쇠를 소지한 상태에서 책상과 상호작용합니다.|

#### 5) 오브젝트 이름 : 서랍 Drawer

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(잠김 상태)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(잠김 상태)|열쇠가 필요하다는 내용의 자막을 표출합니다.|서랍의 열쇠가 없는 상태에서 서랍과 상호작용합니다.|
|기본 상태(잠김 상태)|열림 상태|서랍의 열쇠를 소지한 상태에서 과 상호작용합니다.|

#### 6) 오브젝트 이름 : 액자 Frame

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|떨어짐 상태|액자와 상호작용 합니다.|

#### 7) 오브젝트 이름 : 열쇠 Key

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|플레이어가 획득한 상태(열쇠 오브젝트를 비활성화 합니다.)|열쇠와 상호작용 합니다.|

#### 8) 오브젝트 이름 : 종이 및 사진 아이템 Paper or Picture Items

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|플레이어와 상호작용 중인 상태|해당 오브젝트와 상호작용 합니다.|

#### 9) 오브젝트 이름 : 소파 sofa

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|플레이어와 상호작용 중인 상태|해당 오브젝트가 이동합니다.|

#### 10) 오브젝트 이름 : 첫 번째 방의 책장 First Room BookShelf

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|플레이어와 상호작용 중인 상태|해당 오브젝트와 상호작용 합니다.|

#### 11) 오브젝트 이름 : 두 번째 방의 책장 Second Room BookShelf

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|플레이어와 첫 번째부터 세 번째 상호작용 중인 상태|플레이어의 화면 하단 중앙에 자막을 표출합니다.|
|기본 상태(Idle)|플레이어와 네 번째 상호작용 중인 상태|해당 오브젝트가 이동합니다.|

#### 12) 오브젝트 이름 : 꽃 Flower

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|플레이어와 상호작용 중인 상태|해당 오브젝트가 비활성화되고 플레이어 화면 좌측 하단에 꽃 이미지가 활성화됩니다.|
|꽃과 상호작용을 한 상태|화병과 상호작용 중인 상태|플레이어 화면 좌측 하단에 꽃 이미지가 비활성화 됩니다.|

#### 13) 오브젝트 이름 : 화병 Vase

|현상태|전이상태|전이조건|
|:---:|:---:|:---:|
|기본 상태(Idle)||아무것도 하지 않은 기본 상태 입니다.|
|기본 상태(Idle)|플레이어와 상호작용 중인 상태|아무런 반응을 하지 않습니다.|
|꽃과 상호작용을 한 상태|화병과 상호작용 중인 상태|화병에 플레이어가 상호작용한 꽃의 오브젝트가 활성화됩니다.|
|꽃을 알맞지 않게 모두 꽂은 상태|초기화 상태|꽂은 꽃이 화병에 알맞지 않게 되어 화병과 꽃면 초기화됩니다.|
|꽃을 알맞게 모두 꽂은 상태|게임 클리어 상태|게임의 모든 문제를 해결하여 게임이 클리어됩니다.|

<br>

***

<br>

### 8. 게임의 규칙

#### 1) 핵심 규칙

- 플레이어는 모든 스테이지의 문을 열고 탈출하면 게임이 클리어됩니다.
- 게임이 전달하고자하는 의미는 플레이어가 스테이지 내에 있는 힌트를 통하여 파악해야 합니다.

#### 2) 보조 규칙

- 게임은 각 방을 하나의 스테이지로 합니다.
- 게임은 플레이어가 어떤 오브젝트와 상호작용이 가능한지 알려주지 않고 플레이어가 직접 스테이지를 돌아다니며 상호작용이 가능한지 확인하며 힌트와 문제를 발견해야 합니다.
- 플레이어는 스테이지 안에서 오브젝트와 상호작용하여 힌트 및 문제를 발견해야 합니다.
- 플레이어는 발견한 힌트를 이용하여 문제를 풀고 문의 열쇠를 얻어야 합니다.
- 플레이어는 문의 열쇠를 획득하면 해당 스테이지의 방문을 열고 다음 스테이지를 진행할 수 있습니다.
- 스테이지 클리어를 위한 문제에 힌트를 주는 스토리와 게임의 의미를 파악하기 위한 스토리가 있습니다.
- 이전 스테이지에서 발견한 힌트는 이후 스테이지에서 활용될 수 있습니다.

<br>

***

<br>

### 9. 게임에서 사용될 공식

- 플레이어는 'W', 'A', 'S', 'D'키를 통하여 캐릭터를 이동 시킬 수 있습니다.
- 플레이어는 'F'키를 통하여 스테이지 내의 오브젝트와 상호작용 할 수 있습니다.
- 플레이어는 마우스를 통하여 캐릭터의 시아를 조정할 수 있습니다.
- 플레이어는 화면 중앙의 CrossHair에 원하는 게임 오브젝트를 가져가는 것으로 상호작용할 오브젝트를 결정할 수 있습니다.
- 획득한 아이템은 화면 좌측 상단에 표시되며, 획득한 아이템은 사용할 수 있습니다.

<br><br>

## [개발 요구사항 & 흐름도]<a name='7'></a>

### 1. 요구사항

- 시작화면, 메뉴화면, 게임화면으로 총 3개의 화면으로 구성되어 있습니다.
- 시작화면에는 대표 이미지와 화면 중앙에 게임의 타이틀이 적혀 있고 화면 중앙 하단에는 "Press Any Key"의 문구가 적혀 있습니다.
- 시작화면에서 'Esc'키를 누르면 메뉴화면이 활성화 됩니다.
- 메뉴화면에는 게임새로시작 버튼과 게임저장 버튼, 게임종료으로 총 3개의 버튼으로 구성되어 있습니다.
- 메뉴화면에는 게임 내에서 나오는 소리의 음량을 조절할 수 있는 슬라이더가 있습니다.
- 메뉴화면에서 게임새로시작 버튼을 누를 경우, 현재까지 저장하였던 게임의 내용이 지워지고 처음부터 다시할 수 있게 됩니다.
- 메뉴화면에서 게임저장 버튼을 누를 경우, 현재까지 진행하였던 게임이 저장되어 게임을 재실행하였을 때, 저장한 스테이지부터 다시시작할 수 있습니다.
- 메뉴화면에서 게임종료 버튼을 누를 경우, 게임이 종료됩니다.
- 메뉴화면에서 음량 조절 슬라이더를 움직일 경우, 게임 내에서 나오는 소리의 음량을 조절할 수 있습니다.
- 메뉴화면이 활성화 되어있는 상태에서 'Esc'키를 누를 경우, 메뉴화면이 비활성화 되고 원래의 화면으로 돌아갑니다.
- 시작화면에서 'Esc'키를 제외한 아무키를 누르면 게임화면으로 'FadeIn' 하며 게임이 시작됩니다.
- 게임화면에는 좌측 상단에 소지한 아이템이 표시되고 화면 중앙에 CrossHair가 작고 반투명하게 표시됩니다.
- 플레이어는 게임화면에서 ''W, 'A', 'S', 'D'키를 이용하여 플레이어 캐릭터를 조종할 수 있습니다.
- 플레이어는 게임화면에서 마우스를 이용하여 플레이어 캐릭터의 시아를 조종할 수 있습니다.
- 플레이어는 게임화면에서 마우스를 통해 CrossHair를 상호작용하고 싶은 오브젝트에 가져가 'F'키를 누르는 것으로 게임 내의 오브젝트와 상호작용할 수 있습니다.
- 서랍, 책상서랍, 상자와 같은 오브젝트는 열쇠가 있어야 상호작용할 수 있고 열쇠가 있을 때, 상호작용을 하면 서랍 및 상자가 열립니다.
- 금고, 비밀번호가 있는 문과 같은 오브젝트는 상호작용을 하면 비밀번호를 입력할 수 있는 InputField가 화면 중앙에 표시되고 비밀번호가 일치할 경우 금고 및 문이 열립니다.
- 종이, 사진과 같은 오브젝트는 상호작용을 하면 플레이어의 화면 중앙에 해당 종이 및 사진이 확대되어 표시됩니다.
- 액자, 책장과 같은 오브젝트는 상호작용을 하면 액자가 떨어지거나 책장에 있는 졸업앨범이 나오는 등, 형태나 상태가 변합니다.
- 게임 내의 오브젝트는 플레이어와 상호작용시, 효과음을 추가 합니다.
- 플레이어가 상호작용 할 수 있는 오브젝트를 직관적으로 확인할 수 있도록 오브젝트에 테두리 효과를 추가합니다.
- 첫번째 스테이지는 가정 집의 안방을 모티브로 구현합니다.
- 첫번째 스테이지에서 필요로하는 오브젝트를 수집 및 제작합니다.
- 첫번째 스테이지에서 플레이어와 상호작용하는 오브젝트에 기능을 구현합니다.
- 두번째 스테이지는 취조실을 모티브로 구현 합니다.
- 두번째 스테이지에서 필요로하는 오브젝트를 수집 및 제작합니다.
- 두번째 스테이지에서 플레이어와 상호작용하는 오브젝트에 기능을 구현합니다.
- 세번째 스테이지는 콘크리트가 드러난 복도를 모티브로 구현 합니다.
- 세번째 스테이지에서 필요로하는 오브젝트를 수집 및 제작합니다.
- 세번째 스테이지에서 플레이어와 상호작용하는 오브젝트에 기능을 구현합니다.
- 선행 스테이지의 문제 및 힌트를 이용하여 풀어야 하는 문제를 추가 합니다.
- 선행 스테이지의 문제와 다른 방식의 문제를 추가합니다.
- 스테이지의 문을 열쇠를 통해 혹은 비밀번호를 맞추어 열게되면 다음 스테이지를 진행 할 수 있게 됩니다.
- 스테이지를 클리어 하여도 플레이어는 이전 스테이지로 언제든 돌아올 수 있습니다.
- 마지막 스테이지의 문을 열고 문을 통과하면 게임이 클리어되고 시작화면으로 돌아옵니다.
- 사람들에게 ProtoType을 플레이해보고 받은 피드백을 바탕으로 게임을 다듬습니다.
- ProtoType 제작을 마무리하고 오류 및 수정사항을 재검토합니다.
- 최종본 제작을 마무리하고 오류 및 수정사항을 재검토합니다.

<br>

### 2. 키보드 이벤트 흐름도 Flowchart

![키보드이벤트_이미지_1](./img/KeyBoard1_img.png)
![키보드이벤트_이미지_2](./img/KeyBoard2_img.png)

<br><br>

## [스토리 보드]<a name='8'></a>

![스토리보드 이미지1](./img/StoryBoard_01.png)
![스토리보드_이미지2](./img/StoryBoard_02.png)
![스토리보드_이미지3](./img/StoryBoard_03.png)
![스토리보드_이미지4](./img/StoryBoard_04.png)
![스토리보드_이미지5](./img/StoryBoard_05.png)

<br><br>

## [프로토타입 개발 요구사항 (6주 개발)]<a name='9'></a>

### 1주차

- ~~시작화면에는 대표 이미지와 화면 중앙에 게임의 타이틀이 적혀 있고 화면 중앙 하단에는 "Press Any Key"의 문구가 적혀 있습니다.~~
- ~~시작화면에서 'Esc'키를 제외한 아무키를 누르면 게임화면으로 'FadeIn' 하며 게임이 시작됩니다.~~
- ~~게임화면에는 좌측 하단에 소지한 아이템이 표시되고 화면 중앙에 CrossHair가 작고 반투명하게 표시됩니다.~~
- ~~플레이어는 게임화면에서 ''W, 'A', 'S', 'D'키를 이용하여 플레이어 캐릭터를 조종할 수 있습니다.~~
- ~~플레이어는 게임화면에서 마우스를 이용하여 플레이어 캐릭터의 시아를 조종할 수 있습니다.~~
- ~~플레이어는 게임화면에서 마우스를 통해 CrossHair를 상호작용하고 싶은 오브젝트에 가져가 'F'키를 누르는 것으로 게임 내의 오브젝트와 상호작용할 수 있습니다.~~
- ~~서랍, 책상서랍, 상자와 같은 오브젝트는 열쇠가 있어야 상호작용할 수 있고 열쇠가 있을 때, 상호작용을 하면 서랍 및 상자가 열립니다.~~
- ~~금고, 비밀번호가 있는 문과 같은 오브젝트는 상호작용을 하면 비밀번호를 입력할 수 있는 InputField가 화면 중앙에 표시되고 비밀번호가 일치할 경우 금고 및 문이 열립니다.~~
- ~~종이, 사진과 같은 오브젝트는 상호작용을 하면 플레이어의 화면 중앙에 해당 종이 및 사진이 확대되어 표시됩니다.~~
- ~~액자, 책장과 같은 오브젝트는 상호작용을 하면 액자가 떨어지거나 책장에 있는 졸업앨범이 나오는 등, 형태나 상태가 변합니다.~~

### 2주차

- ~~첫번째 스테이지는 가정 집의 안방을 모티브로 합니다.~~
- ~~첫번째 스테이지에서 필요로하는 오브젝트를 수집 및 제작합니다.~~
- ~~첫번째 스테이지에서 플레이어와 상호작용하는 오브젝트에 기능을 구현합니다.~~

### 3주차

- ~~두번째 스테이지는 취조실을 모티브로 구현 합니다.~~
- ~~두번째 스테이지에서 필요로하는 오브젝트를 수집 및 제작합니다.~~
- ~~두번째 스테이지에서 플레이어와 상호작용하는 오브젝트에 기능을 구현합니다.~~

### 4주차

- ~~세번째 스테이지는 콘크리트가 드러난 복도를 모티브로 구현 합니다.~~
- ~~세번째 스테이지에서 필요로하는 오브젝트를 수집 및 제작합니다.~~
- ~~세번째 스테이지에서 플레이어와 상호작용하는 오브젝트에 기능을 구현합니다.~~

### 5주차

- ~~게임 내의 오브젝트는 플레이어와 상호작용시, 효과음을 추가 합니다.~~
- ~~스테이지의 문을 열쇠를 통해 혹은 비밀번호를 맞추어 열게되면 다음 스테이지를 진행 할 수 있게 됩니다.~~
- ~~스테이지를 클리어 하여도 플레이어는 이전 스테이지로 언제든 돌아올 수 있습니다.~~

### 6주차

- ~~사람들에게 ProtoType을 플레이해보고 받은 피드백을 바탕으로 게임을 다듬습니다.~~
- ~~ProtoType 제작을 마무리 하고 오류 및 수정사항을 재검토합니다.~~

<br><br>

## [프로토타입 개발작업 일정 (6주 개발)]<a name='10'></a>

![프로토타입_작업일정_이미지](./img/ProtoPlan_img.PNG)
