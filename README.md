Aqui ficará toda documentação do processo de automação


Estratégia de Modelagem de Testes (Heurística SFDPOT)

Entendido. Se o seu ambiente de visualização de README não renderiza tabelas de Markdown (comum em alguns visualizadores legados ou sistemas de tickets específicos), a estratégia de elite é usar Listas de Definição ou Blocos de Código Estruturados.

Abaixo, apresento o formato Hierárquico com Tópicos, que é universalmente compatível, fácil de ler em dispositivos móveis e mantém a autoridade técnica.

🛠 Estratégia de Testes: Heurística SFDPOT
Para garantir a cobertura técnica e funcional, este projeto aplica o modelo SFDPOT. Esta abordagem decompõe o software em dimensões críticas para identificar falhas sistêmicas além do "caminho feliz".


[S] STRUCTURE (Estrutura)
Foco: De que o produto é feito?

Investigação: Integridade de componentes, dependências de pacotes, estrutura de arquivos e código-fonte.

Cenário Exemplo: Validar se todos os assets e fontes carregam sem erros 404.

[F] FUNCTION (Função)
Foco: O que o produto faz?

Investigação: Requisitos funcionais, regras de negócio e lógica de interface.

Cenário Exemplo: Garantir que o cálculo de frete segue a regra de negócio para cada região.

[D] DATA (Dados)
Foco: O que o produto processa?

Investigação: Entradas (inputs), saídas (outputs), tipos de dados e persistência.

Cenário Exemplo: Testar o comportamento do sistema com caracteres especiais (UTF-8) e campos nulos.

[P] PLATFORM (Plataforma)
Foco: O que o cerca o produto?

Investigação: Navegadores, sistemas operacionais, hardware e latência de rede.

Cenário Exemplo: Verificar a renderização em diferentes resoluções (Mobile vs Desktop).

[O] OPERATIONS (Operações)
Foco: Quem usa e como usa?

Investigação: Casos de uso reais, fluxos de usuários comuns e perfis de acesso.

Cenário Exemplo: Simular a jornada de um usuário que interrompe o fluxo de compra e retorna depois.

[T] TIME (Tempo)
Foco: Como o tempo afeta o sistema?

Investigação: Concorrência, timeouts, processamentos noturnos e datas críticas.

Cenário Exemplo: Testar se dois usuários podem editar o mesmo registro simultaneamente sem perda de dados.