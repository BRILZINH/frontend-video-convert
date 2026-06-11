# frontend-video-convert

Olá,esse foi meu primero site com html e css,conseguir fazer o frontend do site.

Feito só com html e css,não fiz a parte do backend do site,pois sou iniciante ainda e to aprendendo ainda.Quero focar na parte 
vizual do site  que é oque eu gosto de fazer por enquanto 
Fiz uma interface de conversor de video para audio,algo que eu queria fazer,e por incrivel oq parece não ficou tão ruim,
fiz os codigos acompanhando video de um profissional fazendo um site do zero,mais enfim demorei um pouco para fazer,claro no meio
dos codigos eu usei um pouco da IA do Github Copilot no vs code para me ajudar um pouco, to muito feliz pela meu projeto
demorei um pouco,mas consegui.
Eu tentei deixar o mais organizado que eu podia,coloquei no html usando SECTION 1, SECTION 2 e SECTION 3 

entre outra tags,nao conseguir deixar bem organizado como devia ter ficado,mas na proxima vez eu irei focar mais na organização.
Obrigado pela atenção!!


<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap"
        rel="stylesheet">
    <title>MP3 Converter</title>



</head>

<!-- # SECTION 1  -->
<section class="section1">

    <body>
        <header>
            <img class="icone" src="img projetos/download-svgrepo-com.svg" alt="">
            <img class="icone" src="img projetos/musica.svg" alt="Logo do site">
            <h2>CONMP3.COM</h2>

            <nav class="nav-links">

                <ul>
                    <li>traducões</li>
                </ul>
            </nav>
        </header>

        <section>

            <div>
                <h2>Convert YouTube to MP3</h2>

                <!-- SECTION: Convert Button -->
                <div>
                    <p>Converte vídeos do YouTube para áudio MP3</p>
                    <div class="convert-button">
                        <input type="text" id="link" placeholder="Cole o URL do vídeo do YouTube aqui">

                        <button onclick="converter()" class="button2">
                            <img class="logoButton" src="img projetos/downloadicon.svg" alt=""> Converter
                        </button>

                        <div id="resultado"></div>


                        <!-- SECTION: Features -->
                    </div>
                    <div class="icon-row">
                        <div class="feature2">
                            <img class="icone3" src="img projetos/flash-1-svgrepo-com (1).svg" alt="">
                            <h3>Conversão Rápida</h3>
                        </div>
                        <div class="feature2">
                            <img class="icone3" src="img projetos/audio-svgrepo-com (1).svg" alt="">
                            <h3>Áudio de Alta Qualidade</h3>
                        </div>
                        <div class="feature2">
                            <img class="icone3" src="img projetos/security-pass.svg" alt="">
                            <h3>Segurança Garantida</h3>
                        </div>
                    </div>
        </section>



        <!-- # SECTION 2 -->
        <section class="section2">
            <h1>Como Funciona</h1>
            <div>
                <img class="icone" src="img projetos/one-circle-fill-svgrepo-com.svg" alt="">
                <h3>copiar URL</h3>
                <p>copie o URL/link do vídeo do YouTube</p>
            </div>

            <div>
                <img class="icone" src="img projetos/two-circle-fill-svgrepo-com.svg" alt="">
                <h3>Converter</h3>
                <p>cole o URL e clique no botão "converter" para iniciar o processo</p>
            </div>

            <div>
                <img class="icone" src="img projetos/three-circle-fill-svgrepo-com.svg" alt="">
                <h3>baixar</h3>
                <p>seu arquivo MP3 estará pronto para download</p>
            </div>



            <!-- # SECTION 3 -->
            <section class="section3">
                <h2>porque usar nosso serviço?</h2>
                <p>nosso serviço oferece uma conversão ultra rápida e fácil de vídeos do YouTube para áudio MP3,
                    mantendo a
                    qualidade sonora original
                    com o nosso sistema de processamento avançado, garantimos que cada conversão seja feita com
                    eficiência e
                    segurança, proporcionando uma experiência sem complicações para nossos usuários</p>

                <div class="icon-row">
                    <div class="feature">
                        <img class="icone2" src="img projetos/infinite-svgrepo-com (1).svg" alt="">
                        <h3>Unlimited Conversions</h3>
                        <p>convert YouTube videos to mp3 as many times as you want for free, without ads and without
                            delay</p>
                    </div>

                    <div class="feature">
                        <img class="icone2" src="img projetos/download-file-1-svgrepo-com (1).svg" alt="">
                        <h3>High-Quality Audio</h3>
                        <p>our converter ensures that the audio quality of the converted MP3 files is preserved,
                            providing you with
                            clear and crisp sound</p>
                    </div>

                    <div class="feature">
                        <img class="icone2" src="img projetos/security-secure-protection-27-svgrepo-com.svg" alt="">
                        <h3>no registration required</h3>
                        <p>you can use our service without creating an account or providing any personal information</p>
                    </div>

            </section>

    </body>

