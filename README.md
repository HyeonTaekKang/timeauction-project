# ⏰ 시간을 사고파는 사이트 TimeAuction

<img src="https://github.com/user-attachments/assets/abef65a6-7c90-4c3a-806f-466e59922e75"/>

- 배포 URL : https://timeauction.net
- Test ID : wjavmtngkr12345@gmail.com
- Test PW : Ekzmfkdl11!!??

<br>

## ✨ 프로젝트 소개
<img src="https://github.com/user-attachments/assets/1ad816d1-b8be-48d1-8186-929f7a8e58d4"/>
<img src="https://github.com/user-attachments/assets/09846430-d918-484b-99c7-dc7ea6449069"/>
<img src="https://github.com/user-attachments/assets/7dd0fb61-18d2-46ef-be80-2b259c85347f"/>
<img src="https://github.com/user-attachments/assets/b6069b93-f306-470c-a3e2-268ebf570a03"/>
<img src="https://github.com/user-attachments/assets/3f4ddb77-1e31-4282-a495-d638ea288ba49"/>
<img src="https://github.com/user-attachments/assets/655be0c7-0d70-4b2b-ba96-f46633de6ab7"/>

<br><br><br><br>

- 프로젝트 소개글( 왜 이 프로젝트를 시작했는지 ) : https://blog.naver.com/wjavmtngkr1/223657675707

<br>


- TimeAuction은 자신의 시간을 판매할 수 있습니다.

- 경매또는 시간당으로 판매할 수 있습니다.
  
- 경매에 참여하기 위해서는 경매권을 구입하고 참여할 수 있고 , 일반시간구매는 1:1 로 채팅을 보내서 시간을 구입합니다.
  
- 경매 입찰에 성공할 경우 ( 최고 입찰금을 냈을 경우 ) 경매 생성자와 입찰자간의 채팅방이 자동으로 생성됩니다.

<br>

## 🧑‍🤝‍🧑 팀원 구성

1인 ( 본인혼자 )


<br>

## 📅 개발 기간

2년

<br>

## ☁️ 개발 환경

- Front : React , html , css
- Back-end : java17( 8문법을 더 많이 사용 ) , Spring boot(3.0.6) , spring webflux , spring security , spring data jpa , querydsl , redis , mysql
- devOps : amplify , lambda , api gateway , rds , s3 , cloudwatch , ec2 , elasticache 
- 버전관리 : Github
<br>


## ⚙️ 시스템 아키텍쳐
<img src="https://github.com/user-attachments/assets/03b96692-deb9-44ea-a9b7-a9d84e1b4f18"/>

- aws sam(Serverless Application Model)을 사용하여 api gateway + lambda 를 사용한 서버리스 시스템 아키텍쳐 개발
- chat ( 채팅 ) 부분은 ec2 따로
- 여러 기능들을 여러 lambda에 쪼개서 배포 ( MSA 는 아님 )
- 프론트는 Amplify 사용
- rds mysql사용
<br>


## 🔗 erd
<img src="https://github.com/user-attachments/assets/bb120b7b-3072-41ec-8cfe-319ab79e6d62"/>

<br>


## front 코드
https://github.com/HyeonTaekKang/timeauctionfront/tree/master


## backend 코드
- auction ( 경매 ) : https://github.com/HyeonTaekKang/timeauction-auction
- auctionBid ( 경매 입찰 ) : https://github.com/HyeonTaekKang/timeauction-auctionbid
- product( 일반 시간판매 ) : https://github.com/HyeonTaekKang/timeauction-timeproduct
- community ( 커뮤니티 ) : https://github.com/HyeonTaekKang/timeauction-community
- auction wait queue ( 경매 입장 대기열 ) : https://github.com/HyeonTaekKang/timeauction-auctionQueue
- chat ( 채팅 ) : https://github.com/HyeonTaekKang/timeauction-chat
- portone ( 결제 ) : https://github.com/HyeonTaekKang/timeauction-portone
- notification ( 알림 ) : https://github.com/HyeonTaekKang/timeauction-notification
- auctionEnded ( 경매 종료 ) : https://github.com/HyeonTaekKang/timeauction-auctionended
- auth ( 인증 ) : https://github.com/HyeonTaekKang/timeauction-auth

<br>

##  개발하며 생긴 문제를 기술로 해결
- 특정요일이나 시간에 이벤트 발생시키기 : https://blog.naver.com/wjavmtngkr1/223657860103
- 대기열 시스템 개발기 : https://blog.naver.com/wjavmtngkr1/223663997672
- 동시성 문제 해결해보기https://blog.naver.com/wjavmtngkr1/223664920257
- aws lambda에 배포하며 느낌점과 고민들 그리고 팁까지 : https://blog.naver.com/wjavmtngkr1/223829903880






