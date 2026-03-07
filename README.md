# EndofLinux Terminal

블로그 [www.endoflinux.com](https://www.endoflinux.com)에 임베드되는 인터랙티브 웹 터미널입니다.

## Demo

GitHub Pages: [lowahn.github.io/terminal/terminal.html](https://lowahn.github.io/terminal/terminal.html)

## Commands

| Command | Description |
|---------|-------------|
| `help` | 명령어 목록 |
| `whoami` | 블로그 주인장 정보 |
| `ls [dir]` | 파일 목록 |
| `cat <file>` | 파일 내용 보기 |
| `cd <dir>` | 디렉토리 이동 |
| `neofetch` | 시스템 정보 |
| `ps aux` | 실행 중 프로세스 |
| `df -h` | 디스크 사용량 |
| `git log` | 실제 블로그 최근 포스트 (Blogger API 연동) |
| `open <번호>` | git log 결과에서 포스트 열기 |
| `uname -a` | 커널 정보 |
| `contact` | 연락처 |
| `clear` | 화면 지우기 |

## Features

- **블로그 실시간 연동** - `git log`가 실제 Blogger 피드에서 최근 포스트를 가져옴
- **포스트 바로가기** - `git log` 결과의 제목 클릭 또는 `open <번호>`로 포스트 이동
- **Tab 자동완성** - 명령어 + 파일명/디렉토리 자동완성
- **방향키 히스토리** - Up/Down으로 이전 명령어 탐색
- **실시간 상태바** - uptime / load 실시간 표시
- **부팅 애니메이션** - 터미널 접속 시 부팅 시퀀스 표시
- **가상 파일시스템** - `~/posts/`, `~/projects/` 디렉토리 탐색

## Changelog

### v2026.03.07
- `git log` Blogger API 연동 (실제 포스트 표시)
- `open <번호>` 명령어 추가 (포스트 바로 열기)
- `git log` 결과 제목 클릭 시 해당 포스트로 이동
- neofetch ASCII 아트 개선
- Tab 자동완성에 파일명/디렉토리 지원 추가
- endofpython → endoflinux 전체 리브랜딩

## Tech

- Vanilla JS (프레임워크 없음)
- Blogger JSON Feed API
- JetBrains Mono 폰트
- GitHub Pages 호스팅