</html>


essa foi a parte do hmtl que eu fiz!
agora vou mostrar a parte do css:


* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: rgb(1, 1, 19);
    color: rgb(0, 0, 0);
    font-family: 'Poppins'
}

header {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    padding: 10px 20px;
    z-index: 1000;
    background: transparent;
    margin-bottom: 20px;
    z-index: 99;
}

header nav ul {
    display: flex;
    gap: 30px;
    list-style: none;
    background-color: rgba(255, 255, 255, 0.486);
    padding: 10px 20px;
    border-radius: 10px;
    backdrop-filter: blur(10px);
    margin: 0;


}

header nav {
    margin-left: auto;

}


.logotipo {
    width: 70px;



}




.icon-row {
    display: flex;
    justify-content: center;
    align-items: flex-start;
    gap: 100px;
    flex-wrap: wrap;
    margin-top: 20px;
    color: rgba(231, 241, 236, 0);
    padding: 70px;

    h3 {
        font-size: 18px;
        color: rgba(8, 7, 7, 0.863);

    }

}

.feature {
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 10px;
    text-align: center;
    max-width: 180px;
    color: rgb(7, 2, 2);


}




.icone {
    width: 40px;
    height: 40px;

}

.icone2 {
    width: 40px;
    height: 40px;

}

.icone3 {
    width: 25px;
    height: 25px;



}

.section1 {
    background-color: rgba(255, 255, 255, 0.822);
    background-color: lab(93.53% -0.78 -1.92 / 0.938);
    backdrop-filter: blur(10px);
    background-size: cover;
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    padding: 50px 20px;
    text-align: center;

    p {
        font-size: 16px;
        color: rgba(54, 49, 49, 0.842);
        padding: 0 20px;

    }
}

.section2 {
    background-color: rgba(255, 255, 255, 0.918);
    background-size: cover;
    display: flex;
    flex-direction: inherit;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
    padding: 50px 20px;
    text-align: center;


}

.section3 {
    background-color: (93.53% -0.78 -1.92 / 0.938);
    display: flex;
    flex-direction: column;
    align-items: center;
    gap: 20px;
    padding: 50px 20px;
    text-align: center;
    color: rgba(0, 0, 0, 0.9);


}

.nav-links li {

    cursor: pointer;
    transition: color 0.3s ease;

}


.convert-button {
    display: flex;
    align-items: center;
    flex-direction: column;
    gap: 10px;
    margin: 20px auto 0;
    justify-content: center;
    width: 90%;
    max-width: 500px;
}

#link {
    width: 100%;
    padding: 15px 20px;
    font-size: 16px;
    border: 2px solid #ddd;
    border-radius: 8px;
    font-family: 'Poppins';
    transition: all 0.3s ease;
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

#link:focus {
    outline: none;
    border-color: #4e4646;
    box-shadow: 0 0 0 3px rgba(255, 107, 107, 0.1);
}

#link::placeholder {
    color: #66626242;
}

.button2 {
    width: 100%;
    padding: 15px 30px;
    font-size: 16px;
    font-weight: 600;
    background: linear-gradient(135deg, #999595c7 0%, #d4d0d188 100%);
    color: rgb(22, 12, 12);
    border: none;
    border-radius: 8px;
    cursor: pointer;
    transition: all 0.3s ease;
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 10px;
    box-shadow: 0 4px 15px rgba(43, 8, 8, 0.3);
    font-family: 'Poppins';
}

.button2:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 20px rgba(37, 19, 19, 0.4);
    background: linear-gradient(135deg, #999595c7 0%, #d4d0d188 100%);
}

.button2:active {
    transform: translateY(0);
    box-shadow: 0 2px 10px rgba(94, 90, 90, 0.3);
}

.button2 img {
    width: 30px;
    height: 30px;
}

#resultado {
    width: 100%;
    margin-top: 20px;
    padding: 15px;
    border-radius: 8px;
    text-align: center;

}


