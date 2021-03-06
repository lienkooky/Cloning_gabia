# Cloning_gabia

🤯21.09.30_Cloning gabiaWebsite with html and css

### section

> 일반적으로 문서의 콘텐츠 섹션을 의미합니다.<br>
> 콘텐츠와 관련된 한 가지 주제 영역을 말합니다.<br>
> section 요소는 문장이나 문서의 스타일링 요소가 아니기 때문에 편의나 영역을 위함이면 div 태그가 좋습니다.<br>
> section 요소는 제목이 없는 경우, section이라고 할 수 없기 때문에 제목을 제공해야 합니다.<br>
> section 요소는 일반적인 주제가 아니라면 구체적인 요소(article, aside, nav)를 사용하는 것이 더 적절합니다.<br>

### article

> 콘텐츠의 독립적인 항목을 나타냅니다.<br>
> article은 포럼, 신문기사, 잡지, 블로그 항목, 게시판 글 등 콘텐츠의 독립적인 항목을 나타냅니다.<br>
> section은 하나의 주제를 나타낸다면, article은 주제를 묶는 독립적인 콘텐츠입니다.<br>
> section 요소 안에는 article을 쓸 수 있으며, article 요소 안에도 section을 쓸 수 있습니다.<br>

### nav

> 페이지 내에서 이동할 수 있는 네비게이션 링크 그룹입니다.<br>
> nav는 문서의 핵심적인 페이지의 menu 및 submenu에서 사용하고, 문서에서 주로 한 번만 사용합니다.<br>
> 문서 안에 링크가 포함된 콘텐츠는 nav를 사용하지 않습니다.<br>
> nav는 핵심적인 네비게이션에 사용해야 하므로, 푸터 내에 링크 그룹의 사용은 적절하지 않습니다.<br>

### main

> 웹 문서의 주요 콘텐츠 영역을 나타낼 때 사용합니다.<br>
> main은 웹 페이지에서 한 번만 사용할 수 있으며, 접근성과 검색 영역에 노출을 향상시킵니다.<br>
> article, aside, footer, header, nav를 하위 요소로 사용할 수 있습니다.<br>

### aside

> 웹 문서의 메인 콘텐츠와 관련된 사이드 콘텐츠 영역을 나타냅니다.<br>
> main 콘텐츠와 관련된 사이드의 정보, 광고 등 부분적인 정보를 그룹화할 때 사용합니다.<br>

### header

> 웹 문서의 헤더 영역을 나타냅니다.<br>
> header는 웹 페이지에 대한 소개, 네비게이션 영역, 테이블 영역, 검색 영역, 로고 영역을 포함한 영역입니다.<br>
> header는 제목 태그가 포함될 수 있으나, 필수 조건은 아닙니다.<br>
> header는 섹션 콘텐츠가 아닌 그룹화하기 위한 요소이므로 section 요소를 포함할 수 없습니다.<br>

### footer

> 웹 문서의 푸터 영역을 나타냅니다.<br>
> footer는 저작권 정보, 회사 정보, 관련 링크, 주소, 바닥글, 사이트 정보 등을 포함하는 콘텐츠 영역입니다.<br>
> footer는 섹션 콘텐츠가 아닌 그룹을 나타내는 요소이며, section, article, aside 등을 포함할 수 있습니다.<br>

### position:relative

> position:absolute의 기준점이 필요할 때 사용합니다.<br>
> z-index를 사용해야하는 경우 포지션 값이 없으면 relative를 사용하여 z-index의 값을 인식시킬 수 있습니다.<br>
> 요소의 위치를 유지한 채 left, top, right, bottom의 위치 값을 사용하고 싶을 때 사용할 수 있습니다.<br>
