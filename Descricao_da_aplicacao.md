# Sistema de cadastro de colaboradores (HRM)

### Descrição da Aplicação
Desenvolvemos uma página WEB que tem como objetivo cadastrar colaboradores.
O site foi dividido em três abas (Informações Gerais, Informações Pessoais e Documentação), para facilitar a visualização do usuário, e a manutenção do código pelo desenvolvedor. 

### 1º Informações Gerais (Formulario_1.html)
 **Contém os seguintes campos:**
> - Situação (Ligado ou Desligado)
> - Tipo de pagamento (Mensal, Semanal e Diario)
> - Departamento (Planejamento, Inventario, Financeiro, Recursos Humanos, Transporte, TI e Projetos)
> - Cargo (Gerente, Supervisor, Coordenador, Especialista, Análista Sr, Análista Pl, Análista Jr, Assistente, Auxiliar, Estagiario)
> - Jornada Semanal
> - % Adiantamento
> - Sálario
> Data de Admissão
> Tipo de Admissão (Admissão, transferencia da empresa, Admissão por sucessão ou fusão, Trabalhador cedido e Temporario)
> - Foto 3X4
> - Descrição da Função

#### Código HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FISIA - Register Employee System</title>
    <link rel="icon" href="icone.jpg">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">  
  </head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark" style="padding: 30px;">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Human Resource Management</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-circle-fill" viewBox="0 0 16 16">
                    <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.5 4.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3z"/>
                  </svg>
                  Cadastro
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                    <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                  </svg>
                  Consulta
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\login_1.html">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-box-arrow-left" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M6 12.5a.5.5 0 0 0 .5.5h8a.5.5 0 0 0 .5-.5v-9a.5.5 0 0 0-.5-.5h-8a.5.5 0 0 0-.5.5v2a.5.5 0 0 1-1 0v-2A1.5 1.5 0 0 1 6.5 2h8A1.5 1.5 0 0 1 16 3.5v9a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 5 12.5v-2a.5.5 0 0 1 1 0v2z"/>
                    <path fill-rule="evenodd" d="M.146 8.354a.5.5 0 0 1 0-.708l3-3a.5.5 0 1 1 .708.708L1.707 7.5H10.5a.5.5 0 0 1 0 1H1.707l2.147 2.146a.5.5 0 0 1-.708.708l-3-3z"/>
                  </svg>
                  Sair
                </a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Formulario_1.html">Informações Gerais</a>
              </li>
              <li class="nav-item" >
                <a class="nav-link" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Fomulario_2.html" >Informações Pessoais</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Formulario_3.html">Documentação</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <hr>
      <br>
  <form class="row g-3 needs-validation" novalidate style="margin-left: 10px;margin-right: 10px;">
      <legend>Informações Gerais</legend>
      <div class="col-md-4">
        <div class="input-group has-validation">
          <span class="input-group-text" id="inputGroupPrepend">Situação</span>
            <select class="form-select" id="validationCustom04" required>
                <option selected disabled value="">Escolha...</option>
                <option value="Gerente">Ligado</option>
                <option value="Supervisor">Desligado</option>
            </select>
          <div class="invalid-feedback">
                Please choose a username.
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="input-group has-validation">
          <span class="input-group-text" id="inputGroupPrepend">Tipo de Pagamento</span>
            <select class="form-select" id="validationCustom04" required>
                <option selected disabled value="">Escolha...</option>
                <option value="Gerente">Mensal</option>
                <option value="Supervisor">Semanal</option>
                <option value="Supervisor">Diario</option>
            </select>
          <div class="invalid-feedback">
                Please choose a username.
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="input-group has-validation">
          <span class="input-group-text" id="inputGroupPrepend">Departamento</span>
            <select class="form-select" id="validationCustom04" required>
              <option selected disabled value="">Escolha...</option>
              <option value="Planejameto">Planejameto</option>
              <option value="Inventário">Inventário</option>
              <option value="Financeiro">Financeiro</option>
              <option value="Recursos Humanos">Recursos Humanos</option>
              <option value="Transporte">Transporte</option>
              <option value="TI">TI</option>
              <option value="Projetos">Projetos</option>
            </select>
          <div class="invalid-feedback">
                Please choose a username.
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="input-group has-validation">
          <span class="input-group-text" id="inputGroupPrepend">Cargo</span>
            <select class="form-select" id="validationCustom04" required>
              <option value="Gerente">Gerente</option>
                <option value="Supervisor">Supervisor</option>
                <option value="Coordenador">Coordenador</option>
                <option value="Especialista">Especialista</option>
                <option value="Análista Sr">Análista Sr</option>
                <option value="Análista Pl">Análista Pl</option>
                <option value="Análista Jr">Análista Jr</option>
                <option value="Assistente">Assistente</option>
                <option value="Auxiliar">Auxiliar</option>
                <option value="Estagiario">Estagiario</option>
            </select>
          <div class="invalid-feedback">
                Please choose a username.
          </div>
        </div>
      </div>

      <div class="col-md-4">
        <div class="input-group has-validation">
          <span class="input-group-text" id="inputGroupPrepend">jornanda Semanal</span>
          <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
          <div class="invalid-feedback">
                Please choose a username.
          </div>
        </div>
    </div>

    <div class="col-md-4">
      <div class="input-group has-validation">
        <span class="input-group-text" id="inputGroupPrepend">% Adiantamento</span>
        <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
        <div class="invalid-feedback">
              Please choose a username.
        </div>
      </div>
    </div>

    <div class="col-md-4">
      <div class="input-group has-validation">
        <span class="input-group-text" id="inputGroupPrepend">Sálario</span>
        <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;" placeholder="R$">
        <div class="invalid-feedback">
              Please choose a username.
        </div>
      </div>
   </div>

