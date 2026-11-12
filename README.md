# 미래엔수학 은평덕양 콘텐츠

은평구·덕양구 미래엔수학 원장님 전용 홍보 소재함입니다.
원장님은 소재를 고르고 학원명·전화번호 등을 입력해 바로 저장해 씁니다.

## 폴더 구성
- `index.html` — 웹사이트 화면 전체
- `data/db.json` — 소재 목록(제목, 게시 문구, 글자 칸 위치 등)
- `media/` — 올린 이미지·영상 파일

이 파일들은 웹사이트의 관리자 화면에서 올리기·수정·삭제할 때 자동으로 바뀝니다. 직접 고치지 않아도 됩니다.

## 관리자 로그인
1. 웹사이트 하단의 「관리자」(또는 첫 화면의 「관리자 로그인」)를 누릅니다.
2. GitHub에서 만든 관리자 토큰을 붙여 넣습니다.

### 관리자 토큰 만들기
GitHub → 오른쪽 위 프로필 → Settings → Developer settings → Personal access tokens → **Fine-grained tokens** → Generate new token
- Repository access: **Only select repositories** → 이 저장소
- Permissions → Repository permissions → **Contents: Read and write**
- 만든 토큰(github_pat_…)을 복사해 관리자 로그인 창에 붙여 넣습니다.

토큰은 그 기기의 브라우저에만 저장됩니다. 다른 사람에게 알려 주지 마십시오.
