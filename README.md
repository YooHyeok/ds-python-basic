# Anaconda
**[아나콘다 설치 공식 페이지](https://www.anaconda.com/download/success)**
1. 패키지 매니지먼트
Python에서 사용되는 Scientific computing 관련 패키지 혹은 라이브러리를 포함시켜 배포하는 기능이 있다.  
conda라는 패키지 매니저가 라이브러리를 설치, 관리해준다.

2. 배포 목적
Python은 venv 같은 가상환경 기능을 통해 프로젝트별로 독립된 실행 환경과 라이브러리 환경을 구성할 수 있다.
Anaconda는 conda를 통해 이러한 가상환경을 더 쉽게 만들고 관리할 수 있게 해주며,
프로젝트마다 필요한 Python 버전과 패키지 버전을 분리해서 사용할 수 있도록 도와준다.

<br>
<hr>
<br>

# Jupyter Notebook/Lab
ipynb 확장자로 구성되며 실험, 기록등의 연습장, 플레이그라운드 개념
- 셀: 코드 입력란
- 셀 실행 횟수: 좌측 [n] 표기

### 명령 단축키
- 셀 실행
  - 단순 실행: Ctrl + Enter
  - 실행 후 다음 셀 추가: Shift + Enter
- 읽기모드 : ESC
- 셀 추가(아래) : b
- 셀 추가(위) : a
- 셀 삭제 : dd
- 실행취소 : z
- 복사/붙여넣기/잘라내기 : c / v / x

### 마크다운 셀(타입)
코드셀에 한글이나 영어와 같은 텍스트를 입력하고 실행하면 오류가 발생하므로 파이썬이 이해할 수 있는 명령어만 입력해야한다.
마크다운 셀에서는 허용해준다.
- 코드셀/마크다운 단축키: y/m
- 셀 분리: Shift + -
- 셀 병합: Shift + M

### 코드 셀(타입)
Python 문법을 입력하여 실행 가능하며, 시스템 관련 터미널 명령도 작동한다.
- 주피터 시스템 터미널 명령어 : ls / pwd 등
- 텍스트 + tab 키 : jupyter 혹은 python에서 제공하는 키워드 자동완성 제공
- Shift + tab : 공식 함수 등에 대한 도큐먼트 제공

<br>
<hr>
<br>

# Extension 설치

### Table Of Contents Extension

**[구글 jupytor toc 검색 > Github Repository](https://github.com/jupyterlab/jupyterlab-toc)**

```bash
jupyter labextension install @jupyterlab/toc
```
최신 Anaconda/JupyterLab 계열에서는 TOC가 기본으로 지원되고있음.  
위의 적용방법처럼 다른 Extension을 설치하면됨.