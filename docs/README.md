# Desafio#3 - VTEX IO + AWS

Desenvolver uma réplica mais parecida possível do [UpMedal](https://www.upmedal.com/desafios) com a solução a partir do [boiler template padrão da Vtex IO](https://github.com/vtex-apps/minimum-boilerplate-theme);

## Objetivos:
 
- Utilizar o Markdown + o css para formatação - [Markdown](https://pt.wikipedia.org/wiki/Markdown);
- Flex Layout para criar as cores em css - [https://vtex.io/docs/components/all/vtex.flex-layout@0.17.0/](https://vtex.io/docs/components/all/vtex.flex-layout@0.17.0/)
- Priorizar as páginas criada nos arquivos.jsonc colocando comentários dos blocos criados
- Utilizar Slider layout para mostrar produtos em destaque - [https://vtex.io/docs/app/vtex.slider-layout](https://vtex.io/docs/app/vtex.slider-layout)
- Criar um componente Tab layout para separar produtos por categoria - [https://vtex.io/docs/components/all/vtex.tab-layout@0.4.3/](https://vtex.io/docs/components/all/vtex.tab-layout@0.4.3/)
- Criar um bloco de lista de produtos - [https://vtex.io/docs/app/vtex.product-list@0.31.0/](https://vtex.io/docs/app/vtex.product-list@0.31.0/)
- Criar Minicart para lista dos produtos no carrinho - [https://vtex.io/docs/components/content-blocks/vtex.minicart@2.60.0/](https://vtex.io/docs/components/content-blocks/vtex.minicart@2.60.0/)
- Ao clicar no produto ir para a tela com Product Summary - [https://vtex.io/docs/components/all/vtex.product-summary@2.53.0/](https://vtex.io/docs/components/all/vtex.product-summary@2.53.0/)
Layout mobile
- Criar um componente customizado para falar com suporte no whatsapp, no rodapé - Utilizar o Vtex Componentes com React para criar o componente - [https://vtex.io/docs/components/all/vtex.store-components@3.150.0/](https://vtex.io/docs/components/all/vtex.store-components@3.150.0/) - Créditos [Edney Moita](https://github.com/edneymoita/whatsapp-io)
- API whatsapp - [https://www.convertte.com.br/gerador-link-whatsapp/](https://www.convertte.com.br/gerador-link-whatsapp/)
- Criar um componente customizado para cadastrar leads (possíveis clientes prospectos)
    - Nome
    - Email
    - Telefone
     - Este componente pode servir de isca digital, fazendo dando uma bonificação para o prospecto que preencher as informações da lead.
## AWS API Gateway
- Com o objetivo de armazenar as leads que o Vtex componente irá utilizar no React, criar uma API Gateway na AWS para colocar as informações - [https://aws.amazon.com/pt/api-gateway/](https://aws.amazon.com/pt/api-gateway/)

Exemplos de arquivo API Gateway para estudo:
* https://github.com/awslabs/aws-api-gateway-developer-portal/blob/master/cloudformation/template.yaml
* https://github.com/mattpodolak/email-api-lambda
* https://github.com/amazon-archives/realworld-serverless-application/blob/master/backend/sam/app/api.template.yaml
