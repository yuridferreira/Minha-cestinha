# Minha Cestinha 🛒

Um aplicativo mobile para gerenciar lista de compras de forma simples e intuitiva.

## 📱 Sobre o Projeto

**Minha Cestinha** é um aplicativo desenvolvido com React Native e Expo que permite aos usuários:
- Criar e gerenciar listas de compras
- Adicionar e remover itens
- Marcar itens como comprados
- Sincronizar dados localmente
- Acessar de múltiplas plataformas

## 🚀 Tecnologias Utilizadas

- **React Native** - Framework para desenvolvimento multiplataforma
- **Expo** - Plataforma para desenvolvimento e distribuição de apps React Native
- **TypeScript** - Tipagem estática para maior confiabilidade
- **AsyncStorage** - Armazenamento persistente de dados
- **React 19** - Versão mais recente do React

## 📋 Pré-requisitos

Antes de começar, verifique se você tem instalado:

- **Node.js** (v16 ou superior)
- **npm** ou **yarn**
- **Expo CLI**: `npm install -g expo-cli`
- Para iOS: **Xcode** e **CocoaPods**
- Para Android: **Android Studio** e **JDK**

## 🔧 Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/yuridferreira/Minha-cestinha.git
   cd Minha-cestinha
   ```

2. **Instale as dependências**
   ```bash
   npm install
   ```

3. **Inicie o servidor de desenvolvimento**
   ```bash
   npm start
   ```

## 💻 Scripts Disponíveis

- `npm start` - Inicia o servidor de desenvolvimento do Expo
- `npm run android` - Executa o app no Android
- `npm run ios` - Executa o app no iOS
- `npm run web` - Executa o app na web

## 📁 Estrutura do Projeto

```
Minha-cestinha/
├── src/
│   ├── app/
│   │   └── Home.tsx
│   └── ...
├── assets/
│   ├── icon.png
│   ├── splash-icon.png
│   ├── adaptive-icon.png
│   └── favicon.png
├── App.tsx
├── index.ts
├── app.json
├── package.json
├── tsconfig.json
├── metro.config.js
└── README.md
```

## 🎯 Como Usar

1. **Abra o aplicativo**
2. **Crie uma nova lista de compras**
3. **Adicione itens** à sua lista
4. **Marque itens** conforme os compra
5. **Remova itens** quando necessário

Os dados são salvos automaticamente no dispositivo usando AsyncStorage.

## 🌐 Plataformas Suportadas

- ✅ **Android** - Aplicativo nativo
- ✅ **iOS** - Aplicativo nativo  
- ✅ **Web** - Versão web responsiva

## 📝 Dependências Principais

| Pacote | Versão | Descrição |
|--------|--------|-----------|
| react | ^19.1.0 | Biblioteca React |
| react-native | ^0.81.5 | Framework React Native |
| expo | ~54.0.26 | Plataforma Expo |
| @react-native-async-storage/async-storage | ^2.2.0 | Armazenamento persistente |
| memoize-one | ^6.0.0 | Otimização de performance |

## 🔐 Licença

Este projeto é privado.

## 👤 Autor

**Yuri Demétrio Ferreira**
- GitHub: [@yuridferreira](https://github.com/yuridferreira)

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para abrir issues ou pull requests.

## 📞 Suporte

Se encontrar algum problema, abra uma issue no repositório.

---

Desenvolvido com ❤️ usando React Native e Expo