# NOL 페스티벌 VIP 스태프 가이드

스태프용 좌석배치도·VIP 명단 검색·팔찌·와이파이 안내 페이지입니다.

- 주소: https://wooseokkoh.github.io/nolfestivalstaff/
- 명단·사진은 `data.bin`에 **비밀번호로 암호화**되어 있어 비밀번호 없이는 내용을 볼 수 없습니다.
- 비밀번호 변경: 페이지 안 **설정** 탭 → 새 비밀번호 + GitHub 토큰(이 저장소 Contents 읽기/쓰기) → 1~2분 뒤 모두에게 적용
- 명단 수정: `node tools/seal.mjs unseal <비밀번호> data.json` 으로 풀어서 고친 뒤 `node tools/seal.mjs seal data.json <비밀번호>` 로 다시 잠그기. 평문 JSON은 저장소에 올리지 마세요.
