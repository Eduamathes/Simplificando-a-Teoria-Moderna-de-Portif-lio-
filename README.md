# Simplificando-a-Teoria-Moderna-de-Portifólio-
O objetivo desse repositório é apresentar de forma simples a Teoria Moderna de Portifólio, ou Modern Portfolio Theory (MPT) de Harry Markowitz, Nobel de economia em 1990, e como ela pode ser aplicável facilmente na montagem de uma carteira para investidores iniciantes. Para o desafio de projeto da DIO.

A escolha desse tema foi motivada pela sua importância e relevância para a vida de qualquer profissional, que merece, por respeito a sua dignidade, saber investir seu patrimônio com uma metodologia verificada, digna de Nobel, afim de que ele cresça e se multiplique ao longo do tempo. Explicando introdutoriamente um meio prático de como fazer isso.

# Fontes Utilizadas:

- https://finance.martinsewell.com/capm/Markowitz1952.pdf
- https://www.nobelprize.org/uploads/2018/06/markowitz-lecture.pdf
- https://www.stat.berkeley.edu/~aldous/24/Posted/Ali_Setayesh.pdf
- https://npd.uem.br/eventos/assets/uploads/files/evt/38/Minicursos/Teoria%20do%20Portf%C3%B3lio%20-%20Vinicius.pdf
- https://vicosaprev.ce.gov.br/wp-content/uploads/2022/04/LEMA-MARKOWITZ-VI%C3%87OSAPREV.pdf


# Engenharia de Prompts e "Cicatrizes": Interações com o NotebookLM

Esta seção documenta as perguntas estratégicas elaboradas, as variações de prompts testadas e as respostas obtidas nas interações com o NotebookLM. O registro dessas interações evidencia o raciocínio por trás dos resultados e as dificuldades encontradas durante o processo.

---

## Interação 1: Introdução à MPT e Aplicação Prática para Iniciantes

### Prompt

> Explique, de forma simples e direta, no que consiste a teoria moderna de portfólio elaborada por Markowitz e como um investidor iniciante pode aplicá-la montando sua carteira de investimentos fundamentada?

### Resposta

A Moderna Teoria do Portfólio (MPT), desenvolvida por Harry Markowitz, é uma estratégia de investimento que busca maximizar o retorno esperado para um determinado nível de risco ou, inversamente, minimizar o risco para um retorno desejado. O conceito central é que o risco de um ativo não deve ser avaliado isoladamente, mas sim pelo impacto que ele causa no risco total da carteira.

Abaixo, uma explicação direta de seus fundamentos e como aplicá-los:

### O que consiste a teoria?

- **Binômio Risco e Retorno:** A teoria assume que os investidores são racionais e avessos ao risco, o que significa que, entre dois investimentos com o mesmo retorno, eles escolherão o menos arriscado. Para buscar retornos maiores, é inevitável aceitar um risco maior.
- **A Força da Diversificação:** Markowitz demonstrou que um portfólio não é apenas uma lista de ações, mas um "todo equilibrado". A diversificação reduz o risco total da carteira ao combinar ativos que não se movem exatamente da mesma maneira (que possuem baixa correlação).
- **Fronteira Eficiente:** É o conjunto de carteiras "ótimas" que oferecem a melhor rentabilidade possível para cada nível de risco. Qualquer carteira abaixo dessa linha é considerada ineficiente, pois poderia render mais com o mesmo risco.

### Como um investidor iniciante pode aplicá-la?

Para montar uma carteira fundamentada seguindo Markowitz, o iniciante não precisa dominar as fórmulas matemáticas complexas, mas sim seguir estes passos práticos:

