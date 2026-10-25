# reign 사용 요청

reign 은 허용한 사람만 받는 하네스 엔진입니다.

1. 이 레포에 **사용 요청** 이슈를 올립니다. 이슈를 올린 GitHub 계정이 승인 대상입니다(아이디와 이슈는 공개됩니다).
2. 승인되면 비공개 레포 `reign-agents/reign` 의 읽기 초대가 갑니다. GitHub 알림이나 https://github.com/reign-agents/reign/invitations 에서 수락합니다.
3. 설치(gh 로그인 필요):

       gh release download --repo reign-agents/reign --pattern install.sh -O - | sh

4. 처음 한 번: `harness license register`
