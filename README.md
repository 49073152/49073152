index.html
<!doctype html>
</head>
<body>
    <h1>Meu formulário</h1>
     <form action="" method="get">
            <input type="text" name="telefone"
                placeholder="(99)9999-9999" size="30"
                maxlength="13">
            <br><br>
        <label for="senha">Senha:</label>
        <input type="password" name="senha" id="senha"
            placeholder="informe sua senha">
            <label>Brasileiro nato?
                <input type="checkbox" name="bras">
            </label>
            <fieldset>
                <legend>Sexo</legend>
                <label for="masc">Masculino</label>
                <input type="radio" name="sexo"
                    value="M" id="masc">
                <legend>Sexo</legend>
                <label for="fem">Feminino</label>
                <input type="radio" name="sexo"
                    value="F" id="fem">
            </fieldset>
            <br>
            <label for="mensagem">Escreva uma mensagem
            <br>
            <texrarea id="mensagem" name="mensagem" 
                rows="10" cols="20"
                placeholder="escreva sua mensagem aqui..."></texrarea>
            <fieldset>
                <legend>Estado</legend>
            <seclect name="estado">
                    <option selected disabled>Selecione</option>
                        <option vaule="AC">Acre</option>
                        <option vaule="AP">Amapá</option>
                        <option vaule="AM">Amazonas</option>
                        <option vaule="AL">Alagoas</option>
                        <option vaule="BA">Bahia</option>
            </seclect>
            </fieldset>
            </form>
            <br>
            <input type="submit" value="enviar"> &nbsp;&nbsp;
            <input type="reset" value="Limpar">
    </form>
</body>
</html>
