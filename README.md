# 📱 DevTITANS 10 - Hands-On AOSP - 1 - Equipe 05

![Android](https://img.shields.io/badge/Android-14.0.0__r27-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![AOSP](https://img.shields.io/badge/AOSP-Open%20Source-4285F4?style=for-the-badge&logo=android&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-Ubuntu-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Hardware](https://img.shields.io/badge/Hardware-Required-FF6F00?style=for-the-badge&logo=raspberry-pi&logoColor=white)

## 📖 Introdução

Este repositório contém um trabalho prático sobre a alteração da tela de desbloqueio por padrão (**pattern lockscreen**) no **Android Open Source Project (AOSP)**.  

Aqui você encontrará os patches necessários para modificar o comportamento padrão da tela de desbloqueio do Android.

---

## 🗂️ Tabela de Conteúdos

1. [Contribuidores](#-contribuidores)
2. [Recursos](#-recursos)
3. [Requisitos](#-requisitos)
4. [Configuração de Hardware](#-configuração-de-hardware)
5. [Uso](#-uso)
6. [Contato](#-contato)

---

## 👥 Contribuidores

<p align="center">
  <img src="https://github.com/DevTITANS05/Hands-On-Linux-fork-/assets/21023906/85e61f3e-476c-47a4-82d5-4054e856c67b" width="180" />
  <img src="https://github.com/DevTITANS05/Hands-On-Linux-fork-/assets/21023906/85e61f3e-476c-47a4-82d5-4054e856c67b" width="180" />
  <img src="https://github.com/DevTITANS05/Hands-On-Linux-fork-/assets/21023906/85e61f3e-476c-47a4-82d5-4054e856c67b" width="180" />
  <img src="https://github.com/DevTITANS05/Hands-On-Linux-fork-/assets/21023906/85e61f3e-476c-47a4-82d5-4054e856c67b" width="180" />
  <img src="https://github.com/DevTITANS05/Hands-On-Linux-fork-/assets/21023906/85e61f3e-476c-47a4-82d5-4054e856c67b" width="180" />
  <img src="https://github.com/DevTITANS05/Hands-On-Linux-fork-/assets/21023906/85e61f3e-476c-47a4-82d5-4054e856c67b" width="180" />
</p>

### 🛠️ Papéis dos Contribuidores

- **Desenvolvedor 1**
  - Pesquisa do código responsável pela tela de desbloqueio
  - Desenvolvimento das alterações em Java
  - Documentação da atividade

- **Desenvolvedor 2**
  - Pesquisa do código responsável pela tela de desbloqueio
  - Desenvolvimento das alterações em Java
  - Documentação da atividade

- **Desenvolvedor 3**
  - Desenvolvimento das alterações em Java
  - Aplicação de patches e testes

- **Desenvolvedor 4**
  - Desenvolvimento das alterações em Java
  - Aplicação de patches e testes

- **Desenvolvedor 5**
  - Pesquisa do código responsável pela tela de desbloqueio
  - Documentação da atividade

---

## 📦 Recursos

Para rodar esta atividade, você precisará de:

- Um computador com os requisitos descritos na seção [Configuração de Hardware](#-configuração-de-hardware)
- O **AOSP** na versão **14.0.0_r27** baixado no seu computador

---

## ⚙️ Requisitos

![Linux](https://img.shields.io/badge/OS-Linux%20(Ubuntu)-FCC624?style=flat-square&logo=linux&logoColor=black)
![Repo](https://img.shields.io/badge/Tool-Repo-4285F4?style=flat-square&logo=google&logoColor=white)
![Git](https://img.shields.io/badge/Tool-Git-F05032?style=flat-square&logo=git&logoColor=white)
![AOSP](https://img.shields.io/badge/Environment-AOSP%20Ready-3DDC84?style=flat-square&logo=android&logoColor=white)

- Sistema operacional: **Linux** (preferencialmente Ubuntu)
- Repo
- Git
- Ambiente de desenvolvimento configurado para AOSP

---

## 🖥️ Configuração de Hardware

![CPU](https://img.shields.io/badge/CPU-8%2B%20cores-00C853?style=flat-square&logo=intel&logoColor=white)
![RAM](https://img.shields.io/badge/RAM-16GB%2B-2962FF?style=flat-square&logo=memory&logoColor=white)
![Storage](https://img.shields.io/badge/Storage-250GB%2B-FF6D00?style=flat-square&logo=google-drive&logoColor=white)
![Network](https://img.shields.io/badge/Network-High%20Speed-00B0FF?style=flat-square&logo=speedtest&logoColor=white)

Para compilar e testar o AOSP, é recomendável ter:

- **CPU**: 8 núcleos (16 recomendados)
- **RAM**: 16 GB (32 GB recomendados)
- **Espaço em disco**: 250 GB (500 GB recomendados)
- **Conexão de internet** de alta velocidade

---

## 🚀 Uso

Após aplicar os patches, compile o AOSP normalmente.  
O processo pode variar dependendo da versão do AOSP e do dispositivo de destino. Em geral, os comandos são:

1. Configure o ambiente de compilação:

```bash
source build/envsetup.sh

```
📬 Contato
Para mais informações ou dúvidas, entre em contato com:

📧 Email: sergioademircarmo@gmail.com
🐙 GitHub: seu-usuario

Sinta-se à vontade para abrir issues ou enviar pull requests para contribuir com este projeto.

## Progresso
- Arquivo identificado para modificação do Lockscreen: `frameworks/base/core/java/com/android/internal/widget/LockPatternView.java`
