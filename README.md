# 경북대학교 동아리 소개 프로젝트

# 1. 프로젝트 소개

# 2. 팀원

# 3. 중앙동아리 소개
- 해당 동아리 소개

# 4. 컴퓨터학부 동아리 소개
- 해당 동아리 소개
 
# 5. 협업방식

# 6. 프로젝트 구조
oss-club-recommend
├── README.md
├── dev
├── main_club (folder)
│   ├── feature/RCY.md
│   ├── feature/terpsichore.md
│   └── feature/cheongeum.md
├── cs_club (folder)
│   ├── feature/gori.md
│   └── feature/L&C.md
├── feature/README.md
│   ├── feature/README-projlntro
│   ├── feature/README-member
│   ├── feature/README-mainclub
│   ├── feature/README-project-method
│   └── feature/README-Project-Structure

* README.md
-프로젝트 전체를 설명하는 문서<br>
* main_club 폴더
- 중아동아리 동아리(RCY, terpsichore, cheongeum)의 정보를 담은 문서들이 위치  <br>
- 각 문서는 브랜치에서 작성 및 수정한 뒤에 dev 브랜치에 merge commit으로 병합  <br>
* cs_club 폴더
- 컴퓨터학부 동아리(Gori, L&C)의 정보를 담은 문서들이 위치 <br>
- 각 문서는 브랜치에서 작성 및 수정한 뒤에 dev 브랜치에 merge commit으로 병합 <br>
* feature/README.md 브랜치
- 프로젝트 전체를 설명하는 README.md 파일을 다루는 상위 branch로 아래 branch들의 결과들 모아서 README.md에 반영하는 역할 <br>
- (feature/README-projlntro, feature/README-member, feature/README-mainclub, feature/README-project-method , feature/README-Project-Structure) <br>
브랜치들은 feature/README.md에 squash and merge로 병합 <br>
- 이후  feature/README.md 브랜치는 dev 브랜치에 merge commit으로 병합
