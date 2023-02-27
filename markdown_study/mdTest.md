# 1. 헤더 특수문자. <code>#</code>, <code>===</code>, <code>---</code>  
>* <code>#</code> 사용 예시<br>
>#### <code># This is an H1</code>
># This is an H1
>#### <code>## This is an H2</code>
>## This is an H2
>#### <code>### This is an H3</code>
>### This is an H3
>#### <code>#### This is an H4</code>
>#### This is an H4
>#### <code>##### This is an H5</code>
>##### This is an H5
>#### <code>###### This is an H6</code>
>###### This is an H6
<br><br>
<<<<<<< HEAD
> * <code>===</code>, <code>---</code> 사용 예시<br>
![image](https://user-images.githubusercontent.com/120539323/221498467-94702af7-5833-4c9f-9e48-f373f7719a08.png)  
>이렇게 원하는 글자 밑에 === 혹은 --- 를 넣어주면 된다.

<br><br>
# 2. 이미지 넣기

* 두가지 방법이 있다. markdown 형식, tag 형식<br>
    1. markdown 형식 : \!\[alt](이미지경로 "title")
        - alt : 이미지 안나올때 대신 보일 내용. 공백으로 둬도 된다. [] 는 써야함.
        - title : 이미지에 마우스 올려놓으면 나올 내용. "" 자체를 안써도 된다. 이미지경로만 입력해도 됨.  
    2. tag 형식 : \<img src = "이미지경로" alt="" title="">
        - alt : markdown 형식과 같다. alt="" 전부 안써도 된다.
        - title : markdown 형식과 같다. title="" 전부 안써도 된다.
        - tag 형식은 html 문법이라 alt 랑 title 말고도 다른 속성들 많다. (ex. width="100px" height="50px")
<br><br>
* 일단 중요한건 경로다. world나 한글 파일이랑 달리 이미지가 경로로 들어가는거라 로컬에 있는 이미지 경로를 그대로 쓰려고 하면, 내 컴퓨터에서 볼때나 괜찮지 남들이 보면 안나온다. 이를 어떻게 해결해야 할까 생각해보면 md 파일이란거 자체가 html 비스무리하다보니 인터넷 연결되어있어야 쓸모있단걸 생각하면 이미지를 네트워크에 올려놓고 해당 경로를 가져오는 방식을 쓰면 해결된다.<br>
이 중 유용한 방법은 github 의 아무 Repository 나 들어간 다음. issues 에 들어가 New issue 를 눌러 나오는 Write 부분에 경로를 따기 원하는 이미지를 올려놓으면 경로가 반환되는데, 여기서 src 에 있는 경로를 가져다 쓰면 된다.


<img src="https://user-images.githubusercontent.com/120539323/221552606-e5d28e85-c2db-4b40-b763-1e929fec2741.png" alt="Github->Repositories">

![Issues->New issue](https://user-images.githubusercontent.com/120539323/221552284-51f4b7e7-ab37-4024-8ce6-a35f8fee8f41.png)

<img src="https://user-images.githubusercontent.com/120539323/221564314-b1a87d7d-010b-4a91-a1ed-b3e2921cd736.png" alt="Write-src">

물론 이렇게 했을 때 단점도 있다. 잘못해서 이 경로 수정했을 때, 이런식으로 하면 다시 못찾음. 그래서 보완책으로 repository 에 사진 올려놓고 거기 경로 따와도 되고, 뭐 어짜피 커밋할거면 지난 커밋 파일에서 경로 찾아와도 되긴 한다.

<br>
=======
>2. <code>===</code>, <code>---</code> 사용 예시<br>
![image](https://user-images.githubusercontent.com/120539323/221498467-94702af7-5833-4c9f-9e48-f373f7719a08.png)  
>이렇게 원하는 글자 밑에 === 혹은 --- 를 넣어주면 된다.
<br><br>
