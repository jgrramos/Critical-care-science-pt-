> ⚠️ **TRADUÇÃO NÃO OFICIAL.** Texto traduzido automaticamente por inteligência artificial (Claude, Anthropic). Não foi revisado nem endossado pela revista *Critical Care Science*, pelos autores do artigo ou pelo autor deste repositório. Podem existir erros de tradução. **Em caso de dúvida, consulte sempre a versão original em inglês.**

# Plano de análise estatística de um ensaio clínico randomizado em cluster com delineamento stepped-wedge para avaliar o impacto clínico de diferentes práticas de telemedicina em unidades de terapia intensiva – ensaio TELESCOPE 2

*Título original: Statistical analysis plan for a stepped-wedge cluster randomized clinical trial for the evaluation of the clinical impact of different telemedicine practices in intensive care units – TELESCOPE 2 trial*

| | |
|---|---|
| **Autores** | Tiago Mendonça dos Santos, Renato Carneiro de Freitas Chaves, Bruna Gomes Barbeiro, Maura Cristina dos Santos, Thiago Domingos Corrêa, Alexandre Biasi Cavalcanti, Ary Neto Serpa, Carlos Henrique Sartorato Pedrotti, Fernando Godinho Zampieri, Guilherme de Paula Pinto Schettino, Jorge Ibrain Figueira Salluh, Leandro Utino Taniguchi, Leonardo José Rolim Ferraz, Luciano Cesar Pontes Azevedo, Otávio Berwanger, Regis Goulart Rosa, Renata Albaladejo Morbeck, Rodrigo Santos Biondi, Suzana Margareth Lobo, Jessica Kasza, Adriano José Pereira, Otavio Ranzani |
| **Revista** | Critical Care Science, 2026;38:e20260013 |
| **Tipo de artigo** | Plano de análise estatística (*Statistical Analysis Plan*; rotulado na página da revista como *Clinical Report*) |
| **Data de publicação** | 08/10/2026 |
| **DOI** | [10.62675/2965-2774.20260013](https://doi.org/10.62675/2965-2774.20260013) |
| **Artigo original** | [https://criticalcarescience.org/article/statistical-analysis-plan-for-a-stepped-wedge-cluster-randomized-clinical-trial-for-the-evaluation-of-the-clinical-impact-of-different-telemedicine-practices-in-intensive-care-units-telescop/](https://criticalcarescience.org/article/statistical-analysis-plan-for-a-stepped-wedge-cluster-randomized-clinical-trial-for-the-evaluation-of-the-clinical-impact-of-different-telemedicine-practices-in-intensive-care-units-telescop/) |
| **Licença do original** | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

**Atribuição:** tradução de obra licenciada sob CC BY 4.0. Os direitos do texto original pertencem aos autores e à revista *Critical Care Science*. Foram feitas alterações (tradução para o português). Fonte: site da revista.

**Nota do tradutor:** (1) A ordem dos nomes dos autores foi reconstituída a partir do XML (formato Nome Sobrenome); o autor "Ary Neto Serpa" consta no XML com sobrenome "Serpa" e prenomes "Ary Neto" (nas referências do próprio artigo aparece como "Serpa Neto"), e foi mantido conforme o XML. (2) A tabela foi reconstruída em Markdown a partir das linhas do XML. (3) A equação do modelo, que não consta no texto extraído, foi reconstruída em texto simples a partir do MathML do XML. (4) Os erros e as imprecisões do original (por exemplo, "TELESCOPE-I", "TELESCOPE 2" e "TELESCOPE-2" usados alternadamente; "SAPS3" e "SAPS 3"; "ɣ" usado tanto para o log do tempo de internação quanto para o efeito aleatório do tempo dentro do cluster; versão do R 4.2.2 e "4.3.3 ou posterior") foram mantidos. (5) O original não traz subtítulos para as seções de ética, registro, financiamento e contribuições; os rótulos correspondentes foram acrescentados na tradução. (6) A seção de palavras-chave do original apresenta-se vazia no XML; as palavras-chave foram obtidas dos metadados do artigo. (7) As funções de cada autor foram reconstituídas a partir dos metadados do XML (taxonomia CRediT). (8) O Material Suplementar não está incluído nesta tradução.

---

## RESUMO

**Contexto:** O modelo ideal para a oferta de Tele-UTI ainda não está definido. No ensaio TELE-critical Care verSus usual Care on ICU Performance (TELESCOPE), a implementação de rounds multidisciplinares diários liderados por médicos não mostrou evidência de melhora dos desfechos clínicos. O ensaio TELESCOPE 2 foi, portanto, concebido para avaliar se a ampliação desse modelo, de modo a incluir um pacote de cuidados multidisciplinar estruturado, juntamente com uma estrutura formalizada de gestão de qualidade e segurança, traduziria as melhorias de processo em benefícios mensuráveis nos desfechos centrados no paciente.

**Objetivo:** Avaliar se uma intervenção estruturada de Tele-UTI, composta por rounds multidisciplinares diários liderados por intensivistas, um pacote de cuidados multidisciplinar (enfermagem, fisioterapia, farmácia) e um pacote de gestão de qualidade e segurança, pode reduzir o tempo de internação em unidade de terapia intensiva em unidades de terapia intensiva públicas brasileiras.

**Métodos:** O TELESCOPE 2 é um ensaio multicêntrico, aberto, randomizado em cluster com delineamento stepped-wedge, que inclui 25 unidades de terapia intensiva no Brasil, de janeiro de 2024 a janeiro de 2026. As unidades de terapia intensiva são randomizadas em cinco sequências, recebendo a intervenção em momentos escalonados. Todos os pacientes adultos admitidos nas unidades participantes são elegíveis, exceto aqueles admitidos por razões não médicas ou previamente incluídos no estudo. A intervenção multifacetada de telemedicina compreende: i) rounds multidisciplinares diários liderados por intensivistas com título de especialista; ii) cuidado coordenado por uma equipe multidisciplinar; e iii) uma estratégia de gestão focada na melhoria da qualidade e na segurança do paciente. O desfecho primário é o tempo de internação em unidade de terapia intensiva. Os desfechos secundários incluem desfechos clínicos (mortalidade, dias livres de ventilação mecânica em 28 dias e eventos associados à ventilação mecânica), indicadores de processo de cuidado (mobilização, elevação da cabeceira e manejo da sedação) e desfechos organizacionais em nível de unidade.

