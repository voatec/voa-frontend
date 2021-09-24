# Overview
Este teste busca avaliar quesitos técnicos de nossos queridos canditados, então borá lá! :smile:

### Desafio
O objetivo é criar uma landing page seguindo o layout desta url: https://raw.githubusercontent.com/voatec/voa-frontend/main/materials/images/landing.png

### Materiais
Todas as imagens e fonts utilizadas na landing page estão disponíveis nesse mesmo repositório na branch __*material*__ na branch `main`

> 💡️ **Dica**
>
> Fique a vontade para tratar as imagens da maneira como achar necessário, quanto mais leve melhor. Levaremos em consideração o peso final de sua aplicação.

As fonts utilizadas no layout são:
- **Space Mono**, disponível no google fonts
- **Scotch Display**, disponível nos materiais do repositório

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
  - Antes de postar seu formulário, verifique se o e-mail digitado já possui cadastro através da API, para isso utilize o e-mail `test@frontend.com` como e-mail fictício para simular a existencia e válidar o seu formulário.
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
