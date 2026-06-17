# 📝 Planilha de Casos de Teste (CT) - Amazon Brasil

| ID | Cenário de Teste | Passos para Executar | Resultado Esperado | Status |
| :--- | :--- | :--- | :--- | :--- |
| **CT01** | Busca por produto existente. | 1. Acessar amazon.com.br.<br>2. Buscar por "iPhone 15".<br>3. Pressionar Enter. | Exibir lista de produtos relevantes. | **Passou** |
| **CT02** | Busca sem resultados. | 1. Buscar por "xj9992348972".<br>2. Pressionar Enter. | Exibir mensagem: "Nenhum resultado para...". | **Passou** |
| **CT03** | Adicionar ao carrinho deslogado. | 1. Abrir aba anônima.<br>2. Buscar por um livro.<br>3. Clicar em "Adicionar ao carrinho". | Item adicionado e contador do carrinho atualiza para 1. | **Passou** |
| **CT04** | Alterar quantidade no carrinho. | 1. Ir até o carrinho.<br>2. Alterar a quantidade de 1 para 3. | Valor total atualiza instantaneamente. | **Passou** |
