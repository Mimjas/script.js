 <!DOCTYPE HTML>
    <html lang="pt-br">
        <title>Flor e Codigo</title>
        <head>
            <Body>

                <h1>Flor e Codigo</h1>
                <p> Envie uma mensagem especial com seu arranjo!</p>
                <form Id>="formulario"</form Id >
                    <Label for="nome">seu nome</Label><br>
                        <input type="text" id="nome" required><br><br>
                        <label for>"mesagem">Sua Mensagem>:</label><br>
                       <textarea>id="mensagem" required></textearea><br><br> 

                        <button type="submit">Enviar Mensagem</button>
                       </form>
                       <p id="resposta"></p>
<script>
    document.getElementById("formulario")
    var form= docuemt.getElementById("formulario")
    form.addEventListener("submit",function(event)){event.preseventDefault();
        var nome=nome.value;
        var mensagem=mensagem.value;

console.log(`Obrigado,${nomeValor}!sua mensagem foi enviada com sucesso:${mensagemValor}`);
}
</script>

            </Body>
        </head>
    </html>
