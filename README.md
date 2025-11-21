# 🧰 Atron Suite

> **Otimize, Atualize e Gerencie.** A sua suíte definitiva de manutenção para Windows.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg) ![Platform](https://img.shields.io/badge/platform-Windows_10%2F11-0078D6.svg) ![License](https://img.shields.io/badge/license-Free_for_Personal_Use-green.svg)

## 📖 Sobre o Projeto

O **Atron Suite** é uma ferramenta centralizada, segura e eficiente desenvolvida para otimizar o sistema operacional Windows. O software unifica a limpeza de arquivos temporários, atualização de softwares e gerenciamento de drivers em uma interface amigável, utilizando o poder do repositório oficial do Windows (Winget).

Desenvolvido por **Queiroz**.

---

## ✨ Funcionalidades (Módulos)

O sistema é dividido em três ferramentas essenciais acessíveis via painel inicial:

### 🧹 1. Atron Cleaner (Limpeza de Sistema)
Focado em privacidade e liberação de espaço em disco, removendo acúmulos desnecessários do sistema.
* **Windows Temp:** Limpeza de arquivos temporários do SO e instaladores.
* **Prefetch:** Limpeza do cache de inicialização (útil para corrigir erros de boot).
* **User Temp:** Limpeza de temporários gerados por aplicativos do usuário (`AppData\Local\Temp` e `Prefetch`).
* **Smart Recycle:** Botão dedicado para esvaziar a lixeira de todas as unidades com um único clique.

### 🔄 2. Atron Apps (Atualizador de Softwares)
Gerencie as atualizações dos seus programas utilizando a base oficial do **Winget**.
* **Listagem Inteligente:** Clique em *Buscar Apps* para ver o que está desatualizado.
* **Filtro de Conteúdo:** O sistema filtra automaticamente drivers e componentes de sistema para focar em softwares de uso geral (Navegadores, Editores, Utilitários).
* **Ação em Lote:** Atualize um software específico ou utilize a função **Atualizar TODOS**.

### 🛠️ 3. Atron Drivers (Atualizador de Drivers)
Módulo especializado para manter o hardware performando ao máximo. Ideal para gamers e profissionais.
* **Busca Inteligente:** Diferente do módulo de Apps, este filtro busca especificamente por palavras-chave de hardware: `NVIDIA`, `Intel`, `AMD`, `Realtek`, `Audio`, `Bluetooth`, `LAN`, `Chipset`, etc.

---

## 💻 Requisitos do Sistema

Para garantir o funcionamento correto, seu ambiente deve atender aos seguintes requisitos:

* **Sistema Operacional:** Windows 10 (v. 1809 ou superior) ou Windows 11.
* **Permissões:** É **obrigatório** executar como **Administrador** (para acesso a pastas protegidas como `Windows\Temp`).
* **Framework:** .NET Framework 4.7.2 ou superior.
* **Dependência:** Winget (App Installer).
    * *Nota: Geralmente pré-instalado no Windows atualizado. Caso contrário, instale o "Instalador de Aplicativo" via Microsoft Store.*

---

## 🔧 Instalação e Uso

1. **Download:** Baixe o arquivo **[atronsuite.zip](./atronsuite.zip)** clicando aqui.
2. Extraia todo o conteúdo do arquivo `.zip` para uma pasta de sua preferência.
3. Clique com o botão direito no executável `setup.exe`.
4. Faça a instalação
5. Selecione **"Executar como Administrador"**.

---

## ❓ Solução de Problemas Comuns (Troubleshooting)

| Erro | Causa Provável | Solução |
| :--- | :--- | :--- |
| **"Acesso Negado" / 0 bytes limpos** | Falta de privilégios administrativos. | Feche o programa e abra-o novamente selecionando **"Executar como Administrador"**. |
| **Winget não encontra atualizações** | Gerenciador de pacotes desatualizado ou sem fontes. | Abra o PowerShell/CMD e digite: <br>`winget source update`<br>Aguarde e tente novamente. |
| **Download da atualização falha** | Instabilidade na internet ou no servidor do fornecedor. | Tente novamente mais tarde. O AtronSuite usa servidores oficiais (Microsoft, Google, Adobe, etc) e não armazena arquivos. |

---

## 📝 Licença e Créditos

**Versão:** 1.0.0
**Licença:** Gratuito para uso pessoal.

Copyright © 2025 **QRZ / Dev. Queiroz**.
Todos os direitos reservados.