# 2023 한신대학교 동계 프로젝트


# 깃허브 커밋 메시지 규칙
```
[#이슈번호] feat: 새로운 기능 추가했을 때
[#이슈번호] fix: 버그나 오류 수정했을 때
[#이슈번호] refactor: 코드 리팩토링했을 때
[#이슈번호] chore: 약간 애매한 기타 변경사항
[#이슈번호] docs: 리드미 파일이나 md 파일 수정할 때 (문서작업)
```

# 협업 규칙
* 각자 저장소를 Fork하여 작업
* Git Flow 전략에 따라서 feature, develop, main으로 브랜치 관리
* 작업 시작전에 해당 작업에 대한 이슈를 등록
* 브랜치를 생성 (ex. feature/#{이슈번호}-{간단한 설명})
* 작업 진행
* 해당 기능에 대한 모든 작업이 끝나면 develop으로 Pull Request 요청
* 팀원들에게 PR 내용을 공유 후 Rebase and Merge 적용 (Commit Message를 깔끔하게 관리하기 위해 채택)
* Pull Request 과정에서 충돌이 난 경우 충돌난 코드와 관련된 팀원들이 소통하여 충돌 해결 후 Merge
* develop에서 모든 작업이 끝난 후 main으로 Pull Request & Rebase and Merge 후 프로젝트 종료
