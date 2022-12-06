# 0221206 final report 
## [1] 라이센스
<img width="920" alt="KakaoTalk_20221206_223002962" src="https://user-images.githubusercontent.com/54700476/205927325-336a6f07-eff5-4697-9e36-047fc1ec82c5.png">

## [2] 오픈소스 참고
by.https://github.com/davidwinter/java-blackjack

<img width="768" alt="1" src="https://user-images.githubusercontent.com/54700476/205927432-b29bdad9-df79-4489-be70-e339d8857b31.png">

## [3] 구동 과정
{1}  
<img width="768" alt="2" src="https://user-images.githubusercontent.com/54700476/205927584-46fb1806-2f16-4e13-a1c7-16a2ee3f6302.png">
이름 입력  
{2}  
<img width="768" alt="2" src="https://user-images.githubusercontent.com/54700476/205927702-5f82cab9-de0c-4f87-b975-aa0f0edb4b2c.png">
처음 시작 화면  
{3}  
<img width="768" alt="2" src="https://user-images.githubusercontent.com/54700476/205927832-86b567f1-643c-485d-aa15-de553babf96c.png">
베팅 이후 화면  
{4}  
<img width="768" alt="2" src="https://user-images.githubusercontent.com/54700476/205927913-98a33b9f-cc8b-4585-b79d-c3821fa55380.png">
플레이어가 이긴 후의 화면  
{5}  
<img width="768" alt="2" src="https://user-images.githubusercontent.com/54700476/205927982-0669fb4a-dde5-4a00-95f5-d1a7ee7dde10.png">
플레이어가 진 후의 화면  
## [4] 블랙잭 규칙
{1} 승리 조건  
첫 두장의 합이 21이면 무조건 승리한다.  
추가로 받은 카드가 21이여도 무조건 승리한다.  
만약 추가로 받은 후에 카드를 그만 받고 오픈을 하였을때, 카드의 합이 21 이하이고, 딜러보다 크면 승리한다.  
{2} 패배 조건
카드의 합이 21을 초과하면 무조건 패배한다.  
만약 패를 오픈한 후에 카드의 합이 21 이하여도, 딜러보다 작으면 패배한다.  
{3} 비기는 조건  
만약 패를 오픈했을 때, 카드의 합이 21 이하이고, 딜러와 같으면 비긴다.  
{4} 특수 요건  
에이스 카드는 1 혹은 11로, 유리한 방향으로 계산 가능하다.  
