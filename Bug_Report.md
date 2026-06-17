# 🐛 Relatório de Bug (Bug Report)

> **ID do Bug:** BUG-001  
> **Título:** Botão "Adicionar ao carrinho" fica sobreposto ao texto de descrição em telas menores (Resolução 360x740)  
> **Gravidade:** Menor (Problema visual de layout, mas a função ainda está ativa)  
> **Prioridade:** Baixa  

---

### 💻 Ambiente de Teste
* **Navegador:** Google Chrome v120
* **Dispositivo:** Emulador Mobile (Samsung Galaxy S20 Ultra)
* **Resolução:** 360x740 pixels

### 📋 Passos para Reproduzir
1. Acessar a página de qualquer produto (Ex: Link do livro testado).
2. Reduzir a largura da tela do navegador para simular um celular pequeno.
3. Rolar a página até a seção de compra.

### 🛑 Resultado Obtido
O botão amarelo de compra ficou posicionado em cima das últimas linhas do texto de frete, cobrindo as palavras e tornando a leitura impossível.

### ✅ Resultado Esperado
O layout deve ser responsivo. O botão deve se mover automaticamente para baixo do texto de frete, mantendo um espaçamento (margin) de segurança de 16px.
