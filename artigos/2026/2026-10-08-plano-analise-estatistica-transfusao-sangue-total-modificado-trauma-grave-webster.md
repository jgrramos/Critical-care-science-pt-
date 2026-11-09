> ⚠️ **TRADUÇÃO NÃO OFICIAL.** Texto traduzido automaticamente por inteligência artificial (Claude, Anthropic). Não foi revisado nem endossado pela revista *Critical Care Science*, pelos autores do artigo ou pelo autor deste repositório. Podem existir erros de tradução. **Em caso de dúvida, consulte sempre a versão original em inglês.**

# Plano de análise estatística para a transfusão de sangue total modificado *versus* terapia com hemocomponentes em pacientes com trauma grave: ensaio clínico randomizado – estudo WEBSTER

*Título original: Statistical analysis plan for transfusion of modified whole blood versus blood components therapy in patients with severe trauma: randomized controlled trial – WEBSTER trial*

| | |
|---|---|
| **Autores** | Alberto Federico García, Andrés Gempeler, Edgar-Yaset Caicedo, Juan Carlos Puyana, Carlos A. Ordóñez, Gustavo Adolfo Ospina-Tascón |
| **Revista** | Critical Care Science, 2026;38:e20260116 |
| **Tipo de artigo** | Relato clínico (*Clinical Report*) |
| **Data de publicação** | 08/10/2026 |
| **DOI** | [10.62675/2965-2774.20260116](https://doi.org/10.62675/2965-2774.20260116) |
| **Artigo original** | [https://criticalcarescience.org/article/statistical-analysis-plan-for-transfusion-of-modified-whole-blood-versus-blood-components-therapy-in-patients-with-severe-trauma-randomized-controlled-trial-webster-trial/](https://criticalcarescience.org/article/statistical-analysis-plan-for-transfusion-of-modified-whole-blood-versus-blood-components-therapy-in-patients-with-severe-trauma-randomized-controlled-trial-webster-trial/) |
| **Licença do original** | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

**Atribuição:** tradução de obra licenciada sob CC BY 4.0. Os direitos do texto original pertencem aos autores e à revista *Critical Care Science*. Foram feitas alterações (tradução para o português). Fonte: site da revista.

**Nota do tradutor:** (1) A ordem dos nomes dos autores foi reconstituída a partir da página do artigo e do XML (formato Nome Sobrenome). (2) A Tabela 1, que no texto-fonte estava em formato corrido, foi reconstruída em Markdown a partir das linhas do XML; as células de mortalidade, com células mescladas (*rowspan*), foram repetidas em cada linha. (3) O valor "‘43" da Tabela 1 foi mantido como aparece no original (provável erro tipográfico para 43). (4) Os títulos "BACKGROUND" e "CONCLUSION" foram traduzidos como "CONTEXTO" e "CONCLUSÃO". (5) Os erros e as imprecisões do original (por exemplo, "longer than > 5 minutes", "platelets < 100.000/mm3", "chi2test" e o uso alternado de "ED" e "ER" para o serviço de emergência) foram mantidos ou apenas refletidos na tradução. (6) O texto-fonte não contém seções de agradecimentos, financiamento, contribuições dos autores ou conflitos de interesse; foram traduzidos apenas os itens presentes (registro, disponibilidade de dados e declaração sobre IA). (7) O material suplementar (tabelas simuladas 1S a 4S) não está incluído nesta tradução.

---

## RESUMO

**Contexto:** A ressuscitação hemostática com sangue total modificado é uma alternativa à terapia balanceada com hemocomponentes para pacientes com trauma e choque hemorrágico, com potencial eficácia e vantagens logísticas. O estudo WEBSTER foi delineado para comparar essas intervenções em pacientes com choque hemorrágico traumático.

**Métodos:** Ensaio clínico randomizado, unicêntrico, aberto, de grupos paralelos, comparando sangue total com hemocomponentes em adultos com choque hemorrágico traumático.

**Desfecho primário:** Desfecho composto hierárquico de mortalidade por todas as causas em 28 dias e escore SOFA durante os primeiros 5 dias após a randomização. Estimaremos os efeitos do tratamento por meio de uma análise de razão de vitórias (*win ratio*) que prioriza a mortalidade. A análise primária segue o princípio de intenção de tratar; estão planejadas análises secundárias nas populações conforme tratado e por protocolo. Os desfechos secundários incluem mortalidade em outros momentos, métricas de disfunção orgânica, parâmetros de coagulação, necessidades transfusionais e eventos adversos.

**Resultados:** As análises do desfecho primário relatarão razões de vitórias, e os desfechos secundários serão analisados com testes de hipóteses ou modelos de regressão de tempo até o evento; intervalos de confiança de 95% acompanharão todas as estimativas. Não planejamos ajuste formal para multiplicidade porque os desfechos compartilham o mesmo construto subjacente. Todos os desfechos serão interpretados no contexto do padrão geral dos resultados.

**Conclusão:** Este plano de análise estatística pré-especifica métodos transparentes para avaliar o efeito do sangue total *versus* a terapia com hemocomponentes em pacientes com trauma. O arcabouço hierárquico, as análises de sensibilidade complementares e a interpretação abrangente destinam-se a fornecer uma avaliação robusta e clinicamente significativa dos efeitos do sangue total.

**Palavras-chave:** Transfusão de sangue; Choque hemorrágico; Trauma; Transfusão; Falência de múltiplos órgãos

## CONTEXTO

O uso de hemocomponentes (HC) é um elemento fundamental no manejo do paciente com trauma, no qual a intervenção oportuna é essencial para corrigir a coagulopatia induzida pelo trauma e melhorar os desfechos de curto prazo [1,2]. Uma estratégia transfusional baseada na proporção de 1:1:1 de concentrado de hemácias, plasma e plaquetas, concebida para refletir as proporções fisiológicas, tem sido associada a melhor sobrevida e melhor controle da hemorragia [3-5]. No entanto, desafios técnicos e logísticos significativos dificultam sua adoção generalizada, tornando a implementação rotineira difícil em muitos cenários de atendimento ao trauma [6].

A transfusão de sangue total (ST), reintroduzida pelas forças militares dos Estados Unidos durante as guerras do Iraque e do Afeganistão, foi posteriormente incorporada a alguns centros de trauma civis [7]. Seus defensores propõem que o ST proporciona uma ressuscitação mais balanceada do ponto de vista fisiológico, simplifica a logística transfusional e melhora as propriedades hemostáticas em comparação com os HC [8,9]. Apesar desses benefícios teóricos e de um perfil de segurança favorável, estudos observacionais e revisões sistemáticas relataram achados conflitantes, e são necessárias evidências sólidas de ensaios clínicos que respaldem seu uso generalizado [10,11].

Este artigo descreve o plano de análise estatística do estudo WEBSTER, a fim de evitar o viés de análise *post hoc* e o viés de relato seletivo.

### Objetivos do estudo

#### Objetivo primário

Avaliar os efeitos da ressuscitação hemostática com ST modificado em comparação com HC sobre a mortalidade e a disfunção orgânica em pacientes com trauma e choque hemorrágico.

#### Objetivos secundários

O estudo também avaliará os efeitos do ST em comparação com os HC sobre desfechos secundários, incluindo mortalidade por todas as causas nas primeiras 6 horas, em 24 horas e em 28 dias; incidência de disfunção de múltiplos órgãos; incidência e correção da coagulopatia induzida pelo trauma; e incidência de eventos adversos graves. Desfechos terciários (exploratórios) também são considerados e estão listados na seção Desfechos.

## Visão geral do delineamento do estudo

### Delineamento do ensaio

O estudo WEBSTER é um ensaio clínico randomizado de superioridade, aberto, unicêntrico, de grupos paralelos, com dois braços: transfusão de sangue total modificado *versus* HC, com razão de alocação de 1:1. O protocolo do estudo foi publicado [12] e está registrado no ClinicalTrials.gov (NCT05634109).

### População do estudo

Pacientes adultos com trauma contuso ou penetrante que necessitam de transfusão por choque hemorrágico no departamento de emergência em até 4 horas após a lesão, com necessidade de transfusão definida por escore ABC ≥ 2 ou a critério do médico, e disponibilidade concomitante de sangue total e de HC no momento da randomização. Os principais critérios de exclusão incluem cirurgia pré-hospitalar, lesão cerebral catastrófica, estado *in extremis*, queimaduras > 20% da superfície corporal total, reanimação cardiopulmonar antes da chegada ao departamento de emergência (DE) ou por mais de > 5 minutos antes da randomização, transfusão prévia de mais de uma unidade de concentrado de hemácias, gravidez, encarceramento e ordem prévia de não reanimar. O protocolo publicado descreve todos os critérios de elegibilidade [12].

## Randomização

Este estudo usa uma razão de alocação de 1:1, obtida por randomização em blocos permutados de tamanhos 4 e 6. Geramos a sequência de randomização com os pacotes "blockrand" e "randomizr" no RStudio e a carregamos no REDCap. A alocação é ocultada dos investigadores do estudo e inacessível a eles. Inicialmente, planejamos uma randomização estratificada com base na presença de traumatismo cranioencefálico (TCE) moderado ou grave, por seu impacto na mortalidade por trauma [13]; no entanto, a gravidade do TCE é de difícil avaliação no cenário de emergência, o que levou a frequente classificação incorreta de pacientes durante o estudo-piloto. Portanto, após a aprovação do Comitê de Ética em Pesquisa (CEP), randomizamos sem estratificação.

O grupo designado ao participante só é revelado depois que o médico da sala de emergência (SE) avalia os critérios de elegibilidade e entra em contato com o banco de sangue. A equipe do banco de sangue então acessa o REDCap e realiza a randomização por meio de uma ferramenta baseada na web. Esse processo não interfere no atendimento clínico nem nos procedimentos na SE ou no banco de sangue.

## Intervenções do estudo

Os participantes são alocados para ST ou HC por randomização computadorizada no banco de sangue, quando é solicitado um pacote de transfusão para trauma e a elegibilidade do paciente é confirmada pela SE. A transfusão de ST ou de HC segue os procedimentos institucionais padrão, orientados por tromboelastografia e por testes convencionais de coagulação.

## Desvios de protocolo

### Adesão ao protocolo e desvios de protocolo

Os desvios de protocolo serão relatados como contagens e proporções, no geral e por grupo de intervenção. Os desvios maiores que determinarão as populações de análise incluem desvios no recrutamento de participantes (erros na aplicação dos critérios de elegibilidade) e desvios das intervenções designadas.

### Exclusões pós-randomização

Dado o cenário de emergência do estudo, esperam-se exclusões pós-randomização de 10% a 20%, conforme relatado em estudos semelhantes. Essas exclusões refletem critérios de inclusão não atendidos ou critérios de exclusão não identificados antes da randomização. De acordo com Fergusson et al., exclusões pós-randomização aceitáveis da população por intenção de tratar (ITT) incluem pacientes inelegíveis incluídos erroneamente no estudo [14]. Para que a decisão de remover esses pacientes não seja influenciada por eventos posteriores à randomização e permaneça isenta de viés, seguimos a recomendação desses autores de avaliar os desvios relativos ao não cumprimento dos critérios de elegibilidade de forma cega em relação à alocação do tratamento e ao desfecho. Dois pesquisadores independentes executarão essa tarefa e avaliarão o risco de viés ou de erro aleatório em cada caso, pois a validade de excluir pacientes de todas as análises ou de incluí-los na análise ITT (e conforme tratado) depende principalmente do critério não cumprido. Um terceiro investigador resolverá as discrepâncias. Esse processo será realizado em duplicata na análise interina e na conclusão do estudo. Para garantir a reprodutibilidade, relataremos, junto com nossos resultados, todos os julgamentos e motivos das exclusões pós-randomização.

## Análise interina

Planejamos uma análise interina após a conclusão de 50% do tamanho amostral calculado para a análise ITT. Realizamos a análise interina, com a designação da intervenção ainda cega, após o recrutamento de 126 pacientes, abrangendo apenas os desfechos primário e de segurança. Somente o Comitê Independente de Monitoramento de Segurança de Dados (DSMB) teve acesso aos resultados. O DSMB foi composto por dois cirurgiões de trauma e pesquisadores de ensaios clínicos experientes e um estatístico sênior, que revisaram os desfechos de segurança cegados e não encontraram fundamento para o desmascaramento nem para o encerramento precoce.

## Cálculo do tamanho amostral e justificativa

Considerações de viabilidade orientaram o tamanho amostral, com inclusão estimada de 220 pacientes ao longo de 2 anos, com base em dados do centro do estudo sobre a frequência de pacientes elegíveis em anos anteriores. As simulações para avaliar o poder estatístico de detecção de uma diferença clinicamente significativa usando a razão de vitórias para o desfecho composto hierárquico de óbito e escore *Sequential Organ Failure Assessment* (SOFA) utilizaram uma mortalidade esperada de 21,8% e uma diferença no escore SOFA entre os dias 1 e 5 de -1,38 (desvio padrão = 3,02) sob o tratamento padrão. Esses valores foram derivados de dados retrospectivos do centro do estudo e de um ensaio clínico randomizado sobre solução salina hipertônica conduzido em nossa instituição nos últimos anos, respectivamente [15]. Com 220 pacientes, uma análise de razão de vitórias alcançaria poder > 80% para detectar diferenças absolutas de 4% na mortalidade e de 1,5 ponto no escore SOFA entre os grupos, bem como para diferentes combinações de diferenças de mortalidade e de SOFA, conforme descrito na tabela 1.

**Tabela 1.** Poder empírico da análise de razão de vitórias para diferentes combinações de diferenças de mortalidade em 28 dias e de escore SOFA entre os grupos

| Diferença absoluta na mortalidade em 28 dias (%) | Diferença no escore SOFA | Poder empírico da razão de vitórias (%) |
|---|---|---|
| -2 | -1 | ‘43 |
| -2 | -1,5 | 71,5 |
| -2 | -2 | 90,8 |
| -2 | -2,5 | 97,8 |
| -3 | -1 | 48 |
| -3 | -1,5 | 78,6 |
| -3 | -2 | 92,8 |
| -3 | -2,5 | 98,9 |
| -4 | -1 | 58 |
| -4 | -1,5 | 82,3 |
| -4 | -2 | 95,2 |
| -4 | -2,5 | 99 |

SOFA: *Sequential Organ Failure Assessment*.

Antecipando exclusões pós-randomização devidas a erros na avaliação da elegibilidade, inerentes a um ensaio em cenário de emergência, esperadas em uma taxa entre 10% e 20%, será necessário randomizar entre 242 e 264 participantes para assegurar poder estatístico adequado para a análise primária. O recrutamento será, assim, encerrado quando completarmos 220 pacientes na população ITT.

## Populações de análise

### Análise primária: população por intenção de tratar

A análise primária seguirá o princípio ITT. Ela pode incluir participantes com critérios de exclusão não identificados antes da randomização, mas não incluirá participantes randomizados sem que tenham cumprido os critérios de inclusão. Na análise ITT, os pacientes serão analisados como parte do grupo alocado pela randomização, independentemente da não adesão à intervenção pretendida.

### Análises secundárias: populações conforme tratado e por protocolo

As análises secundárias serão conduzidas nas populações conforme tratado e por protocolo: a análise conforme tratado determinará o grupo dos participantes de acordo com a intervenção recebida, apesar de diferenças em relação à alocação randomizada, e incluirá participantes apesar de outros desvios maiores de protocolo. Qualquer paciente que tenha recebido pelo menos uma unidade de ST após a randomização será analisado como parte do grupo ST na análise conforme tratado. A análise por protocolo determinará o grupo dos participantes de acordo com a intervenção recebida, apesar da randomização, da mesma forma que a análise conforme tratado, mas excluirá participantes com outros desvios de protocolo.

A Figura 1 apresenta o fluxograma CONSORT que ilustra a composição das populações de análise primária e secundárias.

**Figura 1.** Fluxograma de triagem, randomização e confirmação das populações de análise primária e secundárias do estudo. ITT: população por intenção de tratar; ST: sangue total; HC: hemocomponentes. \* Exclusões pós-randomização (erros durante a triagem de elegibilidade inerentes ao cenário de ensaio em emergência) adjudicadas por dois investigadores cegados para a alocação do tratamento; a soma pode exceder o total, pois os pacientes podem atender a > 1 critério; † ITT: população por intenção de tratar; todos os 220 pacientes randomizados foram analisados conforme a alocação, independentemente da adesão; ‡ A caixa de desvio de protocolo mostra os cruzamentos (*crossovers*; pacientes que receberam o tratamento oposto) e outros desvios maiores. Os pacientes com cruzamento são incluídos nas análises conforme tratado e por protocolo, no grupo correspondente ao tratamento recebido. Os pacientes com outros desvios são incluídos na análise conforme tratado, mas excluídos da análise por protocolo; § outros desvios (sem cruzamento): por exemplo, descoberta, após a randomização, de erros de elegibilidade não excluídos da população por intenção de tratar; não adesão quando o paciente recebeu tanto sangue total quanto hemocomponentes não contemplados no protocolo do estudo. *(A figura está disponível no artigo original.)*

## Desfechos

### Arcabouço de interpretação

Interpretaremos achados consistentes entre as análises como evidência favorável a um efeito do tratamento, e interpretaremos com cautela os achados discordantes.

Como essas análises abordam uma única questão clínica primária, e não múltiplas hipóteses independentes, não faremos ajuste formal para multiplicidade. A interpretação enfatizará a direção, a magnitude e a consistência dos efeitos, e não a significância estatística isolada. Pré-especificamos os desfechos secundários para avaliar formalmente as consequências clinicamente relevantes da intervenção e fornecer resultados explicativos. Interpretaremos esses desfechos de forma inferencial, com foco nas estimativas de efeito e nos intervalos de confiança. Consideraremos todos os desfechos terciários exploratórios e não faremos ajuste para comparações múltiplas nessas análises.

### Desfecho primário

Desfecho composto hierárquico de mortalidade por todas as causas em 28 dias após a randomização e evolução do escore SOFA nos 5 dias após a randomização. O desfecho hierárquico exige definir vitórias, derrotas e empates dentro de pares de participantes de grupos diferentes. A razão de vitórias será calculada comparando todos os participantes do grupo sangue total com todos os participantes do grupo HC. Uma razão de vitórias > 1 indica benefício clínico líquido para o grupo ST. Para cada par de participantes (um de cada grupo), os desfechos são comparados hierarquicamente da seguinte forma:

Nível 1 - Mortalidade em 28 dias

- Se apenas um participante do par morrer em até 28 dias, o grupo do participante sobrevivente recebe uma "vitória".
- Se ambos os participantes morrerem, a comparação é considerada um empate.
- Se ambos os participantes sobreviverem, passa-se ao Nível 2.

Nível 2 - Variação do escore SOFA (dia 1 ao dia 5)

- Calcular ΔSOFA = SOFA no dia 1 - SOFA no dia 5 para cada participante (valores positivos indicam melhora), a menos que os grupos difiram nos escores SOFA basais do dia 1.
- Entre os pares em que ambos os participantes sobrevivem, o participante com maior ΔSOFA (maior redução da disfunção orgânica) recebe uma "vitória" para o grupo desse participante.
- Se o ΔSOFA não diferir em pelo menos 1 ponto, a comparação é considerada um "empate".
- Se os escores SOFA do dia 1 forem diferentes entre os grupos (o que sugere risco de viés devido a uma redução maior em pacientes com escores mais altos), esse nível comparará os escores SOFA no dia 5 entre os pares. Dentro de um par de sobreviventes, o grupo do participante com o menor escore SOFA no dia 5 receberá uma vitória.

### Análises de sensibilidade pré-especificadas

Durante a elaboração deste plano de análise estatística, identificamos uma possível limitação do desfecho especificado no protocolo: medir a variação do SOFA apenas entre os dias 1 e 5, ou comparar apenas o dia 5, pode não captar o pico de disfunção orgânica que se desenvolve e se resolve entre esses momentos de medição. Os pacientes podem apresentar falência orgânica clinicamente significativa nos dias 2, 3 ou 4 que melhora até o dia 5, resultando em ΔSOFA semelhante ou em escores SOFA semelhantes entre os grupos, apesar de uma carga de morbidade substancialmente diferente. Para abordar essa preocupação e garantir uma avaliação robusta do efeito da intervenção sobre a disfunção orgânica, planejamos a seguinte análise de sensibilidade *a priori*:

Nível 2 modificado - Escore SOFA máximo (dias 1 a 5)

- Identificar o escore SOFA máximo (mais alto) registrado em qualquer dia, do dia 1 ao dia 5, para cada participante.
- Entre os pares em que ambos os participantes sobrevivem 28 dias, o participante com o menor escore SOFA máximo recebe uma "vitória" para o grupo do participante.
- Se o escore SOFA máximo não diferir em pelo menos 1 ponto, a comparação é considerada um "empate".

Dadas as limitações conhecidas da razão de vitórias na presença de um grande número de empates, conduziremos uma análise de sensibilidade usando o método de *win odds*, conforme proposto por Brunner et al. [16]. O *win odds* é calculado como o número total de vitórias mais metade do número total de empates, dividido pelo número total de derrotas mais metade do número total de empates. Isso retém todas as informações pareadas (não exclui as comparações empatadas) ao incorporar os empates tanto no numerador quanto no denominador, reduzindo o potencial de superestimação do efeito do tratamento quando uma proporção substancial dos pares é empatada. A interpretação dos resultados priorizará a consistência na direção das estimativas de vitória.

### Desfechos secundários

Mortalidade

Incidência de mortalidade por todas as causas e por causas específicas em 6 horas, 24 horas e 28 dias após a randomização. Se for detectada uma diferença de mortalidade entre os grupos maior que 5%, analisaremos todos os demais desfechos secundários usando uma abordagem de riscos competitivos com o óbito.

Disfunção de múltiplos órgãos

Duas abordagens são usadas para assegurar que quaisquer efeitos clinicamente relevantes da intervenção sobre a disfunção orgânica sejam detectados:

- Incidência de disfunção de múltiplos órgãos (DMO) nos primeiros 5 dias após a randomização.
- Maiores escores SOFA nos primeiros 5 dias após a randomização.

A DMO é definida como escore SOFA ≥ 2 pontos em um sistema ou ≥ 1 em dois ou mais sistemas no mesmo dia. Os subescores do SOFA serão relatados para identificar efeitos em sistemas específicos que possam ser afetados pelas intervenções, incluindo o subescore de coagulação.

Eventos adversos graves

Compararemos a incidência e o número de eventos adversos graves (EAGs) entre os grupos, no geral e de acordo com a potencial relação determinada pelo comitê de adjudicação. Os eventos adversos graves são definidos de acordo com as Diretrizes de Boas Práticas Clínicas, e o protocolo do nosso estudo descreve esse processo em detalhes.

Coagulopatia

A coagulopatia inclui hipocoagulabilidade e coagulopatia fibrinolítica. Definiremos hipocoagulabilidade como parâmetros tromboelastográficos (TEG) R > 10 min, K > 2,5 min, α < 65º, MA < 55mm, ou testes de coagulação convencionais com INR > 1,2, plaquetas < 100.000/mm3 ou fibrinogênio < 2g/L. A coagulopatia fibrinolítica será definida como LY-30 > 8%. Compararemos os grupos quanto a:

- Prevalência de coagulopatia em 6 horas e 12 horas após a randomização.
- Incidência de hipocoagulabilidade ou coagulopatia fibrinolítica nas primeiras 24 horas após a randomização. Para essa incidência cumulativa, não incluiremos pacientes com coagulopatia antes da randomização.
- Diferença no subescore de coagulação do SOFA nos dias 1 e 5.

Os parâmetros tromboelastográficos, os tempos de coagulação e as tendências do fibrinogênio durante as primeiras 24 horas após a randomização serão avaliados graficamente por meio de gráficos de trajetória de participantes individuais, por grupo de intervenção.

## Necessidades de transfusão de sangue durante as primeiras 24 horas

Diferença no número de unidades de ST ou HC entre os grupos. As comparações seguirão as seguintes definições: 1 unidade de sangue total = 1 unidade de concentrado de hemácias; 1 unidade de sangue total = 1 unidade de plasma; e 1 unidade de sangue total = 1 unidade de plaquetas.

### Tempo de internação hospitalar

Diferença nos dias livres de hospital no dia 28 após a randomização entre ST e HC.

### Desfechos terciários

- Dias livres de vasopressores no dia 28 após a randomização.
- Dias livres de ventilação mecânica no dia 28 após a randomização.
- Dias livres de terapia renal substitutiva no dia 28 após a randomização.
- Proporção de participantes que necessitam de cirurgia de controle de danos nos primeiros 28 dias após a randomização.
- Número de procedimentos cirúrgicos após a cirurgia índice ou até o fechamento da cavidade, até o dia 28 após a randomização.
- Volume de fluidos de ressuscitação nas primeiras 24 horas após a randomização.
- Lactato sérico nas primeiras 3, 6, 12 e 24 horas após a randomização.
- Evolução da hemoglobina e do hematócrito nas primeiras 24 horas após a randomização.
- Evolução dos leucócitos nas primeiras 24 horas após a randomização.
- Evolução das plaquetas nas primeiras 24 horas após a randomização.
- Evolução do pH nas primeiras 24 horas após a randomização.
- Evolução do excesso de bases nas primeiras 24 horas após a randomização.
- Evolução do sódio, do potássio e do cálcio iônico nas primeiras 24 horas após a randomização.

## Análises estatísticas

### Princípios gerais

As análises estatísticas serão conduzidas no RStudio (R, Posit). A razão de vitórias será calculada usando o pacote WINS. Relataremos as análises estatísticas por meio de tabelas-resumo (Material Suplementar), figuras e listagens de dados. Resumiremos as variáveis contínuas como mediana (intervalo interquartil) e amplitude (mín-máx). As variáveis qualitativas serão expressas como contagens e proporções.

### Intervalos de confiança e valores de p

Todas as estimativas de efeito serão relatadas com intervalos de confiança de 95% (IC95%). Os testes de hipóteses serão bicaudais, com nível de significância de 5% (α = 0,05). A razão de vitórias e seu IC95% serão estimados na escala logarítmica, usando um estimador de variância baseado em estatística U que leva em conta a covariância entre vitórias e derrotas [17], e depois retransformados para a escala original. Derivaremos o valor de p bicaudal correspondente do mesmo estimador de variância. O IC95% do *win odds* será estimado usando o mesmo estimador de variância baseado em estatística U em escala logarítmica, levando em conta a covariância entre vitórias, derrotas e empates.

## Verificação da qualidade dos dados e bloqueio do banco de dados

Verificações automatizadas de intervalo e de consistência são programadas no REDCap. As discrepâncias identificadas durante a revisão dos dados são encaminhadas como consultas (*queries*) aos coordenadores do estudo, documentadas e resolvidas como parte do monitoramento contínuo, que verifica a exatidão de todas as variáveis do banco de dados. O REDCap mantém uma trilha de auditoria de todas as alterações nos dados.

O banco de dados do estudo será bloqueado após a conclusão do tamanho amostral de 220 para a população ITT, o que implica: conclusão da entrada de dados, conclusão do monitoramento dos dados e resolução de todas as consultas em aberto. O investigador principal e o gerente de dados autorizarão o bloqueio do banco de dados antes da análise estatística. Um conjunto de dados limpo para análise será exportado do REDCap após o bloqueio do banco de dados. O conjunto de dados será submetido a controle de versão e congelado antes do desmascaramento.

## Tratamento de dados ausentes

Os escores SOFA ausentes serão tratados usando regras de interpolação pré-especificadas, conforme descrito no protocolo publicado.

Para todas as variáveis de desfecho secundário, usaremos a análise de casos completos como abordagem primária, desde que a proporção de dados ausentes não exceda os limiares pré-especificados para qualquer desfecho (> 5% de dados ausentes no geral ou diferença > 3% nos dados ausentes entre os grupos; excluindo os dados ausentes atribuíveis ao óbito). Se excedidos, conduziremos imputação múltipla (IM) usando o algoritmo de equações encadeadas (*multivariate imputation by chained equations* - MICE) com 50 imputações, com correspondência preditiva pela média (*predictive mean matching*) para variáveis contínuas e regressão logística para variáveis binárias. O modelo de imputação incluirá características basais, componentes e escore total do SOFA em todos os momentos disponíveis, alocação do tratamento e estado de sobrevivência. Avaliaremos a convergência inspecionando os gráficos de traço entre as iterações antes da combinação. Obteremos as estimativas combinadas usando as regras de Rubin. Relataremos uma análise de sensibilidade comparando os resultados de casos completos e de IM para avaliar a robustez das premissas de imputação.

## Métodos de análise

### Características basais e tratamentos recebidos

Descreveremos as características clínicas e paraclínicas basais dos participantes e as intervenções recebidas durante o estudo para as três populações de análise.

## Plano de análise dos desfechos

Desfecho composto hierárquico de óbito ou disfunção de múltiplos órgãos (desfecho primário): após a interpolação dos escores SOFA conforme descrito em nosso protocolo publicado, os desfechos primários serão avaliados em uma análise de razão de vitórias "todos contra todos" que relatará a razão de vitórias (RV) (total de vitórias nos grupos de intervenção dividido pelo total de vitórias no grupo controle) acompanhada de intervalo de confiança de 95%.

### Desfechos secundários

- Mortalidade: avaliaremos as diferenças na mortalidade com o teste do qui-quadrado (chi2test) e relataremos a razão de risco (RR) com IC95%. Nosso protocolo publicado pré-especificou que aplicaríamos análises de riscos competitivos condicionalmente se a mortalidade observada diferisse em mais de 5% entre os grupos. Após o retorno dos revisores e a revisão metodológica, reconhecemos que existem riscos competitivos sempre que o óbito pode impedir a ocorrência de um desfecho, independentemente da magnitude das diferenças de mortalidade entre os grupos. Assim, compararemos os desfechos secundários dicotômicos entre os grupos usando testes do qui-quadrado ou o teste exato de Fisher, conforme apropriado, relataremos as diferenças de risco e os IC95%, e relataremos modelos de risco de subdistribuição de Fine-Gray como análises de sensibilidade para todos os desfechos dicotômicos em que o óbito representa um risco competitivo. Para todos os desfechos de dias livres, o óbito antes do dia 28 receberá zero dia livre, o que leva em conta, de forma inerente, a natureza competitiva do óbito para esses desfechos.
- Disfunção de múltiplos órgãos: avaliaremos as diferenças na incidência de DMO durante os primeiros 5 dias após a randomização com o teste do qui-quadrado (chi2test). As diferenças entre os grupos no maior escore SOFA registrado serão avaliadas com o teste t de Student ou o teste U de Wilcoxon-Mann-Whitney, conforme apropriado.
- Eventos adversos graves: as diferenças na incidência de EAG serão avaliadas com o teste do qui-quadrado (chi2test) na ausência de riscos competitivos.
- Coagulopatia: as diferenças na incidência de coagulopatia serão avaliadas com o teste do qui-quadrado (chi2test) na ausência de riscos competitivos.
- Necessidades de transfusão de sangue: as diferenças nas necessidades transfusionais serão avaliadas com o teste t de Student ou o teste U de Wilcoxon-Mann-Whitney, conforme apropriado com base na distribuição dos dados.

Se houver desequilíbrio nas características prognósticas basais entre os grupos, será realizada uma análise de sensibilidade do efeito da intervenção sobre os desfechos secundários, ajustada de acordo, por meio de um modelo de regressão logística multivariável para desfechos dicotômicos e de um modelo linear generalizado com distribuição gaussiana e função de ligação logarítmica para desfechos quantitativos, ambos seguindo um processo de seleção intencional de variáveis para controlar a confusão [18]. Todas as tabelas simuladas (para características basais, intervenções recebidas e desfechos), estratificadas por grupos de intervenção para as populações de análise primária e secundárias, estão disponíveis nas tabelas 1S a 4S (Material Suplementar).

### Análise de subgrupos

Com finalidade exploratória, os efeitos do tratamento serão avaliados sobre os desfechos primário e secundários de acordo com os seguintes subgrupos: idade (< e ≥ 50 anos), tempo entre o trauma e a randomização segundo tercis, tempo entre a admissão e a transfusão (< e ≥ 30 minutos), tempo para a ressuscitação hemostática (< e ≥ 120 minutos), pressão arterial sistólica na admissão (< e ≥ 90mmHg), níveis de lactato na admissão (< e ≥ 4mmol/L), INR na admissão (< e ≥ 1,8), cálcio iônico na admissão (< e ≥ 0,9mmol/L), parâmetro TEG-MA na admissão (< e ≥ 55mm) e escore de gravidade da lesão (*injury severity score*) (< e ≥ 25 pontos).

## CONCLUSÃO

Este plano de análise estatística pré-especifica os princípios analíticos, as definições dos desfechos e o arcabouço estatístico para analisar e interpretar os resultados do estudo WEBSTER. Ao pré-especificar todas as análises primárias, secundárias e exploratórias antes do bloqueio do banco de dados, este artigo visa proteger o estudo contra análises orientadas pelos dados, relato seletivo e reinterpretação *post hoc* dos resultados. As análises planejadas baseiam-se no princípio de intenção de tratar, com estimandos claramente definidos, tratamento de dados ausentes e abordagens pré-especificadas para as análises de sensibilidade. Demos atenção especial ao complexo contexto clínico do choque hemorrágico, incluindo os riscos competitivos, para assegurar que os métodos estatísticos estejam alinhados com a fisiopatologia subjacente e com os objetivos do estudo.

### Informações adicionais

Registro no ClinicalTrials.gov: NCT05634109.

**Disponibilidade de dados e materiais:** Este manuscrito descreve o plano de análise estatística de um ensaio clínico randomizado. Assim, nenhum dado foi utilizado em sua elaboração. Os *scripts* de *software* estatístico para o cálculo do tamanho amostral e outros materiais usados no planejamento da análise podem ser disponibilizados mediante solicitação.

**Declaração sobre o uso de Inteligência Artificial:** O Claude (Anthropic, versão Sonnet 4.6) foi utilizado para auxiliar na geração das tabelas simuladas e na revisão de gramática, ortografia e linguagem na preparação deste manuscrito. Todo o conteúdo científico, as interpretações e as conclusões são de responsabilidade exclusiva dos autores.

---

## Referências (mantidas no idioma original)

1. Kalkwarf KJ, Cotton BA. Resuscitation for hypovolemic shock. Surg Clin North Am. 2017;97(6):1307-21.
2. Moore EE, Moore HB, Kornblith LZ, Neal MD, Hoffman M, Mutch NJ, et al. Trauma-induced coagulopathy. Nat Rev Dis Primers. 2021;7(1):30.
3. Van PY, Holcomb JB, Schreiber MA. Novel concepts for damage control resuscitation in trauma. Curr Opin Crit Care. 2017;23(6):498-502.
4. Holcomb JB, Tilley BC, Baraniuk S, Fox EE, Wade CE, Podbielski JM, et al.; PROPPR Study Group. Transfusion of plasma, platelets, and red blood cells in a 1:1:1 vs a 1:1:2 ratio and mortality in patients with severe trauma: the PROPPR randomized clinical trial. JAMA. 2015;313(5):471-82.
5. Nguyen M, Pirracchio R, Kornblith LZ, Callcut R, Fox EE, Wade CE, et al. Dynamic impact of transfusion ratios on outcomes in severely injured patients: targeted machine learning analysis of the Pragmatic, Randomized Optimal Platelet and Plasma Ratios randomized clinical trial. J Trauma Acute Care Surg. 2020;89(3):505-13.
6. Schaefer RM, Bank EA, Krohmer JR, Haskell A, Taylor AL, Jenkins DH, et al. Removing the barriers to prehospital blood: a roadmap to success. J Trauma Acute Care Surg. 2024;97(2S Suppl 1):S138-44.
7. Walsh M, Fries D, Moore E, Moore H, Thomas S, Kwaan HC, et al. Whole blood for civilian urban trauma resuscitation: historical, present, and future considerations. Semin Thromb Hemost. 2020;46(2):221-34.
8. Jones AR, Miller JL, Jansen JO, Wang HE. Whole blood for resuscitation of traumatic hemorrhagic shock in adults. Adv Emerg Nurs J. 2021;43(4):344-54.
9. Johnson T, Mack TJ, Burke R, Damiano N, Heger L, Minner N, et al. Whole blood trauma resuscitation in community trauma centers confers survival benefit over component therapy. Am Surg. 2023;89(7):3148-52.
10. Malkin M, Nevo A, Brundage SI, Schreiber M. Effectiveness and safety of whole blood compared to balanced blood components in resuscitation of hemorrhaging trauma patients - A systematic review. Injury. 2021;52(2):182-8.
11. Lee JS, Khan AD, Wright FL, McIntyre RC Jr, Dorlac WC, Cribari C, et al. Whole blood versus conventional blood component massive transfusion protocol therapy in civilian trauma patients. Am Surg. 2022;88(5):880-6.
12. García AF, Caicedo Y, Gempeler A, Vallecilla L, Macia C, Orlas C, et al. Transfusion of modified whole blood versus blood components therapy in patients with severe trauma: randomized controlled trial protocol (WEBSTER trial). Injury. 2025;56(5):112173.
13. Cotton BA, Podbielski J, Camp E, Welch T, del Junco D, Bai Y, et al.; Early Whole Blood Investigators. A randomized controlled pilot trial of modified whole blood versus component therapy in severely injured patients requiring large volume transfusions. Ann Surg. 2013;258(4):527-32.
14. Fergusson D, Aaron SD, Guyatt G, Hébert P. Post-randomisation exclusions: the intention to treat principle and excluding patients from analysis. BMJ. 2002;325(7365):652-4.
15. García AF, Manzano-Nunez R, Carrillo DC, Chica-Yanten J, Naranjo MP, Sánchez ÁI, et al. Hypertonic saline infusion does not improve the chance of primary fascial closure after damage control laparotomy: a randomized controlled trial. World J Emerg Surg. 2023;18(1):4.
16. Brunner E, Vandemeulebroecke M, Mütze T. Win odds: an adaptation of the win ratio to include ties. Stat Med. 2021;40(14):3367-84.
17. Bebu I, Lachin JM. Large sample inference for a win ratio analysis of a composite outcome based on prioritized components. Biostatistics. 2016;17(1):178-87.
18. Bursac Z, Gauss CH, Williams DK, Hosmer DW. Purposeful selection of variables in logistic regression. Source Code Biol Med. 2008;3(1):17.

---

*Tradução não oficial gerada por IA. Consulte o artigo original: https://criticalcarescience.org/article/statistical-analysis-plan-for-transfusion-of-modified-whole-blood-versus-blood-components-therapy-in-patients-with-severe-trauma-randomized-controlled-trial-webster-trial/*
