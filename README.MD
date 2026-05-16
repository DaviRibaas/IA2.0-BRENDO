# 🧛 DevCard - Gerador de Cartão de Visitas Digital

O DevCard é uma aplicação mobile desenvolvida em React Native (Expo) que permite a desenvolvedores criarem um cartão de visitas personalizado em tempo real. O projeto foca em uma interface limpa (UI), experiência do usuário fluida (UX) e lógica de negócios para classificação de níveis profissionais.

## 🚀 Funcionalidades

* **Cadastro Dinâmico:** Formulário com validação de campos obrigatórios e feedback de erro.
* **Classificação Automática:** O app define se o desenvolvedor é Júnior, Pleno ou Sênior com base nos anos de experiência informados.
* **Personalização de Cores:** Escolha de temas (Azul, Verde, Roxo) que alteram visualmente o cartão final.
* **Preview em Tempo Real:** Visualização do cartão no estilo "Badge de Conferência" antes da finalização.
* **Design Moderno:** Interface limpa, focada em componentes nativos de alta qualidade.
* **Navegação Fluida:** Sistema de rotas utilizando `expo-router`.

## 📸 Screenshots

Aqui estão as principais telas da aplicação:

![Tela Home](./assets/home.png)
![Tela Cadastro](./assets/cadastro.png)
![Tela Sucesso](./assets/sucesso.png)

## 🛠️ Tecnologias Utilizadas

* React Native
* Expo (SDK 50+)
* TypeScript
* Expo Router (File-based routing)
* StyleSheet (CSS-in-JS para estilização nativa)

## 🏗️ Estrutura do Projeto

* `src/app/index.tsx`: Tela de boas-vindas.
* `src/app/cadastro.tsx`: Formulário de entrada de dados.
* `src/app/preview.tsx`: Tela de visualização do cartão gerado.
* `src/app/sucesso.tsx`: Confirmação final com feedback visual.
* `src/app/_layout.tsx`: Configuração global de navegação e cabeçalhos.

## 📥 Como rodar o projeto

1. Clone o repositório:

```bash
git clone https://github.com/DaviRibaas/IA2.0-BRENDO
```

2. Instale as dependências:

```bash
npm install
```

3. Inicie o Expo:

```bash
npx expo start
```

4. Abra no seu dispositivo: Escaneie o QR Code com o app Expo Go.

---

Desenvolvido por Davi Ribas - Instrumento Avaliativo 2 de Aplicações Móveis.