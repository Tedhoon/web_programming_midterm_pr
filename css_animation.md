```css
transition-property : 값; 
/* 변화시키고 싶은 값, all가능 */
transition-duration : 값;
/* 작동시간 정의 */
transition-timing-function : 값;
/* 변하는 속도의 패턴 설정(ex:ease, lineat, 등)) */
transition-delay : 값;
/* 설정한 시간을 기다렸다가 작동 (다른 값들을 기다렸다가 작동시키기 가능) */

transition : width 35s ease 1s;
transition : 35s all;
/* 함축시켜서 적용 가능 */
```



```css
animation-name : 아무거나;

animation-duration : 2s;
/* 애니메이션 진행시간*/

animation-delay : 2s;
/* 2s 기다렸다가 효과 */

animation-iteration-count : 3;
/* 반복 횟수 infinite속성 가능 */

animation-timing-function : ease-in;
/* 애니메이션 적용 속도 조절 */

animation-fill-mode : forwards;
/* to 상태에서 멈추기 backwards가능*/

animation-direction : alternate;
/* [순 - normal] [역 - reverse] [순-역 : alternate] */

animation : 아무거나 2s 2s 3 ease-in forwards alternate;



@keyframes 아무거나;{
    from {

    }

    to {
        
    }
}

/* 또는 %로 지정 가능 */
```