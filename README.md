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
| `git log` | 최근 포스트 |
| `uname -a` | 커널 정보 |
| `contact` | 연락처 |
| `clear` | 화면 지우기 |

## Features

- Tab 자동완성 (명령어 + 파일명/디렉토리)
- 방향키 히스토리 (Up/Down)
- 실시간 uptime / load 표시
- 부팅 애니메이션
- 가상 파일시스템 (`~/posts/`, `~/projects/`)

## Tech

- Vanilla JS (프레임워크 없음)
- JetBrains Mono 폰트
- GitHub Pages 호스팅