<div class="col-md-4">
  <div class="input-group has-validation">
    <span class="input-group-text" id="inputGroupPrepend">Data Admissão</span>
    <input type="date" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;" placeholder="R$">
    <div class="invalid-feedback">
          Please choose a username.
    </div>
  </div>
</div>

<div class="col-md-4">
  <div class="input-group has-validation">
    <span class="input-group-text" id="inputGroupPrepend">Tipo de Admissão</span>
      <select class="form-select" id="validationCustom04" required>
        <option selected disabled value="">Escolha...</option>  
        <option>1 - Admissão</option>
        <option>2 - Transferência de empresa do mesmo grupo econômico</option>
        <option>3 - Admissão por sucessão, incorporação ou fusão</option>
        <option>4 - Trabalhador cedido</option>
        <option>5 - Temporario</option>
      </select>
    <div class="invalid-feedback">
          Please choose a username.
    </div>
  </div>
</div>

<div class="col-md-4">
  <div class="input-group has-validation">
    <span class="input-group-text" id="inputGroupPrepend">Foto 3x4</span>
    <input type="file" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;" placeholder="R$">
    <div class="invalid-feedback">
          Please choose a username.
    </div>
  </div>
</div>

  <div class="col-md-4">
    <div class="input-group has-validation">
      <span class="input-group-text" id="inputGroupPrepend">Descrição da Função</span>
      <textarea type="" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
      </textarea>
        <div class="invalid-feedback">
            Please choose a username.
      </div>
    </div>
  </div>

  <div class="col-12">
     <button class="btn btn-primary btn-dark" type="submit">Submit form</button>
     <button class="btn btn-primary btn-dark" type="reset">Delete</button>
  </div>
