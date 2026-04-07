# 경북대학교 동아리 소개 프로젝트

# 1. 프로젝트 소개

# 2. 팀원

# 3. 중앙동아리 소개
- 해당 동아리 소개

# 4. 컴퓨터학부 동아리 소개
- 해당 동아리 소개
 
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

## 🔀 Branch 작업 요약

| 대상 | Branch 흐름 | Merge 방식 | 선택 이유 |
|------|--------------|------------|-----------|
| 동아리 소개 파일 | `feature/동아리명` → `dev` | Merge Commit | 기여 이력을 명확하게 추적 가능 |
| README 파트 | `feature/README-파트명` → `feature/README` | Squash and Merge | 파트별 커밋을 하나로 정리, 간결한 히스토리 유지 |
| README 통합 | `feature/README` → `dev` | Merge Commit | 최종 README 결과를 이력과 함께 dev에 반영 |
| 최종 병합 | `dev` → `main` | Merge Commit | 프로젝트 전체의 최종 통합 이력 보존 |

# 6. 프로젝트 구조
