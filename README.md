# MyUtils - All In One

**85가지 macOS 유틸리티를 하나의 메뉴 막대 앱으로.** 창 스냅부터 화면 캡처·마크다운 편집기·가사 자막 생성까지, 자주 쓰는 도구를 모듈로 묶었습니다. 필요한 모듈만 켜서 쓰고, 한국어·영어·일본어를 지원합니다.

**85 macOS utilities in one menu bar app.** Window snapping, screen capture, Markdown editor, lyrics subtitle generator and more — each a module you can switch on or off. Korean, English and Japanese UI.

## 소개 페이지 · Overview

기능을 한눈에 보려면 **[myutil 소개 페이지](https://myutils-mac.vercel.app/)** 를 보세요. 한국어·영어를 지원합니다.
See the **[MyUtils overview page](https://myutils-mac.vercel.app/)** for a visual tour. Available in Korean and English.

## 다운로드 · Download

- **최신 버전 / Latest**: **v2.6.4** (2026-09-17) — [MyUtil-2.6.4.dmg](https://github.com/naggingmachine/myutil-releases/releases/download/v2.6.4/MyUtil-2.6.4.dmg) · [릴리스 노트 / Release notes](https://github.com/naggingmachine/myutil-releases/releases/tag/v2.6.4) · [모든 버전 / All releases](https://github.com/naggingmachine/myutil-releases/releases)
- macOS 14 Sonoma 이상, Apple Silicon / Intel. Developer ID 서명과 Apple 공증이 완료되어 경고 없이 실행됩니다.

### 설치 · Install
1. DMG 를 열고 `MyUtils - All In One.app` 을 `Applications` 폴더로 드래그합니다. / Open the DMG and drag `MyUtils - All In One.app` to `Applications`.
2. 메뉴 막대의 격자 아이콘을 누르면 검색 필드와 카테고리 메뉴가 나옵니다. **설정…** 에서 모듈을 켜고 끄세요. / Click the grid icon in the menu bar; use **Settings…** to enable modules.
3. 처음에는 MyUtils 아이콘만 표시됩니다. 설정 > 일반 > "메뉴 막대에 표시할 항목" 에서 시계·CPU·타이머 같은 항목을 메뉴 막대에 추가할 수 있습니다.

### 권한 · Permissions
일부 모듈은 macOS 권한이 필요합니다. 각 모듈 설정 상단의 배너에서 요청할 수 있습니다.

| 권한 | 필요한 모듈 |
|---|---|
| 손쉬운 사용 (Accessibility) | 창 스냅, 클립보드 붙여넣기, 스니펫 확장, 한/영 교정, 이모지 입력, 단축키 치트시트, 커서 하이라이트, 읽어주기·번역의 선택 텍스트 |
| 화면 기록 (Screen Recording) | 화면 캡처, 화면 OCR, 컬러 피커, 픽셀 자, QR 인식 |
| 위치 / 캘린더 | 날씨·달력, Wi-Fi 비밀번호(SSID) |
| 마이크 | 음성 메모 |
| 관리자 권한 (root helper) | 배터리 충전 제한, 웹사이트 차단 — 앱 설정의 "helper 설치" 버튼으로 등록 |

## 유틸리티 목록 (한국어)

### 창·디스플레이

| 유틸리티 | 설명 |
|---|---|
| **창 스냅** | 단축키로 창을 반/사분할/최대화/중앙 정렬 |
| **클램셸·디스플레이 프로필** | 디스플레이 조합별 구성 저장·자동 적용 |
| **화면 켜짐 유지** | 잠자기와 화면 꺼짐 방지 |
| **창 레이아웃** | 창 배치를 이름 붙여 저장하고 단축키로 복원 |
| **외장 모니터 밝기** | 외장 모니터 밝기·대비·볼륨을 단축키와 메뉴로 조절 |
| **화면 색온도** | 야간 모드·True Tone 을 앱에서 바로 조절 |
| **창 띄워 두기** | 다른 창을 항상 위에 뜨는 작은 창으로 띄워 둡니다 |

### 화면 캡처

| 유틸리티 | 설명 |
|---|---|
| **스크린샷 관리** | 새 스크린샷을 OCR 로 읽어 앱·키워드 기반 이름 짓기, 폴더 분류, 태그·Spotlight 코멘트 저장 |
| **컬러 피커** | 화면 어디서든 색 추출 |
| **커서 하이라이트** | 발표용 커서 강조·키 입력 표시 |
| **화면 캡처·편집** | 단축키로 영역·창·전체 캡처 후 주석 편집 |
| **화면 텍스트 인식** | 화면 영역을 선택해 텍스트를 인식·복사 |
| **픽셀 자** | 화면 위 거리·영역 크기를 픽셀로 측정 |
| **화면 녹화** | 영역·창·전체 화면을 동영상이나 GIF 로 녹화 |
| **화면 스튜디오** | 녹화한 화면을 자동 확대·부드러운 커서로 다듬어 영상 제작 |
| **화면에 그리기** | 발표 중에 화면 위에 도형과 선을 그려 설명합니다 |

### 입력·키보드

| 유틸리티 | 설명 |
|---|---|
| **클립보드 히스토리** | 복사 기록 검색·붙여넣기 (⌘⇧V) |
| **텍스트 스니펫 확장** | 트리거 문자열(;addr 등)을 긴 텍스트로 확장 |
| **한/영 전환 교정** | 직전 단어를 한↔영 변환 (⌥Space), 오타 자동 감지 |
| **이모지·특수문자** | 검색형 이모지·기호 팔레트 (⌥⌘E) |
| **단축키 치트시트** | 활성 앱의 메뉴 단축키를 오버레이로 표시 (⌃⌥/, ⌘ 길게) |
| **앱별 입력기 기억** | 앱마다 한글·영문 입력기를 기억해 전환할 때 자동으로 되돌리기 |
| **마우스 옆 버튼** | 옆 버튼으로 뒤로·앞으로 이동 |
| **PC 키 동작** | Home·End 를 Windows 처럼 줄 끝으로 |
| **링크 청소기** | 복사한 링크에서 추적 파라미터를 떼어 냅니다 |
| **서식 없이 붙여넣기** | 복사한 글의 글꼴·색을 떼고 글자만 붙여 넣습니다 |

### 파일·디스크

| 유틸리티 | 설명 |
|---|---|
| **다운로드 자동 정리** | 다운로드 폴더를 규칙에 따라 자동 정리 (하위 폴더 이동·이름 변경·태그·휴지통, 되돌리기 지원) |
| **중복 파일 찾기** | 크기 → 앞 4KB → SHA-256 3단계 비교와 이미지 pHash 유사 검출로 중복 파일을 찾아 휴지통으로 정리 |
| **일괄 이름 변경** | 규칙 체인으로 파일 이름을 일괄 변경하고 되돌리기 |
| **PDF 도구** | PDF 합치기·분할·페이지 관리·압축·이미지 변환·암호·메타데이터·텍스트 추출 |
| **디스크 사용량** | 폴더별 용량을 스캔해 트리·선버스트·트리맵으로 보고 큰 파일을 정리 |
| **캐시 정리** | 사용자 캐시·로그·개발 도구 캐시 용량을 계산하고 휴지통으로 정리 |
| **압축·해제** | zip·tar·gz 압축과 해제, 암호 압축 지원 |
| **드래그 셸프** | 드래그 중인 파일을 잠시 모아 두는 보관대 |
| **파인더 보강** | 잘라내기·새 파일·경로 복사·터미널 열기 |

### 미디어

| 유틸리티 | 설명 |
|---|---|
| **이미지 압축·변환** | 드롭 또는 Finder 퀵액션으로 이미지를 JPG/PNG/WebP/HEIC 로 변환·리사이즈·압축 (프리셋 지원) |
| **오디오 전환** | 입출력 장치 전환·볼륨 |
| **가사 자막 생성** | 음악 파일과 가사로 SRT 자막 생성·편집 (유튜브·DistroKid) |
| **음성 메모·받아쓰기** | 녹음 후 온디바이스 받아쓰기로 텍스트 변환 |
| **앱 아이콘 생성기** | 이미지 한 장으로 앱 아이콘·파비콘 세트 생성 |
| **미디어 변환** | 동영상·오디오 포맷 변환, 자르기, 오디오 추출, GIF 만들기 |
| **동영상 플레이어** | 자막·재생 속도·PiP 를 지원하는 동영상·음악 플레이어 |
| **유튜브 다운로드** | 유튜브 영상·음원을 화질 골라 내려받기 |
| **자막 스튜디오** | 자막 자동 추출·편집·효과 입혀 영상에 굽기 |
| **이미지 배경 제거** | 사진에서 피사체만 남기고 배경을 지웁니다 (기기 안에서 처리) |

### 텍스트·개발

| 유틸리티 | 설명 |
|---|---|
| **마크다운 편집기** | 구문 강조·실시간 미리보기·열기·저장이 되는 MD 편집기 |
| **개발자 도구상자** | JSON 포맷, Base64, URL 인코딩, 해시, UUID, 타임스탬프, 진법 변환 |
| **정규식 테스터** | 정규식 실시간 매칭·그룹·치환 테스트 |
| **계산 메모** | 자연어 수식을 줄 단위로 계산하는 메모형 계산기 |
| **텍스트 읽어주기** | 선택한 텍스트나 클립보드를 음성으로 읽기 |
| **빠른 번역** | 선택 텍스트를 온디바이스로 번역(한·영·일 등) |
| **선택 텍스트 변환** | 고른 글자를 대소문자·슬러그·공백 정리 등으로 그 자리에서 바꿉니다 |

### 시스템·앱

| 유틸리티 | 설명 |
|---|---|
| **배터리 충전 제한** | 지정 퍼센트에서 충전 중단 (SMC + helper) |
| **시스템 모니터** | CPU·메모리·네트워크 메뉴바 표시 |
| **앱 사용 시간** | 앱별 사용 시간 자동 기록(유휴 제외), 카테고리·히트맵 리포트 |
| **앱 완전 삭제** | 앱과 관련 지원 파일·캐시·설정을 찾아 휴지통으로 이동 |
| **블루투스 배터리** | 에어팟·키보드·마우스 등 블루투스 기기 배터리 표시 |
| **빠른 실행** | 앱·시스템 설정·모듈을 단축키로 검색해 실행 (⌃Space) |
| **시작 항목 관리** | 로그인 항목·런치 에이전트 정리와 앱 일괄 종료 |
| **기본 앱 설정** | 확장자별 기본 앱을 한곳에서 바꾸기 |
| **작업 관리자** | 멈춘 앱을 바로 찾아 종료 |
| **예약 종료·잠자기** | 정한 시각이나 시간 뒤에 종료·재시작·잠자기를 예약합니다 |

### 네트워크

| 유틸리티 | 설명 |
|---|---|
| **Wi-Fi 비밀번호** | 저장된 Wi-Fi 비밀번호 확인·QR 공유 |
| **네트워크 정보** | 내부·공인 IP, DNS, Wi-Fi 신호, 핑, 속도 측정 |
| **앱별 네트워크 사용량** | 어떤 앱이 얼마나 통신하는지 실시간으로 확인 |
| **Wi-Fi 따라 프로필** | 연결한 Wi-Fi 에 따라 오디오·프린터·앱을 한꺼번에 바꿉니다 |
| **폴더 공유 서버** | 폴더를 같은 네트워크에 웹으로 띄우고 QR 로 주소를 보여 줍니다 |

### 보안

| 유틸리티 | 설명 |
|---|---|
| **비밀번호 생성기** | 안전한 비밀번호·패스프레이즈 생성과 강도 평가 |
| **2단계 인증** | TOTP 인증 코드 생성과 자동 복사 |
| **파일 암호화** | 암호로 파일·폴더를 AES-256-GCM 으로 암호화하고 복호화 (.myenc) |
| **마이크·카메라 감시** | 지금 어떤 앱이 마이크와 카메라를 쓰는지 메뉴 막대에서 보여 줍니다 |

### 시간·생산성

| 유틸리티 | 설명 |
|---|---|
| **날씨·달력** | 메뉴바 날짜 표시, 현재 위치 날씨와 오늘·내일 일정, 미니 달력 |
| **세계 시계·환율** | 메뉴바에 여러 도시 시각, 미팅 시간 계산기, 환율 계산기 |
| **포모도로 타이머** | 메뉴바 포모도로 타이머, 휴식 오버레이, 세션 기록과 통계 |
| **웹사이트 차단** | 집중 세션 동안 사이트 차단 (hosts) |
| **빠른 메모** | 단축키로 여는 마크다운 메모 패널 (⌃⌥N) |
| **빠른 할 일** | 메뉴 막대에서 바로 적는 할 일 목록 |
| **타이머·스톱워치** | 여러 개의 타이머·스톱워치·알람을 메뉴 막대에서 |
| **휴식 알림** | 눈 휴식(20-20-20)·스트레칭 알림 |
| **디데이** | 기념일·마감 디데이를 메뉴 막대에 표시 |
| **일기장** | 날짜별 일기 작성, 기분·태그 기록, 달력 보기와 검색 (⌃⌥W) |

### 메뉴 막대

| 유틸리티 | 설명 |
|---|---|
| **빠른 토글** | 다크 모드·색온도·마이크 음소거·숨김 파일 등 자주 쓰는 토글 모음 |
| **메뉴 막대 정리** | 메뉴 막대 아이콘을 접어 두고 필요할 때만 펼치기 |

### 기타

| 유틸리티 | 설명 |
|---|---|
| **QR 생성·인식** | 클립보드 QR 생성, 화면 QR 인식 |
| **단위 변환** | 길이·무게·온도·데이터·시간·면적·속도 단위 변환 |

## Utilities (English)

### Windows & Displays

| Utility | Description |
|---|---|
| **Window Snap** | Snap windows to halves, quarters, maximize or center with hotkeys |
| **Clamshell & Display Profiles** | Save a layout per display combination and re-apply it automatically |
| **Keep Awake** | Prevent sleep and display dimming |
| **Window Layouts** | Save named window arrangements and restore them with a hotkey |
| **External Display Brightness** | Control external display brightness, contrast and volume from hotkeys and the menu bar |
| **Display Warmth** | Control Night Shift and True Tone right here |
| **Pin a Window** | Keep another window in a small always-on-top window |

### Screen Capture

| Utility | Description |
|---|---|
| **Screenshot Manager** | Reads new screenshots with OCR to name them by app and keywords, sort into folders, and save tags and Spotlight comments |
| **Color Picker** | Pick a color from anywhere on screen |
| **Cursor Highlight** | Highlight the cursor & show keystrokes for presentations |
| **Screen Capture & Annotate** | Capture an area, window, or screen with a hotkey, then annotate |
| **Screen Text Recognition** | Select a screen area to recognize and copy text |
| **Pixel Ruler** | Measure distances and area sizes on screen in pixels |
| **Screen Recorder** | Record an area, a window, or the whole screen to video or GIF |
| **Screen Studio** | Turn screen recordings into polished videos with auto zoom and a smooth cursor |
| **Draw on Screen** | Draw shapes and lines over the screen to explain things while presenting |

### Input & Keyboard

| Utility | Description |
|---|---|
| **Clipboard History** | Search and paste from your copy history (⌘⇧V) |
| **Text Snippets** | Expand trigger strings (;addr, …) into longer text |
| **Korean/English Fixer** | Convert the previous word between Korean and English (⌥Space), detect layout typos |
| **Emoji & Symbols** | Searchable emoji and symbol palette (⌥⌘E) |
| **Shortcut Cheatsheet** | Overlay showing the active app's menu shortcuts (⌃⌥/, hold ⌘) |
| **Per-App Input Source** | Remembers each app's Korean/English input source and restores it when you switch apps |
| **Mouse Side Buttons** | Navigate back and forward with the side buttons |
| **PC Key Behavior** | Home/End jump to line ends, like Windows |
| **Link Cleaner** | Strips tracking parameters from links you copy |
| **Paste Without Formatting** | Drops the font and colour from copied text and pastes the words only |

### Files & Disk

| Utility | Description |
|---|---|
| **Downloads Organizer** | Automatically tidies your Downloads folder by rules (move to subfolder, rename, tag, trash — with undo) |
| **Duplicate Finder** | Finds duplicate files with a 3-stage size → first 4KB → SHA-256 comparison plus pHash image similarity, then moves them to the Trash |
| **Batch Renamer** | Rename files in bulk with rule chains, with undo |
| **PDF Tools** | Merge, split, manage pages, compress, convert to images, password, metadata, extract text |
| **Disk Usage** | Scan folder sizes as tree, sunburst or treemap and clean up large files |
| **Cache Cleaner** | Measure user caches, logs and developer tool caches and clean them to the Trash |
| **Archiver** | Compress and extract zip/tar/gz archives, with password-protected zip support |
| **Drag Shelf** | A temporary holding area for files you are dragging |
| **Finder Plus** | Cut & paste, new file, copy path, open terminal |

### Media

| Utility | Description |
|---|---|
| **Image Converter** | Convert, resize, and compress images to JPG/PNG/WebP/HEIC by drag & drop or a Finder Quick Action (with presets) |
| **Audio Switcher** | Switch input/output devices & volume |
| **Lyrics Subtitles** | Create and edit SRT subtitles from a music file and lyrics (YouTube, DistroKid) |
| **Voice Memo & Dictation** | Record, then transcribe on-device |
| **App Icon Generator** | Generate app icon and favicon sets from a single image |
| **Media Converter** | Convert video/audio formats, trim clips, extract audio, and make GIFs |
| **Media Player** | Video and audio player with subtitles, playback speed and Picture in Picture |
| **YouTube Downloader** | Download YouTube video or audio at the quality you choose |
| **Subtitle Studio** | Auto-extract, edit, and burn styled subtitles into video |
| **Remove Image Background** | Keeps only the subject and erases the background (processed on device) |

### Text & Developer

| Utility | Description |
|---|---|
| **Markdown Editor** | Markdown editor with syntax highlighting, live preview, open and save |
| **Developer Toolbox** | JSON formatting, Base64, URL encoding, hashes, UUID, timestamps, radix conversion |
| **Regex Tester** | Live regex matching, groups and replacement |
| **Calc Notes** | Notepad-style calculator that evaluates each line as you type |
| **Text to Speech** | Read selected text or the clipboard aloud |
| **Quick Translate** | Translate selected text on-device (Korean, English, Japanese, …) |
| **Transform Selected Text** | Changes the text you selected in place — case, slug, whitespace and more |

### System & Apps

| Utility | Description |
|---|---|
| **Battery Charge Limit** | Stop charging at a chosen percentage (SMC + helper) |
| **System Monitor** | CPU, memory & network in the menu bar |
| **App Usage** | Automatically logs time per app (idle excluded) with category and heatmap reports |
| **App Uninstaller** | Find an app's support files, caches and preferences and move them to the Trash |
| **Bluetooth Battery** | Show battery of AirPods, keyboards, mice and other Bluetooth devices |
| **Quick Launcher** | Search and launch apps, system settings and modules with one shortcut (⌃Space) |
| **Startup Items** | Review login items and launch agents, and quit running apps in bulk |
| **Default Apps** | Change the default app for every file extension in one place |
| **Task Manager** | Find and quit a stuck app instantly |
| **Scheduled Shutdown & Sleep** | Schedule a shutdown, restart or sleep at a time or after a delay |

### Network

| Utility | Description |
|---|---|
| **Wi-Fi Password** | View saved Wi-Fi passwords & share as QR |
| **Network Info** | Local & public IP, DNS, Wi-Fi signal, ping, speed test |
| **Per-App Network Usage** | See which apps are using the network, live |
| **Wi-Fi Profiles** | Switch audio, printer and apps together based on the Wi-Fi network you join |
| **Folder Sharing Server** | Serves a folder over your local network and shows the address as a QR code |

### Security

| Utility | Description |
|---|---|
| **Password Generator** | Generate secure passwords and passphrases with strength rating |
| **Two-Factor Auth** | Generate TOTP codes and copy them in one click |
| **File Encryption** | Encrypt and decrypt files and folders with a password using AES-256-GCM (.myenc) |
| **Mic & Camera Watch** | Shows in the menu bar which apps are using the microphone and camera right now |

### Time & Productivity

| Utility | Description |
|---|---|
| **Weather & Calendar** | Date in the menu bar, local weather, today's and tomorrow's events, and a mini calendar |
| **World Clock & Currency** | City times in the menu bar, a meeting time finder, and a currency converter |
| **Pomodoro Timer** | Menu bar Pomodoro timer with break overlay, session history, and statistics |
| **Website Blocker** | Block distracting sites during focus sessions (hosts) |
| **Quick Notes** | Markdown notes panel opened with a shortcut (⌃⌥N) |
| **Quick Todo** | A to-do list you jot down right from the menu bar |
| **Timers & Stopwatch** | Multiple timers, a stopwatch and alarms from the menu bar |
| **Break Reminder** | Eye rest (20-20-20) and stretch reminders |
| **D-Day** | Show anniversaries and deadlines as D-Day counters in the menu bar |
| **Diary** | Daily journal with mood, tags, calendar view and search (⌃⌥W) |

### Menu Bar

| Utility | Description |
|---|---|
| **Quick Toggles** | Dark mode, color temperature, mic mute, hidden files and other everyday toggles |
| **Menu Bar Tidy** | Fold menu bar icons away and unfold them only when you need them |

### Everything Else

| Utility | Description |
|---|---|
| **QR Generate & Scan** | Make QR from clipboard, read QR from screen |
| **Unit Converter** | Convert length, mass, temperature, data, time, area and speed units |

## 주요 기능 · Highlights

- **바탕화면 위젯**: 디데이·할 일·포모도로·시스템 모니터 등 14종을 바탕화면에 띄웁니다. 클릭을 통과시켜 아이콘을 가리지 않게 할 수 있고, 크기·투명도를 조절합니다. / **Desktop widgets**: 14 widgets you can pin to the desktop, with click-through, size and opacity control.
- **iCloud 동기화**: 메모·일기·클립보드 같은 데이터를 iCloud Drive 에 두어 맥 사이에서 이어 씁니다. 기본은 전체 동기화이고 모듈별로 제외할 수 있습니다. / **iCloud sync**: keep module data in iCloud Drive across Macs; everything syncs by default, exclude modules individually.
- **메뉴 검색**: 메뉴 막대 아이콘 → 맨 위 검색 필드에 이름을 입력하면 바로 필터링, Return 으로 실행.
- **즐겨찾기·최근 사용**: 자주 쓰는 모듈은 메뉴 맨 위에 고정, 최근 사용 3개 자동 표시.
- **세계 시계**: 메뉴 막대 시계를 누르면 도시별 시각·국가·시간대·시차를 한눈에, 회의 시간 찾기 그리드 포함.
- **가사 자막 생성**: 음악 파일의 보컬을 온디바이스 음성 인식으로 분석해 SRT/LRC 타임스탬프 자동 생성, 파형 편집기.
- **화면 캡처·편집**: ⌃⇧3/4/5 캡처 후 화살표·텍스트·번호·모자이크·자르기 주석, 복사·저장·공유.

## 문의 · Feedback

버그 제보나 기능 제안은 이 저장소의 [Issues](https://github.com/steve-bmf/myutil-releases/issues) 에 남겨 주세요. / Please file bugs and requests in Issues.

## 라이선스 · License

배포 바이너리는 무료로 사용할 수 있습니다. 소스 코드는 비공개입니다. / The binary is free to use; source is not public.
