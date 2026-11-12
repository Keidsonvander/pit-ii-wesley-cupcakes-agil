# Evidências dos Testes e Correções — PIT II

**Aluno:** Wesley Sousa Machado  
**RGM:** 37181921  
**Projeto:** Aplicativo de vendas online para loja de cupcakes gourmet

## 1. Mensagem de confirmação do carrinho
**Problema identificado:** a mensagem exibida após adicionar um produto apresentava pouco destaque visual.

**Correção aplicada:** foram criadas mensagens distintas para sucesso e erro, com maior contraste e texto mais claro.

**Evidência:** classes `msg ok` e `msg erro` e função `mensagem()` adicionadas ao arquivo `index.html`.

## 2. Validação dos campos obrigatórios
**Problema identificado:** a orientação apresentada quando faltavam dados era genérica.

**Correção aplicada:** o sistema passou a verificar nome, telefone, endereço, pagamento e entrega, informando exatamente quais campos precisam ser preenchidos.

**Evidência:** nova lógica de validação adicionada à finalização do formulário.

## 3. Acompanhamento do pedido
**Problema identificado:** a etapa atual do pedido não possuía destaque suficiente.

**Correção aplicada:** a etapa “Pedido recebido” passou a receber destaque visual e a identificação “atual”, mantendo visíveis as demais fases do processo.

**Evidência:** atualização do componente de acompanhamento no `index.html`.

## 4. Responsividade
**Problema identificado:** em telas menores, alguns campos e botões ficavam muito próximos.

**Correção aplicada:** foram aumentados os espaçamentos, áreas de toque e organização dos componentes para smartphones.

**Evidência:** novas regras inseridas no media query para telas de até 600 pixels.

## 5. Confirmação final
**Problema identificado:** a confirmação final apresentava poucas informações.

**Correção aplicada:** foi incluído um resumo com número do pedido, cliente, forma de pagamento, modalidade de entrega e status atual.

**Evidência:** novo bloco `confirmacao` adicionado ao arquivo `index.html`.

## Resultado da nova verificação
Após as correções, foram novamente avaliados catálogo, carrinho, mensagens, validações, pagamento, entrega, acompanhamento, confirmação e responsividade. O fluxo principal apresentou funcionamento satisfatório e maior clareza para o usuário.

## Funcionalidades previstas para evolução futura
- cadastro e login de usuários;
- pagamento real integrado;
- rastreamento da entrega em tempo real;
- histórico de pedidos;
- área administrativa;
- testes em maior variedade de dispositivos e navegadores.
