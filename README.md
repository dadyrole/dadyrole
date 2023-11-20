<style>
    *{
        font-family: monospace;
    }
    .svg{
        height: 40px;
        align: left;
    }
    .typing-animation{
        overflow-hidden;
        width: fit-content;
        border-right: .15em solid green;
        letter-spacing: .15em;
        animation: 
            typing 3.5s steps(30, end),
            blink-caret .5s step-end infinite;
    }
    @keyframes typing {
        from { width: 0 }
        to { width: 100% }
    }
    @keyframes blink-caret {
        from, to { border-color: transparent }
        50% { border-color: rgb(39, 184, 187) }
    }
</style>

<div class="typing-animation">
    <h1>hi, i am dadyrole</h1>
</div>
