# 📦 Sistema de Gerenciamento de Estoque

## 🏗️ Introdução

Este sistema foi projetado para ajudar empresas a **rastrear, monitorar e gerenciar** seu estoque de forma eficiente, garantindo **alertas automáticos**, **registro de histórico de vendas** e **gestão de pedidos de reposição**.

---

## 📌 Entidades de Domínio

### **Produto**

Representa um item armazenado no estoque.  
🔹 ID único  
🔹 Nome  
🔹 Tamanho  
🔹 Cor  
🔹 Quantidade disponível  
🔹 Quantidade mínima de estoque  
🔹 Histórico de movimentação

### **Estoque**

Gerencia o conjunto de produtos armazenados.  
🔹 Lista de produtos cadastrados  
🔹 Controle de entrada e saída

### **Venda**

Registra a saída de produtos do estoque.  
🔹 ID da venda  
🔹 Produtos vendidos  
🔹 Data da venda  
🔹 Lucro gerado

### **Ordem de Compra**

Automatiza pedidos de reposição de estoque.  
🔹 Produtos a serem comprados  
🔹 Quantidade necessária  
🔹 Status do pedido  
🔹 Prazos de entrega

### **Fornecedor**

Responsável pela entrega dos produtos ao estoque.  
🔹 Nome da empresa  
🔹 Produtos disponíveis  
🔹 Prazos de entrega  
🔹 Status do fornecimento

### **Alerta de Estoque**

Notificação para reposição de produtos.  
🔹 Produto afetado  
🔹 Motivo do alerta (estoque baixo)  
🔹 Canal de envio (e-mail, sistema)

---

## ⚡ Casos de Uso

✔ **Cadastro e gerenciamento de produtos** → Adicionar, editar e excluir produtos.  
✔ **Rastreamento individual de produtos** → Consultar movimentação e histórico.  
✔ **Definição de quantidade mínima de estoque** → Configurar limites de produtos.  
✔ **Geração de alertas de estoque baixo** → Notificar necessidade de reposição.  
✔ **Registro de vendas e cálculo de lucro** → Acompanhar desempenho dos produtos.  
✔ **Visualização do histórico de vendas e estoque** → Relatórios para decisões estratégicas.  
✔ **Criação e gerenciamento de ordens de compra** → Automatizar reposições com base em demanda.  
✔ **Integração com fornecedores** → Receber atualizações automáticas sobre prazos.  
✔ **Geração de relatórios estratégicos** → Identificar tendências e otimizar compras.

---

## 🚀 Como usar?

Para configurar e rodar o sistema:

1️⃣ **Clone este repositório**

```sh
git clone https://github.com/seu-usuario/sistema-estoque.git
```