- **Defina seu Perfil de Risco:** Identifique se você é conservador, moderado ou arrojado. Isso determinará em que ponto da Fronteira Eficiente você deve se posicionar.
- **Não foque apenas em Retorno:** Em vez de escolher apenas o ativo que mais rendeu no passado, procure entender como ele se comporta em relação aos outros ativos da sua carteira.
- **Combine Classes de Ativos Distintas:** Para uma diversificação real, misture ativos de naturezas diferentes, como Renda Fixa (títulos públicos, CDI), Renda Variável (ações, fundos imobiliários) e até investimentos no exterior. Quando a bolsa cai, muitas vezes a renda fixa ou o dólar podem subir, equilibrando as perdas.
- **Atenção à Correlação:** Evite ter apenas ativos do mesmo setor (ex.: apenas ações de bancos). Se um setor sofrer uma crise, toda a sua carteira sofrerá. Procure ativos com comportamentos distintos para reduzir o risco diversificável.
- **Utilize o Conceito de Carteira Otimizada:** Você pode buscar modelos de alocação que já sugerem pesos ideais. Por exemplo, uma carteira moderada pode ter uma divisão entre fundos de renda fixa simples, títulos atrelados à inflação e uma parcela menor em fundos de ações para potencializar o retorno sem explodir o risco.

Embora a teoria utilize dados históricos que não garantem resultados futuros, ela serve como um guia essencial para que o investidor pare de "especular" e passe a investir de forma estruturada e protegida.

---

## Interação 2: Definições de Perfis de Investidor sob a Ótica de Markowitz

### Prompt

> Baseando-se na produção de Markowitz, me forneça duas definições:
>
> - Investidor insensato (concentra seu patrimônio em fatores únicos de risco);
> - Investidor prudente (utiliza-se de diversificação coesa).

### Resposta

Com base na produção de Harry Markowitz e na Moderna Teoria do Portfólio, as definições para esses dois perfis de investidor são:

**Investidor Insensato:** É aquele que pauta suas decisões de investimento exclusivamente na maximização do retorno esperado, ignorando a natureza fundamental da incerteza. Markowitz argumenta que agir com base apenas no retorno (como se o futuro fosse certo) leva o investidor a concentrar todo o seu patrimônio em um único ativo, aquele que apresenta o maior rendimento previsto. Esse comportamento é rejeitado pela teoria como irracional ou "especulativo", pois falha em proteger o capital contra contingências e não utiliza a variância (risco) como um filtro necessário para a sobrevivência patrimonial.

**Investidor Prudente:** É o agente racional e avesso ao risco que enxerga sua carteira não como uma lista de ativos isolados, mas como um "todo equilibrado". Ele utiliza a diversificação coesa, ou "diversificação correta pelas razões certas", que consiste em selecionar ativos de diferentes indústrias e naturezas que possuam baixa correlação ou covariância entre si. Ao combinar ativos que não se movem de forma idêntica, o investidor prudente consegue reduzir a variância total da carteira (risco diversificável) e busca posicionar-se na Fronteira Eficiente, obtendo o máximo retorno possível para um nível de risco que ele esteja disposto a suportar.

---

## Interação 3: Aplicação Prática da MPT para Iniciantes

### Prompt

> Explique, detalhadamente, como um novato no mundo dos investimentos pode adotar a MPT e montar a sua carteira baseando-se nos seus princípios, visando maior crescimento patrimonial ao longo dos anos.

### Resposta

Para um investidor iniciante, adotar a Moderna Teoria do Portfólio (MPT) significa mudar o foco de ativos individuais para a carteira como um "todo equilibrado". Elaborada por Harry Markowitz, essa teoria permite construir um portfólio que busca o maior retorno possível para um nível de risco que você esteja disposto a aceitar.

Abaixo, um passo a passo detalhado para aplicar esses princípios e buscar o crescimento patrimonial a longo prazo:

### 1. Entenda as Duas Etapas da Seleção de Carteira

Markowitz divide o processo em dois estágios fundamentais:

- **Primeiro estágio:** Começa com a observação e a experiência, nas quais você analisa o desempenho futuro provável das categorias de ativos disponíveis.
- **Segundo estágio:** Começa com crenças relevantes sobre esses desempenhos e termina com a escolha da combinação ideal de ativos.

