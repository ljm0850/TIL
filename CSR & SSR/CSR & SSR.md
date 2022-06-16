## CSR & SSR

### CSR

- Client Side Rendering
- SPA(Single page application)에서 사용하는 방식
- Client에서 JavaScript에 의해 View를 동적으로 생성
  - 최초 접속 시 모든 파일을 가져오는 방식
    - page 전환이 SSR 대비 빠름(이미 파일을 가져와서)
    - 최초 접속 시 파일 가져오는 시간에 의해 로딩이 느리다

- SEO(검색 엔진 최적화)에 불리



### SSR

- Server Side Rendering
- MPA(Multi page application)에서 사용하는 방식
- Page 전환할 때 마다 client가 server에 View요청을 하여 받아오는 방식
  - page 전환이 CSR대비 느림(Page 전활 될 때 마다 가져오므로)
  - page 요청이 빈번해 질수록 CSR 대비 server 부하가 커짐(같은 데이터를 반복해서 가져오는게 많아짐)

