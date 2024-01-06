# 🌏 날씨, 일기를 작성/조회/수정/삭제 하는 백엔드를 구현해보기

- 테스트 코드 작성해보기
- 외부 API의 데이터를 활용해보기
- JPA 방식으로 MySQL 사용하기

# 📕 프로젝트 소개
## 최종 구현 API 리스트
### ✅ POST / create / diary
- date parameter 로 받아주세요. (date 형식 : yyyy-MM-dd)
- text parameter 로 일기 글을 받아주세요.
- 외부 API 에서 받아온 날씨 데이터와 함께 DB에 저장해주세요.

### ✅ GET / read / diary
- date parameter 로 조회할 날짜를 받아주세요.
- 해당 날짜의 일기를 List 형태로 반환해주세요.

### ✅ GET / read / diaries
- startDate, endDate parameter 로 조회할 날짜 기간의 시작일/종료일을 받아주세요.
- 해당 기간의 일기를 List 형태로 반환해주세요.

### ✅ PUT / update / diary
- date parameter 로 수정할 날짜를 받아주세요.
- text parameter 로 수정할 새 일기 글을 받아주세요.
- 해당 날짜의 첫번째 일기 글을 새로 받아온 일기글로 수정해주세요.

### ✅ DELETE / delete / diary
- date parameter 로 삭제할 날짜를 받아주세요.
- 해당 날짜의 모든 일기를 지워주세요.


## 프로젝트 완성도 높이기
#### ✅ DB와 관련된 함수들을 트랜잭션 처리한다.

- 매일 새벽 1시에 날씨 데이터를 외부 API 에서 받아다 DB에 저장해두는 로직을 구현한다.
- logback 을 이용하여 프로젝트에 로그를 남긴다.
- ExceptionHandler 을 이용한 예외처리를 한다.
- swagger 을 이용하여 API documentation 을 한다.


## 사용하는 사이트
### ✅ Open Weather Map api
- 날씨 데이트를 얻어오는데에 사용


# 📕 개발 기간
23.01.02 ~ 24.01.06

## 🖥️ 개발 환경
- 언어 : Java
- 프로그램 : IntelliJ IDEA(Ultimate)
- spring boot 2.6.6
- JDK 8

### 💪 느낀점 
- 저번 과제보다는 좀더 수월하다고 느꼈다. 확실히 과제를 할 시간이 많으니까 이해 안되는 부분도 좀더 찾아 볼수 있고, 강사님이 설명을 잘 해주신거 같다.
  그래도 혼자서 하라고 하면 잘 못할거 같다... 최대한 많이 공부해서 혼자 해보는 복습도 해야겠다.
  