</form>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
</body>
</html>
```





### 2º Informações Pessoais (Fomulario_2.html)
**Contém os seguintes campos:**
> - Nome completo
> - Data de Nascimento
> - Sexo (Masculino e Feminino)
> - Deficiente (Não, Física, Audititva, Visual, Mental, Multipla, Reabilitado)
> - Estado civil (Casado, Solteiro, Divorciado, Viúvo, União Estável, Outros)
> - Grau de Instrução (Até a 4º Série Incompleta, 4º Série Completa, Da 5º a 8º Série Completa, Fundamental Completo, 1º Grau Incompleto, 1º Grau Completo, 2º Grau Incompleto, 2º Grau Completo, 3º Grau Incompleto, 3º Grau Completo, Superior Incompleto, Superior Completo, Pós Graduação, Mestrado, Doutorado)
> - Nome do Pai
> - Nome da Mãe
> - CEP
> - Tipo (Rua, Avenida e Rodovia)
> - Rua
> - Número
> - Complemento
> - Bairro
> - Cidade
> - Estado
> - IBGE
> - Tel Fixo
> - Cel 
> - Email

Código HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FISIA - Register Employee System</title>
    <link rel="icon" href="icone.jpg">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

</head>
<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-dark " style="padding: 30px;">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Human Resource Management </a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-circle-fill" viewBox="0 0 16 16">
                    <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.5 4.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3z"/>
                  </svg>
                  Cadastro
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                    <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                  </svg>
                  Consulta
                </a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\login_1.html">
                  <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-box-arrow-left" viewBox="0 0 16 16">
                    <path fill-rule="evenodd" d="M6 12.5a.5.5 0 0 0 .5.5h8a.5.5 0 0 0 .5-.5v-9a.5.5 0 0 0-.5-.5h-8a.5.5 0 0 0-.5.5v2a.5.5 0 0 1-1 0v-2A1.5 1.5 0 0 1 6.5 2h8A1.5 1.5 0 0 1 16 3.5v9a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 5 12.5v-2a.5.5 0 0 1 1 0v2z"/>
                    <path fill-rule="evenodd" d="M.146 8.354a.5.5 0 0 1 0-.708l3-3a.5.5 0 1 1 .708.708L1.707 7.5H10.5a.5.5 0 0 1 0 1H1.707l2.147 2.146a.5.5 0 0 1-.708.708l-3-3z"/>
                  </svg>
                  Sair
                </a>
              </li>
            </ul>
          </div>
        </div>
    </nav>
    <nav class="navbar navbar-expand-lg navbar-light bg-light ">
        <div class="container-fluid">
          <a class="navbar-brand" href="#"></a>
          <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link" aria-current="" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Formulario_1.html">Informações Gerais</a>
              </li>
              <li class="nav-item" >
                <a class="nav-link active" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Fomulario_2.html" >Informações Pessoais</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Formulario_3.html">Documentação</a>
              </li>
            </ul>
          </div>
        </div>
    </nav>
    <hr>
    <br>
    <form class="row g-3 needs-validation" novalidate style="margin-left: 10px;margin-right: 10px;">
        <legend>Informações Pessoais</legend>
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Nome Completo</span>
              <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Data de Nascimento</span>
              <input type="date" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Sexo</span>
                <select class="form-select" id="validationCustom04" required>
                    <option selected disabled value="">Escolha...</option>
                    <option value="Gerente">Masculino</option>
                    <option value="Supervisor">Feminino</option>
                </select>
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Deficiente</span>
                <select class="form-select" id="validationCustom04" required>
                    <option selected disabled value="">Escolha...</option>
                    <option>0 - Não</option>            
                    <option>1 - Física</option>            
                    <option>2 - Auditiva</option>            
                    <option>3 - Visual</option>            
                    <option>4 - Mental</option>
                    <option>5 - Multipla</option>
                    <option>6 - Reabilitado</option>
                </select>
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Estado Civil</span>
                <select class="form-select" id="validationCustom04" required>
                    <option selected disabled value="">Escolha...</option>
                    <option>1 - Casado</option>
                    <option>2 - Solteiro</option>
                    <option>3 - Divorciado</option>
                    <option>4 - Viúvo</option>
                    <option>5 - Unisão Estável</option>
                    <option>6 - Outros</option>
                </select>
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend"> Grau de Instrução</span>
                <select class="form-select" id="validationCustom04" required>
                    <option selected disabled value="">Escolha...</option>
                    <option>1 - Até a 4º Série Incompleta</option>
                    <option>2- 4º Série Completa</option>
                    <option>3 - Da 5º a 8º Série Incompleta</option>
                    <option>4 - Fundamental Completo</option>
                    <option>5 - 1º Grau Incompleto</option>
                    <option>6 - 1º Grau Completo</option>
                    <option>7 - 2º Grau Incompleto</option>
                    <option>8 - 2º Greu Completo</option>
                    <option>9 - 3º Grau Incompleto</option>
                    <option>10 - 3º Grau Completo</option>
                    <option>11 - Superior Incompleto</option>
                    <option>12 - Superior Completo</option>
                    <option>13 - Pós Graduação</option>
                    <option>14 - Mestrado</option>
                    <option>15 - Doutorado</option>
                </select>
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Nome do Pai</span>
              <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
        
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Nome da Mãe</span>
              <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
        <br><br>
        <legend>Endereço</legend>
    <div>
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">CEP</span>
              <input type="text" class="form-control" name="cep" id="cep" value="" size="10" aria-describedby="inputGroupPrepend" required style="width: 5px;" onblur="pesquisacep(this.value);">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
    </div>
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Tipo</span>
                <select class="form-select" id="validationCustom04" required>
                    <option selected disabled value="">Escolha...</option>
                    <option>Avenida</option>
                    <option>Rua</option>
                    <option>Rodovia</option>
                </select>
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Rua</span>
              <input name="rua" type="text" value="" size="60" id="rua" class="form-control" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Numero</span>
              <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Complemento</span>
              <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Bairro</span>
              <input name="bairro" type="text" value="" size="40" id="bairro" class="form-control" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Cidade</span>
              <input name="cidade" type="text" value="" size="40" id="cidade" class="form-control" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
        <div class="col-md-4">
          <div class="input-group has-validation">
            <span class="input-group-text" id="inputGroupPrepend">Estado</span>
            <input name="uf" type="text" value="" size="2" id="uf" class="form-control" aria-describedby="inputGroupPrepend" required style="width: 5px;">
            <div class="invalid-feedback">
                  Please choose a username.
            </div>
          </div>
      </div>
      <div class="col-md-4">
        <div class="input-group has-validation">
          <span class="input-group-text" id="inputGroupPrepend">IBGE:</span>
          <input name="ibge" type="text" value="" size="8" id="ibge" class="form-control" aria-describedby="inputGroupPrepend" required style="width: 5px;">
          <div class="invalid-feedback">
                Please choose a username.
          </div>
        </div>
    </div>


        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Telefone Fixo</span>
              <input type="tel" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
        
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Celular</span>
              <input type="tel" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>
       
        <div class="col-md-4">
            <div class="input-group has-validation">
              <span class="input-group-text" id="inputGroupPrepend">Email</span>
              <input type="email" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
              <div class="invalid-feedback">
                    Please choose a username.
              </div>
            </div>
        </div>

        <div class="col-12">
            <button class="btn btn-primary btn-dark" type="submit" style="margin-bottom: 20px; margin-top: 20px;">Submit form</button>
        
        
            <button class="btn btn-primary btn-dark" type="reset" style="margin-bottom: 20px; margin-top: 20px;">Delete</button>
        </div>
    </form>
    

    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    <script src="main.js"></script>
</body>
</html>
```