**Conclusão:** Descrevemos o plano de análise estatística do ensaio TELESCOPE 2, finalizado antes do bloqueio do banco de dados. Essa abordagem pré-especificada mitiga o viés de análise e garante a transparência e a robustez dos resultados relatados.

**Palavras-chave:** Telemedicina; Cuidados críticos; Unidades de terapia intensiva; Melhoria da qualidade; Desfechos clínicos

## INTRODUÇÃO

A unidade de terapia intensiva (UTI) com telemedicina (Tele-UTI) é um modelo de cuidado habilitado por tecnologia que permite que intensivistas apoiem remotamente as equipes à beira do leito. Essa abordagem ganhou força como resposta à distribuição desigual de intensivistas e ao acesso limitado a cuidados críticos em regiões carentes do Brasil, como em vários outros países [1].

Intervenções de Tele-UTI, como rounds multidisciplinares diários (DMR) remotos, apoio clínico em tempo real e monitoramento de desempenho, foram associadas à melhora do cuidado ao paciente, incluindo redução da mortalidade na UTI, menor tempo de internação hospitalar (LOS) e respostas mais rápidas aos alarmes. No entanto, o melhor modelo de oferta de Tele-UTI é incerto [1].

Os dois ensaios clínicos randomizados (os ensaios ERIC e TELESCOPE-I) [2,3] voltados a ambientes de UTI não mostraram melhoras diretas nos desfechos clínicos, embora tenham observado melhoras em determinados processos de cuidado [2]. No ensaio ERIC, um programa de melhoria da qualidade por telemedicina aumentou significativamente a adesão a métricas de desempenho predefinidas no cuidado agudo em UTI em hospitais da região metropolitana de Berlim [2]. Em contrapartida, o ensaio TELESCOPE-I não observou melhoras comparáveis nos indicadores de processo, e os DMR por telemedicina liderados por um intensivista com título de especialista não reduziram o LOS na UTI entre adultos criticamente enfermos [3].

Uma das possíveis razões para a ausência de sucesso em demonstrar benefício nos desfechos clínicos foi o modelo de oferta, isto é, centrado no intensivista, sem considerar especificamente a equipe clínica multidisciplinar e os fatores organizacionais. A Tele-UTI é, por natureza, uma intervenção complexa, e tanto o seu modelo de oferta quanto a variedade e as competências dos profissionais envolvidos são provavelmente determinantes críticos de sua efetividade e de sua capacidade de traduzir melhorias de processo em desfechos significativos centrados no paciente. Embora a viabilidade e os benefícios da Tele-UTI estejam bem documentados, as evidências permanecem limitadas quanto ao impacto de diferentes modelos de oferta, como a integração da telemedicina com o cuidado multidisciplinar e com estratégias de gestão da qualidade.

O estudo TELESCOPE-2 tem como objetivo avaliar se uma intervenção estruturada de telemedicina, composta por DMR liderados por um intensivista, um pacote de cuidados multidisciplinar (enfermagem, fisioterapia, farmácia) e um pacote de gestão de qualidade e segurança, pode reduzir o LOS na UTI em UTIs públicas brasileiras.

## MÉTODOS

### Delineamento do estudo

O estudo TELESCOPE-2 é um ensaio controlado randomizado em cluster com delineamento stepped-wedge, aberto, nacional e multicêntrico. A unidade de randomização é a UTI, pois a intervenção tem como alvo toda a equipe multidisciplinar. Randomizaremos 25 UTIs em cinco sequências (Figura 1). O Material Suplementar fornece uma lista completa dos centros participantes e dos membros dos comitês do ensaio.

**Figura 1.** Diagrama esquemático que ilustra a linha do tempo do ensaio. Cinco unidades de terapia intensiva são randomizadas para cada sequência. *(A figura está disponível no artigo original.)*

Cada sequência inclui um período de controle sem intervenção, seguido da implementação escalonada da intervenção de acordo com a sequência atribuída. Dada a complexidade do pacote de intervenção, prevemos um atraso para que se atinja o efeito pleno do pacote. Portanto, todas as sequências incluem um período de transição durante o qual a implementação da intervenção será iniciada, mas os dados coletados durante o período de transição serão excluídos da análise primária. Todas as UTIs acabarão recebendo o pacote de intervenção completo em momentos diferentes, o que permite comparações tanto dentro das sequências quanto entre elas.

