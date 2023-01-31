|- public
|- server
| |- config.json # API 서버를 실행할 때 필요한 옵션
| |- database.json # db file
|- src
| |- components # 서비스에서 사용하는 컴포넌트
| | |- Article # 목록에 있는 글 컴포넌트
| | | |- index.scss  
| | | |- index.js  
| | |- ArticleList # 목록 글 컴포넌트
| | | |- index.scss  
| | | |- index.js
| | |- Footer # 서비스 푸터
| | | |- index.scss  
| | | |- index.js
| | |- Header # 서비스 헤더
| | | |- index.scss  
| | |- Markdowns # markdown 에서 사용하는 스타일 컴포넌트
| | | |- CodeBlock.js # 글에서 코드 포맷을 보여 주기 위한 컴포넌트
| |- pages # 서비스 페이지
| | |- ListPage # 서비스 글 목록 컴포넌트
| | | |- index.scss  
| | | |- index.js  
| | |- ViewPage # 글 상세 컴포넌트
| | | |- index.scss  
| | | |- index.js  
| |- templates # 페이지 기본 구조 정의 템플릿
....
