# 오늘의 등산

**오늘의 등산**은 사용자에게 '100개의 명산등산로' 를 추천해주고, 명산등산로 중 사용자가 원하는 산의 정보를 제공해주는 웹 사이트입니다.

## 프로젝트 개요
- Sprint Planning
- 와이어프레임

## 주요 기능

1. **메인 페이지**
    - 웹 사이트에 접속하면 메인 페이지가 표시됩니다.
    - 메인 페이지에서는 슬라이드 형식으로 산 목록을 확인할 수 있습니다.
    - 산 동호회 링크 통해 사용자들과 소통할 수 있습니다.
2. **산 검색**
    - 메인 페이지와 산 목록 페이지에서는 산 검색 기능을 제공합니다.
    - 검색 결과에서 원하는 산을 선택하여 상세 정보를 확인할 수 있습니다.
3. **산 상세 페이지**
    - 산의 기본 정보와 관련장소를 제공하고, 콜랩스 방식으로 추가정보를 확인할 수 있습니다.
    - 산 위치를 기반으로 오늘 기준 5일치의 날씨와 지도를 확인 할 수 있으며 팝오버 방식으로 등산로를 확인할 수 있습니다.

## 사용 기술 스택

- **프론트엔드**: HTML, CSS, JavaScript, Bootstrap, Swiper
- **사용 API**:
    1. [공공데이터 포털 API](https://www.data.go.kr/):
        1. 산림청_명산등산로(100개 등산로)
        2. 산림청_산정보 서비스(국내 소재 3,368개 설명)
    2. [네이버 API](https://www.ncloud.com/):
        1. Geocoding
        2. Web Dynamic Map
    3. [openweathermap API](https://openweathermap.org/)


## 스크린샷

[위 사이트 접속하기](https://forest-road-byjs.netlify.app/)