### Randomização e alocação

Os centros serão randomizados em cinco sequências por meio de uma abordagem estratificada. A randomização usará dados preliminares dos primeiros 2 meses do período basal. O primeiro período basal consistirá em 3 meses; no entanto, o terceiro mês será designado para a preparação organizacional e a divulgação da alocação da primeira sequência.

A estratificação será baseada em duas variáveis: região geográfica e LOS na UTI.

Região (Figura 2)

**Figura 2.** Agrupamento regional dos estados brasileiros para fins de randomização. *(A figura está disponível no artigo original.)*

Sul: centros localizados nas regiões Sul e Sudeste.

Norte: centros localizados nas regiões Centro-Oeste, Norte e Nordeste.

LOS na UTI:

Abaixo: centros cuja mediana de LOS na UTI é inferior à mediana de sua respectiva região.

Acima: centros cuja mediana de LOS na UTI é superior à mediana de sua respectiva região.

Essa estratificação, que gera quatro estratos, foi adotada para aumentar o equilíbrio entre as sequências, pois a região geográfica no Brasil está associada a diversas características estruturais e relacionadas à assistência à saúde [3,4]. O estrato que combina a região Sul e LOS abaixo da mediana incluiu sete centros, enquanto os outros três estratos incluíram seis centros cada.

Todas as 25 UTIs serão randomizadas simultaneamente por meio de uma lista de alocação gerada por computador, preparada por um estatístico independente. A randomização será restrita a um subconjunto de sequências para garantir o equilíbrio regional e um equilíbrio aproximado do LOS basal na UTI entre as sequências (e dentro dos estratos), de modo a levar em conta o número desigual de centros por estrato. Especificamente, as sequências 1, 3 e 5 serão construídas de modo a incluir um centro adicional da região Sul, enquanto as sequências 2 e 4 incluirão um centro adicional da região Norte. A Tabela 1 detalha a distribuição exata dos centros pelos quatro estratos (região e LOS na UTI) para cada sequência. Excluiremos as alocações candidatas que não atendam às restrições de região e de LOS basal e selecionaremos uma alocação, de forma uniformemente aleatória, entre as alocações elegíveis. Essa randomização restrita preservará o equilíbrio global, mantendo a natureza probabilística da alocação [5].

**Tabela 1.** Distribuição dos centros por sequência de acordo com as variáveis de estratificação (região e tempo de internação na unidade de terapia intensiva)

| Sequência | Norte/LOS abaixo da mediana | Norte/LOS acima da mediana | Sul/LOS abaixo da mediana | Sul/LOS acima da mediana | Total de centros |
|---|---|---|---|---|---|
| 1 | 1 | 1 | 2 | 1 | 5 |
| 2 | 1 | 2 | 1 | 1 | 5 |
| 3 | 1 | 1 | 1 | 2 | 5 |
| 4 | 2 | 1 | 1 | 1 | 5 |
| 5 | 1 | 1 | 2 | 1 | 5 |
| Total | 6 | 6 | 7 | 6 | 25 |

LOS: tempo de internação; UTI: unidade de terapia intensiva.

O sigilo da alocação será assegurado restringindo o acesso à sequência de randomização ao estatístico, que terá acesso apenas aos códigos de identificação das UTIs e permanecerá cego quanto à identidade das unidades. A lista de alocação será então fornecida ao coordenador do estudo, que divulgará a designação de cada centro 30 dias antes da fase de transição, para permitir a preparação organizacional.

A randomização será realizada no R (versão 4.2.2) [6]. As análises primárias serão ajustadas para a região e para a categoria de LOS basal, reconhecendo, assim, a randomização restrita.

### Cálculo do tamanho amostral

Determinamos o tamanho amostral necessário por meio da simulação de um modelo de efeitos mistos para o LOS na UTI, com mil replicações por cenário e a correção de Kenward-Roger [7]. O modelo usou a transformação pelo logaritmo natural do LOS na UTI como desfecho, para lidar com a distribuição assimétrica à direita, e incluiu efeitos fixos para o intercepto (2,079), uma tendência temporal (-0,012, isto é, uma redução do log-LOS de 0,012 unidade por mês) e o efeito da intervenção (-0,148), correspondente a uma redução de 13,75% a partir de uma média basal de 8 dias (isto é, uma redução de 1,1 dia). Os efeitos aleatórios foram caracterizados por: variabilidade em nível de cluster seguindo uma distribuição normal com variância de 0,102; um efeito de período dentro do cluster seguindo uma distribuição normal com variância de 0,019; e um erro residual em nível individual seguindo uma distribuição normal com variância de 1,090. Esses valores resultam em um coeficiente de correlação intraclasse (ICC) estimado de 0,10 e em um coeficiente de autocorrelação do cluster (CAC) de 0,84. Essas estimativas empíricas foram derivadas do estudo TELESCOPE-I [3]. Com base nessas simulações, é necessário um tamanho amostral total entre 18.750 e 25.000 pacientes para atingir um poder de pelo menos 95% com nível de significância bilateral de 5%. Essa faixa reflete uma taxa mensal esperada de recrutamento de 30 a 40 pacientes por UTI.

Como a retirada de centros é uma contingência possível em estudos multicêntricos, avaliamos a robustez do delineamento em dois cenários: a retirada de três centros da primeira sequência e a retirada de três centros da última sequência. Em um cenário conservador, com 30 pacientes por UTI por período e a retirada de três centros de qualquer sequência, o poder permanece de pelo menos 93%.

### Análise interina

Como nossa intervenção incorpora as melhores evidências disponíveis para o cuidado de pacientes criticamente enfermos em UTIs e não se prevê nenhum risco inerente à execução do ensaio, não planejamos análises interinas. Como resultado, consideramos desnecessário um comitê formal de monitoramento de dados.

Critérios de elegibilidade: as UTIs públicas e filantrópicas selecionadas foram convidadas, por comunicação eletrônica, a participar de uma entrevista para avaliar os critérios de inclusão e exclusão, por meio de um questionário eletrônico de avaliação de viabilidade. Todos os pacientes admitidos nas UTIs incluídas serão elegíveis para inclusão no estudo. Os critérios de inclusão e exclusão, tanto para as UTIs quanto para os pacientes elegíveis, são detalhados a seguir.

Critérios de inclusão para as UTIs: hospitais públicos ou filantrópicos com 7 a 20 leitos; disponibilidade de médicos e enfermeiros 24 horas por dia e de um fisioterapeuta por pelo menos 18 horas por dia.

Critérios de exclusão para as UTIs: (i) UTIs com round multidisciplinar estruturado, definido como reuniões (DMR) ≥ 3 vezes por semana, em dias úteis, conduzidas por um intensivista com título de especialista e documentadas no prontuário, com duração fixa da visita (> 5 minutos/paciente), com uso de alguma ferramenta de apoio (*checklist* ou formulário padronizado), orientadas por metas, baseadas em protocolos estabelecidos, incluindo todos os pacientes admitidos na UTI; ou (ii) UTIs com gestão mensal de indicadores implementada (auditoria e *feedback*) com planejamento específico; ou (iii) unidades de terapia intensiva coronariana ou cardíaca, ou outras unidades especializadas (por exemplo, neurológicas ou de queimados); ou (iv) unidades semi-intensivas ou de cuidados intermediários; ou (v) UTIs sem disponibilidade de terapia renal substitutiva; ou (vi) UTIs cujos coordenadores sejam intensivistas com título de especialista e tenham qualificação de Master of Business Administration (ou equivalente).

Critérios de inclusão dos pacientes: adultos (≥ 18 anos).

Critérios de exclusão dos pacientes: admissões por razões não médicas (por exemplo, judiciais) e pacientes previamente incluídos no estudo Telescope 2.

### Desfechos

O período de acompanhamento para definir todos os desfechos será truncado em 90 dias a partir da admissão na UTI.

#### Desfecho primário

O desfecho primário deste ensaio em nível do paciente é o LOS na UTI, definido como o intervalo de tempo, em horas, entre a admissão na UTI e o momento da alta da UTI (isto é, transferência para outra instituição de cuidados ou hospital) ou do óbito na UTI, conforme a data e a hora do sistema do hospital. A data e a hora serão inseridas pelo profissional de saúde responsável pela coleta de dados. O LOS na UTI será derivado em períodos de 24 horas com casas decimais, conforme recomendado [8].

#### Desfechos secundários

Mortalidade na UTI, definida como óbito por qualquer causa durante a internação índice na UTI [3].

Mortalidade hospitalar, definida como óbito por qualquer causa durante a internação hospitalar índice [3].

Dias livres de ventilação mecânica nos primeiros 28 dias, definidos como o número de dias vivo e livre de ventilação mecânica por pelo menos 24 horas consecutivas, desde o desmame bem-sucedido até o dia 28. Pacientes que morrerem antes do desmame serão considerados como tendo zero dias livres de ventilação mecânica, e pacientes que receberem alta hospitalar antes de 28 dias serão considerados vivos e livres de ventilação mecânica aos 28 dias [3].

Readmissão na UTI em até 48 horas [3,9].

Reintubação precoce (< 48 horas após extubação eletiva) [3].

Eventos associados à ventilação mecânica: definidos como um aumento da pressão expiratória final positiva (PEEP) mínima diária de ≥ 3cmH2O sustentado por pelo menos dois dias consecutivos do calendário, após um período de pelo menos 2 dias de PEEP estável ou decrescente, ou um aumento da fração inspirada de oxigênio (FiO2) de ≥ 20 pontos percentuais sustentado por pelo menos dois dias consecutivos, após um mínimo de 2 dias de níveis estáveis ou decrescentes de FiO2 [10].

Taxa de extubação acidental [3].

#### Indicadores de processo de cuidado e de qualidade

Densidade de mobilização do paciente na UTI: definida como o número de dias em que o paciente é submetido a qualquer forma de mobilização, incluindo movimentação passiva dos membros superiores ou inferiores no leito, sentar na beira da cama ou em uma poltrona, ou caminhar [2,11,12].

Adesão à manutenção da elevação da cabeceira (30°- 45°) [3,11].

Prevenção adequada de tromboembolismo venoso [11,13].

