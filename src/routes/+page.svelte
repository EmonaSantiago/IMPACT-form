<body>
    <h1>IMPACT</h1>
    <h3>Welkom bij ons <span>aanmeldingsformulier</span> voor een <span>positie bij Impact!</span> We zijn verheugd dat je interesse toont om deel uit te maken van ons team.</h3>

    
    <ul>
       <li><a class="button" href="src/routes/pages/creative/+page.svelte">Creative</a></li> 
       <li><a class="button" href="src/routes/pages/crew/+page.svelte">Crew</a></li>
        <li><a class="button" href="src/routes/pages/model/+page.svelte">Model</a></li>
    </ul>

    
</body>

<style>
    * {
    margin: 0;
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}

:root {
    --main-yellow-: #F8F053;
}

body {
    background-image: url("/Users/emonasantiago/Documents/IMPACT-form/src/assets/darkimg.png");
    margin: 1em;
    height: 1000px;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;
}


    body {
        margin-top: 3em;
        text-align: center;
    }

    h1 {
        font-size: 110px;
        color: #F8F053;
    }
    h3 {
        color: #F8F053;
        font-size: 16px;
    }

    span { 
        color: white;
    }

    a {
        text-decoration: none;
        color: black;
    }

    li {
        list-style-type: none;
        width: 250px;
        padding: 1em;
        margin-bottom: 30px;  
        background-color: #F8F053;
        text-align: center;
    }

    ul {
        padding: 0;
        display: inline-block;
        text-align: left;
        margin-top: 5em;
    }



</style>