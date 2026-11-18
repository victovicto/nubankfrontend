# 💜 Nubank MAV

Protótipo mobile inspirado no aplicativo do Nubank, desenvolvido com **React Native + Expo + TypeScript** para fins de estudo na disciplina de Dispositivos Móveis.

> ⚠️ Projeto acadêmico, sem fins comerciais e sem qualquer vínculo com o Nubank. Todos os dados exibidos são fictícios.

## ✨ Telas e funcionalidades

| Tela | Descrição |
|------|-----------|
| **Início** (`Tela1`) | Saudação, saldo da conta com opção de mostrar/ocultar, atalhos (Pix, Pagar, Transferir, Recarga, Investir), cartão de crédito com fatura e limite, e seção "Meus cartões" |
| **Finanças** (`Tela2`) | "Acompanhe seu dinheiro": Caixinha, Investimentos, Cripto e opções de Seguros (vida e celular) |
| **Descontos** (`Tela3`) | Ofertas de parceiros (Nike, Netflix, Amazon), categorias (Alimentação, Esportes, Games, Música, Transporte, Moda) e cashback especial |
| **Me Ajuda** (`Tela4`) | Campo de busca, avaliação do atendimento e categorias de ajuda (Conta e Cartão, Pix e Transferências, Investimentos, Seguros) |

Também há um **menu inferior** para alternar entre Início, Finanças e Descontos. A tela de ajuda é aberta pelo ícone no cabeçalho e tem botão de voltar.

## 🛠️ Tecnologias

- [React Native](https://reactnative.dev/) 0.79 e [React](https://react.dev/) 19
- [Expo](https://expo.dev/) SDK 53
- [TypeScript](https://www.typescriptlang.org/)
- [React Navigation](https://reactnavigation.org/) (Native Stack)
- [Expo Vector Icons](https://icons.expo.fyi/) (Ionicons)
- React Native Reanimated, Gesture Handler, Screens e Safe Area Context

## 🚀 Como executar

**Pré-requisitos:** [Node.js](https://nodejs.org/) (LTS) e o app **Expo Go** no celular (opcional).

```bash
# Clone o repositório
git clone https://github.com/victovicto/nubankfrontend.git

# Acesse a pasta
cd nubankfrontend

# Instale as dependências
npm install

# Inicie o projeto
npm start
```

Depois de iniciar, escolha como visualizar:

- **Celular:** escaneie o QR Code com o Expo Go
- **Android:** `npm run android` (emulador ou dispositivo)
- **iOS:** `npm run ios` (somente no macOS)
- **Web:** `npm run web`

## 📁 Estrutura do projeto

```
nubankfrontend/
├── assets/          # Ícones e splash screen
├── screens/
│   ├── Tela1.tsx    # Início
│   ├── Tela2.tsx    # Finanças
│   ├── Tela3.tsx    # Descontos
│   └── Tela4.tsx    # Me Ajuda
├── App.tsx          # Navegação e menu inferior
├── app.json         # Configurações do Expo
└── index.ts         # Ponto de entrada
```

## 👤 Autor

Feito por [victovicto](https://github.com/victovicto)