Taxa de pacientes-dia sob sedação adequada (definida por Escala de Agitação e Sedação de Richmond [RASS] = -3 a +1) [11,14].

Taxa de pacientes-dia com nutrição oral ou enteral [2,11].

Taxa de pacientes com controle glicêmico adequado (definido como glicemia entre 70 e 180mg/dL) [3,11,13].

Taxa de pacientes-dia em normoxemia (definida como saturação periférica de oxigênio = 92 a 96%) [3].

Taxa de uso de cateter venoso central [3,11].

Tempo de permanência do cateter venoso central [3,11].

Taxa de uso de cateter urinário de demora [3,11].

Tempo de permanência do cateter urinário de demora [3,11].

#### Desfechos organizacionais em nível de unidade

–Classificação da UTI por uso padronizado de recursos (SRU) e taxa de mortalidade padronizada (SMR): definida pela SRU e pela SMR [13]. O uso padronizado de recursos reflete a razão entre a taxa observada e a esperada de utilização de recursos, estimada como o LOS na UTI dos pacientes sobreviventes e ajustada para a gravidade da doença do paciente. A taxa de mortalidade padronizada reflete a razão entre a taxa observada e a esperada de óbitos hospitalares, de acordo com o *Simplified Acute Physiology Score* (SAPS 3). Os perfis combinam a SMR (acima ou abaixo da mediana) e a SRU (acima ou abaixo da mediana). Cada unidade será atribuída a um de quatro grupos: "mais eficiente" (SMR e SRU abaixo da mediana); "menos eficiente" (SMR e SRU acima da mediana); "de alto desempenho" (*overachieving*; SMR baixa, SRU alta); "de baixo desempenho" (*underachieving*; SMR alta, SRU baixa) [15].

### Princípios estatísticos

Todos os testes estatísticos serão bilaterais, e todas as análises usarão um nível de significância de 5%. As análises primárias seguirão o princípio da intenção de tratar, com os pacientes analisados de acordo com a UTI à qual foram randomizados, independentemente da exposição à intervenção (isto é, considerar-se-á que as UTIs passaram para a intervenção no momento programado). Relataremos os achados seguindo os padrões estabelecidos pela extensão do CONSORT para ensaios stepped-wedge [16].

As análises serão conduzidas no R (versão 4.3.3 ou posterior; Viena, Áustria). Os modelos de efeitos mistos (descritos a seguir) serão ajustados principalmente com o pacote lme4 [17]. Para desfechos contínuos, devido ao número reduzido de clusters, será aplicada a correção de Kenward-Roger para pequenas amostras. Os desfechos secundários pré-especificados e as análises de subgrupos não serão ajustados para comparações múltiplas e serão considerados exploratórios.

Será realizada imputação múltipla se os dados faltantes em variáveis centrais excederem 10%, seguindo procedimentos padrão com equações encadeadas por meio do pacote mice [18].

### Análise do desfecho primário

Analisaremos o desfecho primário, o LOS na UTI, por meio de um modelo linear de efeitos mistos sobre o logaritmo natural do LOS na UTI (dias). Essa transformação lida com a distribuição tipicamente assimétrica à direita do LOS. O modelo incluirá efeitos fixos e aleatórios para levar em conta a estrutura hierárquica do delineamento stepped-wedge, as variáveis de randomização estratificada e o escore SAPS 3 em nível do paciente.

Formalmente, o modelo é definido como:

```
ɣ_kti = β0 + β1·X1_kt + β2·X2_k + β3·X3_k + β4t·T_t + β5·SAPS3_kti + α_k + ɣ_tk + ε_kti
```

Onde:

ɣkti: LOS na UTI transformado em logaritmo para o paciente i no período t no cluster k.

β0: intercepto fixo (log-LOS esperado na linha de base).

β1: efeito fixo da intervenção.

X1kt: indicador de intervenção para o cluster k no tempo t, definido como um para intervenção e zero para controle.

β2: efeito fixo da variável de estratificação região do Brasil.

X2k: localização regional do cluster k, definida como zero para centros da região Norte e um para centros da região Sul.

β3: efeito fixo da variável de estratificação categoria de LOS na UTI.

X3k: categoria de LOS basal na UTI para o cluster k, definida como 0 para abaixo da mediana e 1 para acima da mediana dentro da região.

β4t: efeito fixo do tempo calendário.

Tt: fator para o mês.

β5: efeito fixo do SAPS 3.

SAPS3kti: SAPS 3 para o paciente i no período t e no cluster k.

αk ~ N (0,σα2): intercepto aleatório para o cluster k (UTI), que captura a variabilidade entre clusters.

ɣtk ~ N (0,σγ2): efeito aleatório do tempo dentro do cluster, que leva em conta a correlação temporal dentro do cluster.

εkti ~ N (0,σε2): erro residual em nível individual.

Esse modelo leva em conta o agrupamento e as medidas repetidas dentro de cada UTI e permite estimar o efeito da intervenção ao mesmo tempo em que ajusta para as tendências temporais e para a variabilidade entre clusters.

### Análise dos desfechos secundários, de processo de cuidado e organizacionais em nível de unidade

