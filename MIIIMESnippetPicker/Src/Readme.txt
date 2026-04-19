========================================================================
        MIIIME Snippet Picker (MSP)
========================================================================

A lightweight Windows desktop utility that lets you build text strings
from registered special characters and symbols, then copy them to the clipboard.

등록된 특수문자·기호를 버튼 클릭으로 조합해 클립보드에 복사하는
경량 Windows 데스크탑 유틸리티입니다.

========================================================================
[Features]
========================================================================

- Build text strings by clicking snippet buttons.
  스니펫 버튼 클릭으로 문자열 조합.

- Copy assembled text to clipboard with one click.
  조합된 텍스트를 원클릭으로 클립보드 전송.

- Category and snippet data managed via INI file.
  INI 파일로 카테고리 및 스니펫 데이터 관리.

- 4-tier button layout (Size 1–4): 8 / 4 / 2 / 1 columns.
  4단계 버튼 레이아웃 (Size 1~4): 8열 / 4열 / 2열 / 1열.

- Undo stack with configurable depth.
  횟수 설정 가능한 Undo 스택 지원.

========================================================================
[Button Layout]
========================================================================

  Size 1 : 8 columns / 8열  |  23 px  |  max 64 items / 최대 64개
  Size 2 : 4 columns / 4열  |  47 px  |  max 32 items / 최대 32개
  Size 3 : 2 columns / 2열  |  95 px  |  max 16 items / 최대 16개
  Size 4 : 1 column  / 1열  | 191 px  |  max  8 items / 최대  8개

========================================================================
[Controls]
========================================================================

  T         	: Toggle Always on Top / 항상 위 토글
  I         		: Open INI file / INI 파일 열기
  R         	: Reset input field / 입력창 초기화
  U         	: Undo last snippet / 마지막 스니펫 제거
  Clipboard 	: Copy input to clipboard / 입력창 내용을 클립보드로 복사

========================================================================
[Configuration]
========================================================================

Manage categories and snippets via MIIIMESnippetPicker.ini.
MIIIMESnippetPicker.ini 파일로 카테고리와 스니펫을 관리.

[Options]
UndoLimit : 
Stack depth. 0=unlimited (max 100). Default 5. / Undo 스택 깊이. 0=무제한(최대 100), 기본값 5.

[Category]
01=Category Name1 / 카테고리명1
02=Category Name2 / 카테고리명2

[01]
Size=3 : 
1–4. Defaults to 1 if omitted. / 1~4, 미지정 시 기본값 1.
Data=item1|item2|item3 :
|-delimited. Items exceeding the Size limit are ignored. / | 구분자, Size별 최대 개수 초과분 무시.

========================================================================
[Directory Structure]
========================================================================

  MIIIMESnippetPicker/
    ├─ MIIIMESnippetPicker.exe   # Executable / 실행 파일
    └─ MIIIMESnippetPicker.ini   	# Configuration / 설정 파일

______________________________________________________________________________________________________________________

This program was created with AutoIt. Some antivirus programs may incorrectly detect it as a virus.
본 프로그램은 AutoIt으로 제작되었습니다. 일부 백신이 바이러스로 오진 할 수 있습니다.

========================================================================
[Disclaimer]
========================================================================

Provided **"AS IS"**, without warranty.
This is a **private project**. No technical support is provided.
본 프로그램은 **"있는 그대로"** 제공되며, 사용 중 발생하는 문제에 대해 제작자는 책임을 지지 않습니다.
기술 지원은 제공되지 않습니다.

Developer	: MIIIME 
Website		: https://www.miiime.com 
GitHub		: @miiime6248 
Update		: 2026.04.19
