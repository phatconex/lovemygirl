@import url("https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;700&display=swap");
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    background: #f7c0c8;
    font-family: "Montserrat", sans-serif;
    height: 100vh;
    position: relative;
    /* overflow: hidden; */
}
img {
    width: 100%;
    display: block;
}
.boxheart {
    transition: 3s;
}
.heart,
.beat {
    position: fixed;
    width: 300px;
    height: 300px;
    top: calc(50% - 150px);
    left: calc(50% - 150px);
    text-align: center;
    transform: scale(0.95);
    animation-duration: 2000ms;
    animation-timing-function: cubic-bezier(0, 0, 0, 1.74);
    animation-delay: 500ms;
    animation-iteration-count: infinite;
    animation-play-state: running;
    cursor: pointer;
}
.boxheart.active {
    opacity: 0;
    visibility: hidden;
}
.boxheart.active .heart::before {
    left: -300px;
}
.boxheart.active .heart::after {
    left: 300px;
}
.heart {
    animation-name: heartbeat;
    cursor: pointer;
}
.heart h1 {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    z-index: 999;
    color: #fff;
}
.beat {
    animation-name: beat;
}

.heart::before,
.heart::after,
.beat::before,
.beat::after {
    content: "";
    position: fixed;
    top: 40px;
    width: 150px;
    height: 240px;
    background: #f66;
    border-radius: 150px 150px 0 0;
    transform: rotate(-45deg);
    transform-origin: 0 100%;
    transition: 2s;
}

.heart::before,
.beat::before {
    left: 150px;
}

.heart::after,
.beat::after {
    left: 0;
    transform: rotate(45deg);
    transform-origin: 100% 100%;
}

@keyframes heartbeat {
    0%,
    100% {
        transform: scale(0.9);
    }
    50% {
        transform: scale(1);
    }
}
@keyframes beat {
    0% {
        opacity: 0.1;
        transform: scale(1);
    }
    100% {
        opacity: 0;
        transform: scale(10);
    }
}
.boxchoose {
    width: 50%;
    margin: 50px auto;
    text-align: center;
    opacity: 0;
    pointer-events: none;
    transition: 2s;
    transition-delay: 2s;
}
.boxchoose.active {
    opacity: 1;
    pointer-events: auto;
}
.boxchoose h2 {
    color: #f66;
    font-size: 30px;
    filter: drop-shadow(0 0 100px rgb(255, 0, 0));
    text-shadow: 1px 3px 8px #ffcdcd;
    margin-bottom: 50px;
}
.boxchoose button {
    background-color: #ffffff6b;
    border: none;
    font-family: inherit;
    padding: 5px 10px;
    border-radius: 50px;
    cursor: pointer;
}
#no {
    position: absolute;
    transform: translateX(-50px);
    z-index: 999;
}
#yes {
    background-color: rgb(255 167 167);
    font-size: 30px;
    padding: 12px 23px;
    color: #bb3400;
    font-weight: bold;
    margin-left: 40px;
    animation: shakeBtn 0.5s infinite alternate;
}
@keyframes shakeBtn {
    from {
        transform: rotate(-15deg);
        box-shadow: 0 0 50px rgba(255, 0, 0, 0.575);
    }
    to {
        transform: rotate(15deg);
    }
}
.popup {
    position: absolute;
    width: 100%;
    height: 100%;
    background-color: #f8b3bb;
    top: -48px;
    left: 0;
    z-index: 999;
    opacity: 0;
    pointer-events: none;
    transition: 1s;
}
.popup.active {
    opacity: 1;
    pointer-events: visible;
}
.popup .inner {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%) scale(0);
    text-align: center;
    background-color: #e2919a;
    width: 70%;
    padding: 50px;
    border-radius: 30px;
    z-index: 999;
    box-shadow: rgba(17, 12, 46, 0.15) 0px 48px 100px 0px;
    transition: 1s;
}
.popup.active .inner {
    transform: translate(-50%, -50%) scale(1);
}
.popup img {
    width: 50%;
    margin: 0 auto;
    border-radius: 30px;
}
.popup h3 {
    font-size: 28px;
    color: #ed4a5d;
    margin-bottom: 20px;
    text-shadow: 5px 4px 23px #fff;
    font-weight: bold;
}
.popup p {
    font-size: 17px;
    margin-top: 15px;
    color: #fff;
    text-shadow: 1px 1px 1px #808080;
    font-weight: bold;
}
.popup p span {
    color: yellow;
    font-weight: bold;
}
