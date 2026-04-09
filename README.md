# 경북대학교 동아리 소개 프로젝트

## 목차
[1. 프로젝트 소개](#1-프로젝트-소개)\
[2. 팀원](#2-팀원)\
[3. 중앙동아리 소개](#3-중앙동아리-소개)\
[4. 컴퓨터학부 동아리 소개](#4-컴퓨터학부-동아리-소개)\
[5. 협업방식](#5-협업방식)\
[6. 프로젝트 구조](#6-프로젝트-구조)

# 1. 프로젝트 소개
본 프로젝트는 동아리 선택에 어려움을 겪거나 고민을 하고 있는 경북대학교 학우들에게 정보 전달을 목표로 한다.

본문에는 경북대학교의 중앙동아리와 컴퓨터학부 동아리의 분과별 소개와\
팀원 개인이 작성한 md 파일로 이어지는 링크가 있다.\
해당 링크를 클릭하면 소속된 동아리의 설명과 구체적인 참여 후기가 담겨있다. 

또한 해당 프로젝트를 진행하며 사용한 협업 방식, 프로젝트 구조에 대한 설명이 문서 하단에 포함되어있다.

# 2. 팀원
| 이름 | 동아리 구분 | 동아리명 |
|------|--------|---------------|  
| 강수빈 | 중앙 | [터프시커리](./main_club/terpsichore_recommend.md) |
| 김고은 | 학부 | [L&C](./cs_club/L&C.md) |
| 나하윤 | 중앙 | [RCY](./main_club/RCY.md) |
| 차은지 | 중앙 | [청음반](./main_club/cheongeum.md) |
| 황영종 | 학부 | [Gori](./cs_club/gori.md) | 


# 3. 중앙동아리 소개
경북대학교 중앙동아리는 경북대학교 총동아리연합회를 중심으로 다양한 분야의 동아리들이 운영되는 학생 자치 조직이다. 

문예, 체육, 사회, 학술, 종교분과 등 학생이 원하는 다양한 주제의 활동으로 동아리를 즐길 수 있다. 

대부분의 동아리는 학기 초에 진행되는 가두모집을 통해 신입생을 모집하므로, 

동아리 활동에 관심 있는 학우들은 해당 기간에 적극적으로 참여하는 것을 권장한다.

아래에서 팀원들이 소속된 중앙동아리를 경험한 내용을 자세히 소개하는 글을 아래에서 확인할 수 있다.

|동아리 | 분과 |
|----|---|
| [RCY](main_club/RCY.md)| 사회분과 | 
| [청음반](main_club/cheongeum.md) | 문예분과 |
| [터프시커리](main_club/terpsichore_recommend.md) | 문예분과 |

# 4. 컴퓨터학부 동아리 소개

* 경북대학교 컴퓨터학부에는 학술 탐구부터 사회 봉사, 예술 활동까지 다양한 분야의 동아리들이 활발히 운영되고 있습니다. 
* 각 동아리는 전공 역량을 키우는 것뿐만 아니라 선후배 간의 끈끈한 유대감을 바탕으로 즐거운 학부 생활을 만들어가는 중심축 역할을 합니다.

###  봉사 동아리 (Volunteer)

 * **L&C (Lovely & Communication)**: 초/중/고등학생을 대상으로 스크래치, 아두이노 등 SW 교육 봉사를 진행하며 사회적 가치를 실현합니다.
   > [**직접 참여해본 L&C 생생한 후기 보러가기 >>**](https://github.com/soobeenkang/oss-club-recommend/blob/feature/L%26C/L%26C.md)

###  예술 및 친목 동아리 (Arts & Social)

 * **그루터기**: 컴퓨터학부 대표 밴드 동아리로, 음악을 매개로 선후배 간의 돈독한 유대감을 쌓고 정기 공연을 진행합니다.
 * **산사랑**: 연극 공연을 준비하며 팀워크를 배우고, 다양한 친목 활동을 통해 즐거운 학부 생활을 만듭니다.

###  학술 및 기술 동아리 (Academic & Tech)

 * **KERT**: 정보보호 및 해킹 방어 연구를 중심으로 시스템, 네트워크 등 IT 전반을 탐구합니다.
 * **REVOLUTION**: Unity 엔진 등을 활용하여 인디 게임을 기획하고 실제로 출시하는 게임 개발 모임입니다.
 * **GORI**: 알고리즘 및 문제 해결 기법(PS)을 연구하며, 프로그래밍 경진대회 참여를 목표로 합니다.
   > [**직접 참여해본 GORI 생생한 후기 보러가기 >>**](https://github.com/soobeenkang/oss-club-recommend/blob/feature/Gori/gori.md)
 * **GET IT**: SW 개발과 창업 아이디어를 결합해 실제 서비스로 구현해내는 에너지 넘치는 동아리입니다.
 
# 5. 협업 방식

## 🌿 Branch 전략

동아리 md파일과 README.md 파일을 공동작업하기 위해 개인 branch를 생성하여 작업하였으며, `feature`, `dev`, `main` 브랜치 구조를 통해 안정적으로 병합을 진행하였다.

---

### 동아리 소개 파일

- **Branch명**: `feature/동아리명`
- 각자 맡은 동아리 md 파일을 개인 branch에서 독립적으로 작업
- **Merge 순서**: `feature/동아리명` → `dev` → `main`
- **Merge 방식**: Merge Commit
  - 각 팀원의 작업 이력이 별도의 merge 커밋으로 남아, 누가 어떤 파일을 작업했는지 기여 이력을 명확하게 추적할 수 있기 때문
  - `dev`에서 `main`으로 병합 시에도 최종 이력을 보존하기 위해 Merge Commit 방식 사용

---

### README.md 파일

- **Branch명**: `feature/README-파트명`
- README.md를 파트별로 분배하여 팀원 간 협업 진행
- **Merge 순서**: `feature/README-파트명` → `feature/README` → `dev` → `main`
- **Merge 방식**:
  - **feature/README-파트명 → feature/README**: Squash and Merge
    - 각 파트 branch에서 작업한 여러 커밋을 하나로 합쳐 상위 branch에 반영함으로써 커밋 히스토리를 간결하게 유지하기 위함
  - **feature/README → dev**: Merge Commit
    - 정리된 README 최종 작업 결과물을 이력과 함께 통합하기 위함

---

## 📝 Commit 정책 및 규칙

### 동아리 Commit

- 각자의 동아리 branch 생성: `feature/동아리명` 형식
- 자신의 branch에서 동아리 소개 파일 생성: `동아리명.md` 형식
- **04/05 ~ 04/07** 기간 동안 총 **8회** commit
- commit 시마다 내용을 반드시 추가하거나 다듬을 것
- md 문법을 필수적으로 사용할 것


### README.md Commit

- 공통 형식 유지를 위한 템플릿 branch 생성: `feature/README`
- `feature/README` 에서 파트별 branch 분기: `feature/README-파트명` 형식
- **04/07 ~ 04/09** 기간 동안 자신의 파트를 책임지고 완성할 것
- commit 시 **자신의 파트 외 내용은 수정 금지** → Merge Conflict 방지


---

## 🔀 Branch 작업 요약

| 대상 | Branch 흐름 | Merge 방식 | 선택 이유 |
|------|-------------|------------|-----------|
| 동아리 소개 파일 | `feature/동아리명` → `dev` | Merge Commit | 기여 이력을 명확하게 추적 가능 |
| README 파트 | `feature/README-파트명` → `feature/README` | Squash and Merge | 파트별 커밋을 하나로 정리, 간결한 히스토리 유지 |
| README 통합 | `feature/README` → `dev` | Merge Commit | 최종 README 결과를 이력과 함께 dev에 반영 |
| 최종 병합 | `dev` → `main` | Merge Commit | 프로젝트 전체의 최종 통합 이력 보존 |

# 6. 프로젝트 구조
### oss-club-recommend structure (branch) <br>
```
main
└── dev
    ├── feature/RCY
    ├── feature/terpsichore
    ├── feature/cheongeum
    ├── feature/Gori
    ├── feature/L&C
    └── feature/README
        ├── feature/README-projIntro
        ├── feature/README-member
        ├── feature/README-mainclub
        ├── feature/README-CS-CLUB
        ├── feature/README-cooperation-method
        └── feature/README-Project-Structure
```

### oss-club-recommend structure (file) <br>
```
oss-club-recommend
├── README.md
├── main_club
    ├── RCY.md
    ├── terpsichore.md
    ├── terpsichore_thumb.png
    ├── terpsichore_recommend.md
    ├── cheongeum.md
└── cs_club
    ├── gori.md
    ├── gori_ICPC 2025 메달.jpg
    ├── gori_ICPC 2025 현장.jpg
    └── L&C.md
```
