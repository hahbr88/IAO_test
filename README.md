## IAO 입사 TEST

> UI는 자유롭게 제작하시면 됩니다.

### 1.달력만들기

> #### Conditions
>
> - Calendar.jsx 파일에 답안을 작성하세요
> - 라이브러리를 사용하지 않고 달력을 제작해야합니다.
> - 오늘 날짜에 구분되는 background-color가 들어가야합니다.
> - 선택한 날짜에도 구분되는 background-color가 들어가야합니다.
> - 버튼을 눌러서 이전 달 과 다음 달로 이동할 수있어야 합니다.
> - 날짜를 선택하면 해당 Date 정보를 상태로 저장 할 수 있어야 합니다.
> 
> - **참고하실 예시 UI**<br/>
>   ![스크린샷 2023-08-17 174549](https://github.com/hahbr88/IAO_coding_test/assets/90291796/03f1614d-8efa-4750-873e-cb4dadacfbb6)
> - 이대로 똑같이 만드실 필요는 없습니다. 

<br/><br/>

### 2. 배송예상기간 산정

> #### Conditions
>
> - Delivery.jsx 파일에 답안을 작성하세요
> - 주문일 기준은 위에서 제작한 달력으로 저장한 상태값입니다.
> - 현재 판매중인 상품은 `product1`, `product2` 두개입니다.
> - 배송 속도는 `일반` 과 `특급` 두가지를 선택할 수 있습니다.
> - `일반` 옵션은 72시간, `특급` 옵션은 24시간이 소요됩니다.
> - 각각 두개의 제품은 발송준비시간이 각각 다릅니다.
> - `product1` 발송준비 시간: 48시간
> - `product2` 발송준비 시간: 24시간
> - 주말엔 영업을 하지 않습니다. 배송기간 중 주말이 끼어있으면 (2 \* 24)시간 만큼 배송 시간을 더해야 합니다.
> - 제품과 배송옵션을 선택한 후 '예상배송기간 보기' 버튼을 클릭하면 하단에 `yyyy년 mm월 dd일 도착예정` 이라는 예상 배송기간 문구가 나타나야 합니다.
