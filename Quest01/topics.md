* HTML의 역사
  * HTML 4.01 / XHTML 1.0 / XHTML 1.1
    - W3C 권고안으로 출시되었습니다.
    - `HTML 4.01`
      : HTML 4.0과 마찬가지로 세 가지 문서 형태를 제공합니다.
      : 엄격(Strict), 변이(Transitional), 프레임셋(Frameset)
    - `XHTML 1.0`
      : XHTML은 XML 1.0을 이용하여 HTML 4.01을 새로 만든 독립된 언어 입니다.
      : HTML 4.0, 4.01과 같이 세 가지 문서 형태에 약간의 규약과 함께 제공합니다.
    - `XHTML 1.1`
      : XHTML 1.0 strict 기반이지만 사소한 변경사항과 사용자 정의 기능을 포함했습니다. 또한 XHTML의 모듈화로부터 모듈을 이용하여 새로 작성되었습니다.
* 브라우저의 역사
  - `Mosaic와 Netscape / Internet Explorer의 독점시대 / Firefox`
    : Mosaic(모자이크)는 이미지까지 표현이 가능한 최초의 그래픽 웹 브라우저입니다. 최종적으로는 마이크로소프트가 모자이크 소스코드를 이용해 인터넷 익스플로러를 개발합니다.
    : Netscape(넷스케이프)는 넷스케이프사가 개발한 브라우저로 당시 폭발적 인기를 끌었습니다. 하지만 익스플로러에 패배했고, 넷스케이프 개발자들이 모질라 재단을 설립해 2002년에 파이어폭스 브라우저를 출시합니다.
    : Internet Explorer는 윈도우 운영체제에 기본으로 포함해 판매하여 사용자가 급격히 증가했습니다. 하지만 모질라 파이어폭스 등 다른 브라우저들이 출시되는 등의 이유 때문에 인기는 점점 떨어지게 되었습니다.
  - `Chrome의 등장`
    : 2008년 구글이 구글 크롬을 출시했습니다. 꾸준한 업데이트와 자동설치가 이루어져 사용자들은 브라우저를 계속 이용하고 있습니다. 또한 '동기화 기능' 덕분에 어떤 PC를 사용해도 개인의 설정 그대로 사용이 가능하다는 장점이 있습니다.
  - `iOS Safari와 모바일 환경의 브라우저`
    : iOS Safari는 Apple에서 만든 macOS, iOS, iPadOS를 사용한 Apple 제품의 기본 브라우저입니다. macOS, iOS, iPadOS에서는 속도가 빠르지만 윈도우 등 타 OS에서는 속도가 느립니다.
    : 모바일 브라우저에서는 크롬이 압도적입니다. 네이버에서도 '웨일'을 출시하며 경쟁에 뛰어들고 있습니다. 크롬, 사파리, 웨일, 파이어폭스, 오페라미니, 삼성 인터넷 등이 있습니다.
* HTML 문서의 구조
  * `<html>`
    : <html> 태그 안에는 기본적으로 <head>, <body> 태그가 들어갑니다.
  * `<head>`
    * <head> 태그 안에는 기본적으로 <meta>, <title> 태그가 들어갑니다.
    * <meta> 태그는 html 문서가 어떤 내용을 담고 있고, 핵심키워드는 무엇이며, 누가, 어떤 언어코드로 설정되었는지의 정보를 담고 있습니다.
    : 검색엔진이나 브라우저에 읽힙니다.
    : charset, description, keyword, author, refresh, mode, viewport 등의 정보를 표기할 수 있습니다.
    * <title> 태그는 웹페이지의 제목을 나타내는 용도로 사용합니다. 검색엔진이 정보수집시 사용하는 정보입니다.
  * `<body>`
    : 텍스트, 하이퍼링크, 이미지, 리스트 등과 같은 모든 콘텐츠를 포함하는 영역을 정의할 때 사용합니다.
  * 시맨틱 엘리먼트
    - 스스로 브라우저와 개발자 모두에게 사용된 의미를 명확히 전달해주는 요소입니다.
    - h1 ~ h6, header, footer, section, article, aside, nav 등이 있습니다.
    - `h1 ~ h6`
      : 글자태그입니다. 숫자가 커질 수록 글자 크기는 작아집니다.
    - `header`
      : 페이지 상단에 위치하여 소개 및 탐색에 도움을 주는 컨텐츠를 나타냅니다.
      : 주로 제목, 로고 등을 나타냅니다.
    - `footer`
      : 페이지 하단에 작성자, 저작권 정보, 관련 문서 등을 표협합니다.
    - `section`
      : HTML 문서의 독립적인 구획을 나타냅니다.
    - `nav`
      : 문서의 부분 중 페이지 링크를 보여줍니다. 메뉴, 목차, 색인 등을 표현합니다.
  * 블록 엘리먼트와 인라인 엘리먼트의 차이
    - 블록 엘리먼트 : 가로폭 전체의 넓이를 가져 공간을 모두 차지합니다. 블록 요소 다음에는 줄바꿈이 이루어집니다.
      : h1 ~ h6, div, header, p, table, ul 등이 있습니다.
    - 인라인 엘리먼트 : 한 줄에서 다른 엘리먼트와 공간을 나누어 사용합니다. 블록 요소 안에 포함되어 있습니다. 줄바꿈이 없고 우측으로 바로 이어서 표시됩니다.
      : css 명령어로 인라인 요소를 블록 요소의 속성으로 변경할 수 있습니다.
      : a, button, i, img, input, select, span, textarea 등이 있습니다.