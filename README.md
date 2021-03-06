# uipath-
💡 Uipath.Core.Activities - UI Automation - Element 
Mouse

Click : 지정된 UI요소 클릭
Double Click : 지정된 UI 요소를 두 번 클릭
Hover : 지정된 UI 요소로 마우스를 올려놓는다
Keyboard

Send Hotkey : 키보드 단축키를 UI 요소로 보냄
Type Into : UI 요소에 키 입력란을 보냄. 특수키 지원
Type Secure Text : UI 요소에 보안 문자열을 보냄 
Control 

Check : 라디오 버튼 및 확인란을 선택하거나 삭제 
Get Text : 지정된 UI 요소에서 텍스트 값을 추출 
Select Item : 콤보 상자 또는 목록 상자에서 항목을 선택 
Set Text : 지정된 UI 요소의 Text 속성에 문자열을 쓸 수 있음 
Find 

Anchor Base : 다른 UI 요소를 앵커로 사용하여 UI 요소를 검색하는 컨테이너 
신뢰할 수 있는 선택기를 사용할 수 없는 경우 이 옵션을 사용 
Element Exists : 보이지 않더라도 UI 요소가 있는지 확인 
Fine Element : 지정된 UI 요소가 화면에 나타나기를 기다리고 UiElement 변수로 반환
Find Relative Element : 고정된 요소에 대한 위치를 사용하여 UI 요소 검색.
신뢰할 수 있는 선택기를 사용할 수 없는 경우 이 옵션을 사용
Indicate On Screen : 사용자가 Workflow를 실행하는 동안 화면에서 UI 요소 또는 영역을 선택
Wait Element Vanish : 지정된 UI 요소가 화면에서 사라질 때까지 대기
 

 

💡 UI Automation - Text 
Mouse 

Click Text : 표시된 UI 요소에서 주어진 문자열을 검색하고 클릭 
Double Click Text : 지정된 UI 요소에서 지정된 문자열을 검색하고 두 번 클릭 
Hover Text : 지정된 UI 요소에서 지정된 문자열을 검색하고 그 위에 마우스를 놓음 
Screen Scraping 

Extract Structured Data : 표시된 웹 페이지에서 데이터를 추출. 
속성 패널의 Extract Metadata 필드에 XML 문자열을 제공하여 추출할 정보 지정 
Find Text Position : UI 요소에서 지정된 문자열을 검색하고 해당 문자열의 화면 위치에 
자르기 영역이 설정된 다른 UI 요소 반환
Get Full Text : FullText 화면 스크래핑 방법을 사용하여 표시된 UI요소에서 문자열과 그 정보를 추출
Get Visible Text : 네이티브 스크린 스크래핑 방법을 사용하여 표시된 UI 요소에서 문자열과 그 정보를 추출
Find 

Text Exists : 지정된 UI 요소에 텍스트가 있는지 검사 
 

 

💡 UI Automation - OCR 
Screen Scraping 

Find OCR Text Position : UI 요소에서 OCR로 추출된 문자열 검색 
Get OCR Text : OCR 화면 Scraping 방법을 사용하여 지정된 UI 요소에서 문자열과 해당 정보 추출 
Engine

Abbyy OCR : Abbyy OCR Engine을 사용하여 OCR 정보 추출
Google OCR : Google OCR Engine을 사용하여 OCR 정보 추출 
Microsoft OCR : MS OCR Engine을 사용하여 OCR 정보 추출 
Find 

OCR Text Exists : OCR 기술을 사용하여 지정된 UI 요소에서 텍스트가 발견되는지 확인 
 

 

💡 UI Automation - Image 
Mouse 

Click Image : UI 요소의 내부의 이미지를 검색하여 클릭
Double Click Image : UI 요소의 내부의 이미지를 검색하여 두 번 클릭 
Hover Image : UI 요소 내부의 이미지를 검색하여 그 위에 놓음 
Find 

Find Image : UI 요소에 이미지가 표시 될 때까지 기다린 다음 클리핑 영역이 발견된 이미지로
설정된 UI 요소를 반환 
Find Image Matches : 대상 UI 요소의 특정 이미지에 대한 일치 항목을 검색하고 클리핑 영역이 
일치 항목의 화면 위치로 설정된 UI 요소 컬렉션을 반환 
Image Exists : 지정된 UI 요소 내에서 이미지가 발견되는지 확인 
Wait Image Vanish : UI 요소에서 이미지가 사라질 때까지 기다림 
Event 

On Image Appear : 이미지가 나타날 때 까지 기다리고 발견된 이미지에서 여러 작업을 수행할 수 있게
해주는 컨테이너
On Image Vanish : 이미지가 사라질 때까지 기다리고 다른 작업을 실행할 수 있게 해주는 컨테이너 
File 

Load Image : 디스크에서 이미지를 로드하여 이미지 변수에 저장할 수 있다
Save Image : 디스크에서 이미지 요소를 이미지 파일로 저장할 수 있다
 

 

💡 UI Automation - Browser 

Attach Browser : 이미 열려있는 브라우저에 연결하고 브라우저에서 여러 작업을 수행할 수 있게 해주는 컨테이너
💡 UI Automation - Window 

Attach Window : 이미 열려있는 창에 연결하고 창에서 여러 작업을 수행할 수 있게 해주는 컨테이너 
Close Window : 표시된 창을 닫음
Maximize Window : 표시된 창을 최대화함
Minimize Window : 표시된 창을 최소화 
 

 

💡 Uipath.Core.Activities - Programming 
Data Table 

Add Data Column : DataColumn을 지정된 DataTable에 추가 
Add Data Row : 지정된 DataTable에 DataRow를 추가
Build Data Table : 지정된 스키마에 따라 DataTable을 만듦 
Clear Data Table : 모든 데이터의 지정된 DataTable을 지움
For Each Row : 제공된 DataTable의 각 행에 대해 한 번 동작을 실행 
Generate Data Table : 구조화되지 않은 데이터에서 DataTable 변수를 생성. 테이블이 생성되는 기준에 따라 
열과 행 구분 기호를 선택할 수 있음
Get Row Item : 지정된 열에 따라 DataRow 변수에서 값을 가져옴 
Merge Data Table : 지정된 DataTable을 현재 DataTable과 병합하여 변경 내용을 유지할지 여부와 현재 
DataTable에서 누락된 스키마를 처리하는 방법을 나타냄
Output Data Table : CSV 형식을 사용하여 DataTable을 문자열에 씀
Remove Data Column : 지정된 DataTable에서 DataColumn을 제거
Remove Data Row : 지정된 DataTable에서 DataRow를 제거