### 3º Documentação (Formulario_3.html)
**Contém os seguintes campos:**

> - CPF
> - RG
> - Orgão de Emissão
> - PIS
> - Titulo de Eleitor
> - Zona
> - Seção 
> - Serv. Militar
> - CNH
> - Categoria
> - Data de emissão
> - Data de vencimento
> - CTPS 
> - Série
> - Data de emissão
> - RIC
> - Instituição Bancaria (Itaú Unibanco Banco Múltiplo S.A., Bradesco BBI S.A, Santander S.A, Banco do Brasil S.A)
> - Banco 
> - Ag
> - Número 
> - Tipo da conta (Conta-corrente ou Conta-poupança)

Código HTML

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>FISIA - Register Employee System</title>
        <link rel="icon" href="icone.jpg">
        <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

    </head>
    <body>
        <nav class="navbar navbar-expand-lg navbar-dark bg-dark " style="padding: 30px;">
            <div class="container-fluid">
              <a class="navbar-brand" href="#">Human Resource Management</a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link active" aria-current="page" href="#">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-plus-circle-fill" viewBox="0 0 16 16">
                        <path d="M16 8A8 8 0 1 1 0 8a8 8 0 0 1 16 0zM8.5 4.5a.5.5 0 0 0-1 0v3h-3a.5.5 0 0 0 0 1h3v3a.5.5 0 0 0 1 0v-3h3a.5.5 0 0 0 0-1h-3v-3z"/>
                      </svg>
                      Cadastro
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="#">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-search" viewBox="0 0 16 16">
                        <path d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"/>
                      </svg>    
                      Consulta
                    </a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\login_1.html">
                      <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-box-arrow-left" viewBox="0 0 16 16">
                        <path fill-rule="evenodd" d="M6 12.5a.5.5 0 0 0 .5.5h8a.5.5 0 0 0 .5-.5v-9a.5.5 0 0 0-.5-.5h-8a.5.5 0 0 0-.5.5v2a.5.5 0 0 1-1 0v-2A1.5 1.5 0 0 1 6.5 2h8A1.5 1.5 0 0 1 16 3.5v9a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 5 12.5v-2a.5.5 0 0 1 1 0v2z"/>
                        <path fill-rule="evenodd" d="M.146 8.354a.5.5 0 0 1 0-.708l3-3a.5.5 0 1 1 .708.708L1.707 7.5H10.5a.5.5 0 0 1 0 1H1.707l2.147 2.146a.5.5 0 0 1-.708.708l-3-3z"/>
                      </svg>    
                      Sair
                    </a>
                  </li>
                </ul>
              </div>
            </div>
        </nav>
        <nav class="navbar navbar-expand-lg navbar-light bg-light ">
            <div class="container-fluid">
              <a class="navbar-brand" href="#"></a>
              <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
              </button>
              <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav">
                  <li class="nav-item">
                    <a class="nav-link" aria-current="" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Formulario_1.html">Informações Gerais</a>
                  </li>
                  <li class="nav-item" >
                    <a class="nav-link" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Fomulario_2.html" >Informações Pessoais</a>
                  </li>
                  <li class="nav-item">
                    <a class="nav-link active" href="C:\Users\MSan77\Desktop\M.S\Metrocamp\Desenvolvimento Web\Projeto AV1\Formulario_3.html">Documentação</a>
                  </li>
                </ul>
              </div>
            </div>
        </nav>
        <hr>
        <br>

        <form class="row g-3 needs-validation" novalidate style="margin-left: 10px;margin-right: 10px;">
            <legend>Documentação</legend>
        
            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">CPF</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">RG</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Orgão de Emissão</span>
                  <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">PIS</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>


            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Titulo  de Eleitor</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>


            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Zona</span>
                  <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Seção</span>
                  <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">C. Serv Militar</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">CNH</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Categoria</span>
                  <input type="text" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Data de Emissão</span>
                  <input type="date" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Data de Vencimento</span>
                  <input type="date" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">CTPS</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Série</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Data de Emissão</span>
                  <input type="date" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">RIC</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>
            
            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Instituição Bancaria</span>
                    <select class="form-select" id="validationCustom04" required>
                        <option selected disabled value="">Escolha...</option>
                        <option>Itaú Unibanco Banco Múltiplo S.A.</option>
                        <option>Bradesco BBI S.A</option>
                        <option>Santander S.A</option>
                        <option>Banco do Brasil S.A</option>
                    </select>
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Banco</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>
            
            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Ag</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Número da conta</span>
                  <input type="number" class="form-control" id="validationCustomUsername" aria-describedby="inputGroupPrepend" required style="width: 5px;">
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>
            
            <div class="col-md-4">
                <div class="input-group has-validation">
                  <span class="input-group-text" id="inputGroupPrepend">Instituição Bancaria</span>
                    <select class="form-select" id="validationCustom04" required>
                        <option selected disabled value="">Escolha...</option>
                        <option>Conta-Corrente</option>
                        <option>Conta-Poupança</option>
                    </select>
                  <div class="invalid-feedback">
                        Please choose a username.
                  </div>
                </div>
            </div>

            <div class="col-12">
                <button class="btn btn-primary btn-dark" type="submit" style="margin-bottom: 20px; margin-top: 20px;">Submit form</button>
                <button class="btn btn-primary btn-dark" type="reset" style="margin-bottom: 20px; margin-top: 20px;">Delete</button>
            </div>

        </form>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.10.2/dist/umd/popper.min.js" integrity="sha384-7+zCNj/IqJ95wo16oMtfsKbZ9ccEh31eOz1HGyDuCQ6wgnyJNSYdrPa03rtR1zdB" crossorigin="anonymous"></script>
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.min.js" integrity="sha384-QJHtvGhmr9XOIpI6YVutG+2QOK9T+ZnN4kzFN1RtK3zEFEIsxhlmWl5/YESvpZ13" crossorigin="anonymous"></script>
    
      </body>
