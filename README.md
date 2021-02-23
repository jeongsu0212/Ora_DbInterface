#### 20210224(수) 작업

#### 20210223(화) 작업
- 오라클에 member테이블 생성 + 더이데이터 입력
- Ora_DbInterface 스프링MVC프로젝트 생성
- pom.xml로 자바,스프링,마이바티스 업데이트+메이븐 업데이트.
- 프로젝트 Facets 부분 web_module = 3.1 변경 + 자바 1.8 변경.
- web.xml의 웹모듈버전 2.5 ㅡ> 3.1로 변경.
- 깃연동OK.
- root-context.xml에 db커넥션 빈생성.
- log4jdbc.log4j2.properties 필수생성: 역할: 쿼리를 콘솔에서 디버그기능.
- mappers폴더생성 후 sampleMapper.xml 쿼리파일 생성(CRUD쿼리)
- 쿼리에서 발생되는 반환값을 담을 공간 = VO클래스로 해결.
- 서비스패키지(DAO포함)생성.(@Repository,@Service) servlet-context.xml파일  component-scan속성 사용.
- JUnit테스트