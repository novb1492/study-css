강의  
https://www.youtube.com/watch?v=jWh3IbgMUPI  

display--------------------------------------------  

div=블럭레벨  
span=인라인레벨  

레벨에 따라 기본값이 다르다  
그걸 display로 컨트롤한다  

block=한줄에 하나씩  
inline-block=한줄에 여러개  
inline=내용이 있어야나옴 사용시 안의 내용에 물건의 크기에 따라 움직임  

position--------------------------------------------  
포지션은 기본값이 static
static=왼쪽위가 기준  
relative=원래 자리에서 상대적이동  
absolute=담겨있는 상자 기준으로 이동  
fixed=상자에서 나와서 윈도우에서 움직임  
sticky=스크롤링시에도 유지  

flex-box--------------------------------------------  
https://www.youtube.com/watch?v=7neASrWEFEM&t=1161s
박스와 아이템들을 행그리고 열로 자유자재로 배치가능  

컨테이너 속성값  
display  
flex-~  
justify-content  
align-~  
등  

아이템 속성값  
flex-~  
order  
align-self  
등  

중심축 반대축  존재  
좌에서우로 정렬시 수평축이 중심축  
위에서아래로 정렬시 수직축이 중심축  

컨테이너 속성값   
flex-direction  
    -row  
        -중심축 수평축  
        -기본값 row 왼->오  
        -row-reverse 오->왼 순서도 바뀜  
    -column  
        -중심축 수직  
        -기본값 위->아래  
        -column-reverse 아래->위 순서도 바뀜  
flex-wrap  
    -nowrap  
        -기본값 창이 작아저도 붙어있음  
    -wrap  
        -창이 작아지면 자동적으로 줄바꿈  
    -wrap-reverse  
        -반대로 맵핑됨  
flex-flow  
    -direction/wrap한번에 적을 수있다  
    -ex) flex-flow: column wrap;  

justify-content  
-중심축 아이템배치  
    -flex-start  
        -아이템 배치 정함  
        -수직=위아래 수평=좌우 
    -flex-end  
        -순서는 유지하대 배치가 반대로  
        -수직=아래위 수평우좌  
    -center  
        -중심축중앙 위치  
    -space-around  
        -박스룰 둘러싸게 공간을 넣어줌  
    -space-evenly  
        -동일 한 사이즈 공안으로 넣어줌  
    -space-between  
        -양 끝은 화면에 맞게 일정한 공간넣어줌  

align-items  
-반대축 아이템배치  
-한 줄을 기준으로 정렬 
-align-items는 수직축의 라인을 기준으로 아이템들이 정렬이 되고  
    -center  

    -baseline  
        -아이템이 균등해짐  
align-content  
-align-content는 두 줄부터 사용하는데 의미가 있다  
-align-content는 수직축의 라인을 기준으로 (두 줄 이상 일 때만) 라인 자체가 정렬이 된다.  
-justify-content 흡사하지만 반대축제어  


아이템 속성값  
flex-grow  
    -컨테이너 메꾸는 정도  
flex-shrink  
    -컨테이너 사이즈 변경시 얼마나 줄어들지  
flex-basis  
    -위 두개 강 없을시  
    -크기변화에 따라 비율 유지하지  
    -기본값 auto
align-self  
    -아이템 하나하나 개별 제어  

Responsive Web--------------------------------  
https://www.youtube.com/watch?v=8-uJ_4136uI  
flex grid/flext box/%/vw/vh/@meida활용  
https://www.youtube.com/watch?v=X91jsJyZofw  
반응형 네비바 만들어보기  

새로배운점  
1.ul태그 역시 flex로 제어하는게 좋다  
2.justify-content사용시 각 박스 헷갈리는거 조심  
ex)
-가로가 줄어들시 nav 클래스가 flex-direction로 바뀜  
하지만 .links클래스의 속성은 row그대로임 이떄 중앙 정렬을  
사용하려면 중심축을 건든는 justify-content를 사용해야함  
처음에 헷갈려서 반대축 건드는 align-items사용  
youtube-------------------------------------  


