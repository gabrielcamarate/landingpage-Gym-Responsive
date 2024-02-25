<header>
    <nav class="navbar-header">
        <div class="navbar">
            <a href="/"><img src="/MAX-GYM.svg" alt="Logo da Academia"></a>
            <div class="buttons-middle">
                <a href="/">Home</a>
                <a href="/">Product</a>
                <a href="/">Contact</a>
            </div>
            <a href="/" class="button-navbar">Login</a>
        </div>
    </nav>

    <div class="infos">
        <div class="square">
            <h2 class="open">OPEN <span class="hours">24H</span></h2>
        </div>

        <div class="left">
            <h1>FORMA SEU <span class="color-vermilion-600">CORPO</span></h1>
            
            <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s.</p>
    
            <div class="buttons">
                <a href="/" class="learn-more button-learn-more">Learn More</a>
                <a href="/" class="contact button-learn-more">Contact</a>
            </div>
        </div>
        
        <div class="right">
            <img src="/gym-image-header.jpg" alt="Imagem Transparente">
            <div class="gradient"></div>
        </div>
    </div>
</header>

<!-- ======================== CSS ======================== -->

<style>

    
    

    .gradient {
        position: absolute;
        width: 590px;
        height: 1080px;
        right: 0;
        top: -425px;
        background: linear-gradient(195.58deg, #FD4C00 12.53%, rgba(244, 117, 63, 0) 88.64%);
        transform: matrix(-1, 0, 0, 1, 0, 0);
        z-index: -1;
    }

    .right img{
        max-width: 851px;
        max-height: 913px;
        border: solid 3px #FD4C00;
    }

    /* ============== BOTÕES ============== */
    
    .buttons {
        display: flex;
        margin-top: 65px;
        gap: 2rem;
    }

    .learn-more {
        background-color: #FD4C00;
        transition: 0.2s;
    }

    .learn-more:hover{
        display: flex;
        color: #fff;
        scale: 0.90;
        
        background: transparent;
        border: 5px solid #fd4c00;
    }
    .contact:hover{
        display: flex;
        background: #fd4c00;
        border: none;
        scale: 0.90;
    }
    
    .contact{
        border: 5px solid #FD4C00;
        transition: 0.2s;
    }
    
    .button-learn-more{
        display: flex;
        justify-content: center;
        align-items: center;
        

        font-family: 'Inter';
        font-style: normal;
        font-weight: 600;
        font-size: 25px;
        color: #FFFFFF;

        width: 259px;
        height: 93px;
    }

    .infos {
        display: flex;
        justify-content: center;
        position: relative;
        margin-top: 40px;
    }
    

/* ============== QUADRADO ============== */
    .square{
        width: 200px;
        height: 200px;
        background: #FD4C00;
        position: absolute;
        top: 340px;
        left: 845px;
        display:flex;
        justify-content: center;
        align-items: center;
        }

    .open {
        max-width: 200px;
        color: white;
        text-align: center;
        width: 136px;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 900;
        font-size: 46.392px;
        line-height: 61px;

        text-align: center;
        color: #FFFFFF;
        }

    .hours {
        width: 180px;
        height: 81px;
        left: 911px;
        top: 653.97px;

        font-family: 'Inter';
        font-style: normal;
        font-weight: 900;
        font-size: 62.7247px;
        /* identical to box height, or 129% */
        color: #FFFFFF;
    }

/* ============== LADO ESQUERDO ============== */

    .left {
        display: flex;
        flex-direction: column;
        margin-right: 95px;
        justify-content: center;
    }

    .left p {
        margin-top: 45px;
        max-width: 648px;

        font-family: 'Inter';
        font-style: normal;
        font-weight: 400;
        font-size: 26px;
        line-height: 30px;
        color: white;
    }

    .left h1 {
        max-width: 506px;

        font-family: 'Inter';
        font-style: normal;
        font-weight: 900;
        font-size: 83px;
        line-height: 107px;

        color: #fff;
    }

/* ============== COR ============== */

    .color-vermilion-600{
        color: #fd4c00;
    }

/* ============= NAVBAR ============= */

    .navbar-header {
        padding: 30px 0px;
    }

/* Aqui foi usado para mecher no home product contact */    
    .navbar .button-navbar:hover{
        color: #fff;
    }

    .navbar a {
        display: inline-block;
        font-family: 'Inter';
        font-style: normal;
        font-weight: 600;
        color: #fff;
        transition: 0.2s;
    }

    .navbar a:hover{
        display: inline-block;
        color: #FD4C00;
        scale: 1.2;
    }

    .navbar{
        display: flex;
        flex-direction: row;
        justify-content: space-around;
        align-items: center;
    }
    
    .buttons-middle > a {
        font-size: 20px;
        margin: 30px 50px;
    }
    
    .button-navbar{
        font-size: 25px;
        line-height: 39px;
        padding: 15px 46px;
        border: 2px solid #fff;
    }
</style>