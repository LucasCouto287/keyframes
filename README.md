# keyframes
keyframes does not work in Css after compress

@keyframes movePlan {
    0.0% {transform:translate(calc(0.0px + 22px),calc(230px - 22px));
    100% {transform:translate(calc(-650px - 0.0px),calc(230px - 21px));}
}

after compress, the unit of zero (px,%) will remove, for solving this issue, We should change 0% or 0px to 0.0% or 0.0px .
