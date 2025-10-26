# 🧩 Solução de Problemas na Criação de uma Instância EC2 (AWS CLI + LAMP)

Este projeto documenta o laboratório prático de **AWS EC2 via CLI**, com instalação de uma pilha **LAMP (Linux, Apache, MariaDB, PHP)** através de *user data*, além de uma aplicação de exemplo (**Café Web App**) e validação por meio de troubleshooting com `nmap` e logs do `cloud-init`.

---

## 🎯 Objetivos

- Iniciar uma instância **EC2** usando a **AWS CLI**  
- Corrigir erros comuns durante a criação da instância  
- Instalar e configurar automaticamente a pilha **LAMP**  
- Verificar a acessibilidade e funcionamento com **nmap** e **cloud-init**  
- Publicar uma aplicação web simples (Café Web App)

---

## ☁️ Arquitetura

A arquitetura é composta por:
- Uma instância **Amazon EC2 (Amazon Linux)**  
- Um **Security Group** com as portas **22 (SSH)** e **80 (HTTP)** abertas  
- Instalação automática via **user data script**  
- Aplicação Café hospedada em `/var/www/html/cafe`
