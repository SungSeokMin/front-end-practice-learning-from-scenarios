앞서 작성했던 [RFC](https://github.com/SungSeokMin/front-end-practice-learning-from-scenarios/blob/master/2%EC%9E%A5%20-%20%EC%83%88%EB%A1%9C%EC%9A%B4%20%EC%B6%9C%EB%B0%9C/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EB%B6%84%EC%84%9D%20%EB%B0%8F%20%EA%B8%B0%ED%9A%8D.md)의 요구사항을 바탕으로 `Client Side Rendering`과 `Server Side Rendering` 중 하나의 기술을 선택하려고 한다.

[CSR | SSR | SSG 파악하기](https://velog.io/@jkl1545/CSR-SSR-SSG)

# 시작하기

`더 많은 사용자 노출` : [SEO](https://developer.mozilla.org/ko/docs/Glossary/SEO)(Search Engine Optimzation)

![SEO](https://user-images.githubusercontent.com/72539723/190345164-f5bf78cb-dce8-42a2-a699-45ace4465d87.png)

- Cross linking : 링크가 많이 걸려있는 문서
- title tag and meta description : html문서 내의 제목과 메타태그를 정교하게 기입
- URL canonicalization : 유니크한 컨텐츠를 하나의 URL로 정리

# Web vitals

[Web vitals](https://web.dev/vitals/)에서 `사용자 경험의 품질을 최적화하는 것은 웹 사이트의 장기적인 성공의 핵심입니다. 비즈니스 소유자, 마케팅 담당자 또는 개발자에 관계없이 Web Vitals는 사이트 경험을 수량화하고 개선할 기회를 식별하는 데 도움이 될 수 있습니다.` 라고 소개한다.

### 3가지 핵심 내용

- `LCP (Largest Contentful Paint) - 최대 콘텐츠 페인트` : 로딩 성능을 측정

- `FID (First Input Delay) - 최초 입력 지연` : 상호 작용을 측정

- `CSL (Cumulative Layout Shift) - 누적 레이아웃 시프트` : 시각적 안정성을 측정
