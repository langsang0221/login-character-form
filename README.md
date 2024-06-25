# login-character-form

https://taegon.kim/archives/9658 블로그를 기반으로 공부

**해당 라이언 캐릭터의 저작권은 (주)카카오에 있습니다.**
공부 목적 외에 사용하지 마시기 바랍니다.

#svg 란?
- Scalable Vector Graphics의 약자로 벡터 기반 그래픽을 XML 형식으로 정의하는 것을 의미
- 내부에 담을 수 있는 것은 원, 사각형, 다각형, 라인, path 등
- 파일의 모든 요소와 모든 속성에 애니메이션을 적용 가능

### circle
- cx: 원의 중심의 x 좌표
- cy: 원의 중심의 x 좌표
- r: 원의 반지름
- fill: 원에 채울 색상
- stroke: 테두리 색상
- stroke-width: 테두리 두께

### line
- x1: 선의 시작점의 x 좌표
- x2: 선의 끝점의 x 좌표
- y1: 선의 시작점의 y 좌표
- y2: 선의 끝점의 y 좌표
- stroke-linecap: 선 끝 부분의 모양을 정의

### path
- d: 경로 데이터를 정의
- fill: 경로의 내부를 채울 색상
- transform: 경로를 변형하는 속성
- https://a11y.gitbook.io/graphics-aria/svg-graphics/svg-paths-shape 참고

### polygon
- points: 다각형의 꼭지점 좌표 목록
- stroke-linejoin: 다각형의 모서리에서 선이 만나는 방식.