# Introdução

## O que é experimentação em projetos de software?

- descreve os métodos e técnicas para realização de estudos exploratórios e de validação
- apoia a execução dos estudos com corretude
- evitar vieses de interpretação humana
  <br/><br/>

## Métodos de pesquisa

- **científico**: construção de modelos baseado nas observações do mundo real.
- **engenharia**: sugere soluções mais adequadas para as já existentes. Abordagem orientada à melhoria evolutiva.
- **experimental**: avalia uma teoria/modelo usando experimentação. Tem como premissa a replicação do experimento.
- **analítico/matemático**: define teorias formais e deriva os resultados a partir da mesma
  <br/><br/>

## Estudos Primários e secundários

- **primário**: visam caracterizar determinada tecnologia em um dado contexto
- **secundário**: apioar os resultados encontrados em estudos experimentais
  <br/><br/>

## Design do estudo

É um conjunto de métodos e procedimentos usados na coleta e analálise de medidas das variáveis especificadas na investigação do problema de pesquisa.

Define:

- tipo de estudo
- problema de pesquisa
- hipótese
- variáveis independentes e dependentes
- desenho do plano de analise experimental e estatística

## Design Fixo

- exige pré-especficação rigorosa antes de chegar à coleta de dados.
- dados geralmente numéricos.
- é comumente referido como como um quantitativo
- relacionado à interpretação

## Design Flexível

- pouca especificação sobre os dados que serão coletados.
- o design evolui durante a coleta de dados.
- tipicamente dados não numéricos.
- usado em estudos qualitativos
- estudar "objetos" em seu ambiente natural
- o design evolui durante a coleta de dados

---

---

<br/><br/>

# Processo de experimentação

Um estudo experimental deve ser visto como um processo de **formulação** ou **verificação** de um modelo ou teoria.

Um processo experimental possui fases sequenciais e interconectadas

- aplicação de ténicas e ferramentas

Dependendo do estudo, o processo pode ter diferenças nas fases, maneira como transforma os dados, métricas, ferramentas, etc.
<br/><br/>

## Alguns tipos de design

1. Survey

   - revisão em retrospecto
   - captura um retrato instantâneo
   - precisa de uma amostra representativa

2. Experimento controlado

   - utilizado quando deseja maior controle de uma situação.

     - isolar o comportamento de variáveis

   - manipular variáveis de forma direta, sistemática e preicsa.

     - controla-se poucas, e outras são constantes para todos os participantes.

   - realizado em laboratório

   - fácil generalização dos resultados

3. Estudo de caso

   - investigar uma entidade/fenômeno em um espaço de tempo específico.
   - coletas/observações abrangentes
   - considera-se vários atributos
   - considera-se um estudo de observação
   - dificil extender conclusões para outros contextos

4. Etnografia
   - estudo descritivo e interpretativo de um grupo ou comunidade
   - grande interação do pesquisador com os participantes
   - dados coletados a partir de observações e entrevistas
     <br/><br/>

## Como construir o desgin de um estudo?

### GQM

Abordagem que divide o processo de experimentação em:

- conceitual (goal)
- operacional (question)
- medição (metric)
  <br/><br/>

### Objetivo

A definição do objetivo do experimento irá determinar o quão abrangente ele será, além do tipo de estudo.

Objetivos relacionados à design fixos:

- avaliar
- analisar
- caracterizar
- comparar
- descrever

Objetivos relacionados à design flexíveis

- investigar
- compreender
  <br/><br/>

### Questões de pesquisa

Direcionam o foco do seu estudo, delimitam o escopo e auxiliam a mostrar os resultados.

Tipos de quesões:

- **descritivas**: o que, quem, onde e quando
- **avaliativas**: o quão bom, positivos/negativos, qual é melhor
- **explicativas**: por que é melhor, como é feito

Exemplo - Objetivo

Problema:

```
- ferramentas online para kanban tem sido bastante usadas.
- a ferramenta melhora a comunicação e colaboração entre os times
- times gastam muito tempo na gestão de projetos através da ferramenta
```

Objetivos:

