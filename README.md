# 책쾌: Chaek-quae

[대표적인 책벌레, Belle](http://gph.is/1LrGJRy)

## 기획 계기: 초기 아이디어
* 직접 읽는 것 외의 독서형태로 정보 습득을 보완할 필요성 느낌.
 책, 독서를 좋아하지만, 개발공부와 더불어 여러 일정이 겹치면서 '책을 읽을 시간이 턱없이 부족한'상황을 경험했다.

* 책 속 핵심내용 또는 견해를 응축적으로 전달해주는 콘텐츠 큐레이션 필요성을 절감.
 산책, 휴식 중 독서를 주제로 한 팟캐스트들을 들어봤지만, 취향에 맞지 않았다.

 팟캐스트는 '대화형'이라서 듣기에는 편하지만, 전달하는 내용이 정돈되지 않아, 듣고나서 남는 것이 별로 없었다.

 책 수다보다는, 책 속 내용을 응축적으로 전달하거나 책 속 조언을 현실에 적용하는 팁 등 구조화된 리뷰를 통해 '직접독서를 보완할 수 있는'콘텐츠 소비를 하고 싶었다.
 
* 본인 외에도 사용 가능성 있는 사람들 목격.
  또한, 부모님께서 글씨가 작은 책은 눈이 불편해 잘 읽지 않으시지만, 유튜브는 라디오 듣듯이 곧잘 활용하시며 정보를 접하신다는 것을 알게 되었다.

* 오디오 북 수요의 확장추세
  개인적 필요에 의해 만드는 프로젝트이긴 하지만, 수요/니즈를 파악하는 것이 의미있다고 생각해서 간단히 탐색했다.
  - 유튜브에서 *오디오북* 검색시, **조회수 10만~100만 이상**
  - 유튜브에서 *책 리뷰* 검색시, **평균적으로 10만 이하**
  - 유튜브에서 *책 추천* 검색시, **1~70만**으로 천차만별
  - 2030은 물론이고, 50대까지 폭넓게 수용하는 **'듣는 독서'** 시장과 서비스간 경쟁 가속화에 관한 [최근 기사](https://www.mk.co.kr/news/culture/view/2021/02/126698/)
----

## 아이디어
* 관심 분야인 **생산성, 브랜드, 개발분야** 도서를 리뷰한 유튜브 콘텐츠를 큐레이션한 사이트를 구축한다.
* 평소 알고 있던 유튜브 채널의 콘텐츠로 우선 구현한다.
* 해당 채널/유튜버의 수익에는 악영향이 없도록, 불법적인 크롤링을 하지 않으며, 클릭 시 해당 유튜브 링크로 이동하는 방식으로 우선 구현한다.
* 우선은 직접 콘텐츠 정보를 입력하고, 차츰 큐레이션 및 정보 입력 방법을 발전시킨다.
* 구성된 책 리뷰 큐레이팅 페이지는 사람에 따라 '읽을 도서 목록'이 될 수도 있고, '들을 도서 목록'으로 활용될 수도 있다.
----

## to do
- [ ] 전체 페이지의 footer 영역을 페이지 하단으로 고정: 현재, main 콘텐츠 담길 영역에 들어가 있음.
- [ ] 개별 페이지에서 메인페이지로 갈 때의 링크 오류 해결: 파일 확장자, syntax ... 순으로 확인하며 디버깅.
- [ ] 큐레이팅의 소스 채널들 출처 표기 방법 구상하기: 키워드와 함께 크리에이터/채널명을 **태그 형식**으로 선택할 수 있게 구성하여, 특정 콘텐츠 목록을 한 눈에 볼 수 있게 하면 편할 듯 함.

## 업데이트 목록
* 2021.02.25.Tur
 - upload: 메인페이지, 중복되는 html코드 작성해둔 서식파일
 - title(대제목),소제목,footer 콘텐츠에 css 지정

* 2021.05.01.Sat
 - README 수정: from *HTML syntax* to **markdown syntax**
 - main page의 목차와 스타일 수정
 - 