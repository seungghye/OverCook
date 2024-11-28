# ⚒ OverCook 

# 📢Info
현재 서비스 중인 OVERCOOKED라는 게임의 프레임워크와 상호작용, 레벨디자인 등을 모작한 멀티플레이 게임을 개발을 하였습니다.

+ __팀원__ : 3명

+ __기획 의도__ : 현재 서비스 중인 OVERCOOKED라는 게임을 모작

+ __개발 목표__ : 현재 서비스 중인 게임의 디자인을 최대한 유사한 레벨과, UI를 구성해보고자하였습니다.

+ __개발 기간__ : 2024.10.11 ~ 2024. 11.22 


## 🛠Entry Level Design
공원의 푸드트럭에서 주문을 한다는 컨셉으로 새롭게 디자인을 하였습니다.

#### 📌Details
0. Mesh
1. LandScape
   
## 🛠Lobby Level Design
원작의 Lobby와 비슷한 디자인을 컨셉으로 그 안에 필요한 Asset과 바닥의 텍스처 등을 제작하였습니다.

#### 📌Details
0. Mesh
1. Tree Material Instances


## 🛠Stage 1-1 Level Design
OVERCOOKED에서는 멸망 직전의 도시에서 몬스터에게 먹을 것을 주어야한다는 컨셉으로 레벨디자인이 되어있습니다.

저희가 모작한 게임에서는 야근 중인 직장인들에게 음식을 제공한다는 컨셉으로 구성하여 진행했습니다.

#### 📌Details
0. Mesh
1. Building의 창문
2. Food Spawn Box
3. Smoke VFX

#### 📌Data Asset
+ __Food Item__
  
   계속해서 변경되는 Food Mesh를 Data Asset으로 관리해 추가 Food Mesh 혹은 유지보수 등에 효율적이도록 구성하였습니다.


+ __Recipe Asset__
  
   Food Item Data Asset의 정보와, Score같은 정보들로 구성되어있습니다.

   또한, Recipe Asset은 BluePrintAsset으로 구성하였습니다.

   특정 Recipe가 되기 위해 필요한 Food Item을 추적하는 기능을 구현하여 비교할 Food Item이 들어온다면, 저장된 Recipe와 같은 것이 맞는지 분별하는 방식으로 데이터의 구조를 설계하였습니다. 
 

## Use Tool
 <img src="https://img.shields.io/badge/UnrealEngine-0E1128?style=flat&logo=unrealengin&logoColor=white"/>

- Maya
- Blender
- Adobe Photoshop
   
