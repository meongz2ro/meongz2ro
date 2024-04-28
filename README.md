###### 24/04/26 (3 day)

#### *Photoshop*

    ■ 패스 저장하기

    1. 모든 도형 레이어 합친 뒤 Ctrl + A
    2. Paths - Make Path
    
    
    □ Alt 누른 채로 레이어 사이에 커서 가져다 대면 클리핑 마스크 (Ctrl + Alt + G)
    □ Shift 누른 채로 도형 만들어야 반듯
    □ 상단에 위치한 정렬 툴 활용
    □ Shape 형태 도형은 마지막에 레이어 우클릭 > Rasterize Layer
    □ Filter - Filter Gallery - Cutout
    □ 글자 모양에 효과

#### *HTML*

    ■ 웹 페이지에 글씨, 움짤(클릭하면 원본 다운로드), 링크 넣기

    1. 새 파일 안에 images(gif) 파일과 down(zip) 파일 생성
    2. 메모장에 코드 적기
    3. 저장 시 파일명은 index.html, 파일 형식은 모든 파일, 인코딩은 UTF-8
    
    ▶ 코드 원문
    <!doctype html>
    <html>
    <head>
    <meta charset="UTF-8">
    <title> 방울방울 </title>
    </head>
    <body>
    비눗방울을만들고있는<br>
    말랭이의모습이보인다<br>
    <a href="https://youtu.be/ft70sAYrFyY?si=HPrnams7GRD-CSim"> 비눗방울만드는법알려줄게 </a><br>
    <a href="./down/mrmr.zip">  <img src="./images/mrmr.gif" alt="비눗방울을 만드는 모습">  </a>
    </body>
    </html>
    

    □ 태그는 소문자로 작성
    □ <!doctype html>: 현재의 문서가 HTML5 웹 표준으로 작성된 문서임을 선언
    □ <html lang="ko">: 한국어
    □ 웹 문서 저장명 한글, 띄어쓰기 불가능
    □ 웹 브라우저는 index라는 이름을 찾아서 무조건 첫 페이지로 보여 줌 (나머지 페이지 파일명은 마음대로)
    □ img 태그에 있는 alt 속성에는 이미지에 들어간 내용을 텍스트로 전부 적어야 함 (웹 접근성)


    ☆ 배운 태그
    html, head, body, a, img, title, meta(얘는 종료 태그 없음)
    

    1. 하이퍼 링크
    <a href="주소"> 이거 누르면 입력한 주소로 이동 </a>

    2. 주석
    <!-- (코드 설명, 팀 협업 시 누가 언제 만들고 수정했는지 표시, 앞뒤로 띄어쓰기 필수) -->

    3. 이미지
    <img src="이미지 링크" alt="사진 설명">

    4. 이미지 클릭 시 링크 이동
    <a href="링크"> <img src="이미지 링크" alt="사진 설명"> </a>

    5. 이미지 클릭 시 새 탭으로 링크 열기
    <a href="링크" target="_blank"> <img src="이미지 링크" alt="사진 설명"> </a>

<hr/> 

###### 24/04/25 (2 day)

#### *Photoshop*

    ■ 정확한 정사각형 선택 영역 만들기
    
    1. Ctrl + A
    2. Select - Transform Selection (선택 영역 변형)
    3. Alt(중앙 기준) 누른 채로 조정

    
    □ Filter - Blur - Motion Blur (잔상 효과)
    □ Edit - Stroke (선 만들기)
    □ Timeline - Tween (앞뒤 프레임 사이에 자연스럽게 중간 과정을 넣어 주는 기능)

<hr/>

###### 24/04/24 (1 day)

#### *Photoshop*

    ■ 여백에 배경 이어지게 만들기
    
    1. 캔버스 크기 조정해서 여백 생성
    2. Ctrl + A 누른 채로 레이어 썸네일 클릭
    3. 선택된 부분 우클릭 > Select Inverse
    4. Edit - Content-Aware Fill
    

    ★ 글자 크기, 자간, 행간 조절 단축키
    
    Ctrl + Shift + Alt + > : 글자 키우기 (10pt)
    ​Ctrl + Shift + Alt + < : 글자 줄이기 (10pt)
    
    Ctrl + Shift + > : 글자 키우기 (2pt)
    Ctrl + Shif + < : 글자 줄이기 (2pt)
    
    Ctrl + Alt + ▶ : 자간 늘리기
    Ctrl + Alt + ◀ : 자간 줄이기
    
    Ctrl + Alt + ▼ : 행간 늘리기
    Ctrl + Alt + ▲ : 행간 줄이기