### 2. Identifique seu Perfil e o Binômio Risco-Retorno

A MPT assume que você é um investidor avesso ao risco. Isso significa que, se houver duas carteiras com o mesmo retorno esperado, você deve preferir a menos arriscada. Para obter retornos maiores, você deve estar disposto a aceitar mais risco.

**Ação prática:** Defina seu nível de tolerância ao risco (perfil conservador, moderado ou arrojado). Isso determinará onde você se posicionará na "Fronteira Eficiente".

### 3. Aplique a "Diversificação Correta"

O erro comum do iniciante é concentrar tudo no ativo que "promete" render mais. Markowitz rejeita essa ideia porque ela ignora a incerteza.

- **Diversificação não é apenas ter muitos ativos:** É ter ativos que não sejam perfeitamente correlacionados. Ou seja, ativos que não se movam sempre na mesma direção ao mesmo tempo.
- **Diversifique entre indústrias:** Não basta ter 60 ações se todas forem do mesmo setor. Você deve diversificar entre indústrias com características econômicas diferentes, pois elas tendem a ter correlações mais baixas.
- **Redução do risco diversificável:** Ao combinar ativos com baixa correlação, você consegue reduzir o risco total da sua carteira sem necessariamente sacrificar o retorno.

### 4. Utilize os Fatores-Chave para a Montagem

Para montar a carteira, você precisa olhar para quatro fatores fundamentais:

- **Retorno esperado:** A média das possíveis rentabilidades futuras.
- **Risco (Desvio Padrão):** O quanto o retorno do ativo costuma oscilar.
- **Correlação:** Como um ativo se comporta em relação ao outro.
- **Peso de cada ativo:** A porcentagem do seu dinheiro em cada investimento.

### 5. Busque a Fronteira Eficiente

A Fronteira Eficiente é uma representação gráfica que mostra o conjunto de carteiras que oferecem a melhor rentabilidade para cada nível de volatilidade.

- **Otimização:** Através de cálculos (que hoje podem ser feitos por softwares ou simuladores), o investidor busca as combinações de ativos que maximizam a utilidade do investimento.
- **O "Portfólio Ótimo":** Para um novato, isso pode ser exemplificado pela escolha de uma combinação que inclua Renda Fixa (para estabilidade e menor risco) e Renda Variável/Ações (para potencializar o crescimento a longo prazo).

### 6. Proteção contra Contingências

Um portfólio bem fundamentado pela MPT não é apenas uma lista de ações boas, mas uma estrutura que proporciona proteções e oportunidades diante de diversas crises ou mudanças de mercado. Como o futuro não é conhecido com certeza, essa estrutura equilibrada é o que garante a sobrevivência e o crescimento do patrimônio ao longo dos anos.

---

## Interação 4: Aplicação Prática com Alocação de R$ 10.000,00

### Prompt

> Com princípios da MPT de Markowitz, defina de forma prática e simples, como um investidor pode aplicá-la, considerando o contexto atual do mercado de finanças e investimentos brasileiro e global; passo a passo informe qual porcentagem o investidor deve aplicar em cada classe de ativo, e qual o papel de cada uma delas dentro da carteira, considerando um aporte inicial fictício de: R$ 10.000,00.

### Resposta

Para um investidor com R$ 10.000,00, a aplicação da Moderna Teoria do Portfólio (MPT) de Markowitz consiste em não escolher ativos isoladamente, mas construir um "todo equilibrado" que maximize o retorno para o nível de risco que ele aceita suportar. No cenário brasileiro e global, isso significa diversificar entre diferentes classes de ativos que não se movam juntas (baixa correlação) para reduzir a volatilidade total.

Abaixo, um passo a passo prático para um perfil moderado, baseado no modelo de carteira otimizada presente nos documentos técnicos:

