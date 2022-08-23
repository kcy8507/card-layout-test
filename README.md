# card-layout-test
flex-wrap을 이용한 카드 레이아웃

카드 레이아웃의 경우, 감싸고 있는 card-wrapper의 높이는 auto 혹은 100%로 주고 카드 height를 지정해줘서 자동으로 높이가 측정되게 한다.

flex-wrap: wrap; 
을 이용하여 창을 줄이면 자연스레 카드가 아래로 탈락되게 한다.

카드의 margin-top여백과 card-wrapper의 margin-top이 겹칠경우, 카드에는

margin-top:calc(카드래퍼의 마진탑 - 카드 마진탑);
값을 주면 겹치지않는다.
