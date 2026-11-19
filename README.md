# Machine CAD 다운로드 (베타)

인벤터 방식으로 쓰는 개인용 3D CAD **Machine CAD**의 베타 테스트용 설치 파일을 받는 곳입니다.

## 👉 [최신 버전 받기](https://github.com/ybRoh/machine-cad-download/releases/latest)

위 링크를 열고 아래 **Assets**에서 내 컴퓨터에 맞는 파일을 받으세요.

| 컴퓨터 | 받을 파일 |
|---|---|
| 윈도우 10/11 (64비트) | `MachineCAD-Setup-<버전>.exe` |
| 맥 (Apple Silicon: M1·M2·M3·M4) | `MachineCAD-<버전>-mac.zip` |

## 설치 방법

### 윈도우
1. 받은 `MachineCAD-Setup-….exe`를 실행합니다.
2. **"Windows의 PC 보호"** 창이 뜨면 **추가 정보 → 실행**을 누릅니다. 베타 버전이라 코드 서명이 없어서 나오는 안내입니다.
3. 설치 위치를 고르고 설치하면 바탕 화면과 시작 메뉴에 **Machine CAD**가 생깁니다.

### 맥
1. 받은 zip 파일을 더블클릭해 압축을 풉니다.
2. **Machine CAD.app**을 **응용 프로그램** 폴더로 옮깁니다.
3. 처음 한 번은 앱을 **우클릭 → 열기 → 열기**로 실행합니다. 베타 버전이라 Apple 공증이 없어서 필요한 단계입니다.
4. "손상되었기 때문에 열 수 없습니다"가 뜨면 **터미널**에서 아래 한 줄을 실행한 뒤 다시 엽니다.
   ```
   xattr -cr "/Applications/Machine CAD.app"
   ```

## AI 기능 (선택)
- 오른쪽 **AI 창**에서 말로 부품을 만들고 고칠 수 있습니다.
- **Claude Code (구독)** 엔진: Claude Pro·Max 구독이 있으면 추가 요금 없이 씁니다. Node.js와 `npm install -g @agentclientprotocol/claude-agent-acp` 설치, 창 위 **[로그인]**이 필요합니다.
- **Claude API (키)** 엔진: console.anthropic.com에서 만든 API 키를 넣습니다. 사용량만큼 요금이 나옵니다.

## 문제 알리기
- 오류 화면이나 동작이 이상한 점은 이 저장소의 [Issues](https://github.com/ybRoh/machine-cad-download/issues)에 올리거나 배포한 분께 알려 주세요.
- 작업한 파일은 **파일 → 저장**으로 따로 보관하세요. 베타 버전입니다.
