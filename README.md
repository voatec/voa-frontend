# Overview
Este teste busca avaliar quesitos técnicos de nossos queridos canditados, então borá lá! :smile:

### O Desafio
O objetivo é criar uma landing page seguindo o layout desta url: 

### Materiais gráficos
Todas as imagens e fonts utilizadas na landing page estão disponíveis nesse mesmo repositório na branch __*material*__

## Pré-requisitos: :white_check_mark:
- Ter um layout responsivo
- Formulário com validação de preenchimento e de e-mail válido
- Possuir 65+ de performance no lighthouse desktop/mobile
- Funcional no navegador Chrome

### Sobre o layout
A imagem de referencia da landing não possui um exemplar mobile, portanto use sua criatividade para moldar a landing para o mobile da forma como achar interessante.

### Sobre o lighthouse
O teste para o resultado de performance será executado em uma janela anônima.

## Plus :star:
- Utilizar pré-processador css
- Aplicar um Google Captcha para o formulário
- Funcional em outros navegadores além do Chrome
- Integrar formulário com a API de contato
  - Antes de postar seu formulário, verificar se o e-mail digitado já possui cadastro, utilizar o e-mail `test@frontend.com` como e-mail fictício já existente na base para válidar o seu teste.
  - Realizar tratamento de retorno para o usuário.

### Sobre a API
> Host: https://voaremos-services.com.br/api_vt

Utilize o endpoint `/test/contact/{contactEmail}` com o email `test@frontend.com`

#### E-mail cadastrado:
```
{
  "status": 200,
  "message": "E-mail encontrado",
  "data": {
    "email": "{contactEmail}"
  }
}
```
#### E-mail não cadastrado:
```
{
  "status": 404,
  "message": "E-mail não encontrado"
}
```


## Tecnologias que podem ser utilizadas
Você é livre para utilizar qualquer framework JS que preferir.

Na parte de CSS, você é livre para utilizar qualquer pré-processador também, mas não é permitido utilizar nenhum framework CSS. Aqui utilizamos SASS (scss).

Sobre task manager, bundler e similares, fica à vontade de utilizar o que achar necessário, apenas pedimos que você adicione instruções detalhadas sobre como fazer funcionar a aplicação.

Boa sorte! :wink:
