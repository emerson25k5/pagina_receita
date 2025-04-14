<p align="center">
  <img src="https://github.com/user-attachments/assets/0ced3ecd-eeb7-490a-bad9-3e400f04f83d" alt="Logo MELB" width="150"/>
</p>

<h1 align="center">AutCert — Sistema de Gestão de Eventos e Emissão de Certificados</h1>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-8.1-blue?style=flat&logo=php" />
  <img src="https://img.shields.io/badge/MySQL-5.7-blue?style=flat&logo=mysql" />
  <img src="https://img.shields.io/badge/Certificados emitidos-400%2B-success" />
  <img src="https://img.shields.io/badge/Acessos únicos-1000-lightgrey" />
</p>

---

## 📸 Print da Interface

<img src="https://via.placeholder.com/800x400?text=Print+do+Sistema+AutCert" alt="Print do sistema em produção" />

---

## ✨ Sobre o Projeto

**AutCert** é uma aplicação web voltada à gestão de eventos e geração automatizada de certificados personalizados. Desenvolvida com PHP puro, o sistema permite controlar eventos, presenças, certificados e realizar envios por e-mail de forma automática, com controle de templates e validação pública.

---

## 🎯 Funcionalidades

- ✔️ Cadastro e gerenciamento de eventos
- ✔️ Lista de presença e controle de participantes
- ✔️ Emissão automática de certificados
- ✔️ Sistema de **validação pública** de certificados
- ✔️ Envio automatizado de e-mails com certificados em anexo
- ✔️ Editor de **templates personalizados**
- ✔️ Exportação de dados em **Excel**
- ✔️ Notificações Web Push (em desenvolvimento)
- ✔️ Sistema de autenticação e perfis administrativos

---

## 🛠️ Tecnologias Utilizadas

- PHP 8+
- MySQL
- HTML5 / CSS3 / JavaScript
- PHPMailer (SMTP)
- FPDF / PhpSpreadsheet
- Session & Routing personalizados
- Web Push API (em progresso)

---

## ⚙️ Instalação e Deploy

```bash
# Clone o repositório
git clone https://github.com/seuusuario/autcert.git
cd autcert

# Configure seu banco de dados
# Execute o script database.sql no seu MySQL

# Ajuste o arquivo de conexão e ambiente

# Configure seu servidor Apache ou Nginx com suporte a PHP
# Configure cronjob (opcional) para workers de envio
