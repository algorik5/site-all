## 테스트
- git clone https://github.com/patternfly/patternfly-org.git --recurse-submodules
- yarn install
- yarn add react-docgen <<< 에러발생시
- yarn develop (yarn build:static && gatsby develop)
- http://localhost:8000/

## 페이지추가
- src/content/test1폴더 생성
- test1.css,about.md,test1.md생성 (get-started에서 복사)
- gatsby-config.js >>> sideNav,topNavItems,gatsby-source-filesystem 추가
- gatsby-theme-patternfly-org\layouts\sideNavLayout\sideNavLayout.js >>> test1추가 (text,path)

## 참고
- src/pages/index.js : 첫페이지
- (주의)한글은 mdx파일을 utf8로 저장하면 됨
- (참고).cache삭제
- (개인꺼-6개월경과) gatsby-theme-patternfly (https://gatsby-theme-patternfly.netlify.com/)

## 안됨 - gatsby new로는 멀해도 안됨
