인 게임에서 드랍되는 재료 또는 판매용 아이템
ItemName(String) : 아이템 이름

ItemImage(Sprite) : 아이템의 아이콘/이미

ItemNum(int) : 아이템 번호

ItemDescription(String) : 아이템 설명

ItemRarity(enum) : 아이템의 희귀도.
- (Common, Rare, Epic, Unique, Legendry)

ItemPrice(float) : 아이템 값어치 

ItemKind(enum) : 아이템 종류 (전투.회복 '소모품' 포함)
- Medical / Buff / Mineral / Key / Tools / Luxury / Rune / Material

ItemWeight(float) : 아이템의 무게

ItemVerticalVolume(int) : 아이템이 차지하는 세로 공간

ItemHorizontalVolume(int) : 아이템이 차지하는 가로 공간

ItemMaxStack(int) : 한 인벤토리 슬롯에서 쌓을 수 있는 아이템의 최대 수량

ItemUsable(bool) : 레이드에서 사용 가능한 아이템인가?
->UsableItem(Medical / Buff) Script 따로 제작






