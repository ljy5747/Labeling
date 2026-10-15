# Labeling

국균연구소(KGL) 사슴벌레 사육 라벨 메이커.

항목을 입력하면 라벨 미리보기에 바로 반영되고, **이미지 저장** 버튼으로 PNG를 받을 수 있습니다. 폰에서는 공유 시트(사진에 저장), PC에서는 파일 다운로드로 저장됩니다.

- `index.html` — 입력 화면과 라벨 그리기
- `template.png` — 빈 라벨 템플릿

## 표기 규칙
- 표 안 글자는 가운데 정렬 (1st~5th 교체 기록만 왼쪽 정렬 + 항목별 열 맞춤)
- 학명(Dorcus Hopei Binodulosus)은 템플릿에 고정 (밑줄 없음)
- 푸딩은 날짜 + 먹이원
- 날짜는 `YY.MM.DD` (예: 26.08.08)

## BeetleLog에서 가져오기
- 구글 로그인(BeetleLog와 같은 계정) → 라인 선택 → 유충 선택 → 라벨 칸 자동 입력
- 본인 계정 데이터만 읽기 (Supabase RLS)
- Supabase Auth Redirect URLs에 `https://ljy5747.github.io/Labeling/` 등록 필요
