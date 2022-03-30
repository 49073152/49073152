<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>formulário</title>
</head>
<body>
    <div>
        <h1>formulário</h1>
        <p><h2>Insira suas imformações</h2></p>
        <br>
    </div>
    <form>
        <fieldset>
            <div>
                 <label>nome completo</label>
                 <input type="text" name="nome completo" id="nome completo">
            </div>

        <div>
            <label>Email</label>
            <input type="email" name="Email" id="Email">
        </div>
            <label>sexo</label>
            <label>
                <input type="radio" name="devweb" value="frontend">feminino
            </label>
            <label>
                <input type="radio" name="devweb" value="backend">masculino
            </label>
        <div>
            <label>cargo:</label>
                 <input type="text" name="cargo:" id="cargo:">
        </div>
        <div>
            <label>data de nascimento:</label>
            <label>
                <input id="date" type="date">
            </label>
        </div>
        <div>
            <label>telefone:</label>
            <label><input type="text" name="telefone" id="telefone"></label>
        </div>
        </fieldset>
        <div>
            <h1>Informações da instituição</h1>
            <p><h4>Preencha os campos abaixo com as Informações da empresa que trabalha</h4></p>
        </div>
        <fieldset>
        <div>
            <label>empresa:</label>
            <label><input type="text" name="empresa:" id="empresa:"></label>
        </div>
        <div>
            <label>Endereço completo:</label>
            <label><input type="text" name="Endereço completo" id="Endereço completo"></label>
        </div>
        <div>
            <label>Cidade:</label>
            <label><input type="text" name="Cidade" id="Cidade"></label>
        </div>
        <div>
            <label>Estado</label>
            <label>
                <select name="estado">
                    <option selected="" value="">Selecione o Estado (UF)</option>
                    <option value="Acre">Acre</option>
                    <option value="Alagoas">Alagoas</option>
                    <option value="Amapá">Amapá</option>
                    <option value="Amazonas">Amazonas</option>
                    <option value="Bahia">Bahia</option>
                    <option value="Ceará">Ceará</option>
                    <option value="Distrito Federal">Distrito Federal</option>
                    <option value="Espírito Santo">Espírito Santo</option>
                    <option value="Goiás">Goiás</option>
                    <option value="Maranhão">Maranhão</option>
                    <option value="Mato Grosso">Mato Grosso</option>
                    <option value="Mato Grosso do Sul">Mato Grosso do Sul</option>
                    <option value="Minas Gerais">Minas Gerais</option>
                    <option value="Pará">Pará</option>
                    <option value="Paraíba">Paraíba</option>
                    <option value="Paraná">Paraná</option>
                    <option value="Pernambuco">Pernambuco</option>
                    <option value="Piauí">Piauí</option>
                    <option value="Rio de Janeiro">Rio de Janeiro</option>
                    <option value="Rio Grande do Sul">Rio Grande do Sul</option>
                    <option value="Rio Grande do Norte">Rio Grande do Norte</option>
                    <option value="Rondônia">Rondônia</option>
                    <option value="Roraima">Roraima</option>
                    <option value="Santa Catarina">Santa Catarina</option>
                    <option value="São Paulo">São Paulo</option>
                    <option value="Sergipe">Sergipe</option>
                    <option value="Tocantins">Tocantins</option>
                </select
         </label>
        </div>
        <div>
            <label>Quantidade de funcionários:</label>
            <label>
                <input type="text" name="Quantidade de funcionários:" id="Quantidade de funcionários:">
            </label>
        </div>
        <div>
            <label>Observações:</label>
            <label>
                <input type="text" name="Observações:"  id="Observações:">
            </label>
        </div>
        </fieldset>
        <div>
            <label>Recibo:</label>
            <label>
                <input type="radio" name="devweb" value="frontend">Emitir em nome da instituição
            </label>
        </div>
        <button type="submit">Fazer inscrição</button>

    </form>
</body>
</html>
