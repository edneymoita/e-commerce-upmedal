# Desafio Final VTEX Hiring Coders 2021
## Montar loja online, tendo como base a loja [UpMedal](https://www.upmedal.com/desafios), e utilizando o VTEX IO como plataforma de desenvolvimento
<br>
Desenvolvido como parte do treinamento VTEX - Hiring Coders 2021.
<br>
<br>
<img src='https://hiringcoders-app.gama.academy/images/logo-sm.png' alt="Hiring Coders" width="auto" height="50" />  <img src='https://vtex.com/wp-content/themes/VTEXTheme/v2/images/base/vtex.svg' alt="VTEX" width="auto" height="50">  <img src='https://assets.website-files.com/5ff79f3ebebf6b12f6b7747f/5ffe04fc6284b7e90070d985_logo-gama-academy-p-500.png' alt="Gama Academy" width="auto" height="50">

***
## Regras do desafio

Foi solicitado que fosse feita uma loja digital baseada no loja atual da empresa [UpMedal](https://www.upmedal.com/desafios), aproximando-se o máximo possível do original. Foi exigido que alguns componentes específicos do VTEX IO deveriam ser utilizados e personalizados para ficarem de acordo, tais como: tab-layout, product-summary, slider-layout, custom-query e minicart; e também fossem criados componentes customizados em React para integração com WhatsApp e nuvem AWS (captação de clientes para lista de distribuição). A aplicação resultante ficou disponível na nuvem da VTEX, na loja HIRINGCODERS2021 (com acesso restrito aos usuários do VTEX IO).

***
## Endereço da Loja

[UpMedal - Hiring Coders - Versão Edney Moita](https://edneymoita--hiringcoders2021.myvtex.com/) (acesso restrito)

***
## Desenvolvido em

<img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/>  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/>  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/>  <img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" alt="nodejs" width="40" height="40"/>  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/>  <img src="https://www.vectorlogo.zone/logos/graphql/graphql-icon.svg" alt="graphql" width="40" height="40"/>  <img src="https://upload.wikimedia.org/wikipedia/commons/9/93/Amazon_Web_Services_Logo.svg" alt="aws" width="40" height="40"/>

***

## Dependências

- [vtex.whatsappio@0.0.0](https://github.com/edneymoita/whatsapp-io) - Componente React responsável pela integração com a API do WhatsApp paa suporte de loja.
- [vtex.recordleads@0.0.0](https://github.com/edneymoita/recordleads) - Componente React responsável por apresentar uma tela de captação de dados dos clientes e armazená-los na nuvem da AWS, usando o GraphQL, Lambda e DynamoDB.

(para linkar corretamente a loja no VTEX IO em um workspace qualquer é preciso antes linkar os componentes acima, disponíveis nos repositórios informados.)

***

## Loja montada

Página inicial da loja, com produtos em destaque e listagem de produtos referentes ao menu destacado.
<br>
<br>
<img src='./assets/screenshots/tela1.png'/>
<br>
<br>
Carrinho de compras seguindo o padrão da loja
<br>
<br>
<img src='./assets/screenshots/tela2.png'/>
<br>
<br>
Página de produto, apresentando o produto escolhido e todos os detalhes.
<br>
<br>
<img src='./assets/screenshots/tela3.png'/>
<br>
<br>
Modal para captação de dados de clientes (componente React externo)
<br>
<br>
<img src='./assets/screenshots/tela4.png'/>
<br>
<br>

***

## Licença

[EM](https://github.com/edneymoita)
