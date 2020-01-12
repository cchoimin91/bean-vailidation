# @Valid와 @ControllerAdvice를 이용한 bean-vailidation하기  
API를 만들때 DTO 즉, bean에 대한 유효성 체크 로직을 매번 작성하는 것은  
매우 비효율이다!  
이러한 문제점을 @Vaild를 통해 해결 할 수 있다.  
또한 @ControllerAdvice와 같이 사용하면 궁합이 매우좋다


개발환경
---------------
Java 1.8  
SpringBoot 2.1.9  
Maven  



### @Vaild만 적용시
----------------------------
![이미지 2](https://user-images.githubusercontent.com/33255462/72217075-e43a7d80-356c-11ea-8230-8c839d65860b.png)


### @Vailid와 @ControllerAdvice 같이 적용 후
-----------------------------------
![포스트맨(2)](https://user-images.githubusercontent.com/33255462/72217055-b5bca280-356c-11ea-8052-c20beadc3f40.png)

