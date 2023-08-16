# Vs_BackUp

## Visual Studio WIN32API 를 활용한 게임 프레임워크 설계 코드 소스입니다.
**모든 소스코드 관련 파일은 .cpp 파일이 아닌 .txt 파일로 이루어져 있습니다.**
**현재 PC의 경로에 한글경로가 있어 수정, 저장 등이 원활하지 않아 추후에 다른 PC에서 사용하기 위해 백업 해두기 위한 저장소입니다.**
**현재까지의 관련 이슈와 체크리스트를 함께 기록합니다.**

+ SingleTon Pattern+ 
+ BITMAP Loading, 2D Animation
+ Component 기반 설계
+ UI 설계
+ TileMap 설계를 위한 Tool

---

## Check-List (UI)

- [ ] PanelUI 해상도 내에 5 x 5 크기의 각각의 Tile 저장 기능 구현
- [ ] PanelUI 내에 ButtomUI에서 마우스 우클릭으로 Tile 오브젝트의 정보를 저장하고 마우스 좌클릭으로 저장된 Tile 오브젝트를 실제 Scene에 Edit 하는 기능 구현
- [X] Scene에 배치한 TileMap Data 저장, 불러오기 기능 구현

---

## Issue

1. Scene을 변경할 때 UI는 남아 있지만, Scene에 배치된 Tile 정보가 사라지는 현상이 있습니다.
2. Player가 발사한 투사체의 충돌체의 위치가 투사체의 위치를 벗어나는 현상이 있습니다.
