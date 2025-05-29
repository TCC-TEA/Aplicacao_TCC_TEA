# Repository dedicated to the project "TCC TEA"

Repositório dedicado a guardar o aplicativo e a documentação que diz respeito ao TCC de Gabriel Marques e Caio Mesquita, Orientados por Ricardo Ajax

## Links importantes: 

### Trello
* https://trello.com/invite/b/67e5d7403e5d2690b94a5875/ATTI4e42dc80fcf83add015a08a60cfffab02988E22F/gestao-do-projeto-tcc-tea

### Parsifal
* https://parsif.al/CaioMesVie/seletividade-alimentar-no-contexto-de-pacientes-com-tea/

### Drive
* https://drive.google.com/drive/folders/1DiFjCPV2-e9z48qcQ2-ZeCcL2AafNs_9?usp=sharing_eip&ts=6764b679
  

## Adentrando no projeto

### ✅ Requisitos

Antes de executar este projeto, certifique-se de ter os seguintes itens instalados:

- [Node.js (versão LTS)](https://nodejs.org/)
- [Git](https://git-scm.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/) (`npm install -g expo-cli`)
- Um emulador Android/iOS **ou** o app **Expo Go** instalado no seu smartphone:
  - [Expo Go - Android](https://play.google.com/store/apps/details?id=host.exp.exponent)
  - [Expo Go - iOS](https://apps.apple.com/app/expo-go/id982107779)

---

### 📦 Instalação do Projeto

Clone o repositório e instale as dependências:

```bash
git clone https://github.com/seu-usuario/nome-do-repositorio.git
cd nome-do-repositorio
npm install
# ou
yarn install
```

---

### 🚀 Como Rodar o Projeto

Você pode rodar o projeto de duas formas:

#### 🔁 1. Modo Local (Rede Local)

Ideal para testar rapidamente em dispositivos conectados à **mesma rede Wi-Fi**.

```bash
npx expo start
```

Esse comando abrirá o **Expo DevTools** no navegador. Com ele, você pode:

- Escanear o QR Code com o aplicativo **Expo Go**
- Abrir o app em um emulador Android/iOS (caso configurado)

📌 **Observação:** Outros dispositivos precisam estar na **mesma rede local** que seu computador para acessar o app.

---

#### 🌐 2. Modo Online (Acesso Externo via Expo)

Permite que qualquer pessoa com internet acesse seu app via link.

Execute o seguinte comando:

```bash
npx expo start --tunnel
```

Isso gera um link público (via túnel) que pode ser aberto de qualquer lugar com o **Expo Go**.

✅ Ideal para testes remotos e compartilhamento com outras pessoas.

---

## 🧹 Dicas Úteis

- Para **limpar o cache** e evitar bugs inesperados:

  ```bash
  npx expo start --clear
  ```

- Caso esteja com problemas de rede, tente usar:

  ```bash
  npx expo start --lan
  # ou
  npx expo start --localhost
  ```

---