Analisaremos os desfechos secundários e exploratórios contínuos usando a mesma estrutura de modelagem de efeitos mistos do desfecho primário, incluindo os mesmos efeitos fixos e aleatórios. Os desfechos de contagem e de taxa serão analisados por meio de modelos lineares generalizados mistos com distribuição de Poisson ou binomial negativa, conforme apropriado, incorporando a mesma estrutura de efeitos fixos e aleatórios do modelo primário.

Analisaremos os desfechos binários por meio de modelos lineares generalizados mistos com função de ligação logit, incorporando o mesmo conjunto de variáveis independentes do modelo primário. Esses modelos levarão em conta o agrupamento em nível de UTI e as medidas repetidas ao longo do tempo.

Para desfechos categóricos com mais de duas categorias, ajustaremos modelos logísticos multinomiais de efeitos mistos com interceptos aleatórios de UTI em nível de cluster (UTI). Usaremos a mesma estrutura de covariáveis do modelo do desfecho primário. Esses modelos permitirão estimar razões de chances específicas por categoria, levando em conta a estrutura hierárquica dos dados.

### Análise de sensibilidade para o desfecho primário

Avaliaremos a robustez da análise primária em relação a escolhas alternativas de modelagem e a pressupostos do delineamento, da seguinte forma:

Ajustes de covariáveis: repetiremos a análise primária ajustando adicionalmente para as seguintes covariáveis: tipo de admissão na UTI (três categorias: clínica, cirúrgica eletiva, cirúrgica não planejada), ventilação mecânica invasiva na admissão na UTI (duas categorias: sim, não), número de leitos de UTI na linha de base (termo contínuo) e desempenho da UTI na linha de base (quatro categorias: mais eficiente, menos eficiente, de alto desempenho, de baixo desempenho). Para as covariáveis basais, definiremos a linha de base usando os dados dos primeiros 2 meses do estudo.

Estruturas de correlação alternativas: avaliaremos a robustez de nossos resultados a diferentes pressupostos sobre a correlação dentro do cluster. Isso incluirá o ajuste de um modelo que considera o cluster como o único efeito aleatório e permite um modelo de decaimento em tempo discreto para levar em conta o possível enfraquecimento da correlação ao longo do tempo.

Prontidão para a alta: para minimizar o viés decorrente de atrasos não clínicos (por exemplo, fins de semana ou disponibilidade de leito na enfermaria), redefiniremos o LOS na UTI como o tempo entre a admissão na UTI e o dia do calendário em que o paciente cumpriu pela primeira vez os critérios de prontidão para a alta [3].

Janela de transição: também analisaremos o período de transição como parte da intervenção, para levar em conta possíveis efeitos durante essa fase.

Risco competitivo: como o desfecho primário, o LOS na UTI, combina dois processos (alta com vida e óbito na UTI), o óbito funciona como um evento competitivo para a alta. Para avaliar a robustez, reanalisaremos o tempo até a alta da UTI com vida em uma estrutura de riscos competitivos que trate o óbito como evento competitivo. Apresentaremos estimativas da razão de riscos específica por causa e a incidência cumulativa de alta com vida [19].

Exclusão da mortalidade precoce: repetiremos a análise primária excluindo os pacientes que morreram nas primeiras 24 horas de admissão na UTI. Como a intervenção tem pouca ou nenhuma oportunidade de afetar os desfechos entre pacientes que chegam criticamente enfermos e morrem muito precocemente, essa análise avalia se tais óbitos precoces diluem ou distorcem o efeito estimado da intervenção.

### Efeitos dinâmicos no tempo

Incluiremos uma interação entre a intervenção e o tempo desde a implementação dentro da UTI, para avaliar um possível aumento gradual ou declínio do efeito ao longo do tempo. Para essa análise exploratória, também incluiremos o período de transição de cada sequência. Seguindo a estrutura do indicador de tempo de exposição, relataremos os efeitos do tratamento como estimativas pontuais separadas para cada mês desde a implementação [20].

### Análise de subgrupos

Realizaremos análises de subgrupos pré-especificadas por meio da adição de termos de interação entre a intervenção e cada variável de subgrupo no modelo do desfecho primário. Os seguintes subgrupos serão explorados:

Tipo de admissão (clínica *versus* cirúrgica).

Experiência com telemedicina (centros com *versus* sem uso prévio de telemedicina).

Escore SAPS3 (categorizado em tercis).

Status de ventilação mecânica na admissão (invasiva *versus* não invasiva *versus* nenhuma).

Desempenho da UTI na linha de base (quatro categorias: mais eficiente, menos eficiente, de alto desempenho, de baixo desempenho). Faremos cada classificação com base nos primeiros dois meses do período basal inicial.

Essas análises serão exploratórias. Interpretaremos as estimativas dos efeitos de interação com cautela, sem ajuste para comparações múltiplas.

### Tratamento do tempo no delineamento stepped-wedge

Neste ensaio randomizado em cluster com delineamento stepped-wedge, o momento da implantação da intervenção entre as UTIs é um componente fundamental da estrutura analítica. Cada UTI contribui com dados durante as fases de controle e de intervenção, separadas por um período de transição durante o qual a intervenção está sendo implementada, mas ainda não se presume que tenha atingido o efeito pleno.

Para a análise primária, incluiremos apenas os pacientes admitidos durante os períodos de controle e de intervenção definidos. Excluiremos os pacientes admitidos durante o período de transição, pois se espera que essa fase envolva adoção parcial e variabilidade na adesão aos protocolos da intervenção.

