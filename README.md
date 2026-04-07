# 경북대학교 동아리 소개 프로젝트

# 1. 프로젝트 소개

# 2. 팀원

# 3. 중앙동아리 소개
- 해당 동아리 소개

# 4. 컴퓨터학부 동아리 소개
- 해당 동아리 소개
 
# 5. 협업 방식

## 🌿 Branch 전략

동아리 md파일과 README.md 파일을 공동작업하기 위해 개인 branch를 생성하여 작업하였다.

---

### 동아리 소개 파일

- **Branch명**: `feature/동아리명`
- 각자 맡은 동아리 md 파일을 개인 branch에서 독립적으로 작업
- **04/08** 에 main branch로 병합
- **Merge 방식**: Merge Commit
  - 각 팀원의 작업 이력이 별도의 merge 커밋으로 남아, 누가 어떤 파일을 작업했는지 기여 이력을 명확하게 추적할 수 있기 때문

---

### README.md 파일

- **Branch명**: `feature/README-파트명`
- README.md를 파트별로 분배하여 팀원 간 협업 진행
- **04/08** 에 main branch로 병합
- **Merge 방식**: Squash and Merge
  - 각 파트 branch에서 작업한 여러 커밋을 하나로 합쳐 main에 반영하기 때문
  - README.md는 파트별 최종 결과물이 중요하므로, 커밋 히스토리를 간결하게 유지하는 것이 적합하기 때문

---

## 🔀 Branch 작업 요약

| 대상 | Branch명 규칙 | Merge 방식 | 선택 이유 |
|------|--------------|------------|-----------|
| 동아리 소개 파일 | `feature/동아리명` | Merge Commit | 기여 이력을 명확하게 추적 가능 |
| README.md | `feature/README-파트명` | Squash and Merge | 파트별 커밋을 하나로 정리, 간결한 히스토리 유지 |

# 6. 프로젝트 구조
