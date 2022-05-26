<template>
    <div>
        <h1>Timer</h1>
        <div id="timer">
            <ul>
                <li><span id="days"></span>Days</li>
                <li><span id="hours"></span>Hours</li>
                <li><span id="minutes"></span>Minutes</li>
                <li><span id="seconds"></span>Seconds</li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss">
    h1 {
        margin-bottom: 3rem;
    }
    #timer ul {
        display: flex;
        align-items: center;
        justify-content: center;
        margin: 1rem 0;
        & li {
            margin: 0 1rem;
            padding: 0 1rem;
            color: brown;
            font-size: 2rem;
            font-weight: 500;
            & span {
     
            }
        }
    }
</style>