Modelaremos o tempo calendário como um efeito fixo em todas as análises primárias e secundárias, para ajustar para possíveis tendências seculares e outros fatores de confusão relacionados ao tempo. Essa abordagem ajuda a isolar o efeito da intervenção das mudanças temporais não relacionadas ao estudo.

Ao excluir os períodos de transição da análise principal e levar explicitamente em conta o tempo no modelo estatístico, buscamos minimizar o viés decorrente da implementação gradual e estimar melhor o verdadeiro efeito da intervenção.

### Sistema de saúde brasileiro

O sistema de saúde brasileiro compreende três setores principais: público, filantrópico e privado [21]. O sistema de saúde público é um sistema universal de saúde estabelecido pela Constituição, que garante a saúde como direito de todos os cidadãos e dever do Estado. O sistema de saúde público é financiado por tributos federais, estaduais e municipais. Ele oferece atenção integral, desde a atenção primária e os programas de vacinação até serviços de alta complexidade, como o tratamento em UTI, gratuitamente no ponto de atendimento. O setor filantrópico pode prestar assistência a pacientes financiados pelo sistema público, bem como àqueles cobertos por seguros privados ou que pagam por conta própria. Os pacientes admitidos pelo sistema público nessas instituições recebem tratamento gratuito. Paralelamente, um setor privado suplementar, financiado por planos de seguro privados ou por pagamentos diretos, atende a uma parcela da população e frequentemente se sobrepõe à prestação de serviços públicos. Embora o sistema de saúde público tenha alcançado avanços substanciais em saúde pública, incluindo a ampliação do acesso e a melhoria dos indicadores de saúde, ele continua enfrentando desafios relacionados às disparidades regionais, às limitações de financiamento, à distribuição da força de trabalho e ao acesso a serviços especializados e de alta complexidade. No ensaio TELESCOPE-2, as UTIs eram elegíveis apenas se tratassem exclusivamente pacientes admitidos pelo sistema de saúde público.

### Agradecimentos

Os autores agradecem à equipe central do TELESCOPE 2, às equipes clínicas e de coleta de dados de cada UTI participante, ao Hospital Israelita Albert Einstein e ao Ministério da Saúde do Brasil.

### Registro do ensaio

Clinicaltrials NCT05960994, Rebec RBR-342wxn9, UTN U1111-1298-9799.

### Aprovação ética e consentimento

Não se aplica. Este manuscrito é um Plano de Análise Estatística e não relata análises de dados em nível de participante do estudo.

### Contribuições dos autores

T. M. dos Santos, R. C. de F. Chaves, B. G. Barbeiro, M. C. dos Santos, T. D. Corrêa, O. Ranzani: conceitualização, redação (rascunho original), redação (revisão e edição), metodologia, análise formal; A. J. Pereira: conceitualização, redação (rascunho original), redação (revisão e edição), metodologia e análise formal; J. Kasza: conceitualização, metodologia, análise formal; A. B. Cavalcanti, A. N. Serpa, C. H. S. Pedrotti, F. G. Zampieri, G. de P. P. Schettino, J. I. F. Salluh, L. U. Taniguchi, L. J. R. Ferraz, L. C. P. Azevedo, O. Berwanger, R. G. Rosa, R. A. Morbeck, R. S. Biondi, S. M. Lobo: redação (revisão e edição), metodologia. Contribuíram igualmente para este estudo: T. M. dos Santos e R. C. de F. Chaves. Autores seniores em coautoria: A. J. Pereira e O. Ranzani.

### Declaração sobre o uso de Inteligência Artificial

Durante a preparação deste manuscrito, os autores usaram o ChatGPT para refinar a estrutura das frases e corrigir erros de gramática e de pontuação. Após o uso dessa ferramenta, os autores revisaram e editaram o conteúdo e assumem total responsabilidade pelo conteúdo da publicação.

### Financiamento

O Ministério da Saúde do Brasil (Programa de Desenvolvimento Institucional do Sistema Único de Saúde – PROADI SUS) foi a principal fonte de financiamento, cobrindo os serviços médicos, a aquisição de equipamentos (*hardware*) para as sessões de telemedicina, a contratação de profissionais locais para a coleta de dados e as despesas de viagem para treinamento e monitoramento. O mesmo financiamento cobriu também os custos relacionados à parte regulatória do estudo, incluindo coleta de dados, monitoramento, curadoria de dados e apoio estatístico. O Hospital Israelita Albert Einstein alocou o tempo de profissionais e especialistas que integraram os comitês executivo e diretivo do estudo e cedeu o seu sistema de serviço de telemedicina. Jessica Kasza é apoiada por uma bolsa Investigator Grant do National Health and Medical Research Council (ID: 2033380).

### Informações editoriais

Conflitos de interesse: nenhum. Recebido em 14 de janeiro de 2026. Aceito em 1º de junho de 2026. Autor correspondente: Tiago Mendonça dos Santos, Insper Instituto de Ensino e Pesquisa, Rua Quatá, 300, CEP 04546-042, São Paulo (SP), Brasil. E-mail: tiago.mendonca.s@gmail.com. Editor responsável: Antonio Paulo Nassar Jr.

---

## Referências (mantidas no idioma original)