### Passo 1: Reserva de Segurança e Liquidez (20% | R$ 2.000,00)

- **Ativo:** Títulos de Renda Fixa Pós-fixados (ex.: Tesouro Selic ou CDBs de liquidez diária atrelados ao CDI).
- **Papel na Carteira:** Oferecer estabilidade e liquidez. Este montante serve como âncora em momentos de crise, garantindo que o investidor não precise resgatar ativos em queda.

### Passo 2: Proteção de Poder de Compra (40% | R$ 4.000,00)

- **Ativo:** Títulos Públicos Atrelados à Inflação (ex.: IPCA+ ou IMA-B) e Pré-fixados (ex.: IRF-M).
- **Papel na Carteira:** Proteger o patrimônio contra a inflação no longo prazo e aproveitar os ciclos de juros brasileiros. Na MPT, esses ativos equilibram a volatilidade das ações.

### Passo 3: Crescimento Patrimonial | Brasil (20% | R$ 2.000,00)

- **Ativo:** Ações brasileiras (ex.: Índice Ibovespa ou fundos de ações).
- **Papel na Carteira:** Potencializar o crescimento do capital. Embora tenham maior risco (volatilidade), a MPT demonstra que o risco de uma ação cai quando combinada com renda fixa.

### Passo 4: Estratégia Ativa e Diversificação (10% | R$ 1.000,00)

- **Ativo:** Fundos Multimercado.
- **Papel na Carteira:** Atuar como um redutor de correlação. Gestores desses fundos podem apostar em diferentes cenários (juros, moedas, bolsas), o que ajuda a suavizar as perdas quando a bolsa brasileira cai.

### Passo 5: Exposição Global e Moeda (10% | R$ 1.000,00)

- **Ativo:** Investimentos no Exterior (ex.: S&P 500 ou fundo de Dólar).
- **Papel na Carteira:** Proteção contra o risco-país. Ativos globais costumam ter correlação baixa ou negativa com o mercado brasileiro; quando o real se desvaloriza, esses ativos tendem a subir, protegendo o valor total da carteira em termos globais.

### Resumo da Alocação (R$ 10.000,00)

| Classe de Ativo | Porcentagem | Valor (R$) | Papel Principal |
|---|---|---|---|
| Pós-fixado (Liquidez) | 20% | R$ 2.000 | Segurança e Estabilidade |
| Inflação/Pré (Renda Fixa) | 40% | R$ 4.000 | Proteção do Poder de Compra |
| Ações (Brasil) | 20% | R$ 2.000 | Crescimento e Dividendos |
| Multimercados | 10% | R$ 1.000 | Gestão de Risco Ativa |
| Exterior/Dólar | 10% | R$ 1.000 | Proteção Cambial e Global |

**Dica de Markowitz:** O segredo não é a quantidade de ativos, mas o "tipo certo de diversificação". Evite ter apenas ativos do mesmo setor (ex.: apenas bancos), pois eles possuem alta correlação e caem juntos. Ao misturar indústrias e naturezas econômicas diferentes (como agro, energia e dólar), você reduz o risco diversificável sem necessariamente abrir mão do retorno.

---

## Interação 5: Explicação Didática da MPT (Persona: Professor Acadêmico)

### Prompt

> Aja como um professor de investimentos altamente qualificado e simpático, e prestigiado dentro da academia de finanças.
>
> Explique a teoria moderna de portfólio de Harry Markowitz (Nobel 1990), de forma simples e didática, em formato de tópicos, passando pelos seguintes pontos:
>
> - O que é um ativo?
> - No que consiste a MPT?
> - Qual a correlação dos ativos dentro de uma carteira?
> - Como montar uma carteira na prática, tendo um aporte inicial baixo e manter ao longo do tempo?

### Resposta

