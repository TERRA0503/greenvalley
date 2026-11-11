# 그린벨리 홈페이지

페이지: index(메인), washer(세탁기), dryer(건조기), boiler(스팀보일러), consulting(빨래방 컨설팅), area(관리 지역), contact(문의·FAQ). 디자인은 style.css 하나에 모여 있습니다.

정적 사이트입니다. 이 폴더를 그대로 웹호스팅에 올리면 됩니다 (Netlify, Cloudflare Pages, GitHub Pages, 카페24 등).

## 배포 전에 바꿀 것
1. **도메인**: 모든 파일의 `https://greenvalley.co.kr` 을 실제 주소로 바꾸기
   (모든 .html, robots.txt, sitemap.xml, llms.txt)
2. **검색엔진 확인 코드**: index.html 의 `네이버_확인코드`, `구글_확인코드`
3. **빨래방 사례**: consulting.html 안의 주석(매장 추가 방법)대로 매장 카드를 넣고 "정리하고 있습니다" 문구 삭제. 사진은 img 폴더에.
4. **관리 지역**: 지도와 거리표의 도시 목록이 실제 방문 지역과 맞는지 확인

## 배포 후 할 일 (검색 노출에 가장 중요)
- 네이버 서치어드바이저(searchadvisor.naver.com): 사이트 등록 → 소유 확인 → sitemap.xml 제출
- 구글 서치콘솔: 등록 → sitemap.xml 제출
- **네이버 스마트플레이스**에 "그린벨리" 업체 등록 (네이버 지도·플레이스 검색 노출, 지역 SEO의 핵심), 홈페이지 주소 연결
- 구글 비즈니스 프로필 등록
- 스마트스토어 판매자 정보와 블로그 등에 홈페이지 링크 걸기

## 적용된 SEO / GEO
- 제목·설명·키워드 메타, canonical, Open Graph(카톡·네이버 공유 미리보기 og-image.jpg)
- 구조화 데이터(JSON-LD): LocalBusiness(주소·전화·영업시간·관리지역·취급 브랜드), 은성 건조기 제품군, FAQ
- robots.txt (AI 검색 크롤러 허용), sitemap.xml, llms.txt(AI 검색용 회사 요약)
- 질문-답변형 FAQ, 사양표 등 AI가 인용하기 쉬운 사실 위주 문장
