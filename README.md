# 🌐 Setting Up Cloud Shell Access to Clusters

Este guia explica como configurar o Oracle Cloud Shell para acessar clusters Kubernetes no Oracle Container Engine for Kubernetes (OKE).

O Cloud Shell é um terminal baseado em navegador, disponível diretamente no console OCI, que vem pré-configurado com ferramentas como kubectl, oci-cli e helm. Isso elimina a necessidade de instalar ferramentas localmente para gerenciar seus clusters.

## 📌 Pré-requisitos

Antes de configurar o acesso ao cluster via Cloud Shell, você precisará:

- Uma conta ativa no Oracle Cloud Infrastructure (OCI).
- Permissão adequada configurada no IAM para acessar clusters do OKE.
- Um cluster Kubernetes já criado no OKE.
- Habilitar o acesso ao Cloud Shell pelo Console OCI.

## ⚙️ Passos para Configuração

### 1. Acessar o Cloud Shell

- No Console OCI, clique no ícone de Cloud Shell (canto superior direito).
- Uma sessão shell será aberta no navegador.

### Listar os Clusters Disponíveis