Olá! É um prazer enorme recebê-lo nesta aula. Como alguém que dedica a vida ao estudo das finanças, fico entusiasmado em ver novos investidores buscando fundamentação sólida. Hoje, vamos conversar sobre o trabalho de Harry Markowitz, que revolucionou o mercado em 1952 e foi laureado com o Prêmio Nobel em 1990.

Preparei uma explicação didática para que você compreenda como transformar sua visão sobre o dinheiro:

### 1. O que é um ativo?

No contexto da teoria financeira, um ativo é qualquer instrumento ou valor mobiliário (como ações de empresas ou títulos de dívida) que um investidor decide manter com a expectativa de obter um retorno futuro. Contudo, como o futuro não é conhecido com certeza, cada ativo carrega consigo uma dose de incerteza ou risco, o que significa que o retorno real pode ser diferente do esperado.

### 2. No que consiste a MPT (Moderna Teoria do Portfólio)?

A essência da MPT é que o investidor não deve olhar para um ativo isoladamente, mas sim para como ele contribui para a carteira como um todo. Os pontos fundamentais são:

- **Aversão ao Risco:** A teoria assume que os investidores são racionais e preferem o menor risco possível para um mesmo nível de retorno.
- **Binômio Risco-Retorno:** O risco é medido pela variância ou desvio padrão dos retornos; para buscar retornos maiores, é inevitável aceitar uma volatilidade maior.
- **Fronteira Eficiente:** É o conceito de que existe uma combinação "ótima" de ativos que oferece a maior rentabilidade para cada nível de risco que você esteja disposto a suportar.
- **O Todo Equilibrado:** Markowitz nos ensina que um bom portfólio é mais do que uma lista de bons ativos; é um conjunto que oferece proteção e oportunidades diante de diversas crises.

### 3. Qual a correlação dos ativos dentro de uma carteira?

A correlação é o "segredo" da diversificação eficiente. Ela mede como dois ativos se movem em relação um ao outro.

- **Redução de Risco:** Markowitz demonstrou que, ao combinar ativos que não possuem correlação perfeita (ou seja, que não caem ou sobem sempre juntos), você reduz o risco total da carteira sem necessariamente sacrificar o retorno.
- **Diversificação Correta:** Não basta ter muitos ativos; o ideal é diversificar entre indústrias e setores diferentes com características econômicas distintas, pois eles tendem a ter baixas correlações entre si.
- **Impacto Matemático:** Quanto menor a correlação entre os ativos, menor será o risco (variância) total do seu investimento.

### 4. Como montar uma carteira na prática (mesmo com pouco capital)?

Para você que está começando e quer manter sua estratégia ao longo do tempo, siga estes passos fundamentais:

- **Defina os Pesos (W):** Decida qual porcentagem do seu dinheiro irá para cada classe de ativo (ex.: 20% em ações, 80% em renda fixa).
- **Comece com Fundos de Índice (ETFs):** Uma aplicação prática do "Teorema dos Dois Fundos Mútuos" de Markowitz sugere que você pode atingir a eficiência combinando apenas dois grandes fundos diversificados que representem o mercado. Isso é excelente para quem tem um aporte inicial baixo.
- **Foque na Diversificação Industrial:** Evite concentrar tudo em um único setor (como apenas bancos). Procure ativos de naturezas diferentes, como empresas de consumo, energia e títulos públicos.
- **Manutenção e Disciplina:** A seleção de carteira começa com observação e experiência. Mantenha seus aportes constantes e reequilibre os pesos anualmente para garantir que sua carteira continue dentro da sua tolerância ao risco (seu *suitability*).

Lembre-se: investir com base na MPT é trocar a "especulação" por uma estrutura equilibrada e protegida. Bons estudos e ótimos investimentos!

# Resumos Estrturados Práticos: Teoria Moderna do Portfólio (MPT) de Harry Markowitz

## O que é a MPT

A Moderna Teoria do Portfólio, desenvolvida por Harry Markowitz (Nobel 1990), não trata de escolher os melhores ativos individuais. Ela ensina a construir a carteira como um **todo equilibrado**, onde a combinação entre os ativos importa mais do que cada um isoladamente.

