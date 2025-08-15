# Coffee Delivery Web

Aplicação web para pedidos de café online, oferecendo uma experiência prática e intuitiva para clientes realizarem compras, personalizarem pedidos e acompanharem a entrega em tempo real.

---

## Principais funcionalidades e casos de uso

- Catálogo de cafés com descrição, preço e imagens
- Adição de itens ao carrinho e personalização de pedidos
- Cadastro de endereço e informações de entrega
- Finalização de pedido e confirmação visual
- Controle do estado do carrinho durante a navegação
- Visualização do status da entrega (simulado ou integrado a API real)
- Interface responsiva para desktop e mobile

---

## Stack e tecnologias utilizadas

- **Frontend:** ReactJS
- **Linguagem:** TypeScript
- **Gerenciamento de rotas:** React Router
- **Estilização:** Styled-components ou CSS Modules
- **Gerenciamento de estado:** Context API ou Redux (conforme implementação)
- **HTTP Client:** Axios ou Fetch API (se houver integração externa)
- **Testes:** Jest, React Testing Library (se aplicável)
- **Outros:** dotenv para variáveis de ambiente

---

## Estrutura de pastas

```
coffee-delivery-web/
├── public/                # Arquivos estáticos (index.html, favicon, etc)
├── src/
│   ├── assets/            # Imagens, ícones e recursos visuais
│   ├── components/        # Componentes reutilizáveis (buttons, cards, etc)
│   ├── contexts/          # Contextos globais (carrinho, usuário, etc)
│   ├── hooks/             # Hooks personalizados
│   ├── pages/             # Páginas e rotas principais (Home, Checkout, Success)
│   ├── routes/            # Definição e configuração das rotas
│   ├── services/          # Serviços de API ou integração
│   ├── styles/            # Estilos globais e temas
│   ├── utils/             # Funções auxiliares
│   ├── App.tsx            # Componente principal da aplicação
│   └── main.tsx           # Ponto de entrada da aplicação React
├── .env.example           # Exemplo de variáveis de ambiente
├── package.json           # Dependências e scripts do projeto
└── README.md              # Documentação do projeto
```

### Explicação das principais partes

- **public/**: Arquivos públicos acessíveis pelo navegador.
- **src/assets/**: Imagens e ícones utilizados na interface.
- **src/components/**: Botões, cards, listas, e outros componentes reutilizáveis.
- **src/contexts/**: Controle de estados globais como carrinho de compras.
- **src/hooks/**: Hooks customizados para abstrair lógicas reutilizáveis.
- **src/pages/**: Páginas principais do aplicativo (catálogo, checkout, confirmação).
- **src/routes/**: Configuração das rotas da aplicação.
- **src/services/**: Comunicação com APIs externas ou lógica de integração.
- **src/styles/**: Estilos globais, temas e variáveis CSS.
- **src/utils/**: Helpers e funções utilitárias.

---

## Instalação e execução local

### Pré-requisitos

- Node.js (18.x+ recomendado)
- npm ou yarn

### Passo a passo

1. **Clone o repositório**
   ```bash
   git clone https://github.com/Cardosofiles/coffee-delivery-web.git
   cd coffee-delivery-web
   ```

2. **Configure as variáveis de ambiente**
   - Copie o arquivo `.env.example` para `.env` e ajuste conforme necessário (ex: endpoints de APIs).

3. **Instale as dependências**
   ```bash
   npm install
   # ou
   yarn
   ```

4. **Inicie o servidor de desenvolvimento**
   ```bash
   npm start
   # ou
   yarn start
   ```

5. **Acesse a aplicação**
   - Abra [http://localhost:3000](http://localhost:3000) no navegador.

---

## Como executar testes

```bash
npm test
# ou
yarn test
```

---

## Exemplos de uso das funcionalidades

- **Adicionar café ao carrinho:**  
  Selecione o café desejado na página inicial, escolha a quantidade e clique em “Adicionar ao carrinho”.

- **Finalizar pedido:**  
  No carrinho, preencha as informações de entrega e selecione o método de pagamento para confirmar a compra.

- **Acompanhar status:**  
  Após finalizar o pedido, visualize uma página de confirmação com o status da entrega.

---

## Boas práticas e recomendações

- Utilize variáveis de ambiente para URLs e chaves sensíveis.
- Prefira componentes reaproveitáveis e bem isolados.
- Mantenha o código organizado seguindo padrões de nomenclatura e estrutura.
- Escreva testes para componentes e funcionalidades críticas.
- Revise dependências periodicamente para evitar vulnerabilidades.
- Siga o fluxo de contribuição do repositório para pull requests e issues.

---

*Contribuições são bem-vindas! Em caso de dúvidas, abra uma issue ou envie um pull request.*

## 📫 Contato

<div align="center">

<a href="mailto:cardosofiles@outlook.com">
  <img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"/>
</a>
<a href="https://www.linkedin.com/in/joaobatista-dev/" target="_blank">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="https://github.com/Cardosofiles" target="_blank">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
</a>
<a href="https://cardosofiles.dev/" target="_blank">
  <img src="https://img.shields.io/badge/Portfólio-222222?style=for-the-badge&logo=about.me&logoColor=white" alt="Portfólio"/>
</a>

</div>
