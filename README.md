# Ruliweb-LoL-Manual-Template
[(미리보기)](https://anesin1109.github.io/ruliweb-lol-manual-template/)
루리웹을 위한 롤 공략 틀입니다. 다른 곳에서 사용하셔도 문제는 없습니다.

## 사용 방법
1. https://github.com/anesin1109/Ruliweb-LoL-Manual-Template/blob/master/template.html 의 소스 코드를 복사하여, 루리웹의 소스 코드 편집 모드(편집 창의 좌측 하단에 <> 모양 아이콘)에 붙여넣습니다.
2. 아래 방법대로 내용을 수정합니다. 모드 전환은 미리보기 모드(편집 모드 아이콘 옆의 돋보기 아이콘)로만 하는 것을 권장합니다. 일반 글쓰기 모드로 돌아가면 간혹 CSS(디자인)가 날아가기도 하기 때문에, 되도록이면 소스 코드 편집 모드에서 편집하는 걸 권장합니다.

### 머리말 넣기
원본 기준 36번째 줄에 있는 "여기는 머리말입니다." 위치에 글을 써넣으시면 됩니다.

### 룬 넣기
룬 정보 생성기[(링크)](https://anesin1109.github.io/rune-generator/)으로 만든 룬 정보를 원본 기준 47번째 줄에 붙여넣으시고, 그 아래 "추가 설명은 여기 적으시면 됩니다."에 글을 써넣으시면 됩니다.

### 스펠 넣기
아래쪽에 있는 "각종 아이콘 삽입 방법"을 이용해 스펠 아이콘을 골라서, 원본 기준 54번째 줄에 붙여넣으시고 내용을 쓰시면 됩니다.

### 스킬 넣기
스킬 정보 생성기[(추후 업데이트 예정)](#)으로 만든 스킬 정보를 원본 기준 60번째 줄에 붙여넣으시고, 그 아래 추가 설명을 적으시면 됩니다.

### 아이템 넣기
아이템 정보 생성기[(추후 업데이트 예정)](#)으로 만든 아이템 정보를 원본 기준 68번째 줄에 붙여넣으시고, 그 아래 추가 설명을 적으시면 됩니다.

### 카운터픽 넣기
원본 기준 76번째 줄부터 83번째 줄까지가 1명의 챔피언을 나타냅니다. 원하는 수만큼 복사&붙여넣기하시고, 원본 기준 78번째 줄의 주소를 [챔피언 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Champion_squares)에서 따온 주소로 바꾸시고(각종 아이콘 삽입 방법 참고), 이름을 바꿔 넣으신 후, 원본 기준 81번째 줄에 글을 적으시면 됩니다. 상대하기 쉬운 챔피언도 86번째 줄에서 93번째 줄까지의 부분으로 같은 방법으로 가능합니다.

### 챔피언별 상대법 넣기
원본 기준 98\~119번째 줄이 1명의 챔피언을 나타냅니다.
먼저 원본 기준 100번째 줄의 주소를 [챔피언 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Champion_squares)에서 선택한 주소로 바꾸고, 챔피언 이름과 별 수를 바꿉니다.
104번과 105번의 주소를 [스펠 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Summoner_spell_icons)에서 선택한 주소로 바꿉니다.
109~114번의 주소를 [아이템 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Item_icons)에서 선택한 주소로 바꿉니다.
117번에 상대법을 적으시면 됩니다.

### 추가 공략 넣기
123번째 줄에 넣으시면 됩니다.

### 각종 아이콘 삽입 방법
1. 이미지를 넣고자 하는 부분에 다음 소스 코드를 붙여 넣습니다.
`<img src="<주소 붙여넣을 곳>" class="manual_icon">`
2. 다음 사이트에 들어가서 원하는 아이콘을 찾습니다.
[챔피언 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Champion_squares)
[아이템 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Item_icons)
[스펠 아이콘](http://leagueoflegends.wikia.com/wiki/Category:Summoner_spell_icons)
3. 원하는 아이콘을 우클릭한 후, 이미지 주소 복사(브라우저마다 다름)를 누릅니다.
4. 1에서 붙여넣은 글귀에서, <주소 붙여넣을 곳>를 지우고 복사된 주소를 붙여넣기하면 됩니다.

## 기여하고 싶다면?
PR 환영합니다.
- Indentation은 2칸입니다.
- 클래스 이름 중복을 막기 위해 모든 클래스는 manual_로 시작합니다.
- 클래스 이름 띄어쓰기는 -로 표시합니다.
- 레이아웃에는 Flexbox 사용을 권장합니다.
