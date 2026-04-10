<div align="center">
  <picture>
    <img src="assets/FreelaverseBanner.png" alt="FreelaVerse Banner" width="100%">
  </picture>
</div>

<br>

<div align="center">
  <a href="https://github.com/pajeeh/FreelaVerse-Showcase">
    <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=800&size=55&pause=1000&color=4ADE80&center=true&vCenter=true&width=600&height=80&lines=FreelaVerse;root@freela:~%23+;System+Online." alt="Typing SVG" />
  </a>
</div>

<div align="center">
  <em>Um Sistema Operacional de bolso para o submundo cibernético.</em>
</div>
<br>

<div align="center">
  <img src="https://img.shields.io/badge/Engine-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter">
  <img src="https://img.shields.io/badge/Language-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" alt="Dart">
  <img src="https://img.shields.io/badge/Cloud-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase">
  <img src="https://img.shields.io/badge/Architecture-Provider-8A2BE2?style=for-the-badge&logo=codeforces&logoColor=white" alt="Provider">
  <img src="https://img.shields.io/badge/Status-Alpha_Build-FF0000?style=for-the-badge&logo=git&logoColor=white" alt="Status">
</div>

---

## 🌐 O Projeto

> *"No submundo digital, a sua máquina é o seu bunker. E o seu terminal, a sua arma."*

O **FreelaVerse** é um simulador de hacking multijogador focado em interface de linha de comandos (CLI). Construído para quem vive no terminal, o jogo funde a mecânica imersiva de exploração de redes (estilo *Hacknet* e *Uplink*) com uma economia passiva de Botnets, Mineração e montagem de Hardware.

A regra é estritamente técnica: faça o reconhecimento (`nmap`), encontre a vulnerabilidade, escale privilégios (`exploit`), roube os dados do contrato, apague os seus logs (`rm -rf`) e desconecte antes que o rastreio ativo atinja 100%.

---

## 📸 Interface Visual (OS UI)

*(Alpha Build Screenshots)*

<div align="center">
  <table>
    <tr>
      <td align="center"><b>Dashboard & Analytics</b><br><img src="assets/screenshots/Dashboard.png" width="400" alt="Dashboard Econômico"></td>
      <td align="center"><b>Topologia Mesh</b><br><img src="assets/screenshots/Mesh.png" width="400" alt="Topologia Mesh"></td>
    </tr>
    <tr>
      <td align="center"><b>Inventário & Setup Local</b><br><img src="assets/screenshots/Inventory.png" width="400" alt="Inventário"></td>
      <td align="center"><b>Dark Web Market</b><br><img src="assets/screenshots/marketplace.png" width="400" alt="Marketplace"></td>
    </tr>
    <tr>
      <td align="center"><b>Pesquisa & Filtros de Mercado</b><br><img src="assets/screenshots/filtroMarketplace.png" width="400" alt="Filtro Marketplace"></td>
      <td align="center"><b>Missões & Contratos</b><br><img src="assets/screenshots/MissoesAtivas.png" width="400" alt="Missões Ativas"></td>
    </tr>
    <tr>
      <td align="center" colspan="2"><b>Inbox & Comunicações Criptografadas</b><br><img src="assets/screenshots/mailService.png" width="800" alt="Mail Service"></td>
    </tr>
  </table>
</div>

---

## 💻 Features Letais

O FreelaVerse não é apenas um terminal falso; é um **Ecossistema Virtual Completo (OS)** rodando dentro do seu dispositivo.

| Módulo Core | Especificação Técnica |
| :--- | :--- |
| 📟 **Terminal Tático (CLI)** | Mais de 20 comandos mapeados via `CommandRegistry` (`ifconfig`, `net_map`, `wifi_tool`, `nano`). O tempo de execução de quebra de senhas reage em tempo real aos *specs* de RAM e CPU do seu hardware virtual. |
| 🕸️ **Topologia Mesh** | Não basta atacar. Você precisa pivotar. Use o `NetworkTreeBuilder` para visualizar nós de rede interconectados, pular entre proxies e invadir Servidores Corporativos camada por camada. |
| 🌐 **Navegador NetSurf (Deep Web)** | Uma internet simulada rodando in-game. Acesse o **FreelaSearch**, Fóruns Hackers, **Exchange de Criptomoedas**, Portais Bancários e a Wiki através de um motor de renderização nativo. |
| ⚙️ **Engenharia de Hardware** | A `MySetupView` suporta **Drag & Drop / Hot-Swap** de Placas-Mãe, CPU, GPU, RAM e Storage. O hardware substituído sofre depreciação matemática e volta para o seu inventário. |
| 🎨 **Arte Procedural** | Nada de imagens estáticas na Loja. O motor utiliza `procedural_hardware_art.dart` para desenhar PCBs e chips em tempo de execução, mudando as cores dependendo do clock e da capacidade da peça. |
| 📧 **Contratos & Corporações** | Um sistema de `Inbox` dinâmico. Receba propostas de facções Red Team, aceite contratos corporativos da *Genesis* e gerencie os seus projetos simultâneos. |
| 🤖 **Integração IA** | Motor PVE alimentado pelo `ia_service.dart`, gerando defesas adaptativas em servidores corporativos que tentam rastrear o jogador em tempo real. |

---

## 🏗️ Arquitetura e Engenharia (Sob o Capô)

<div align="center">
  <picture>
    <img src="assets/FreelaverseSchem.png" alt="Esquema de Arquitetura do FreelaVerse" width="80%">
  </picture>
</div>
<br>

O projeto foi desenhado para escalar até milhares de jogadores simultâneos, mantendo o custo de infraestrutura na nuvem próximo de zero.

* 🧠 **State Management (Mixins):** Padrão `Provider` fragmentado via *Mixins*. Separação rigorosa de domínios (Hardware, Rede, Economia, Status) para evitar super-objetos (*God Classes*).
* 🗺️ **Single Source of Truth (SSOT):** Navegação automatizada via `NavigationRegistry`. Interfaces complexas (Side Panels e IndexedStacks) são geradas em tempo de compilação.
* 💽 **Storage Híbrido (Zero-Lag):**
  * **Local-First:** O dispositivo do utilizador dita a verdade temporária para o Dashboard (Gráficos de Produtividade) e Inventário. Zero latência.
  * **Cloud (Firebase):** Autenticação segura e Backups atômicos assíncronos protegidos por padrões de *Debounce*.
* 🔒 **Segurança Anti-Cheat:** Implementação de *MutEx Locks* (Travas de Exclusão Mútua) nas rotinas de checkout do terminal para neutralizar exploits de *Double-Spending*.

---

## 🎮 Acesso Antecipado (Alpha Build)

O projeto é mantido sob desenvolvimento restrito (Closed-Source Core). 

Se você é um desenvolvedor, analista de segurança ou entusiasta de simuladores imersivos e quer testar os limites do nosso terminal, **junte-se à rede**.

> 📩 **Solicite a sua Chave de Acesso:** [Insira seu link de Discord / Twitter / Email aqui]

<br>
<div align="center">
  <em>Transmissão Criptografada. Cuidado com os Daemons.</em>
</div>
