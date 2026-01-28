#📘 ellaOS 4.0 사용 설명서 (ella.exe)
1️⃣ CMD(명령 프롬프트) 여는 방법
방법 1 (가장 쉬움)

키보드에서 윈도우 키 + R

cmd 입력

Enter

방법 2

시작 메뉴 클릭

cmd 또는 명령 프롬프트 검색

실행

2️⃣ ella.exe 설치 위치 (중요)
📂 설치 위치

ella.exe는 반드시 아래 경로에 넣으세요

C:\Users\사용자이름\


예시:
```
C:\Users\yoonj\ella.exe
```

❌ 바탕화면 / 다운로드 / USB
⭕ C:\Users\사용자이름\ ← 권장 위치

3️⃣ CMD에서 ella 명령어로 실행하기 (핵심)

ella.exe는 CMD에서 ella 라는 명령어로 실행합니다.

3-1. 실행 방법

CMD에서 입력:
```
cd C:\Users\사용자이름
ella
```

👉 ellaOS 4.0 실행

(같은 폴더에 ella.exe가 있기 때문에 .exe 생략 가능)

4️⃣ 최초 실행 (초기 설정)

처음 실행 시 초기 설정 화면이 나타납니다.

🔑 제품 키
```
ellaOS-4.03-71234
```

🔒 비밀번호 설정

비밀번호 입력

비밀번호 확인 입력

설정 완료 클릭

설정이 끝나면 자동으로 로그인 화면으로 이동합니다.

5️⃣ 로그인 방법

비밀번호 입력

Enter 키 또는 로그인 버튼 클릭

❌ 틀리면 오류 메시지 표시
⭕ 맞으면 부팅 화면으로 이동

6️⃣ 부팅 화면

ellaOS 로고 표시

시작음 재생

약 2.5초 후 데스크톱 진입

7️⃣ 데스크톱 조작 방법
🖱️ 마우스

아이콘 클릭 → 앱 실행

창 닫기 → x

최소화 → -

⌨️ 키보드
키	기능
Enter	로그인 확인
Alt + F4	현재 창 닫기
마우스 클릭	앱 실행
8️⃣ 기본 내장 앱
🎨 그림판

마우스 드래그로 그림 그리기

🧮 계산기

사칙연산 지원

= 버튼으로 계산

ℹ️ 정보

ellaOS 버전 정보 표시

9️⃣ 종료 방법
방법 1 (권장)

시작 버튼 클릭

전원 끄기

종료음 재생 후 자동 종료

방법 2

창 닫기 버튼 사용

🔐 설정 파일 저장 위치 (참고)

ellaOS 설정 파일은 자동으로 아래 위치에 생성됩니다:

C:\Users\사용자이름\AppData\Roaming\ellaOS\


파일 목록:

ella_setup.done → 초기 설정 완료 표시

ella_password.txt → 비밀번호 파일

⚠️ 이 파일을 삭제하면 ellaOS가 초기화됩니다.

10️⃣ ellaOS 초기화 방법

CMD에서 아래 명령어 실행:

del "%APPDATA%\ellaOS\ella_setup.done"
del "%APPDATA%\ellaOS\ella_password.txt"


그 후 다시:

ella


→ 초기 설정부터 다시 시작

✅ 요약

설치 위치: `C:\Users\사용자이름\ella.exe`

실행 방법: CMD에서 `ella`

설정은 AppData에 안전하게 저장됨

초기화 가능
