# 🏠 MatchRooms - Versão Beta (Estrutura HTML & Fluxos de Navegação)

> Mapeamento estrutural, wireframing semântico em HTML5 e prototipagem dos fluxos de uso da plataforma MatchRooms.

---

## 📌 Sobre esta Versão (Beta / Estrutural)

Este repositório/pasta contém a **Versão Beta** do **MatchRooms**, construída exclusivamente em **HTML5 puro** para focar na estruturação semântica das páginas e na modelagem dos **casos de uso reais** da plataforma.

Diferente da versão final estilizada e interativa, esta etapa do projeto tem como objetivo **mapear a jornada do usuário de ponta a ponta**, dividindo a experiência em telas específicas para validar a arquitetura da informação, a hierarquia dos conteúdos e a navegação entre feed, resultados de busca, variações da área de favoritos e fluxos completos de chat entre usuários.

---

## 🗺️ Mapeamento de Telas e Casos de Uso

A estrutura de arquivos foi dividida para simular cenários reais de navegação e interações específicas do sistema:

### 1. 🏠 Navegação Principal & Resultados
* **`index.html`:** Página inicial da estrutura Beta e ponto de entrada da navegação.
* **`Tela_resultados.html`:** Estrutura de exibição dos cards de quartos e perfis compatíveis encontrados no feed.
* **`Tela_perfil.html`:** Visualização e estrutura de dados do perfil do usuário, preferências de moradia e informações pessoais.

### 2. ⭐ Fluxo de Favoritos (Variações de Estado)
* **`favoritos_1.html`**, **`favoritos_2.html`** e **`Favoritos_3.html`:** Mapeamento de diferentes estados e etapas da lista de favoritos do usuário (ex.: visualização inicial, lista populada e gestão de itens salvos).

### 3. 💬 Fluxo de Comunicação e Chat (Simulação de Match)
* **`Tela_mensagens.html`:** Central geral de conversas e lista de chats ativos do usuário.
* **`Tela_chat.html`:** Estrutura base da interface de troca de mensagens.
* **`Tela_chat_Roger.html`** e **`Tela_chat_Roger_LIg.html`:** Casos de uso práticos simulando a interação real e visualização do chat com um usuário específico ("Roger"), testando o layout com conversas ativas e ligadas ao perfil do anfitrião.

### 4. 🧪 Casos de Uso Complementares
* **`caso1_1.html`** e **`caso1_2.html`:** Prototipagem de fluxos alternativos de teste para validar a progressão de telas na jornada principal do usuário.

---

## 🛠️ Tecnologia Aplicada

| Tecnologia | Foco nesta Versão |
| :--- | :--- |
| **HTML5** | Estruturação semântica, arquitetura de informação, hiperlinks de navegação e prototipagem dos múltiplos cenários de uso. |

---

## 📂 Estrutura de Arquivos

```text
MatchRooms-EstruturaBeta/
├── css/                       # (Diretório reservado para futura estilização)
├── img/                       # Assets e imagens de teste
├── js/                        # (Diretório reservado para futura interatividade)
├── index.html                 # Página inicial / Entrada
├── Tela_resultados.html       # Feed e resultados de compatibilidade
├── Tela_perfil.html           # Estrutura do perfil do usuário
├── favoritos_1.html           # Favoritos (Estado 1)
├── favoritos_2.html           # Favoritos (Estado 2)
├── Favoritos_3.html           # Favoritos (Estado 3)
├── Tela_mensagens.html        # Central de conversas
├── Tela_chat.html             # Base do chat
├── Tela_chat_Roger.html       # Simulação de chat (Usuário Roger)
├── Tela_chat_Roger_LIg.html   # Simulação de chat ativa (Usuário Roger)
├── caso1_1.html               # Caso de teste de fluxo 1.1
├── caso1_2.html               # Caso de teste de fluxo 1.2
└── ReadMe.md                  # Documentação da estrutura Beta