1. Spies CD, Ranzani OT. Telemedicine in critical care. Intensive Care Med. 2025;51(6):1153-6.
2. Spies CD, Paul N, Adrion C, Berger E, Busse R, Kraufmann B, et al.; ERIC Study Group. Effectiveness of an intensive care telehealth programme to improve process quality (ERIC): a multicentre stepped wedge cluster randomised controlled trial. Intensive Care Med. 2023;49(2):191-204.
3. Pereira AJ, Noritomi DT, Dos Santos MC, Corrêa TD, Ferraz LJ, Schettino GP, et al. Effect of Tele-ICU on clinical outcomes of critically ill patients: the TELESCOPE randomized clinical trial. JAMA. 2024;332(21):1798-807.
4. Ranzani OT, Bastos LS, Gelli JG, Marchesi JF, Baião F, Hamacher S, et al. Characterisation of the first 250,000 hospital admissions for COVID-19 in Brazil: a retrospective analysis of nationwide data. Lancet Respir Med. 2021;9(4):407-18.
5. Copas AJ, Lewis JJ, Thompson JA, Davey C, Baio G, Hargreaves JR. Designing a stepped wedge trial: three main designs, carry-over effects and randomisation approaches. Trials. 2015;16(1):352.
6. R Core Team. R: A language and environment for statistical computing. [Internet]. Vienna, Austria: R Foundation for Statistical Computing; 2024. Available from: https://www.R-project.org/
7. Kenward MG, Roger JH. Small sample inference for fixed effects from restricted maximum likelihood. Biometrics. 1997;53(3):983-97.
8. Harhay MO, Ratcliffe SJ, Small DS, Suttner LH, Crowther MJ, Halpern SD. Measuring and Analyzing Length of Stay in Critical Care Trials. Med Care. 2019;57(9):e53-9.
9. Corrêa TD, Ponzoni CR, Filho RR, Neto AS, Chaves RC, Pardini A, et al. Nighttime intensive care unit discharge and outcomes: a propensity matched retrospective cohort study. Patman S, editor. PLoS One. 2018;13(12):e0207268.
10. Centers for Disease Control and Prevention (CDC). National Healthcare Safety Network (NHSN). Ventilator-Associated Event (VAE). 2024. Available from: https://www.cdc.gov/nhsn/pdfs/pscManual/10-VAE_FINAL.pdf
11. Rhodes A, Moreno RP, Azoulay E, Capuzzo M, Chiche JD, Eddleston J, et al.; Task Force on Safety and Quality of European Society of Intensive Care Medicine (ESICM). Prospectively defined indicators to improve the safety and quality of care for critically ill patients: a report from the Task Force on Safety and Quality of the European Society of Intensive Care Medicine (ESICM). Intensive Care Med. 2012;38(4):598-605.
12. Timenetsky KT, Neto AS, Assunção MS, Taniguchi L, Eid RA, Corrêa TD; e-MOTION group. Mobilization practices in the ICU: a nationwide 1-day point- prevalence study in Brazil. PLoS One. 2020;15(4):e0230971.
13. Vasconcelos NN, Queiroz VN, Souza GM, Mangini S, Silva FM, Costa LG, et al. Perioperative management of adult patients undergoing coronary artery bypass grafting and valve surgery: a literature review. Einstein (Sao Paulo). 2025;23:eRW1353.
14. Ely EW, Truman B, Shintani A, Thomason JW, Wheeler AP, Gordon S, et al. Monitoring sedation status over time in ICU patients: reliability and validity of the Richmond Agitation-Sedation Scale (RASS). JAMA. 2003;289(22):2983-91.
15. Rothen HU, Stricker K, Einfalt J, Bauer P, Metnitz PG, Moreno RP, et al. Variability in outcome and resource use in intensive care units. Intensive Care Med. 2007;33(8):1329-36.
16. Hemming K, Taljaard M, McKenzie JE, Hooper R, Copas A, Thompson JA, et al. Reporting of stepped wedge cluster randomised trials: extension of the CONSORT 2010 statement with explanation and elaboration. BMJ. 2018;363:k1614.
17. Bates D, Mächler M, Bolker BM, Walker SC. Fitting linear mixed-effects models using lme4. J Stat Soft. 2015;67(1):1-48.
18. van Buuren S, Groothuis-Oudshoorn K. mice: Multivariate imputation by chained equations in R. J Stat Softw. 2011;45(3):1-67.
19. Wolkewitz M, Cooper BS, Bonten MJ, Barnett AG, Schumacher M. Interpreting and comparing risks in the presence of competing events. BMJ. 2014;349:g5060.
20. Kenny A, Voldal EC, Xia F, Heagerty PJ, Hughes JP. Analysis of stepped wedge cluster randomized trials in the presence of a time-varying treatment effect. Stat Med. 2022;41(22):4311-39.
21. Paim J, Travassos C, Almeida C, Bahia L, Macinko J. The Brazilian health system: history, advances, and challenges. Lancet. 2011;377(9779):1778-97.

---

*Tradução não oficial gerada por IA. Consulte o artigo original: https://criticalcarescience.org/article/statistical-analysis-plan-for-a-stepped-wedge-cluster-randomized-clinical-trial-for-the-evaluation-of-the-clinical-impact-of-different-telemedicine-practices-in-intensive-care-units-telescop/*
