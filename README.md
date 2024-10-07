# Sauda
### Resumo do Código: Mensagem de Saudação Baseada na Hora

Este projeto HTML demonstra como exibir uma mensagem de saudação com base na hora atual do sistema, utilizando JavaScript para manipulação do DOM.

#### Funcionalidades:

1. **Saudação Dinâmica**:
   - O código obtém a hora atual usando `new Date().getHours()`.
   - Dependendo do valor da hora, uma mensagem apropriada é definida:
     - **Bom dia!** (6h às 11h)
     - **Boa tarde!** (12h às 17h)
     - **Boa noite!** (18h às 5h)

2. **Manipulação do DOM**:
   - O elemento `<span>` com o ID `saudaJs` é selecionado.
   - A mensagem de saudação é então aplicada ao conteúdo interno do elemento, atualizando a interface do usuário dinamicamente.

#### Considerações:
- Este exemplo é uma boa demonstração de como usar JavaScript para interagir com o DOM e exibir informações contextuais ao usuário com base no horário atual.
