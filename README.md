# **WhaTicket SaaS | Gold Edition**

Uma plataforma de atendimento robusta baseada no **Whaticket V6**, aprimorada com um módulo Kanban, modo noturno e integrações avançadas para otimizar a comunicação com seus clientes.

-----
![whatickt-saas-v6](https://github.com/natanael-jr-web/whaticket-saas-v6/blob/main/whaticket-saas-V6.png)

DEMO: (https://app-demo.whaticket.store)
CONTATO: 55 (73) 9 8135-5929  * [WhatsApp](https://wa.me5573981355929)

### **✨ Funcionalidades Principais**

  * **Gestão Visual:** Quadro **Kanban** integrado para organizar e priorizar tickets.
  * **Interface Agradável:** **Modo noturno** para conforto visual em ambientes com pouca luz.
  * **Automação e IA:**
      * DialogFlow
      * N8N
      * TypeBot
      * ChatGPT
  * **Conectividade:** Suporte a **WebHooks** para integrações personalizadas.

### **💻 Requisitos de Sistema**

01 - Servidor VPS Ubuntu 22.04
Para garantir a melhor performance, seu servidor deve atender às seguintes especificações mínimas:

  * **Sistema Operacional:** Ubuntu 22.04 LTS.
  * **Processador (vCores):** 4 ou mais.
  * **Memória RAM:** 8 GB ou mais.
  * **NodeJS:** **Versão 20** é obrigatória para a instalação.
  * **Latência de Rede:** Ideal entre 10ms e 150ms. Latências muito baixas (\<10ms) ou muito altas (\>200ms) podem causar instabilidades.

#### **🚀 Provedores VPS Recomendados**

Contabo vps: https://contabo.com/en/linux-vps/

Hertzen vps: https://www.hetzner.com/cloud/

02 - um(1) Endereço de dominío adicionado a Cloudflare

CloudFlare: https://www.cloudflare.com/pt-br/

-----

### **📚 Documentação e Suporte**

  * **Suporte Técnico:** O suporte técnico é um serviço exclusivo, vinculado à aquisição da Licença Comercial. Após a compra, entre em contato via WhatsApp para obter seu acesso.

#### **🛒 Adquira sua Licença Comercial e Acesso ao Suporte**

Para uso comercial, revenda ou exploração da plataforma como SaaS, é obrigatória a aquisição de uma licença.

Contato para instalação e suporte: 

* [WhatsApp](https://wa.me/5573981355929)

-----

**🔄 Ver Histórico de Versões (Changelog)**

#### **Versão 6.3.5** (`11/11/2025`)

  * Mercado Pago
  * Gemini

#### **Versão 6.3.2** (`28/09/2025`)

  * Correção de criptografia de grupos
  * Correções lib/wbot.ts

#### **Versão 6.3.1** (`20/09/2025`)

  * Correção de bugs relacionados a JID/LID.
  * Melhorias de Performance

#### **Versão 6.0.0** (`16/04/2025`)

  * **Interface:**
      * Aprimoramentos no Dark Mode (mensagens).
      * Botão `Light/Dark` movido para o perfil do usuário.
      * Dashboard: alteração nos estilos dos cards (botão de impressão removido).
      * Estilo de ticket alterado.
      * Layouts reformulados para: Respostas Rápidas, Página de Conexão, Tela de Login e Tela de Signup.
      * Adicionada opção de `SuperAdmin`.
  * **Funcionalidades:**
      * Botão de tradução adicionado.
      * Aviso exibido quando o ticket de um contato está aberto.
  * **Correções:**
      * Correção no envio de menu de filas (na 3ª tentativa, o ticket é enviado para a 1ª fila).
      * Agendamento agora envia imagem com texto e suporta ciclos.
      * Correção de vazamento no WebSocket.

#### **Versão 5.5.0** (`13/12/2024`)

  * **Interface:**
      * Dashboard, Kanban e página de relatórios reformulados.
      * Validação de número em `ContactModal`.
  * **Funcionalidades:**
      * Recusa automática de chamadas.
      * Filas da conexão ao requisitar novo QR Code.
      * Áudio no iPhone.
      * Regressão OpenAI.
  * **Correções:**
      * Correção ao redimensionar a área de tickets.

#### **Versão 5.3.5** (`07/11/2024`)

  * **Funcionalidades:**
      * Automações não são mais enviadas para grupos.
      * Botão `disableBot` para desativar bots ou automações.
      * Permissão para conexões com o mesmo nome.
      * Opção de selecionar e deletar contatos na página de Contatos.
      * Atualização automática do valor na lista do Financeiro após alteração de plano.
  * **Correções:**
      * Correção da data de vencimento no topo (agora fixa).
      * Correção na mensagem citada.
      * Correção no envio de áudio OGG em respostas rápidas.
      * Expiração automática de conexões ao vencer a empresa.
  * **Alterações:**
      * Abas de visualização de tickets fechados e grupos por operador removidas do painel de usuários.

#### **Versão 5.2.6** (`24/07/2024`)

  * Fechamento de todos os tickets abertos ou em espera.
  * Capacidade de reagir a mensagens e encaminhá-las para outro ticket.
  * Notificação no chat quando uma mensagem é apagada no WhatsApp.
  * Aparência do menu aprimorada, com adição do botão `Sair`.
  * Indicação "Digitando" ou "Gravando" no canto inferior direito do ticket.
  * API atualizada.
  * Novo layout da página de login.
