강사님, 2년전 MSA 설계에 참여 했었는데, 실습을 통하니 이해가 쉽고 좋은 강의 였습니다.
Level3 도 신청했는데, Level2 패스가 가능할지 궁금하네요(아키쪽일을 하다보니 개발은 오래되어서 어렵네요) 

** 기능적 요구사항

 1.고객이 메뉴를 선택하여 주문한다.
 
 2.고객이 선택한 메뉴에 대해 결제한다.
 
 3.주문이 되면 주문 내역이 입점상점주인에게 주문정보가 전달된다
 
 4.상점주는 주문을 수락하거나 거절할 수 있다
 
 5.상점주는 요리시작때와 완료 시점에 시스템에 상태를 입력한다
 
 6.고객은 아직 요리가 시작되지 않은 주문은 취소할 수 있다
 
 7.요리가 완료되면 고객의 지역 인근의 라이더들에 의해 배송건 조회가 가능하다
 
 8.라이더가 해당 요리를 pick 한후, pick했다고 앱을 통해 통보한다.
 
 9.고객이 주문상태를 중간중간 조회한다
 
 10.주문상태가 바뀔 때 마다 카톡으로 알림을 보낸다
 
 11.고객이 요리를 배달 받으면 배송확인 버튼을 탭하여, 모든 거래가 완료된다

====> 추가사항

 12. 배달 가능한 라이더가 없으면 배달 요청은 되지 않는다
 
 13. 배달 가능한 라이더가 없으면 주문은 되지 않는다
 
** 실습소스위치 

https://github.com/ycgee/example-food-delivery/issues/11#issue-1458975888

** SAGA 모델링(MSA 모델링)

https://github.com/ycgee/example-food-delivery/issues/10#issue-1458971837

** Compensation / Correlation

https://github.com/ycgee/example-food-delivery/issues/9#issue-1458969681

** Sub/Pub

https://github.com/ycgee/example-food-delivery/issues/8#issue-1458964663

https://github.com/ycgee/example-food-delivery/issues/7#issue-1458963244

** CQRS

https://github.com/ycgee/example-food-delivery/issues/6#issue-1458936633

https://github.com/ycgee/example-food-delivery/issues/5#issue-1458934622

** 서킷브레이크

https://github.com/ycgee/example-food-delivery/issues/4#issue-1458925325

** Req/Res

https://github.com/ycgee/example-food-delivery/issues/3#issue-1458913635

https://github.com/ycgee/example-food-delivery/issues/2#issue-1458912481

** API Gateway

https://github.com/ycgee/example-food-delivery/issues/1#issue-1458900851


Git 사용이 수월하지 않아 작성이 성의 없게 보일지 모르나, 열심히 해보았습니다.
감사합니다.
