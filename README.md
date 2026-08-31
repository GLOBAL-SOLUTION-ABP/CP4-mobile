# Next Chapter — Mobile App

Aplicativo mobile desenvolvido a partir do protótipo **Next Chapter**, uma proposta de marketplace para compra, venda e troca de bolsas de luxo seminovas com curadoria e autenticação.

O projeto transforma o layout criado no Figma em uma aplicação navegável feita com **React Native + Expo + TypeScript**.

## Protótipo

Figma: https://www.figma.com/design/Jf3aAVDyheWxwjL0LCGnbb/Next-Chapter-%E2%80%94-App-Prototype?m=auto&t=bRYpVbxWmI5JbfWA-1

## Objetivo

A Next Chapter busca prolongar o ciclo de vida de bolsas de luxo, permitindo que uma peça tenha um novo dono em vez de ficar sem uso. A aplicação reúne catálogo, autenticação, venda assistida, crédito de troca e um programa de exchange em uma única experiência mobile.

## Funcionalidades implementadas

- Tela inicial da marca;
- Catálogo de bolsas;
- Filtros de navegação;
- Cards de produtos autenticados;
- Tela de detalhe do produto;
- Fluxo de venda de uma bolsa;
- Seleção do estado de conservação;
- Estimativa simulada de valor;
- Área de Exchange & Trade-in;
- Exibição de crédito disponível;
- Lista de peças elegíveis para troca;
- Explicação do Exchange Program;
- Navegação entre as principais telas;
- Dados mockados para demonstração do protótipo.

## Telas

1. **Splash / Introdução**
2. **Home / Catálogo**
3. **Detalhe do produto**
4. **Vender minha bolsa**
5. **Exchange & Trade-in**
6. **Exchange Program**

## Tecnologias

- React Native
- Expo
- TypeScript
- Git / GitHub

## Estrutura do projeto

```text
next-chapter-mobile/
├── assets/
│   └── next-chapter-mark.png
├── docs/
│   └── prototype-overview.png
├── src/
│   ├── components/
│   │   ├── BottomNav.tsx
│   │   ├── Pill.tsx
│   │   └── ProductCard.tsx
│   ├── data/
│   │   └── products.ts
│   ├── screens/
│   │   ├── ExchangeProgramScreen.tsx
│   │   ├── HomeScreen.tsx
│   │   ├── ProductDetailScreen.tsx
│   │   ├── SellScreen.tsx
│   │   ├── SplashScreen.tsx
│   │   └── TradeInScreen.tsx
│   └── theme.ts
├── App.tsx
├── app.json
├── package.json
├── tsconfig.json
└── README.md
```

## Como executar

### 1. Pré-requisitos

Tenha instalado:

- Node.js 22.13 ou superior;
- npm;
- aplicativo Expo Go no celular, caso queira testar em um aparelho físico.

### 2. Instale as dependências

```bash
npm install
```

O projeto está configurado para **Expo SDK 57**, com React Native 0.86.3 e React 19.2.3. Se o Expo indicar incompatibilidade entre versões de pacotes, execute:

```bash
npx expo install --fix
```

### 3. Inicie o projeto

```bash
npm start
```

ou:

```bash
npx expo start
```

Depois disso, abra o projeto pelo Expo Go usando o QR Code exibido no terminal.

## Como publicar no GitHub

Crie um repositório vazio no GitHub e, dentro da pasta do projeto, execute:

```bash
git init
git add .
git commit -m "feat: versão inicial do Next Chapter"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/next-chapter-mobile.git
git push -u origin main
```

Substitua `SEU-USUARIO` pelo seu usuário do GitHub.

## Estado atual

Este repositório representa a **primeira versão funcional do front-end** baseada no protótipo do Figma. Os dados são simulados e não há, nesta versão, backend, autenticação real de usuários, pagamento ou integração com serviço de curadoria.

## Próximas evoluções

- Integrar autenticação;
- Criar backend e banco de dados;
- Permitir upload real de imagens;
- Adicionar favoritos;
- Criar carrinho e checkout;
- Persistir crédito do Trade-in;
- Integrar autenticação de peças;
- Criar testes automatizados.

## Uso

Projeto acadêmico desenvolvido para fins de prototipação e demonstração de uma aplicação mobile.

## Integrantes

- Luan Orlandelli - 554747
- Jorge Luiz - 554418
- Arthur Bobadilla - 555056
- Albert Katri - RM556544
- Bruno Biletsky - RM554739
- Paulo Akira - RM556840
