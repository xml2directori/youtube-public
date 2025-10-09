# ❤️ 대용량 유튜브 비디오 다운로더 5.0 🎥

대용량 **YouTube 비디오 다운로더**, **YouTube MP4 다운로더**, **YouTube MP3 다운로더**, **온라인 YouTube 다운로더**, **무료 YouTube 다운로더**, **워터마크 없는 YouTube 비디오 다운로더**, **YouTube 비디오 다운로더 no watermark**, **YouTube 비디오 다운로더 4K/8K**, **최고의 YouTube HD 다운로더**.  

<div align="center">
  <a href="../../releases/latest">
    <img width="1000" alt="YouTube Video Downloader No Watermark Banner" src="assets/release.png" />
  </a>
</div>

### 고급 기능을 갖춘 현대적인 YouTube 다운로더

[![Python](https://img.shields.io/badge/Python-3.13%2B-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![PySide6](https://img.shields.io/badge/UI-PySide6-41CD52?style=for-the-badge&logo=qt&logoColor=white)](https://pypi.org/project/PySide6/)
[![requests](https://img.shields.io/badge/HTTP-requests-2496ED?style=for-the-badge&logo=python&logoColor=white)](https://pypi.org/project/requests/)
[![FFmpeg](https://img.shields.io/badge/External-FFmpeg-007808?style=for-the-badge&logo=ffmpeg&logoColor=white)](https://ffmpeg.org/)

---

## 📋 목차
- [주요 기능](#-key-features)
- [설치](/../../releases)
- [사용법](#-usage)
- [스크린샷](showcase/showcase.md)
- [기여](CONTRIBUTING.md)
- [라이선스](LICENSE)

### 📜 라이선스
[![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge&logo=gnu&logoColor=white)](LICENSE)

---

## 🌟 주요 기능

### 🛠️ 핵심 기능
- **다운로드 지원**  
  모든 YouTube 링크에서 비디오 및 오디오 다운로드 가능. **플레이리스트, 채널, Shorts, 비공개/미등록 영상** 모두 지원.

- **스마트 플레이리스트 정리**  
  플레이리스트 이름으로 된 폴더에 자동 정리되어 저장.

- **플레이리스트 다운로드**  
  몇 번의 클릭만으로 전체 **YouTube 플레이리스트**를 순차적으로 다운로드.

- **다양한 포맷 지원**  
  **MP4**(비디오), **MP3**, **M4A**, **WAV**, **AAC**, **FLAC**, **OPUS**, **VORBIS** 등 다양한 오디오 포맷으로 고품질 다운로드.

- **고급 오디오 품질 제어** 🎵  
  무손실 추출 기능을 갖춘 혁신적인 오디오 처리 시스템:
  - **Smart Copy 모드**: M4A/AAC/OPUS 포맷에서 품질 손실 없음
  - **사용자 지정 비트레이트**: 128k, 192k, 256k, 320k, 또는 “best”
  - **원본 품질 유지**: 불필요한 인코딩 방지
  - **고충실도 대체 모드**: 320k 비트레이트 + 48kHz 샘플링
  - **포맷별 자동 최적화**

- **고해상도 지원**  
  최대 **8K, 4K, 2K, 1080p, 720p, 360p**까지 지원. 설정에서 원하는 해상도 선택 가능.

- **모듈형 코드 구조**  
  `core/`, `ui/`, `tests/` 디렉토리로 리팩토링되어 유지보수 및 기여가 용이.

---

### 🛠️ 고급 기능
- **배치 처리**  
  여러 개의 YouTube 비디오를 한 번에 큐에 추가해 동시에 관리. 일시정지, 재개, 취소 모두 가능.

- **오디오 품질 혁신** 🎵  
  비트레이트 67% 향상 및 무손실 추출 지원.

- **프로필 관리**  
  사용자 이름, 다운로드 경로, 비디오 해상도, 오디오 포맷 등 설정을 저장.

- **프로필 내보내기 / 가져오기**  
  프로필, 설정, 기록, 프로필 이미지를 ZIP 파일로 내보내고 다른 장치에서 복원 가능.

- **드래그 앤 드롭 인터페이스**  
  YouTube URL을 앱에 드래그하여 즉시 추가.

- **시스템 트레이 통합**  
  최소화 시 트레이에 상주하며 빠른 접근 메뉴로 복원 및 종료 가능.

- **향상된 다운로드 시스템**  
  대용량 파일 안정적 다운로드 및 다중 병렬 다운로드 지원.

- **큐 시스템 최적화**  
  일시정지/재개 전체 기능 및 프록시를 통한 대역폭 제한.

- **자동 업데이트**  
  새 버전을 자동으로 확인하고 설치.

---

### 🎨 사용자 경험
- **다크 & 라이트 모드**  
  다크 테마와 라이트 테마 간 전환 가능.

- **에러 처리**  
  문제 디버깅용 상세 에러 로그.

- **스케줄러**  
  특정 날짜와 시간에 다운로드 자동 시작 예약 가능.

- **다운로드 기록**  
  모든 과거 다운로드 내역을 조회, 검색, 관리 가능.

- **향상된 알림 시스템**  
  **다운로드 완료**, **실패**, **취소됨** 상태 알림.

- **개선된 UI**  
  현대적인 애니메이션, 검색 및 필터 옵션 제공.

---

### 🔧 기술적 기능
- **FFmpeg 자동 감지**  
  FFmpeg이 설치되어 있지 않으면 자동으로 감지 및 설정 요청.
  
## 스크린샷

### 홈화면
![Image](assets/homepage.png)

### 비디오 페이지
![Image](assets/videopage.png)

### 오디오 페이지
![Image](assets/audiopages.png)

### 기록 페이지
![Image](assets/history.png)

---

## ⚙️ 설치 방법

### Windows
- [Releases](../../releases)에서 최신 `.exe` 인스톨러 또는 `.zip` 아카이브 다운로드  
- FFmpeg 포함 모든 의존성 내장  
- 설치 후 또는 압축 해제 후 `YouTube Downloader.exe` 실행  

---

## 🔧 사용법

### 기본 사용
```bash
# 앱 실행
python main.py
````

### 주요 기능 사용

* **설정(Settings)** 에서 프로필 구성
* **MP4** 또는 **MP3** 탭에서 비디오 다운로드 또는 오디오 추출
* 여러 항목을 큐에 추가하여 순차 다운로드
* 예약 기능으로 자동 다운로드 설정

### 팁 & 트릭

* 드래그 & 드롭으로 빠른 URL 추가
* 백그라운드 실행을 위해 트레이 모드 활성화
* 야간 시간대 다운로드 스케줄링
* **최고 음질**: 원본 유지 + 320k 비트레이트
* **무손실 오디오**: M4A/FLAC + copy 모드
* 프로필을 내보내어 다른 장치로 이동

---

## ⚠️ 참고 사항

### 요구사항

```bash
# FFmpeg 필수
# 일부 기능(오디오 추출, 비디오 병합 등)은 FFmpeg에 의존합니다.
# 시스템 PATH에 FFmpeg이 설정되어 있어야 합니다.

# 서드파티 라이브러리
# yt_dlp를 사용하여 다운로드 및 메타데이터 추출을 수행합니다.
```

---

## 🙏 기여 안내

### 기여 방법

```bash
# YouTube Downloader 5.0 개선을 위한 모든 기여를 환영합니다.
# GitHub에서 issue 또는 pull request를 제출해주세요.

# 즐겁게 사용하세요! 🚀
```

### 개발 환경 설정

1. 저장소 Fork
2. 새 브랜치 생성
3. 변경 사항 적용
4. Pull Request 제출

---

## ⚠️ 법적 고지

**YouTube Downloader**는 독립적인 오픈소스 프로젝트입니다.
**YouTube**나 **Google**의 API를 사용하지 않으며, 완전히 독립적으로 작동합니다.
본 프로젝트는 YouTube 서비스 약관에 구속되지 않습니다.

---

## 🔑 SEO 키워드

**유튜브 비디오 다운로더, 유튜브 다운로더 HD, 유튜브 다운로더 4K, 유튜브 MP4 다운로더, 유튜브 MP3 다운로더, 무료 유튜브 다운로더, 워터마크 없는 유튜브 다운로더, 무료로 유튜브 영상 다운로드, 최고의 유튜브 다운로더, 유튜브 비디오 그랩버, 온라인 유튜브 다운로더, PC용 유튜브 영상 다운로드, 안드로이드용 유튜브 다운로더, 아이폰용 유튜브 다운로더, 유튜브 영상을 갤러리에 저장, 유튜브 플레이리스트 다운로더, 유튜브 채널 다운로더, 유튜브 쇼츠 다운로더, 유튜브 8K 영상 다운로드.**
