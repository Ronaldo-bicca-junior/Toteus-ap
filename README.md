1. Apresentação
 
Toteus PDV é um sistema de ponto de venda completo, desenvolvido para pequenos e médios negócios que buscam uma solução acessível, independente e sem custos recorrentes. Funciona totalmente via navegador — sem instalação de programas — e pode ser acessado de qualquer dispositivo: computador, tablet ou celular.
 
 
 
2. Objetivo do Sistema
 
Oferecer uma solução integrada para gestão comercial, cobrindo desde o cadastro de produtos até o fechamento de caixa, passando por vendas, controle de estoque, cadastro de clientes e relatórios de desempenho — tudo em um único sistema simples e intuitivo.
 
 
 
3. Módulos e Funcionalidades
 
🛍️ Módulo de Produtos
 
- Cadastro completo: código, nome, descrição, categoria, preço de custo e venda, código de barras, foto
​
- Edição, inativação e exclusão de itens
​
- Busca rápida por nome, código ou código de barras
​
- Visualização em grade com imagens
 
🛒 Módulo de Vendas — Frente de Caixa
 
- Leitura de código de barras (leitor externo ou câmera do celular)
​
- Busca manual de produtos
​
- Carrinho dinâmico: adição, remoção e alteração de quantidades
​
- Cálculo automático de subtotais, descontos e valor final
​
- Múltiplas formas de pagamento: dinheiro, cartão, PIX, fiado
​
- Cálculo de troco
​
- Envio de pedido e comprovante por WhatsApp
​
- Impressão de cupom
 
📦 Módulo de Estoque
 
- Baixa automática ao confirmar venda
​
- Registro de entrada de mercadorias
​
- Ajustes manuais e inventário
​
- Alerta de estoque mínimo
​
- Histórico completo de movimentações
 
👤 Módulo de Cadastros
 
- Clientes: dados pessoais, contato, endereço, histórico de compras e limite de crédito
​
- Fornecedores: dados cadastrais, contato e histórico de fornecimento
​
- Usuários: controle de acesso com níveis de permissão e registro de operações
 
📊 Módulo de Relatórios e Painel Administrativo
 
- Vendas por período (dia, semana, mês, personalizado)
​
- Produtos mais vendidos e ranking de saída
​
- Faturamento diário e horários de movimento
​
- Estoque baixo e itens para reposição
​
- Desempenho por vendedor
​
- Distribuição por forma de pagamento
​
- Fechamento de caixa e conferência
 
💰 Módulo Financeiro
 
- Controle de contas a receber (vendas a prazo)
​
- Registro de contas a pagar
​
- Fluxo de caixa diário
​
- Conferência de valores no fechamento
 
 
 
4. Arquitetura e Tecnologias
 
Estrutura do Sistema
 
 
 
Arquivos Principais do Projeto
 
Tabela
   
Arquivo Função 
 index.html  Página pública — vitrine/cardápio para clientes 
 vendas.html  Frente de caixa — operação de vendas 
 admin.html  Painel administrativo — relatórios e gestão 
 produtos.html  Cadastro e gestão de produtos 
 estoque.html  Movimentação e controle de estoque 
 style.css  Estilos visuais e layout responsivo 
 app.js  Lógica do sistema — carrinho, cálculos, armazenamento 
 README.md  Documentação do projeto 
 
 
 
5. Fluxo de Operação
 
Na Venda:
 
1. Acessa a frente de caixa → faz login
​
2. Localiza o produto (leitor de código ou busca manual)
​
3. Adiciona ao carrinho → define quantidade
​
4. Confirma itens → aplica desconto se necessário
​
5. Seleciona forma de pagamento → informa valor recebido
​
6. Sistema calcula troco → confirma operação
​
7. Estoque é atualizado → pedido registrado → comprovante emitido/enviado
 
Na Gestão:
 
- Acessa painel administrativo com senha de gerente
​
- Consulta relatórios, faturamento, estoque e histórico
7. Estoque é atualizado → pedido registrado → comprovante emitido/enviado
 
Na Gestão:
 
- Acessa painel administrativo com senha de gerente
​
- Consulta relatórios, faturamento, estoque e histórico
​
- Cadastra/edita produtos, atualiza preços e reposição
​
- Fecha caixa e confere valores no final do expediente
 
 
 
6. Vantagens e Diferenciais
 
Tabela
   
Benefício Descrição 
💰 Sem mensalidade Código próprio, sem taxas recorrentes 
📱 Acessível de qualquer lugar Funciona no celular, tablet ou computador 
🔧 Fácil de usar Interface simples, sem treinamento complexo 
🖼️ Fotos dos produtos Identificação visual rápida na venda 
📲 Integração WhatsApp Pedidos e comprovantes enviados automaticamente 
🔒 Seus dados com você Não depende de servidores terceiros 
♻️ Evolutivo Novas funcionalidades sendo adicionadas continuamente 
 
 
 
7. Próximas Etapas de Desenvolvimento
 
🔐 Área de login protegida por senha
☁️ Banco de dados na nuvem — acesso de qualquer lugar
📲 Aplicativo PWA — instalação direto no celular
🖨️ Emissão de nota fiscal eletrônica
📦 Controle de lotes e validade de produtos
📤 Exportação de relatórios para Excel/PDF
📡 Funcionamento offline — vende sem internet e sincroniza depois
