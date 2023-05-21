# web-movie-details
open API를 활용한 영화소개 페이지입니다.<br>
메인페이지에서 개봉예정 영화목록을 확인할 수 있고 <br>영화포스터 클릭시 트레일러가 있는 상세페이지로 이동합니다.
<br><br>
<b>*하단의 DB를 이용하므로 영화에 따라 세부 정보가 누락되어 있을 수도 있습니다.</b>

- 참고 사이트(https://themoviedb.org)
    
  [Getting Started](https://developer.themoviedb.org/docs)
    
  [개봉예정영화정보](https://api.themoviedb.org/3/movie/upcoming?api_key=a64533e7ece6c72731da47c9c8bc691f&language=ko-KR&page=1)

## 메인페이지
영화포스터에 마우스 행오버시 평점, 타이틀 보여주고 포스터 하이라이트 <br>
![메인](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e5db4a31-98d3-4ba1-acf1-81bb6fca79dd/Untitled.png)

## 1. 트레일러가 있는 영화
트레일러가 있는 영화는 예고편 출력 (음소거 모드로 자동재생) <br>
![트레일러편](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/1ccc3687-0310-4f03-ba2e-4c3cc1619215/Untitled.png)

## 2. 포스터만 있는 영화
트레일러가 없는 영화는 포스터 출력 <br>
![포스터편](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/c723219c-1cf9-4e04-9dad-97fb4e30a570/Untitled.png)