# commit convention

> ✏️ 명시적이고 일관된 커밋 메시지 작성을 촉진하기 위해 다음과 같은 커밋컨벤션을 따릅니다. 


| Tag Name	  | Description   |
|-----| ------ | 
| Feat  | 새로운 기능을 추가 | 
| Design  | 버그 수정 |
| Design  | CSS 등 사용자 UI 디자인 변경 |
| Style  | 코드 포맷 변경, 세미 콜론 누락, 코드 수정이 없는 경우 |
| Refactor | 프로덕션 코드 리팩토링 |
| Comment | 	필요한 주석 추가 및 변경 | 
| Docs | 문서 수정 |
| Test | 테스트 코드, 리펙토링 테스트 코드 추가 |
| Chore | 빌드 업무 수정, 패키지 매니저 수정, 패키지 관리자 구성 등 
| Rename | 	파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우
| Remove | 파일을 삭제하는 작업만 수행한 경우

---


# Commit message structure  

> <"type">("issue_number"): "message" <br/>
> ex : `feat(#123): 사용자 로그인 기능 추가`


- `type`: Tag Name을 작성해주세요.

- `issue_number`: 관련된 이슈 번호입니다. 이슈와의 연관성을 유지하기 위해 권장됩니다.

- `message`: 변경 사항에 대한 간결한 설명입니다. 50자 이내로 작성하는 것이 좋습니다.