```
- identificar qual a melhor ferramenta para gestão de projetos
- avaliar duas ferramentas de quadro kanban
- avaliar o JIRA e o Trello para identificar a que provê maior impacto na gestão das atividades diárias do time
```

Qual dos objetivos acima é **válido e atingível?**

\
Exemplo - Pergunta de pesquisa

Objetivo:

```
- avaliar o JIRA e o Trello para identificar a que provê maior impacto na gestão das atividades diárias do time
```

Pergunta de pesquisa:

```
JIRA é melhor que o Trello?
```

Calibrando a pergunta de pesquisa:

```
Quais são os recursos de cada ferramenta que causam maior impacto na eficiência das atividades diárias do time?
```

\
Exemplo - Métricas

Objetivo:

```
- avaliar o JIRA e o Trello para identificar a que provê maior impacto na gestão das atividades diárias do time
```

Pergunta de pesquisa:

```
Quais são os recursos de cada ferramenta que causam maior impacto na eficiência das atividades iárias do time?
```

Métricas

```
eficiência, tempo, esforço
```

---

---

<br/><br/>

# Experimento Controlado - Fundamentos e Planejamento

Experimento controlado é um teste científico feito sob condições controladas, ou seja, apenas um (ou poucos) fatores são alterados a cada vez, os demais permanecem constantes.

## Características:

- permite conclusões mais generalizadas
- rigoroso quando à preparação
- **hipóteses** são direcionadoras do trabalho
- permite análisese estatísticas descritivas e inferenciais com os dados coletados
- amostra geralmente dividida em dois grupos:

  1. grupo de controle
  2. grupo experimental

- deve ser replicável
  <br/><br/>

## Tipos de variáveis

- independentes (ou fator): podemos controlar e mudar. Possuem efeito sobre as dependentes.
- dependentes: queremos estudar para ver os efeitos das mudanças nas independentes.
- na maioria das vezes não é diretamente mensurável
  <br/><br/>

## Causa - Efeito

Um experimento estuda o efeito de alterar uma ou mais variáveis independentes.

Um **tratamento** é um valor particular de um fator.

Usualmente, existe **uma** variável independente que pode sofrer alterações. As demais são fixas.
<br/><br/>

## Exemplo

Estudar os efeitos de um novo método de desenvolvimento com relação à produtividade dos desenvolvedores. Considerando que um método OO será introduzido no lugar de um método baseado em funções.

**Variável dependente**: produtividade

**Variáveis independentes**:

- método de desenvolvimento
- suporte de ferramentas
- ambiente de trabalho
  <br/><br/>

## Escopo: definição do objetivo