O principio fundamental é que o investidor deve buscar o **maior retorno possível para o risco que esta disposto a aceitar**, e não o ativo que "mais promete".

---

## Os 4 conceitos essenciais

**1. Binômio Risco-Retorno**
Retorno maior exige aceitar risco maior. Não existe almoço grátis no mercado financeiro. O risco é medido pelo desvio padrão (volatilidade) dos retornos.

**2. Diversificação correta**
Não basta ter muitos ativos. É preciso ter ativos de **diferentes naturezas e setores** que não se movam juntos (baixa correlação). Quando um cai, o outro pode subir, equilibrando a carteira.

**3. Correlação entre ativos**
Esse é o segredo da MPT. Ativos com correlação baixa ou negativa entre si reduzem o risco total da carteira sem sacrificar o retorno esperado. Exemplo: ações brasileiras e renda fixa costumam ter correlação baixa.

**4. Fronteira Eficiente**
É o conjunto de carteiras "ótimas" que entregam a melhor rentabilidade possível para cada nível de risco. Qualquer carteira abaixo dessa linha é ineficiente: poderia render mais com o mesmo risco.

---

## O Investidor Prudente vs Insensato

A MPT distingue dois perfis:

- **Investidor insensato**: foca apenas no retorno esperado, ignora o risco, concentra tudo no ativo que "promete mais". Markowitz rejeita esse comportamento como especulativo.
- **Investidor prudente**: enxerga a carteira como um todo equilibrado, diversifica entre setores e classes com baixa correlação, e busca se posicionar na Fronteira Eficiente de acordo com sua tolerância ao risco.

---

## Como aplicar na prática (passo a passo para iniciantes)

**1. Defina seu perfil de risco**
Conservador (prioriza estabilidade), moderado (busca equilíbrio) ou arrojado (aceita volatilidade por mais retorno). Isso define onde você se posiciona na Fronteira Eficiente.

**2. Não escolha ativos isoladamente**
Em vez de perguntar "qual ação rendeu mais?", pergunte "como esse ativo se comporta em relação aos outros da minha carteira?".

**3. Combine classes de ativos distintas**
Misture renda fixa (Tesouro Selic, CDBs, títulos atrelados à inflação), renda variável (ações, FIIs, ETFs) e exposição internacional. Cada classe reage de forma diferente às crises.

**4. Atenção à correlação setorial**
Se todas as suas ações forem do mesmo setor (bancos, por exemplo), uma crise no setor derruba a carteira inteira. Diversifique entre indústrias com características econômicas diferentes.

**5. Reequilibre periodicamente**
Os pesos dos ativos mudam com o tempo. Rebalancear anualmente garante que a carteira continue dentro do seu perfil de risco.

---

## Exemplo de alocação prática (perfil moderado, R$ 10.000)

Aqui está uma sugestão de carteira otimizada baseada nos princípios da MPT:

| Classe | % | Função na carteira |
|--------|---|---|
| Pós-fixado (Tesouro Selic / CDB) | 20% | Segurança e liquidez para emergências |
| Inflação + Pré-fixados (IPCA+) | 40% | Proteção do poder de compra no longo prazo |
| Ações Brasil (Ibovespa / ETFs) | 20% | Crescimento patrimonial |
| Multimercados | 10% | Gestão ativa para reduzir correlação |
| Exterior (S&P 500 / Dólar) | 10% | Proteção cambial e diversificação global |

O segredo não está na quantidade de ativos, mas no **tipo certo de diversificação**. Misturar naturezas econômicas diferentes reduz o risco sem abrir mão do retorno.

---

## Conclusão prática

A MPT de Markowitz troca a especulação por uma estrutura protegida. O investidor iniciante não precisa dominar fórmulas matemáticas complexas para aplicá-la: basta entender que uma carteira bem diversificada entre classes de baixa correlação é mais importante do que acertar o "próximo ativo que vai subir". Invista com disciplina, mantenha aportes constantes e reequilibre anualmente.

