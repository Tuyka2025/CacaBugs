## Template de Relatório - Atividade "Caça-bugs"

### Informações Individual

**Nome do Integrante:** Tábatha Moreira Fernandes Rodrigues de Souza

**Data da atividade:** 04 de Agosto de 2025

### Bugs Encontrados

1. Bug #1 **Link "Home" não funcional**
    
    **Tipo de Bug:** Funcional.

    **Descrição:** Ao clicar em "Home", aparece uma mensagem de alerta ("Página em manutenção!") em vez de navegar para a página inicial.
    
    **Localização:** Menu de navegação superior.
    
    **Severidade:** Média.
    
    **Reprodução:** 1. Abrir index.html;
                    2. Clicar no link 'Home';
    
    **Impacto para o Usuário:** Usuário pode pensar que o site está fora do ar ou incompleto.


2. Bug #2 **Texto do botão com erro ("Adicionar ao Carinho")**

    **Tipo de Bug:** Interface.
    
    **Descrição:** Botão do produto "Laptop Ultra" contém erro ortográfico: "Adicionar ao Carinho".
    
    **Localização:** Página de produtos.
    
    **Severidade:** Baixa.
    
    **Reprodução:** 1. Ir até 'Produtos';
                    2. Observar botão do Laptop Ultra;
    
    **Impacto para o Usuário:** Causa má impressão e diminui a credibilidade da loja.


3. Bug #3 **Descrição do produto com erro ("Laptop poente")**

    **Tipo de Bug:** Usabilidade.
    
    **Descrição:** Texto incorreto: "Laptop poente" ao invés de "potente".
    
    **Localização:** Descrição do produto 'Laptop Ultra'.
    
    **Severidade:** Baixa.
    
    **Reprodução:** 1. Ver produto 'Laptop Ultra';
                    2. Ler a descrição;
    
    **Impacto para o Usuário:** Erro de digitação prejudica a clareza e profissionalismo.


4. Bug #4 **Inconsistência de preço nos 'Fones de Ouvido'**
    
    **Tipo de Bug:** Funcional.

    **Descrição:** Preço no HTML é R$ 299,90, mas no script está como 29.90.
    
    **Localização:** Produto 'Fones de Ouvido Bluetooth'.
    
    **Severidade:** Alta.
    
    **Reprodução:** 1. Adicionar produto ao carrinho;
                    2. Verificar total;
    
    **Impacto para o Usuário:** Total incorreto pode gerar prejuízo financeiro ou confusão ao cliente.


5. Bug #5 **Total do carrinho calculando incorretamente**

    **Tipo de Bug:** Funcional.
    
    **Descrição:** Devido ao erro de preço anterior, o valor final exibido pode estar incorreto.
    
    **Localização:** Seção 'Carrinho'.
    
    **Severidade:** Alta.
    
    **Reprodução:** 1. Adicionar produtos;
                    2. Verificar total calculado;
    
    **Impacto para o Usuário:** Compromete a confiança e a usabilidade do sistema de compras.


6. Bug #6 **Erro ortográfico no botão "Finalizar Compra"**

    **Tipo de Bug:** Interface.
    
    **Descrição:** Botão está com erro: "Finalizar Compra".
    
    **Localização:** Seção de Carrinho.
    
    **Severidade:** Baixa.
    
    **Reprodução:** 1. Ir ao carrinho;
                    2. Observar botão de finalização;
    
    **Impacto para o Usuário:** Erro visual que prejudica a imagem profissional da loja.


7. Bug #7 **Validação de e-mail ineficaz**

    **Tipo de Bug:** Validação.
    
    **Descrição:** Validação verifica apenas se há um '@', permitindo emails inválidos como 'teste@'.
    
    **Localização:** Formulário de Contato.
    
    **Severidade:** Média.
    
    **Reprodução:** 1. Prencher email como 'teste@';
                    2. Clicar 'Enviar';
    
    **Impacto para o Usuário:** POde causar falha no envio de informações ou coleta incorreta de dados.


8. Bug #8 **Rodapé com erro ortográfico"**

    **Tipo de Bug:** Interface.
    
    **Descrição:** Texto incorreto: 'Todos os diritos reservados'.
    
    **Localização:** Rodapé da página.
    
    **Severidade:** Baixa.
    
    **Reprodução:** 1. Rolar até o final da página;
    
    **Impacto para o Usuário:** Demonstra falta de revisão e pode afetar a confiança na marca.


9. Bug #9 **Lógica duplicada para o botão dos fones**

    **Tipo de Bug:** Funcional.

    **Descrição:** Produto ID 3 usa lógica separada para adicionar ao carrinho, diferente dos demais.

    **Localização:** Código JavaScript.

    **Severidade:** Média.

    **Reprodução:** 1. Verificar código JS.
                    2. Comparar lógica dos produtos.
    
    **Impacto para o Usuário:** Aumenta complexidade e risco de bugs em futuras manutenções.


10. Bug #10 **Layout não responsivo em telas pequenas**

    **Tipo de Bug:** Usabilidade.

    **Descrição:** Produtos não se adaptam bem em telas de celulares.

    **Localização:** Seção 'Produtos'.

    **Severidade:** Alta.

    **Reprodução:** 1. Redimensionar tela ou abrir em smartphone.

    **Impacto para o Usuário:** Usuário pode ter dificuldade de navegação em dispositivos móveis.

### Resumo e Estatísticas

**Total de bugs encontrados:** 10.

**Distribuição por tipo:**

- Interface: 3.
- Funcionais: 4.
- Validação: 1.
- Usabilidade: 2.
- Outros: 0.

### Classificação por Severidade

- Alta: 3 bugs.
- Média: 3 bugs.
- Baixa: 4 bugs.

### Reflexão da Equipe

**Desafios encontrados:** Identificar inconsistências de lógica e revisar todos os aspectos visuais e funcionais em um curto espaço de tempo.

**Estratégias utilizadas:** Navegação por todas as seções, adição de itens ao carrinho e preenchimento de formulários com dados inválidos.

**Aprendizados:** Compreensão da importância dos testes exploratórios e atenção aos detalhes em aplicações web.

### Sugestões de Melhorias

- Corrigir erros ortográficos nos textos e botões.
- Ajustar os preços inconsistentes no script.
- Unificar a lógica de adição ao carrinho para todos os produtos.
- Implementar validação de e-mail mais robusta.
- Melhorar a responsividade do layout para dispositivos móveis.