Paradigma GQM:
![GQM](https://i.ibb.co/ct8vYXV/Screenshot-38.jpg)

- **objeto do estudo**: produto, processo, modelo, métrica, teoria
- **propósito**: caracterizar, monitorar, avaliar, comparar, predizer, controlar, alterar
- foco da qualidade: efetividade, custo, manutenabilidade, portabilidade
- **perspectiva**: DEV, PO, PM, usuário, pesquisador
- **contexto**: sujeitos, objetos
  <br/><br/>

## Seleção do contexto

É preciso ter cuidado para não interferir na prática. O contexto pode ser caracterizado pelas dimensões:

- offline vs online
- estudante vs profissional
- simulação vs problemas reais
  <br/><br/>

## Formulação das hipóteses

Base para os testes estatísticos.

Os dados coletados durante o experimento serão a base para o teste das hipóteses.

Hipótese nula (H0):

- é a principal
- circunstância que está sendo testada
- declara que não há relação significante entre causa efeito
- declara que não existem condições de tendência ou padrões em um experimento
  <br/><br/>

Hipóteses alternativas (HA, H1)

- hipótese que rejeita H0
- representa o que se deja provar/estabelecer
  <br/><br/>

## Seleção dos sujeitos

A seleção deve ser representativa. Quando maior a amostra, menor o erro.

**Amostra probabilística:** seleção randômica

**Amostra não-probabilística:** seleção não-aleatória baseada em critérios

**Randomização:** atribuição randômica de cada tratamento.

**Blocking (agrupamento):**

- eliminar efeitos indesejados no estudo
- aumenta precisão do experimento
- existe variável independente que pode influenciar no efeito

**Balanceamento**
Amostra pareada e não-pareada.
<br/><br/>

## Instrumentação

**Objetos manipulados:** produtos, modelos, etc

**Guidelines:** instruções sobre objetos e experimentação, checklists, TLCE, requisitos, tarefas, coleta de perfil

**Instrumentos para coleta de dados:** ferramentas de capturas automatizadas, entrevistas

```
Uso de métodos reconhecidos requerem um aquecimento, para evitar problemas com curva de aprendizagem.

Define-se: objetivo, tempo e materiais.
```

<br/><br/>

# Medição e instrumentação

## Pergunta de pesquisa x hipótese

**Pergunta de pesquisa**

- maior amplitude
- respondida a partir da experimentação
- explica o propósito da pesquisa

**Hipóteses**

- suposta, provável e provisória resposta a uma pergunta de pesquisa.
- submetida à verificação ou teste para ser comprovada ou refutada.
- aponta relações entre variáveis
- procura comparar elementos através de métricas

**Hipóteses e métricas**

- precisam ser justos, para evitar _bias_, comparando medidas de mesmo nível.
- hipótese deve ser respondida a partir de uma mensuração
- não deve ter "ou" em uma hipótese.

Exemplo:

```
PP: Usar o Scrum produz melhor qualidade de software que usar o XP
```

- qual é a medida de melhor qualidade?
  <br/><br/>

```
H0: Não há diferença significativa entre a qualidade de código de um software produzido através do SCRUM e de um produzido através do XP quando considera-se o número de defeitos por linha de código encontrados no produto.
```

Perguntas que devem ser respondidas para definir uma hipótese:

- permite comparação de medidas?
- compara objetos de mesma natureza?
  <br/><br/>

## Medidas

Tema central em experimentos controlados.

Mensurar é o processo pelo qual **números e símbolos** são atribuídos a entidades do mundo real como forma de **descrevê-los** de acordo com **regras claras**.

Em uma escala de medidas, cada nível é incremental.
<br/><br/>

### Escala Nominal

Rotulação sem noção de ordenação.

Exemplo: quero capturar em que etapa os defeitos aconteceram: especificação, design ou codificação:

- 1, se foi na especificação
- 2, se foi no design
- 3, se foi durante a codificação
  <br/><br/>

### Escala Ordinal

Ordenação em escala a partir de critérios (Likert, por exemplo).

Exemplo: desejo capturar quantitativamente a complexidade de desenvolvimento:

- trivial
- simples
- moderada
- complexa
- incompreensível
  <br/><br/>

### Intervalo

Qualquer intervalo de valores com **diferença matemática significativa**, mas não um zero verdadeiro.

Deve permitir compreender a diferença entre um dado e outro, seguindo uma ordem e rotulação.

Exemplo: probabilidade de um usuário recomendar um serviço:

- 0-6: Detractor
- 7-8: Passive
- 9-10: Promoter
  <br/><br/>

### Razão

Caraterizada por um ponto de zero absoluto: não há valor negativo. Dados ordenados, e a diferença entre os valores são significativas.

Permite calculo de razões.

Exemplo: um software com X linhas de código é duas vezes menor do que um com 2X.
<br/><br/>

### Resumo

![resumo_medidas](https://i.ibb.co/vB6mT2d/Screenshot-39.jpg)
<br/><br/>

### Medida objetiva e subjetiva

**Objetiva**

- valor depende somente do objeto
- diferentes medições, mesmos resultados
- ex: linhas de código, data de entrega

**Subjetiva**

- depende da perspectiva de quem mede
- ex: habilidades de um desenvolvedor
  <br/><br/>

### Medida direta e indireta

**Direta**

- não envolve medições
- ex: linhas de código, número de defeitos

**Indireta**

- depende de outros atributos
- derivada a partir de outras métricas
- ex: produtividade de um DEV (linhas de código/esforço)
  <br/><br/>

## Instrumentos de coleta

Como serão coletados os dados.

Coletas podem consistir em:

- perfil dos participantes
- dados diretamente relacionados às métricas
- percepção dos participantes em relação ao objeto de estudo
  <br/><br/>

## Questionário de perfil

Demonstrar e discutir que tem uma amostra representativa.

Suporte para a discussão de tratamento à validade do estudo.

Deve conter questões:

- demográficas (cargo, experiência na área/cargo)
- de conhecimento sobre o objeto

O questionário de perfil é dependente do objeto de estudo.
<br/><br/>

## Medidas e percepção do sujeito

**Medidas:**

- coletas automáticas
- coletas através de planilhas
- geração de novas medidas a partir de outras.

Percepção do sujeito pode ser por entrevistas (dificil quando se tem muitos participantes) ou por instrumentos consolidados, como TAM
<br/><br/>

## Questionário TAM

Modelo teórico com objetivo de avaliar a aceitação de uma tecnologia na visão de um sujeito.

Modelo comportamental baseado em construtos, só pode ser utilizado para questões diretamente relacionadas entre sujeitos e suas percepções.

Perguntas categorizadas em:

- utilidade percebida
- facilidade de uso percebida

![categorias_tam](https://i.ibb.co/Tk1bDNg/Screenshot-40.jpg)

Respostas seguem a escala Likert 6 pontos (concordo totalmente <-> discordo totalmente)
<br/><br/>

# Análise e interpretação

Já possuimos o dataset, agora falta analisá-lo. A primeira é feita a partir da estatística descritiva, que tem impacto na redução do dataset.

## Estatística descritiva

Descreve e sumariza um dataset. Provê a visão global da variação e descreve os dados por meio de **tabelas**, **gráficos** e **medidas descritivas**.

É utilizada **antes** de validar as hipóteses, para compreender melhor os dados e identificar possíveis outliers.

- deve-se buscar explicações para os outliers.

As medidas usadas podem ser:

- distribuição: frequência de cada valor
  - tabelas
  - agrupamentos
- tendência central: média dos valores
  - média
  - moda
  - mediana
- variabilidade ou dispersão dos valores.
  - amplitude (distancia min-max)
  - variância/DP (dispersão em torno da média)
  - coeficiente da variação (DP como porcentagem da média)
    <br/><br/>

## Estatística Inferencial

É baseada em testes estatísticos, e tem como objetivo obter uma afirmação sobre uma população a partir dos testes feitos nas hipóteses.

O objetivo principal é rejeitar H0 com base em uma distribuição estatística. Isso é feito baseado no **grau de significância**.

Os testes devem ser adequados ao tipo de amostra e distribuição dos dados da amostra.
<br /><br />

## Intervalos de significância/confiança

É uma **estimativa** de uma faixa de valores que inclui o valo verdadeiro da população para uma estatística, como uma média.

Exemplo: um nível de 95% de confiança (ou α de 5%) significa 95% de chance de estar certo, ou 5% de estar errado.

Os níveis mais utilizados são: 99, 95 e 90%.
<br /><br />

**Passos de execução:**

- verificar se os dados seguem uma distribuição normal
- escolher o teste estatístico
- executar testes para refutar/comprovas as hipóteses
  <br /><br />

## Distribuição normal

Explicar o teste de shapiro-wilk
<br /><br />

# Ameaças à validade

É extremamente necessário verificar a validade do experimento. Essa verificação é feita no **final do experimento**.

Uma validade adequada garante que os resultados são válidos para uma **população de interesse**, que consiste em:

- subconjunto populacional sob o qual o estudo foi executado
- população mais ampla, para qual os resultados podem ser generalizados

Garante a confiança nos resultados, sem interferência de enviesamento/interpretação humana.
<br /><br />

## Validade de conclusão

Referente à questões que afetam a habilidade de tirar conclusões corretas em relação aos efeitos causados pelos tratamentos e variáveis dependentes.

Evitar "pescar" um resultado: alguem procurando um resultado específico.

**Exemplos de influências:**

- confiabilidade das medidas e implementação dos tratamentos
- tamanho da amostra
- julgamento humano
- potência do teste estatístico
  <br /><br />

## Validade interna

Afetam a habilidade de garantir que os resultados foram obtidos a partir dos tratamentos e não por uma coincidência (ou outro fator que não foi medido ou controlado). É a verdade aproximada sobre as relações de **causa** e **efeito**.

**Questão chave:** as mudanças observadas são atribuídas ao tratamento?

**Exemplos de influência:**

- problemas na instrumentação
- ameaça de abandono dos participantes por exaustão
- ameaça de efeito de expectativa do sujeito
- modo que os participantes são selecionados, agrupados, tratados, recompensados, aleḿ da situação em que ocorre o experimento.
  <br /><br />

## Validade de construção

Refere-se à questões que afetam a habilidade de generalizar os resultados do experimento ao conceito/teorias envolvidos no estudo.

Ameaças surgem a partir do comportamento incorreto do participante OU de quem aplica o estudo.

Os participantes podem basear seu comportamento em suas suposições sobre a hipótese, além de tentarem parecer melhores do que realmente são. Também relacionada na projeção do estudo baseada no viés do pesquisador.

**Exemplos de ameaças:**

- definição incorreta de medidas
- viés de interpretação
- expectativa do pesquisador
  <br /><br />

## Validade externa

Refere-se às questões que afetam a habilidade de se generalizar os resultados do estudo para um contexto mais amplo.

**Exemplos de ameaça:**

- escolha errada de participantes
- ambiente impróprio para execução do experimento
- realização do estudo em um período de tempo que afete o resultado.

---

---

<br /><br />

# Survey

É um estudo do tipo design fixo. Consiste em um método de coleta e análise de informações de uma amostra de indivíduos.

É conduzido para entender a população da qual a amostra faz parte, buscando o conclusões generalizadas.

Sua elaboração é custosa, pois deve-se buscar a maior quantidade de conhecimento com a menor quantidade de variáveis. Requer questões relacionadas a diversas variáveis, e o cruzamento dos dados é um fator importante.

Surveys muito grandes tendem a ser tediosos, ocasionado abandonos e comprometimento de qualidade nas respostas.

**Possíveis instrumentos de coleta:**

- questionário
- entrevistas

É uma abordagem metodológica completa, incluindo amostragem, lembretes e incentivo.

**Vantagens:**

- fácil de coletar vários dados
- útil para o overview de uma população
- não requer ferramentas especiais
- pouco intrusivo

**Desvantagens:**

- dados pouco detalhados
- não é possível extender perguntas (após resposta inicial)
- dados podem estar enviesados (se as questões são direcionadas a opiniões)
- maior tempo de preparação
  <br /><br />

## Survey Descritivo

Focado em descrever características de uma amostra, permitindo afirmações sobre uma população.

Determina a distribuição de certas características ou atributos. Foco em **qual é a distribuição**, e não **porque essa distribuição existe**.
<br /><br />

## Survey Explicativo

Objetivo de fazer explicações sobre a população, como estudar como os desenvolvedores usam uma certa técnica

- pode ser necessário explicar porque alguns DEVs utilizam uma técnica enquanto outros optam por outra
- a análise pode mostrar uma explicação do porque tal técnica foi escolhida
  <br /><br />

## Survey Exploratório

Estudo de caráter investigativo realizado antes de uma investigação mais aprofundada para conseguir prever informações importantes.

Fornece novas possibilidades que podem ser analisadas e deve ser melhor explorada em um survey mais aprofundado e minucioso.

## Identificação da população e amostra

A população deve estar relacionada com a pergunta de pesquisa, e pode incluir critérios de **inclusão** e **exclusão**. Como qualquer pessoa pode responder, é preciso saber **atingir** a população correta.

**Tipos de amostragem:**

- **probabilística:** Individuos selecionados aleatoriamente, de acordo com os **critérios de inclusão/exclusão**

  - aleatória simples
  - estratificada
  - cluster
  - sistemática

- **não-probabilística:** Escolha deliberada de acordo com critérios e julgamentos dos pesquisadores.
  - para determinar a validade da amostra, é necessario coletar uma boa quantidade de dados demográficos, para garantir a diversidade e representatividade.
    <br /><br />

## Preparação

Buscar surveys semelhantes já existentes.

Determinar a **motivação**: por que alguém responderia?

- esclarecer propósito
- ser direto sobre intenções
- recompensas

Criar instrumentos de coleta curtos.

Dividir muitas questões em seções.
<br /><br />

### Perguntas abertas

Natureza exploratória, sem restringir tipo/tamanho das respostas. A desvantagem é a dificuldade de analisar grande quantidades de dados.

Exemplos:

- **questão ampla:** Por que você parou de usar o Jira?
- **questão específica:** O jira permitiu que você completasse as tarefas que queria?
  <br /><br />

### Perguntas fechadas

Conjunto pré-definido de respostas. Podem ser ordenadas ou não.

No caso das não-ordenadas, é possível permitir mais de uma opção.
<br /><br />

## Coleta + Piloto

O piloto pode ser feito com pessoas que não fazem parte da população. Definir o tempo que o survey estará aberto para coleta.

Fornecer mensagens de incentivo e monitorar as respostas.
<br /><br />

## Análise e Interpretação

Depende do propósito do survey (descritivo, explicativo ou exploratório) e dos tipos de questões.

Usa-se estatística descritiva e inferencial.

É construído um relatório no final do processo.

---

---

<br /><br />

# Estudo de caso

Muitas vezes confundido com POCs e exemplos. Um estudo de caso deve ser abrangente e contextualizado.

É um método de pesquisa **empírica**, e os fenômenos em estudo não podem ser separados do contexto.

- os efeitos podem ser amplos
- perguntas de como e por que.

Os pesquisadores tem **pouco controle** sobre as variáveis, e os efeitos levam tempo para aparecer.
<br /><br />

## Características

Permite estudar um fenômeno pouco conhecido, e por ser um estudo qualitativo, gera dados estatísticos significantes.

- entender capacidade de uma nova ferramenta
- caracterizar o processo de atualização de um projeto

As técnicas mais utilizadas são **entrevistas** e **observações**.

- múltiplas fontes de dados

Custosos pois são feitos em ambientes reais, além de demandar mais tempo.

A coleta pode ser incremental.

**Objetivo da investigação**

- **Exploração:** descobrir algo
- **Caraterização:** descrever mais completamente
- **Exploração:** descobrir se uma teoria/hipótese é verdadeira
  <br /><br />

**Fases do estudo**

- **design** do estudo
- **coleta** de dados
- **análise** de dados
- **relatório** dos resultados
  <br /><br />

## Perguntas típicas

A tarefa inicial é esclarecer a natureza das perguntas do estudo, certificando que são do tipo "como" ou "por que"

**Exemplos:**

- por que 2 organizações tem um relacionamento colaborativo?
- como as retros funcionam na prática?
- como uma empresa decide qual projeto iniciar?
  <br /><br />

## Propósitos de um Estudo de caso

### Explicativo

Busca explicações para situação/problema

- epxlicar impacto de algo dentro da prática da ES

**Exemplo:** Quão importante é o viés de implementação na engenharia de requisitos?

### Descritivo

Descreve um retrato do status atual de uma situação ou fenômeno.

**Exemplo:** Como o pair programming ocorre na prática em pequenas empresas?
<br /><br />

### Melhoria

Implementar algo novo e observar o impacto.

**Exemplo:** Usar protótipos de baixa fidelidade ajuda a empresa na especificação de requisitos?
<br /><br />

### Exploratório

Busca novos insights, gera ideias e hipóteses para uma nova pesquisa.

**Exemplo**: O que as startups early stage tem em comum?
<br /><br />

## Proposição

Declarações que **direcionam a atenção** para algo que deve ser examinado.

- **exemplo:** As organizações colaboram porque isto permite a troca de experiências em áreas que elas não têm expertise.

Dirão **onde** buscar evidências

- **exemplo:** Defina e verifique quais áreas cada empresa não tem expertise

Alguns estudos (como os exploratórios) podem não ter proposições.
<br /><br />

## Definição dos elementos

O estudo de caso é definido pelos seguintes elementos:

- o **caso** que está sendo estudado
- a **unidade** de análise
- a **seleção** do estudo de caso
- o **contexto** do estudo de caso
  <br /><br />

### Caso e Objetivo

O caso pode ser qualquer situação relacionada à ES em **ambiente real**. Pode estar relacionado a:

- time de software
- processo
- produto
- evento
- tecnologia

O **objetivo** é o que se pretende descobrir com o estudo.
<br /><br />

### Unidade de análise

Define o que será **explorado** em um caso.

Exemplos:

- **caso:** estudo sobre o uso do Web extension por empresas pequenas
- **unidades de análise:** times de desenvolvimento, percepção dos engenheiros de software, fase de design do software, organização
  <br /><br />

### Seleção do estudo de caso

O caso e as unidades de análise são selecionadas de **forma intencional**

- diferente de surveys e experimentos controlados.

Pode estar relacionado a alguma teoria ou característica desejada.

Exemplo: objeto é estudar times totalmente remotos: posso escolher empresas pré ou pós pandemia.
<br /><br />

### Definição do contexto

Dividido em 6 facetas:

- **Produto:** software que é desenvolvido com o suporte do objeto de estudo.

  - tipo, maturidade, plataforma de desenvolvimento

- **Processo:** processo usado no desenvolvimento

  - atividades, workflow das atividades, artefatos

- **Práticas, Ferramentas, Técnicas:** elementos que descrever as abordagens sistematizadas que são usadas pela organização e interagem com o objetivo de estudo

  - ferramentas, práticas ligadas a abordagens específicas

- **Pessoas:** fatores humanos são importantes para a ES, e impactam no desenvolvimento de software.

  - papéis executados, experiência das pessoas

- **Organização:** detalhes sobre a organização relevantes ao estudo de caso.

  - número de desempregados, ano de fundação, unidades da organização envolvidas no estudo

- **Segmento de mercado:** características do mercado na qual a empresa está inserida
  - B2B, B2C, número de usuários, tipo de mercado
    <br /><br />

## Preparação e coleta de dados

**Direta (1º grau):** contato direto com sujeitos e coleta em tempo real

- entrevistas, focus group, observação, think aloud

**Indireta (2º grau):** sem interação direta com sujeitos

- log de ações, gravação de tela

**Indireta (3º grau):** análise de artefatos disponíveis

- relatório de falhas, documento de requisitos
  <br /><br />

# Coleta de dados

Comumente coeltados a partir de **múltiplas** fontes de evidências.

Deve descrever o tempo em que a coleta ocorreu, os sujeitos e pesquisadores envolvidos.

Métodos comuns de coleta:

- focus group
- entrevistas
- observações
- documentos
  <br /><br />

## Triangulação

São as várias lentes que colocamos para avliar os dados.

**Dados:** os mesmos tipos de dados de diferentes fontes.

- gravando vídeo, entrevista, visita in loco.
  <br /><br />

**Pesquisadores:** diferentes pessoas **coletam** e analisam dados.

- diferentes pesquisadores podem fazer coletas separadamente
  <br /><br />

**Teoria:** diferentes perspectivas para o mesmo conjunto de dados

- exemplo: definições distintas sobre soft skills
  <br /><br />

**Metodológica:** coleta de dados a partir de diferentes **métodos**

- exemplo: entrevista e análise de user stories
  <br /><br />
  <br /><br />

## Técnicas de coleta

### Diários de trabalho

Técnica indireta de 2º grau onde os sujeitos registram eventos do dia, como registrar decisões/problemas nas dailys. Pode ser online ou papel.

**Importante:** pesquisadores devem deixar claro quais são os tipos de dados que devem ser registrados, além de "cutucar" os participantes.
<br /><br />

### Observação

Técnica direta de primeiro grau que exige um planejamento e um **objetivo bem definido**.

Tem um conjunto de perguntas que **motivam** suas descobertas.

**Pode ser:**

- participativa: (você faz parte do grupo)
- não-participativa: (sem interção direta, mas pode fazer perguntas).
  <br /><br />

**Formas de coleta:**

- **conversa:** sem preparação de questões. Usada para esclarecer ou coletar informações extras
- **think aloud:** verbalização do processo de pensamento
- **shadow sincronizado:** dois observadores **observam** um sujeito realizando uma tarefa utilizando think aloud. Permite diferentes tipos de informações, e um conjunto mais detalhado de notas de campo.
  <br /><br />

### Focus Group

Técnica direta de primeiro grau. Semelhante a brainstoming.

Grupo reunido para discutir algo, focado num objetivo determinado.

Deve ter pelo menos um **moderador**, que não deixa o grupo perder o foco e garante que todos participem.

As questões devem ser objetivas e ter um tempo de discussão limitado.
<br /><br />

### Entrevistas

Coletar dados históricos das memorias dos entrevistados, para coletar opiniões ou impressões sobre algo.

**Não-estruturadas:**
Roteiro composto por tópicos (lembretes), apresentados de forma aberta.

**Semi-estruturadas:**
Guia com perguntas para garantir que um conjunto de temas será abordado, mas novas perguntas podem surgir durante a entrevista.

**Estruturadas:**
Perguntas pré-definidas.
<br /><br />

## Como escolher a técnica

1. Qual é a abertura que a empresa tem para coleta de dados?
2. Qual a disponibilidade de tempo dos sujeitos?
3. Qual nível de detalhamento você precisa dos dados?
   <br /><br />

## Design da Coleta

**Técnica da coleta:** técnica selecionada

**Justificativa:** porque a técnica foi escolhida e porque ela atende o objetivo do estudo

**Duração da coleta:** quanto tempo será gasto (estimado)

**Número de participantes:** qual a estimativa

**Critério para inclusão/exclusão do sujeiro na coleta:** considera-se o caso e a unidade de análise.
<br /><br />

## Roteiro para coleta

1. Apresentar o estudo
2. TCLE
3. Gravar (?)
4. Dividir dados a serem coletados em grupos de questões:

- dados da organização
- dados do sujeito
- questões iniciais (sobre o caso do estudo)
- questões aprofundadas (sobre o caso do estudo)
- questões de fechamento (geralmente questionamentos do entrevistador)
  <br /><br />

## Dicas para aplicação da coleta

Construir **relacionamento** com sujeitos

- começar com perguntas simples para construir confiança
  <br /><br />

Perguntas **curtas** e **objetivas**

Evitar **generalização**

- casos específicos fornecem insights importantes
- exemplo: "geralmente estou atrasado nas minhas atividades" -> "Me de um exemplo"
  <br /><br />

# Análise de Dados

Objetivo é descobrir tendências, padrões e generalizações. Os dados geralmente são **categorizados**.

## Características

Dados qualitativos devem ser **significativos** e gerar **diversidade**.

O formato de texto é o mais comum para análises

- diferentes pesquisadores analisarem sob uma mesma perspectiva
- facilidade na rotulação dos dados
- facilidade para gerar relatórios

```
Trabalhar com aspectos socio-técnicos: o olhar sociotécnico busca o descritivo e explicativo.
```

## Objetivos da análise qualitativa

Transformar dados não estruturados em uma descrição detalhada

- apresentar os principais aspectos da situação/problema de investigação

Compreender o que os dados representam e como estão relacionados.
<br /><br />

## Abordagem Ad-hoc

Análise **temática:** procurar padrões no significado dos dados para encontrar temas.

- relevante para extrair temas em áreas pouco exploradas.
  <br /><br />

Análise de **conteúdo:** identificar os padrões no texto, agrupando o conteúdo em palavras, conceitos e temas.
<br /><br />

Teoria **fundamentada:** focada em descobrir/construir modelos a partir de dados analisados por comparações constantes.