---

## Glossário: Conceitos da MPT para Investidores Iniciantes

| Termo | Explicação Simples |
|---|---|
| **Moderna Teoria do Portfólio (MPT)** | Teoria criada por Harry Markowitz que ensina a montar uma carteira como um todo equilibrado, buscando o maior retorno possível para o risco que você aceita correr. Não é escolher os melhores ativos isoladamente, e sim a melhor combinação entre eles. |
| **Harry Markowitz** | Economista que publicou essa teoria em 1952 e recebeu o Prêmio Nobel de Economia em 1990 por ela. Mostrou matematicamente que diversificar reduz o risco da carteira. |
| **Todo Equilibrado** | Ideia central da teoria: uma carteira boa não é apenas uma lista de bons ativos, mas um conjunto que oferece proteção e oportunidades em diversos cenários de mercado. |
| **Risco e Retorno** | Princípio de que não existe almoço grátis: para buscar retornos maiores, você precisa aceitar mais risco. Entre dois investimentos com o mesmo retorno, o investidor racional escolhe o menos arriscado. |
| **Aversão ao Risco** | Premissa de que investidores racionais preferem o menor risco possível. Se duas carteiras rendem o mesmo, você escolhe a que oscila menos. É o que justifica toda a diversificação. |
| **Retorno Esperado** | A média das rentabilidades que você espera obter no futuro com um ativo ou com a carteira inteira. Não é garantia, é uma estimativa baseada em dados históricos e crenças sobre o futuro. |
| **Risco (Volatilidade)** | O quanto o retorno do seu investimento costuma oscilar. Quanto mais oscila, maior o risco. Na MPT, o que importa é o risco da carteira inteira, não de cada ativo separado. |
| **Correlação** | Mede como dois ativos se movem juntos. É o segredo da diversificação: quanto menor a correlação entre os ativos da sua carteira, mais você reduz o risco total sem necessariamente sacrificar o retorno. Se tudo cai junto, não há proteção. |
| **Diversificação Correta** | Não é ter muitos ativos, mas ter ativos de setores e naturezas diferentes que não se movem juntos. Markowitz alerta: 60 ações do mesmo setor são menos diversificadas que poucas ações de setores distintos. |
| **Fronteira Eficiente** | Conjunto de carteiras que oferecem a melhor rentabilidade possível para cada nível de risco. Qualquer carteira abaixo dessa linha é ineficiente, pois poderia render mais com o mesmo risco. |
| **Portfólio Ótimo** | A carteira específica na fronteira eficiente que combina com o seu perfil. Se você é conservador, fica na parte de menor risco; se é arrojado, aceita mais volatilidade por mais retorno. |
| **Peso do Ativo** | A porcentagem do seu dinheiro que vai para cada investimento. Os pesos somam 100%. Definir os pesos certos é o objetivo central da montagem da carteira. |
| **Investidor Prudente** | Investidor racional que enxerga a carteira como um todo equilibrado, diversifica entre setores com baixa correlação e busca se posicionar na fronteira eficiente de acordo com sua tolerância ao risco. |
| **Investidor Insensato** | Aquele que foca apenas no retorno esperado, ignora o risco e concentra tudo no ativo que promete render mais. Markowitz rejeita esse comportamento como especulativo e irracional. |
| **Duas Etapas da Seleção** | Markowitz divide o processo em dois estágios: primeiro, você observa e forma crenças sobre o futuro dos ativos; segundo, com base nessas crenças, escolhe a combinação ideal. A MPT foca no segundo estágio. |
| **Teorema dos Dois Fundos** | Resultado prático da teoria: você pode atingir eficiência combinando apenas dois fundos diversificados. Excelente para quem tem pouco capital e quer começar sem complicar. |
| **Risco Diversificável** | Parte do risco que você consegue reduzir ou eliminar diversificando a carteira. Está ligado a fatores específicos de cada ativo ou setor. Quanto mais ativos de baixa correlação você adiciona, mais esse risco diminui. |
| **Ativo** | Qualquer instrumento que você mantém esperando retorno futuro: ações, títulos públicos, CDBs, fundos. Cada um carrega incerteza, pois o retorno real pode diferir do esperado. |
| **Perfil de Risco** | Seu nível de tolerância à volatilidade: conservador (prioriza estabilidade), moderado (busca equilíbrio) ou arrojado (aceita oscilar mais por retornos maiores). Define onde você se posiciona na fronteira eficiente. |
| **Reequilíbrio** | Prática de ajustar os pesos da carteira periodicamente para mantê-la dentro do seu perfil de risco. Com o tempo, alguns ativos crescem mais que outros e desequilibram a alocação original. |

