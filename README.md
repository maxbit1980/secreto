<div align="center">

# 🔐 SECRETO

### Gerenciador Seguro de Senhas · 100% Offline

**Guarde, organize e consulte suas senhas com privacidade total.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/pt-BR/docs/Web/JavaScript)
[![License](https://img.shields.io/badge/Licen%C3%A7a-MIT-3fb950?style=for-the-badge)](#-licen%C3%A7a)
[![Sem Servidor](https://img.shields.io/badge/Servidor-Nenhum-ff2d55?style=for-the-badge)](#-privacidade)

[🌐 Acessar Web](#-vers%C3%A3o-web) · [📱 Baixar APK](#-vers%C3%A3o-android-apk) · [💚 Apoiar o Projeto](#-apoie-o-projeto)

</div>

---

## 🎯 Sobre o projeto

**SECRETO** é um **gerenciador de senhas pessoal** que funciona **100% offline**, direto no seu celular ou navegador. Ele permite guardar, organizar e consultar todas as suas senhas de forma segura e privada, **sem depender de nenhum servidor externo ou serviço na nuvem**.

Todo o armazenamento é feito **localmente no dispositivo** (via `localStorage`), o que significa que **nenhum dado sai do seu aparelho** — nem para o desenvolvedor, nem para terceiros.

> 🔒 **Privacidade por design.** Sem backend, sem rastreamento, sem coleta de dados. Suas senhas são só suas.

---

## 🚀 Acesso rápido

### 🌐 Versão Web

Acesse direto pelo navegador, sem instalar nada:

<p align="center">
  <a href="https://maxbit1980.github.io/secreto/" target="_blank" rel="noopener noreferrer">
    <img src="https://img.shields.io/badge/🌐_ABRIR_NO_NAVEGADOR-1e90ff?style=for-the-badge&logoColor=white" alt="Abrir no navegador">
  </a>
</p>

> 💡 **Abre em nova aba.** Funciona em qualquer dispositivo: celular, tablet ou desktop.

---

### 📱 Versão Android (APK)

Baixe o arquivo `.apk` e instale no seu celular:

<p align="center">
  <a href="https://github.com/maxbit1980/secreto/releases/download/v1.0.0/secreto.apk">
    <img src="https://img.shields.io/badge/📱_BAIXAR_APK_v1.0.0-ff2d55?style=for-the-badge&logo=android&logoColor=white" alt="Baixar APK">
  </a>
</p>

> ⚠️ **Instalação:** ao abrir o APK, o Android pode exibir um aviso de "fonte desconhecida". Isso é normal para apps distribuídos fora da Play Store. Basta habilitar a permissão de instalação no seu aparelho.

---

**Links diretos (para copiar/colar):**

- 🌐 **Web:** `https://maxbit1980.github.io/secreto/`
- 📱 **APK:** `https://github.com/maxbit1980/secreto/releases/download/v1.0.0/secreto.apk`

---

## ✨ Funcionalidades

### 🔐 Dupla proteção por senha mestra

| Camada | Função |
|---|---|
| **Login de acesso** | Nome de usuário + senha mestra para entrar no app |
| **Confirmação de ações sensíveis** | Toda exclusão exige a senha mestra novamente |

Mesmo que alguém pegue o celular desbloqueado, **não conseguirá ver nem apagar suas senhas** sem saber a senha mestra.

### 🔑 Cadastro e login
- Primeira vez: você define **nome de usuário** e **senha mestra**
- Próximos acessos: basta digitar as credenciais corretas
- Sessão criptografada localmente — **nada trafega pela internet**

### 💾 Armazenamento de senhas
Cada senha é salva com três campos:

| Campo | Exemplo |
|---|---|
| 🌐 **Site/Serviço** | `github.com` |
| 👤 **Usuário** | `meuemail@gmail.com` |
| 🔒 **Senha** | `Xy7#kL9$mN2p` |

### 🎲 Gerador de senhas fortes
Um clique em **🎲 GERAR** cria automaticamente uma senha de **14 caracteres** com:
- Letras maiúsculas e minúsculas
- Números
- Símbolos especiais (`!@#$%^&*`)

### 🔍 Busca instantânea
Filtro em tempo real por **nome do site** ou **nome de usuário**.

### 👁️ Visualização sob demanda
Senhas ficam ocultas por padrão. Clique em **🔓 VER SENHA** para revelar temporariamente — evita olhares por cima do ombro.

### 🗑️ Exclusão protegida
Exclusão exige a **senha mestra** antes de remover qualquer item.

### ⚙️ Alteração de credenciais
Troque nome de usuário e senha mestra nas Configurações — sempre confirmando com a senha atual.

---

## 🎨 Design

- **Tema visual "cyber/hacker"** — fundo Matrix, cores neon verde e rosa, efeito glitch no título
- **Formato vertical** — otimizado para celular (parece um app nativo)
- **Animações suaves** — transições entre telas, brilho pulsante, feedback nos botões
- **Ícones e emojis** — interface amigável e intuitiva
- **100% responsivo** — celular, tablet e desktop

---

## 🔒 Privacidade e segurança

| Aspecto | Status |
|---|---|
| Dados enviados para servidores | ❌ **Nunca** |
| Rastreamento de uso | ❌ **Nenhum** |
| Conexão com internet | ❌ **Não precisa** |
| Armazenamento | ✅ Apenas no `localStorage` do dispositivo |
| Backend / banco de dados | ❌ **Não existe** |
| Coleta de informações | ❌ **Zero** |

> ⚠️ **Importante:** como os dados ficam apenas no dispositivo, se você limpar o cache ou desinstalar o app, **as senhas serão perdidas**. Não há backup automático na nuvem — por design, para máxima privacidade.

---

## 🛠️ Tecnologias

| Camada | Tecnologia |
|---|---|
| **Front-end** | HTML5 + CSS3 (com `backdrop-filter`, animações e gradientes) |
| **Lógica** | JavaScript puro (vanilla) — sem frameworks |
| **Persistência** | `localStorage` |
| **PIX** | Payload EMV® com cálculo CRC16-CCITT em JS puro |
| **Clipboard** | Clipboard API com fallback para `execCommand` |

**Zero dependências externas.** Nenhum `npm install`, nenhum CDN, nenhum framework.

---

## 🚀 Casos de uso

- ✅ Guardar senhas de sites e apps pessoais
- ✅ Manter logins de bancos, e-mails e redes sociais organizados
- ✅ Gerar senhas fortes para novos cadastros
- ✅ Ter um backup mental organizado sem depender de gerenciadores por assinatura
- ✅ Estudar como funciona um app de segurança com HTML+JS puro

---

## 📦 Como rodar localmente

### Versão Web

```bash
git clone https://github.com/maxbit1980/secreto.git
cd secreto
# abra index.html no navegador
# ou rode um servidor local:
python3 -m http.server 8000
# acesse http://localhost:8000
```

### Versão Android

```bash
# instale o APK direto no dispositivo
adb install secreto.apk
```

---

## 💚 Apoie o projeto

Este app é **gratuito, sem anúncios e sem coleta de dados**. Se ele foi útil pra você, considere apoiar com uma doação simbólica via PIX — qualquer valor **a partir de R$ 1,00** ajuda a manter o projeto vivo.

**Chave PIX (aleatória):**

```
bf60e9ea-dbd3-43f1-8a64-7dbdb5191a71
```

O próprio app gera o **código PIX copia-e-cola** com valor livre (R$ 1, R$ 2, R$ 3, R$ 5, R$ 10 ou R$ 20) e CRC16 válido.

---

## 🤝 Contribuindo

Sugestões, relatos de bug e pull requests são bem-vindos!

1. Faça um **fork** do projeto
2. Crie uma branch: `git checkout -b feature/minha-melhoria`
3. Commit suas mudanças: `git commit -m "Adiciona X"`
4. Push: `git push origin feature/minha-melhoria`
5. Abra um **Pull Request**

---

## 📄 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

## 👨‍💻 Autor

**Paulo César**

[![GitHub](https://img.shields.io/badge/GitHub-maxbit1980-181717?style=for-the-badge&logo=github)](https://github.com/maxbit1980)
[![Email](https://img.shields.io/badge/Email-maxbit1980@gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:maxbit1980@gmail.com)

---

<div align="center">

**Feito com 💚 e JavaScript puro**

⭐ Se este projeto foi útil, considere dar uma **estrela** no repositório!

</div>
