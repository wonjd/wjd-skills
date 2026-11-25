# wjd-skills

원정대 업무용 Claude 스킬 모음입니다.

## wjd-interview (원정대 인터뷰)

만들고 싶은 화면이나 고치고 싶은 업무를 개발 요청 전에 정리합니다. Claude가 업무 말로 인터뷰하고, 폴더에 `요청서.md` 한 장을 남깁니다.

### 설치 (Claude 앱의 Code 탭)

아래 문장을 Code 탭에 붙여 넣습니다.

```text
이 파일을 내려받아서 내 사용자 폴더의 .claude/skills/wjd-interview/SKILL.md 로 저장해 줘.
https://raw.githubusercontent.com/wonjd/wjd-skills/main/skills/wjd-interview/SKILL.md
```

새 대화를 열고 "원정대 인터뷰 해 줘"라고 하면 시작합니다.

### 쓰는 법

- 추천 답이 맞으면 "추천대로"라고 합니다.
- 모르는 것은 "모르겠다"고 하고, 누가 정할 수 있는지 알려 줍니다.
- 시간이 없으면 "여기까지"라고 합니다. 다음에 같은 폴더에서 다시 부르면 이어서 묻습니다.

## examples

- `examples/meeting-room.html`: 연습용 회의실 예약 프로토타입입니다. 시간이 겹쳐도 저장되고 누구나 취소할 수 있게 일부러 만들었습니다.