</html>
```

#### Visão em Markdown

```Markdown

# Sistema de cadastro de colaboradores (HRM)

### Descrição da Aplicação
Desenvolvemos uma página WEB que tem como objetivo cadastrar colaborasdores.
O site foi dividido em três abas (Informações Gerais, Informações Pessoais e Documentação), para facilitar a visualização do usuário, e a manutenção do código pelo desenvolvedor. 

### 1º Informações Gerais (Formulario_1.html)
 **Contém os seguintes campos:**
> - Situação (Ligado ou Desligado)
> - Tipo de pagamento (Mensal, Semanal e Diario)
> - Departamento (Planejamento, Inventario, Financeiro, Recursos Humanos, Transporte, TI e Projetos)
> - Cargo (Gerente, Supervisor, Coordenador, Especialista, Análista Sr, Análista Pl, Análista Jr, Assistente, Auxiliar, Estagiario)
> - Jornada Semanal
> - % Adiantamento
> - Sálario
> Data de Admissão
> Tipo de Admissão (Admissão, transferencia da empresa, Admissão por sucessão ou fusão, Trabalhador cedido e Temporario)
> - Foto 3X4
> - Descrição da Função

### 2º Informações Pessoais (Fomulario_2.html)
**Contém os seguintes campos:**
> - Nome completo
> - Data de Nascimento
> - Sexo (Masculino e Feminino)
> - Deficiente (Não, Física, Audititva, Visual, Mental, Multipla, Reabilitado)
> - Estado civil (Casado, Solteiro, Divorciado, Viúvo, União Estável, Outros)
> - Grau de Instrução (Até a 4º Série Incompleta, 4º Série Completa, Da 5º a 8º Série Completa, Fundamental Completo, 1º Grau Incompleto, 1º Grau Completo, 2º Grau Incompleto, 2º Grau Completo, 3º Grau Incompleto, 3º Grau Completo, Superior Incompleto, Superior Completo, Pós Graduação, Mestrado, Doutorado)
> - Nome do Pai
> - Nome da Mãe
> - CEP
> - Tipo (Rua, Avenida e Rodovia)
> - Rua
> - Número
> - Complemento
> - Bairro
> - Cidade
> - Estado
> - IBGE
> - Tel Fixo
> - Cel 
> - Email

### 3º Documentação (Formulario_3.html)
**Contém os seguintes campos:**

> - CPF
> - RG
> - Orgão de Emissão
> - PIS
> - Titulo de Eleitor
> - Zona
> - Seção 
> - Serv. Militar
> - CNH
> - Categoria
> - Data de emissão
> - Data de vencimento
> - CTPS 
> - Série
> - Data de emissão
> - RIC
> - Instituição Bancaria (Itaú Unibanco Banco Múltiplo S.A., Bradesco BBI S.A, Santander S.A, Banco do Brasil S.A)
> - Banco 
> - Ag
> - Número 
> - Tipo da conta (Conta-corrente ou Conta-poupança)
```