---

## Conjunto de prompts reutilizáveis

### Prompt 1: Resumo Didático em Três Blocos
> Aja como um professor de finanças didático. Com base nas fontes deste caderno, explique a Moderna Teoria do Portfólio (MPT) de Harry Markowitz em três blocos: (i) o problema que ela resolve, (ii) os conceitos de risco, retorno e correlação, e (iii) como um investidor iniciante pode aplicá-la. Em cada bloco, use uma analogia do dia a dia antes da explicação técnica. Ao final, liste 5 palavras-chave que eu devo memorizar.

---

### Prompt 2: Quiz de Fixação com 10 Questões
> Com base nas fontes deste caderno, crie um quiz de 10 questões de múltipla escolha sobre a MPT, cobrindo: diversificação, fronteira eficiente, correlação, perfil de risco, investidor prudente vs. insensato e as duas etapas da seleção de carteira. Indique a resposta correta de cada questão com uma justificativa de no máximo duas linhas extraída das fontes.

---

### Prompt 3: Comparação Prudente vs. Insensato em Tabela
> Compare e contraste os conceitos de "investidor prudente" e "investidor insensato" segundo Markowitz, usando uma tabela de duas colunas. Para cada critério de comparação (objetivo, atitude em relação ao risco, estratégia de alocação, resultado esperado e comportamento diante de crises), apresente o que cada perfil faz e por que a MPT aprova ou rejeita essa conduta. Cite as fontes usadas.

---

### Prompt 4: Estudo de Caso Prático com R$ 10.000
> Com base nas fontes, simule um estudo de caso prático: um investidor iniciante com R$ 10.000,00 e perfil moderado quer montar uma carteira seguindo a MPT. Descreva passo a passo: (i) como definir a alocação entre classes de ativos, (ii) quais classes escolher e porcentagens, (iii) qual o papel de cada classe na redução de risco via correlação, e (iv) como e quando reequilibrar a carteira. Justifique cada decisão com os princípios da MPT.

---

### Prompt 5: Mapa Mental Textual e Teste de Retenção
> Aja como um revisor de estudos. Com base nas fontes deste caderno, gere um resumo estruturado em mapa mental textual com os tópicos: fundamentos da MPT, binômio risco-retorno, diversificação e correlação, fronteira eficiente, perfis de investidor e aplicação prática. Para cada tópico, liste de 3 a 5 pontos essenciais em uma frase cada. Ao final, sugira 3 perguntas que eu deveria ser capaz de responder sem consultar o material, como teste de retenção.

> Aja como um revisor de estudos. Com base nas fontes deste caderno, gere um resumo estruturado em mapa mental textual com os tópicos: fundamentos da MPT, binômio risco-retorno, diversificação e correlação, fronteira eficiente, perfis de investidor e aplicação prática. Para cada tópico, liste de 3 a 5 pontos essenciais em uma frase cada. Ao final, sugira 3 perguntas que eu deveria ser capaz de responder sem consultar o material, como teste de retenção.


