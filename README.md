# Lecture_Wise_Saying

<오늘 배운 것>

## 1. 폰트 적용 방법
- Download font
- res 폴더 아래 font directory 생성
- font 폴더에 font 추가
  이때, font 파일 이름에 capital letters 들어가면 X
- activity.xml에  android:fontFamily="@font/bmjua"
  위와 같은 형태로 작성해 주면 된다.  
  
  

## 2. Adapter를 사용해서 Listview 만들기

- Listview를 만들기 위해선 Adapter를 사용해야 한다.

- MainAcitivty 파일에서 리스트 만들고
그 리스트 안에 a, b, c 데이터를 넣어놨다.

- 이 데이터들을 Adapter로 전송해 준다.

- Adapter는 listview_item.xml 파일 즉
list 글꼴이나 크기가 어떤 형태로 뜰지 지정해 놓은 파일에
a, b, c를 저장해 준다.
마치 무대 나가기 전에 화장하는 것처럼
a와 b와 c를 무대에 세우기 전에 치장해주는 것이다.

- 치장이 다 끝났으니 무대에 올라서야 한다.
activity_main.xml 에 있는 ListView에 data를 넣어줌으로서
사용자가 보는 화면에 a, b, c 데이터가 listview 형태로 최종적으로 노출된다.
