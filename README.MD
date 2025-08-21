# Chat de Suporte Meu Pabx Cloud

Uma aplicação web completa em JavaScript puro (HTML/CSS/ES6+) para automação de atendimento técnico do sistema Meu Pabx Cloud.

## Desenvolvedor

* **Nome:** Carlos Alberto
* **Contato (Telefone/WhatsApp):** +55 11 2615-2880

## Motivação

O projeto "Chat de Suporte Meu Pabx Cloud" foi criado para otimizar e automatizar o atendimento técnico, oferecendo aos usuários uma forma rápida e interativa de solucionar dúvidas comuns. A ferramenta serve como uma primeira linha de suporte, guiando o usuário através de fluxos de conversa pré-definidos para resolver problemas de configuração, uso de funcionalidades e integração, disponível 24/7 e de forma totalmente visual.

## Descrição

O Chat de Suporte é uma aplicação web visual e interativa, construída com tecnologias web puras (HTML5, CSS3 e JavaScript Vanilla), que opera diretamente no navegador. Ele simula um assistente virtual inteligente, guiando os usuários por meio de um sistema de conversação baseado em menus e opções. O grande diferencial é o painel de configuração que permite que todo o fluxo do chat seja carregado e gerenciado dinamicamente através de um arquivo JSON, facilitando a manutenção e a expansão dos diálogos.

## Funcionalidades Principais

* **Interface Intuitiva:** Design limpo, moderno e responsivo, garantindo uma ótima experiência em desktops e dispositivos móveis.
* **Configuração via JSON:** Todo o fluxo de conversa, incluindo mensagens, opções e navegação, é controlado por um arquivo JSON externo. Isso permite alterar o comportamento do chat sem modificar o código-fonte.
* **Simulação de Digitação:** Um indicador de "digitando..." em tempo real torna a interação mais humana e natural.
* **Histórico de Conversa:** As mensagens trocadas entre o usuário e o assistente são exibidas de forma clara, simulando um aplicativo de chat real.
* **Painel de Configuração:** Uma área dedicada permite carregar o JSON do fluxo, visualizar configurações de exemplo e obter instruções de uso.
* **Fluxos de Suporte Abrangentes:** O chat já vem com diversos fluxos pré-configurados para o Meu Pabx Cloud, cobrindo tópicos como:
    * Configuração de conta e login.
    * Gerenciamento de chamadas (transferência, espera, estacionamento).
    * Configuração de Caller ID.
    * Integração com SMS e WhatsApp.
    * Configurações de Softphone e Proxy.

## Tecnologias Utilizadas

* **Frontend:**
    * **HTML5:** Estrutura semântica e moderna.
    * **CSS3:** Estilização com variáveis para fácil customização.
    * **JavaScript Vanilla (ES6+):** Toda a lógica da aplicação, manipulação do DOM e interatividade foram construídas sem frameworks.
* **Fontes e Ícones:**
    * **Google Fonts (Segoe UI):** Para uma tipografia limpa e legível.
    * **Font Awesome:** Para os ícones utilizados na interface.

## Como Usar

O projeto não requer um servidor ou processo de build, podendo ser executado diretamente no navegador.

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/ca4ti/manualdesuporte.git](https://github.com/ca4ti/manualdesuporte.git)
    ```

2.  **Navegue até a pasta do projeto:**
    ```bash
    cd manualdesuporte
    ```

3.  **Abra o arquivo principal no navegador:**
    * Abra o arquivo `index.html` diretamente em seu navegador de preferência (Chrome, Firefox, etc.).

## Roadmap

O projeto está em constante evolução. Os planos futuros incluem:

* **Integração com API Real:** Desenvolver um backend para conectar o chat a uma base de dados real, permitindo salvar históricos e buscar informações dinâmicas.
* **Sistema de Tickets:** Integrar uma funcionalidade que permita ao usuário abrir um ticket de suporte diretamente pelo chat caso seu problema não seja resolvido.
* **Base de Conhecimento Pesquisável:** Implementar uma função de busca para que o usuário possa digitar sua dúvida e receber links ou fluxos relevantes como resposta.
* **Persistência de Dados:** Utilizar Local Storage ou um banco de dados para salvar o histórico de conversas entre sessões.

## Contribuição

1.  Faça um fork do projeto.
2.  Crie sua branch (`git checkout -b feature/nova-funcionalidade`).
3.  Commit suas mudanças (`git commit -m 'Adiciona nova funcionalidade'`).
4.  Push para a branch (`git push origin feature/nova-funcionalidade`).
5.  Abra um Pull Request.

## Licença

Distribuído sob licença MIT. Veja `LICENSE` para mais informações.

## Contato

Carlos Alberto - **[Telefone/WhatsApp]** +55 11 2615-2880

**Código-fonte:** [https://github.com/ca4ti/manualdesuporte](https://github.com/ca4ti/manualdesuporte)
