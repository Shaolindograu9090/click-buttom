# click-buttom
um dos meus primeiros codigos em js]
apenas um misero botão
 um antigo projeto de iniciante meu

<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ta doento papai </title>

    <style>
        div#area{
            background-color: rgb(42, 165, 144);
            color: antiquewhite;
            font: normal 20pt Arial;
            width: 200px;
            height:150px;
        }
    </style>

</head>

<body>

    <div id = "area" onclick="clicar()" onmouseenter="entrar()" onmouseout="sair()">
        toque em mim, tenho ansiedade
        

    <script>
        var a = document.getElementById("area")
        // esse comando fica de olhos em futuros eventos, alem de ser prático.
        addEventListener("click",tocou)
        addEventListener("mousenenter",entrou)
        addEventListener("mouseout",saiu)


        // essas "functions" permitem a criação de interações com as ferrametas de click etc.
        // onde ao invocar a function + ação(clicar)+ () + o bloco de informações{}
        function clicar(){
            
            a.innerText = 'tocou'
            a.style.background = "black"
            
        }

        function adentrar() {
            a.innerText = 'entrou'
            a.style.background = "blue"
        }

        function retirar(){
            a.innerText = 'saiu'
            a.style.background = "red" 
            a.style.color = "purple"
        }


    </script>
