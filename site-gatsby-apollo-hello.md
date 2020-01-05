# gatsby-theme-apollo-docs 사용불가

# 아래는 그냥 참고만
## 작업 순서
- git clone ...apollo-client
- docs복사 > site-gatsby-apollo-hello 이름변경
- gatsby-config.js - typescriptApiBox주석처리
- gatsby-config.js - sidebarCategories에서 null/Migrating 제외하고 삭제
- 폴더삭제 - migrating폴더제외한 폴더삭제 
- npm install
- gatsby develop
- http://localhost:8000

## 페이지 추가
- get-started.mdx복사 > test1.mdx생성 : title변경(title이름으로 메뉴에 표시됨)
- gatsby-config.js : sidebarCategories추가



## 참고
- (안됨) npm install gatsby-theme-apollo-docs
- (주의) 수정시마다(페이지추가) 에러발생 > restart시 정상
- (주의) 수정시마다 .cache삭제
