# MIIIME Snippet Picker (MSP™)
MIIIMESnippetPicker · 미메스니펫피커<br>

![OS](https://img.shields.io/badge/Platform-Windows-0078D4?logo=windows&style=flat-square)
[![Language](https://img.shields.io/badge/Language-AutoIt-orange?logo=autoit&style=flat-square)](https://www.autoitscript.com/site/)
![License](https://img.shields.io/badge/License-Freeware-lightgrey?style=flat-square)

<br>
<img width="559" height="136" alt="001" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Enhanced/Id/Neon/4b_136_1_G.png?raw=true" style="margin-top: 20px; margin-bottom: 20px;">
<br>

A lightweight Windows desktop utility that lets you build text strings from registered special characters and symbols, then copy them to the clipboard.  

등록된 특수문자·기호를 버튼 클릭으로 조합해 클립보드에 복사하는 경량 Windows 데스크탑 유틸리티입니다.

<br>
<img width="211" height="549" alt="001" src="https://github.com/miiimeworks/MSP/blob/main/Preview/001.png?raw=true" style="margin-top: 20px; margin-bottom: 20px;"> 
<br>

---

## Overview

- Build text strings by clicking snippet buttons / 스니펫 버튼 클릭으로 문자열 조합
- Copy assembled text to clipboard with one click / 조합된 텍스트를 원클릭으로 클립보드 전송
- Category and snippet data managed via INI file / INI 파일로 카테고리 및 스니펫 데이터 관리
- 4-tier button layout (Size 1–4): 8 / 4 / 2 / 1 columns / 4단계 버튼 레이아웃: 8열 / 4열 / 2열 / 1열
- Undo stack with configurable depth / 횟수 설정 가능한 Undo 스택 지원
- MIIIME Dark Square Theme applied / MIIIME Dark Square Theme 적용

---

## Features

### Button Layout (Size 1–4) / 버튼 레이아웃

| Size | Columns / 열 수 | Button Width / 버튼 폭 | Max Items / 최대 개수 |
|------|----------------|----------------------|----------------------|
| 1    | 8              | 23 px                | 64                   |
| 2    | 4              | 66 px                | 32                   |
| 3    | 2              | 133 px               | 16                   |
| 4    | 1              | 270 px               | 8                    |

### Controls / 조작 버튼

| Button / 버튼 | Function / 기능 |
|--------------|----------------|
| T | Toggle Always on Top / 항상 위 토글 |
| I | Open INI file / INI 파일 열기 |
| R | Clear input field / 입력창 초기화 |
| U | Undo last snippet / 마지막 스니펫 제거 |
| Clipboard | Copy input to clipboard / 입력창 내용을 클립보드로 복사 |

---

## Configuration / 설정

Manage categories and snippets via `MIIIMESnippetPicker.ini`.  
`MIIIMESnippetPicker.ini` 파일로 카테고리와 스니펫을 관리합니다.

### INI Structure / INI 구조

```ini
[Options]
UndoLimit=5   

[Category]
01=Category Name1
02=Category Name2

[01]
Size=3
Data=item1|item2|item3

[02]
Size=1
Data=A|B|C|D
```

**Size** : 1–4. Defaults to 1 if omitted. / 미지정 시 기본값 1  
**Data** : `|`-delimited. Items exceeding the Size limit are ignored. / `|` 구분자, Size별 최대 개수 초과분 무시  
**Category** : Up to 8 entries. / 최대 8개  
**UndoLimit** : Stack depth. 0 = unlimited (max 100). Default 5. / Undo 스택 깊이. 0=무제한(최대 100), 기본값 5

---

## Directory Structure / 디렉토리 구조

```text
MIIIMESnippetPicker/
  ├─ MIIIMESnippetPicker.exe   # Executable / 실행 파일
  └─ MIIIMESnippetPicker.ini   # Configuration / 설정 파일
```

---

## 🛡️ Security & Anti-virus Info

### [✅ VirusTotal Analysis Report](https://www.virustotal.com/gui/file/b409effb9c3dd77c2b2ef736ddb7f4b7ac2ac9cc2b460937124b99ec85965992?nocache=1)

| Status             | Details                                                                        |
|:------------------ |:------------------------------------------------------------------------------ |
| **Major Vendors**  | **Clean** (Passed by AhnLab V3, Kaspersky, Microsoft, Avast, ESET, etc.)       |
| **Detection Rate** | **9 / 72** (Mostly Heuristic/Generic/Trojan-type flags)                        |
| **Integrity**      | The source code is transparently available for verification in this repository |

> This launcher was created with AutoIt. Some antivirus programs may incorrectly detect it as a virus.  
> 본 런처는 AutoIt으로 제작되었습니다. 일부 백신이 바이러스로 오진 할 수 있습니다. 

**File Checksum (SHA-256) :** `b409effb9c3dd77c2b2ef736ddb7f4b7ac2ac9cc2b460937124b99ec85965992`

---

## Disclaimer

Provided **"AS IS"**, without warranty.  
This is a **private project**. No technical support is provided.

본 프로그램은 **"있는 그대로"** 제공되며, 사용 중 발생하는 문제에 대해 제작자는 책임을 지지 않습니다.  
기술 지원은 제공되지 않습니다.

---

## Project Information

**Developer** : MIIIME  
**Website** : https://www.miiime.com  
**GitHub** : [@miiime6248](https://github.com/miiime6248)  
**Last Update** : 2026-02-14  

<br>
<img width="64" height="64" alt="002" src="https://github.com/miiimeworks/M4T/blob/main/4bit_Brutal/Logo/Neon/4b_Mium_64_0_G.png?raw=true">  
<br>
<br>
<br>