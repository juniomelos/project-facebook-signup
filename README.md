# Boas vindas ao repositório do projeto de réplica da página de cadastro do Facebook!

Você já usa o GitHub diariamente para desenvolver os exercícios, certo? Agora, para desenvolver os projetos, você deverá seguir as instruções a seguir. Fique atento a cada passo e, se tiver qualquer dúvida, nos envie por _Slack_! #vqv 🚀

Aqui você vai encontrar os detalhes de como estruturar o desenvolvimento do seu projeto a partir deste repositório, utilizando uma branch específica e um _Pull Request_ para colocar seus códigos.

⚠ **Importante:** O desenvolvimento deste projeto será em dupla. Atentem-se às orientações da facilitação da turma para formar a sua.

## O que deverá ser desenvolvido

Todos os requisitos tem como base a página do **Facebook**.
Use a imagem do site, além de acessar [a página de cadastro/login](https://www.facebook.com/).
Tente ser o mais fiel possível.

Use a inspeção de código para verificar a estrutura da página de cadastro/login do **Facebook**.

Antes de iniciar o projeto, leia atentamente a seção "Entregáveis".
Você irá desenvolver este projeto em **dupla** e é fundamental que siga as instruções do repositório.

---

## Entregáveis

Para entregar o seu projeto você deverá criar um _Pull Request_ para este repositório no **GitHub**.

Este _Pull Request_ deverá conter, necessariamente, os arquivos `index.html`, `style.css` e `script.js`, que conterão seu código **_HTML_**, **_CSS_** e **_JavaScript_**, respectivamente. ⚠️ É importante que seus arquivos tenham exatamente estes nomes! ⚠️

Você pode adicionar outros arquivos se julgar necessário.

---

## Requisitos do projeto

A seguir, estão listados todos os requisitos do projeto. Leia-os atentamente e siga à risca o que for pedido. Em particular, atente-se para os nomes de classes e ids que alguns elementos de seu projeto devem possuir. **Não troque ids por classes ou vice-versa**. O não cumprimento de um requisito, total ou parcialmente, impactará em sua avaliação.

Os requisitos do seu projeto são avaliados automaticamente, sendo utilizada a resolução `1366 x 768` (1366 pixels de largura por 768 pixels de altura). Logo, recomenda-se desenvolver seu projeto usando a mesma resolução, via instalação [deste plugin](https://chrome.google.com/webstore/detail/window-resizer/kkelicaakdanhinjdeammmilcgefonfh?hl=en) do `Chrome` para facilitar a configuração dessa resolução.

Caso você faça o _download_ de bibliotecas externas, utilize o diretório _libs_ (a partir da raiz do projeto) para colocar os arquivos (*.css, *.js, etc...) baixados.

### 1 - Posicionamento de elementos utilizando _CSS Flexbox_.

### 2 - Uma barra azul na parte superior da página do **Facebook** com a classe `"top-bar"`.

### 3 - O logotipo do **Facebook** no canto superior esquerdo com a classe `"facebook-logo"`.

### 4 - Um campo de entrada de texto no canto superior direito para receber o email ou o telefone do usuário com o id `"user-email-phone"`.

### 5 - Um título com o texto 'Email ou telefone' acima do campo de entrada de texto para email ou telefone com o id `"user-email-phone-label"`.

### 6 - Um campo de entrada de texto para digitar a senha do usuário, posicionado no canto superior direito. O campo também deve estar posicionado à direita do campo de entrada de texto para email ou telefone.

  Pontos importantes:
    * Ao digitar a senha, o padrão deve ser '*****'.

### 7 - Um botão com o id `"button-login"` e o texto 'Entrar', à direita do campo de entrada de texto para senha.

  Pontos importantes:
    * Ao clicar no botão, um `alert` deve ser exibido com o email ou telefone digitado pelo usuário.

### 8 - Um texto 'O Facebook ajuda você a se conectar e compartilhar com as pessoas que fazem parte da sua vida.' abaixo da barra superior azul do **Facebook**, no canto esquerdo.

### 9 - Uma imagem com id `"facebook-networking"`, que ficará abaixo do item 8. Essa imagem deve conter o mapa do mundo e as conexões entre as pessoas.

  Pontos importantes:
    * Dê o nome "networking.png" para a imagem.

### 10 - Um texto 'Abra uma conta' posicionado abaixo da caixa de texto de email/telefone.

### 11 - Um texto 'É rápido e fácil.' posicionado abaixo do texto 'Abra uma conta'.

### 12 - Um campo de entrada de texto para o nome do usuário. Posicione esse campo abaixo do texto 'É rápido e fácil.'.

  Pontos importantes:
    * Defina o `placeholder` com o valor "Nome".

### 13 - Um campo de entrada de texto para o sobrenome do usuário. Posicione esse campo à direita do campo nome.

  Pontos importantes:
    * Defina o `placeholder` com o valor "Sobrenome".

### 14 - Um campo de entrada de texto para o celular ou email. Posicione esse campo abaixo do sobrenome do usuário.

  Pontos importantes:
    * Defina o `placeholder` com o valor "Celular ou email".

### 15 - Um campo de entrada de texto para a nova senha do usuário. Posicione esse campo abaixo do celular/email.

  Pontos importantes:
    * Lembre-se de respeitar a formatação de senha '*****'.
    * Defina o `placeholder` com o valor "Nova senha".

### 16 - Um texto 'Data de nascimento' abaixo do campo de entrada de texto de nova senha.

### 17 - Um campo para selecionar a data de nascimento.

  Pontos importantes:
    * Diferentemente do Facebook, esse campo deve ser composto de um único _input_, e você deverá utilizar alguma biblioteca para transformá-lo em um _datepicker_.
    * Defina o `placeholder` com o valor "dd/mm/aaaa".

### 18 - Um texto 'Gênero' abaixo dos campos de data.

### 19 - Três `radio buttons` com os nomes 'Feminino', 'Masculino' e 'Personalizado'.

  Pontos importantes:
    * Posicione abaixo do texto 'Gênero'.

### 20 - Um botão com o texto 'Cadastre-se' e id `"facebook-register"`.

  Pontos importantes:
    * Esse botão deve pegar os dados dos itens 12 até 19 e validá-los.
    * Caso tudo esteja certo, exiba um `alert` com todos os dados no seguinte formato:
      Por exemplo:
        Se a pessoa que usa digitar o nome "João" e selecionar "Personalizado", o conteúdo da mensagem no `alert` deve ser 'João - Personalizado'.
    * Caso alguma validação dê errado, exiba um `alert` com a mensagem 'Dados inválidos'.

---


### REVISANDO UM PULL REQUEST

⚠⚠⚠

À medida que você e demais estudantes forem entregando os projetos, vocês receberão alertas **via Slack** para também fazer a revisão dos _Pull Requests_ dos seus colegas. Atentem-se às mensagens do _"Pull Reminders"_ no _Slack_!

