# 프로젝트 투입 전 MSA 개인 스터디

## MicroService 구현
```
https://www.inflearn.com/course/java-msa-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%8B%A4%EC%8A%B5/dashboard 색션 0~4 실습
```
![image](https://github.com/shimyoonbum/msa-study/assets/56707897/f2f1b134-4ca2-427e-837c-7ec7621065bb)

### MicroService docker 연동
```
https://www.inflearn.com/course/java-msa-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%8B%A4%EC%8A%B5/dashboard 색션 5~6 실습

docker hub에 build한 image push
[Eureka Server](https://hub.docker.com/repository/docker/xxyt778/eureka-server-image/general)
[Config Server](https://hub.docker.com/repository/docker/xxyt778/config-server-image/general)
[Gateway](https://hub.docker.com/repository/docker/xxyt778/gateway-server/general)
```
![image](https://github.com/shimyoonbum/msa-study/assets/56707897/63f90016-f6b2-4ae1-a489-8652cb25b443)

### Zipkin, Prometheus, Kafka 연동
```
https://www.inflearn.com/course/java-msa-%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8-%EC%8B%A4%EC%8A%B5/dashboard 색션 7~9 실습
(Kafka의 경우 docker container로 연동시 connect가 안되는 문제가 있어 추후 해결 필요)
```
![image](https://github.com/shimyoonbum/msa-study/assets/56707897/8507c4c1-06bd-4391-bb9e-4cc6604a6bf9)
item에 대한 history 적재를 kafka로 하도록 설정되어 있으며 추후에 login-history, manage도 topic으로 추가 가능
