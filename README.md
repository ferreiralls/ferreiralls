<!DOCTYPE html>
<html lang="en"
    itemscope itemtype="http://schema.org/Organization"
    xmlns:mml="http://www.w3.org/1998/Math/MathML" 
    xmlns:og="http://opengraphprotocol.org/schema/"
    xmlns:fb="http://www.facebook.com/2008/fbml">
<head prefix="og: http://ogp.me/ns# khanacademy: http://ogp.me/ns/apps/khanacademy#">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8"/>
    <title>Khan Academy</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0"/>
    <link rel='canonical' href='/science/hs-chemistry/x2613d8165d88df5e:thermochemistry/x2613d8165d88df5e:calorimetry/e/apply-calorimetry'>
    <meta property='og:url' content='/science/hs-chemistry/x2613d8165d88df5e:thermochemistry/x2613d8165d88df5e:calorimetry/e/apply-calorimetry'>
    <link rel="stylesheet" type="text/css" href="https://cdn.kastatic.org/genwebpack/prod/en/app.4cf5b5c3f747759f1629.css"/>
    <link rel="shortcut icon" href="https://cdn.kastatic.org/images/favicon.ico?logo">
    <link rel="apple-touch-icon-precomposed" sizes="57x57" href="https://cdn.kastatic.org/images/apple-touch-icon-57x57-precomposed.new.png"/>
    <link rel="apple-touch-icon-precomposed" sizes="72x72" href="https://cdn.kastatic.org/images/apple-touch-icon-72x72-precomposed.new.png"/>
    <link rel="apple-touch-icon-precomposed" sizes="114x114" href="https://cdn.kastatic.org/images/apple-touch-icon-114x114-precomposed.new.png"/>
    <link rel="apple-touch-icon-precomposed" sizes="144x144" href="https://cdn.kastatic.org/images/apple-touch-icon-144x144-precomposed.new.png"/>
    <script>
        (function(w,d,s,l,i){
            w[l]=w[l]||[];
            w[l].push({'gtm.start':new Date().getTime(),event:'gtm.js'});
            var f=d.getElementsByTagName(s)[0],
                j=d.createElement(s),
                dl=l!='dataLayer'?'&l='+l:'';
            j.async=true;
            j.src='https://www.googletagmanager.com/gtm.js?id='+i+dl;
            f.parentNode.insertBefore(j,f);
        })(window,document,'script','dataLayer','GTM-WSX5PBP');
        
        function gerarResposta(pergunta) {
            let resposta = "";

            // Respostas baseadas nas perguntas comuns
            if (pergunta.includes("O que é calorimetria?")) {
                resposta = "Calorimetria é o estudo das quantidades de calor envolvidas nas reações químicas e nas mudanças de estado físico.";
            } else if (pergunta.includes("Como calcular a energia calorífica?")) {
                resposta = "A energia calorífica pode ser calculada pela fórmula Q = mcΔT, onde Q é a energia calorífica, m é a massa, c é a capacidade calorífica e ΔT é a variação de temperatura.";
            } else if (pergunta.includes("Qual é a unidade de medida do calor?")) {
                resposta = "A unidade de medida do calor é o Joule (J) no Sistema Internacional de Unidades (SI).";
            } else if (pergunta.includes("Como a temperatura afeta a energia térmica?")) {
                resposta = "A temperatura é uma medida da energia térmica de um sistema; à medida que a temperatura aumenta, a energia térmica também aumenta.";
            } else {
                resposta = "Desculpe, não consegui entender sua pergunta. Por favor, reformule ou consulte a seção de ajuda.";
            }

            return resposta;
        }

        function responder() {
            let perguntaUsuario = document.getElementById("pergunta").value;
            let respostaAutomatica = gerarResposta(perguntaUsuario);
            document.getElementById("resposta").innerText = respostaAutomatica;
        }
    </script>
</head>
<body>
    <h1>Bem-vindo à Khan Academy</h1>
    <p>Como posso ajudar você hoje?</p>
    
    <input type="text" id="pergunta" placeholder="Digite sua pergunta aqui">
    <button onclick="responder()">Enviar</button>
    <p id="resposta"></p>

    <!-- Adicione mais conteúdo da sua página aqui -->

</body>
</html>
