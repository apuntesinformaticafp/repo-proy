# Rúbrica pública de Proxecto DAM — 2026–2027

**Curso 2026–2027 · repo-proy**

Única rúbrica para alumnado e profesorado. Os formatos e límites figuran
na [guía](guia.md) e os criterios oficiais, no
[anexo da programación](programacion.md#anexo-curricular).

A [folla individual](tribunal/hoja-individual.md) e a
[folla de consolidación](tribunal/hoja-consolidacion.md) rexistran evidencias,
puntos e xustificacións, sen requisitos adicionais. O
[fluxo de traballo](guia.md#fluxo-de-traballo) distingue o informe previo
do repositorio, de ata 6 puntos, da valoración final.

As rutas das evidencias (`docs/`, `proyecto/README.md`, `proyecto/src/`,
`proyecto/tests/` e `proyecto/datos/`) son relativas á raíz do repositorio.

## 1. Estrutura e escala

| Bloque       | Indicadores                                       | Máximo |
| ------------ | ------------------------------------------------- | -----: |
| Repositorio  | R1–R6: un punto cada un                           |      6 |
| Presentación | P1: síntese, 0,5; P2: exposición e respostas, 1,5 |      2 |
| Demo         | D1: construción/preparación e demostración do MVP |      2 |
| **Total**    |                                                   | **10** |

| Nivel                   | Coeficiente |
| ----------------------- | ----------: |
| Sen evidencia avaliable |           0 |
| Insuficiente            |        0,25 |
| Básico                  |        0,50 |
| Adecuado                |        0,75 |
| Avanzado                |           1 |

**Puntos = máximo do indicador × coeficiente do nivel.**

Os **tres membros do tribunal** puntúan cada indicador. A persoa titora
acompaña e coordina, pero non puntúa. A proposta automatizada non conta
como outra valoración.

Para cada indicador faise a media aritmética dos seus puntos:
`media_i = (T1_i + T2_i + T3_i) / 3`. A media pode quedar entre dous niveis
da escala; non se forza a un nivel nin se redondea. Súmanse as nove medias,
sen redondear indicadores nin subtotais.

Só o total S se redondea ao **enteiro máis próximo, co medio punto cara
arriba**. Para unha cualificación numérica entre 1 e 10:
`nota = max(1, floor(S + 0.5))`. Así, 4,49 → 4; 4,50 → 5; 7,50 → 8.
Non se utiliza `ceil` nin redondeo bancario.

Apróbase coa **nota oficial igual ou superior a 5**, sen mínimos
independentes. Non ter MVP, non facer demo ou non defender non anula os
demais bloques.
Se falta unha das tres valoracións, debe resolverse antes de pechar a nota,
sen atribuír cero á casilla nin substituíla pola do tutor ou a automatizada.

## 2. Indicadores do repositorio — 6 puntos

### R1. Contexto, necesidade e alcance — 1 punto

**Evidencias:** `docs/01-contexto.md` e `docs/02-alcance.md`.
**CA principais:** CA1.1–CA1.6, CA2.1–CA2.4.

| Nivel        | Descriptor                                                                                                                                                                                        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | A necesidade é xenérica ou pouco xustificada; non se entende a quen se dirixe a solución, que resolve ou cal é o alcance viable.                                                                  |
| Básico       | Identifica un contexto profesional e destinatarios concretos; caracteriza brevemente o sector; define obxectivos, fases, exclusións e un alcance viable, considerando unha alternativa relevante. |
| Adecuado     | Relaciona a necesidade coa organización e funcións de empresas tipo, demandas e oportunidades do sector; compara alternativas e xustifica alcance e viabilidade con información pertinente.       |
| Avanzado     | Contrasta fontes e supostos decisivos, fundamenta a elección e identifica incertezas e condicións que obrigarían a revisar o alcance, sen necesitar máis funcionalidades.                         |

### R2. Deseño técnico e datos — 1 punto

**Evidencias:** `docs/03-diseno.md`, diagramas e modelo de datos.
**CA principais:** CA2.8, CA2.9.

| Nivel        | Descriptor                                                                                                                                                                                         |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | O deseño non permite comprender os compoñentes, as relacións ou os datos, ou contradí o alcance en aspectos esenciais.                                                                             |
| Básico       | Explica compoñentes e interaccións, o almacén de datos, a estrutura esencial e o acceso; identifica os aspectos de calidade relevantes.                                                            |
| Adecuado     | Permite seguir un percorrido de datos entre interface, lóxica e persistencia; xustifica as decisións e contempla os aspectos pertinentes de integridade, seguridade, usabilidade e accesibilidade. |
| Avanzado     | Contrasta alternativas e compromisos, identifica riscos e xustifica os controis e as decisións principais, distinguindo o deseñado do implementado.                                                |

Un bo deseño documentado non acredita por si mesmo funcionamento: iso
compróbase na demo.

### R3. Recursos, custos e condicionantes — 1 punto

**Evidencias:** `docs/04-recursos.md`, fontes e referencias pertinentes.
**CA principais:** CA1.7–CA1.8, CA2.5–CA2.7, CA3.7.

| Nivel        | Descriptor                                                                                                                                                                                           |
| ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | Omite recursos, custos, financiamento ou condicionantes relevantes, ou nega a súa existencia sen análise.                                                                                            |
| Básico       | Identifica recursos materiais e humanos, estima custos e financiamento e examina obrigas fiscais, laborais e preventivas, axudas e licenzas; xustifica os casos sen custo ou sen aplicación directa. |
| Adecuado     | Presenta unha estimación coherente co alcance, distingue desembolsos e outros custos e apoia os condicionantes e axudas en fontes identificables.                                                    |
| Avanzado     | Analiza os supostos económicos e legais decisivos e o efecto dunha variación sobre a viabilidade, sen unha análise empresarial innecesaria.                                                          |

Non se esixe contratar servizos nin solicitar axudas reais.

### R4. Planificación, execución e riscos — 1 punto

**Evidencias:** `docs/05-planificacion.md`, tarefas e diagramas de planificación.
**CA principais:** CA1.9, CA3.1–CA3.6, CA3.8.

| Nivel        | Descriptor                                                                                                                                        |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | O plan non ofrece unha secuencia utilizable ou omite recursos, tempos, procedementos ou riscos esenciais.                                         |
| Básico       | Ordena tarefas e fitos, estima tempos e recursos e identifica permisos, procedementos de execución e riscos pertinentes, con medidas preventivas. |
| Adecuado     | Relaciona tarefas, dependencias, recursos e prazos e explica a execución e a xestión de riscos cun plan coherente co alcance.                     |
| Avanzado     | Xustifica estimacións e prioridades, identifica tarefas críticas e prevé alternativas proporcionadas ante restricións ou atrasos.                 |

Non se inventarán persoal, permisos ou riscos para completar unha lista:
analízanse e xustifícanse os pertinentes.

### R5. Seguimento, decisións e cambios — 1 punto

**Evidencias:** `docs/06-seguimento.md`, revisións e rexistros referenciados.
**CA principais:** CA4.3–CA4.4.

| Nivel        | Descriptor                                                                                                                             |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | Non permite reconstruír o avance e as decisións esenciais, ou non define como xestionar incidencias e cambios.                         |
| Básico       | Define detección, resolución e rexistro de incidencias e cambios; conserva as revisións e decisións esenciais.                         |
| Adecuado     | Contrasta avance e plan e xustifica axustes e consecuencias. Se non houbo cambios relevantes, explica esa estabilidade con evidencias. |
| Avanzado     | Detecta anticipadamente desviacións ou riscos, compara opcións e fundamenta decisións que preservan os obxectivos esenciais.           |

Non se puntúa o número de commits nin se esixe inventar incidencias.

### R6. Validación documentada e reproducibilidade — 1 punto

**Evidencias:** `proyecto/README.md`, `docs/07-validacion.md`, scripts, manifests, bloqueos,
preparación dos datos, probas e rexistros.
**CA principais:** CA4.1–CA4.2, CA4.5–CA4.7.

| Nivel        | Descriptor                                                                                                                                                                                                                                                   |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Insuficiente | Afirma funcionamento sen comprobacións claras ou as instrucións non permiten preparar e revisar a versión entregada.                                                                                                                                         |
| Básico       | Identifica versión e requisitos e documenta como construír ou preparar, cargar datos ficticios e executar; define comprobacións, indicadores e rexistros, participación de usuarios e control do prego cando exista; distingue resultados reais e previstos. |
| Adecuado     | O procedemento é reproducible con ferramentas e dependencias identificadas; relaciona comprobacións e obxectivos e documenta condicións, resultados, fallos e límites; inclúe os documentos de participación de usuarios e control das condicións acordadas. |
| Avanzado     | Xustifica as comprobacións e os seus límites, permite reconstruír o contorno de revisión e deriva melloras concretas das discrepancias, sen depender de instrucións verbais non documentadas.                                                                |

Valórase a reproducibilidade documentada, non a mera existencia dun script
ou dun ficheiro de bloqueo. Non se prescribe unha tecnoloxía nin unha
construción binaria bit a bit. Sen MVP, valóranse os procedementos e
documentos existentes, sen atribuír resultados de execución inexistentes.
Non se esixe unha persoa cliente real.

## 3. Presentación — 2 puntos

### P1. Síntese escrita — 0,5 puntos

**Evidencias:** `docs/sintese.pdf`, máximo dúas páxinas, e a mesma copia impresa.
**CA principais:** CA5.1–CA5.8.

| Nivel        | Descriptor                                                                                                                                              |
| ------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | A síntese é confusa, omite aspectos esenciais ou contradí as evidencias do repositorio.                                                                 |
| Básico       | Resume obxectivos, necesidade, solución, decisións do proceso, resultados e conclusións de forma comprensible, con referencia á versión do repositorio. |
| Adecuado     | Selecciona o esencial en dúas páxinas, explica as decisións de planificación e control e relaciona resultados, límites e melloras coas evidencias.      |
| Avanzado     | Sintetiza criticamente: distingue feitos, supostos e pendentes e fundamenta conclusións e melloras sen repetir a documentación.                         |

Puntúase a síntese comunicativa, non de novo a calidade técnica.
A falta de papel non implica cero automático se hai PDF avaliable.

O tribunal le a síntese impresa nos primeiros cinco minutos da franxa,
antes da exposición e sen consumir o seu tempo. A convocatoria indica
o número de copias.

### P2. Exposición e respostas — 1,5 puntos

**Evidencias:** exposición individual con apoios informáticos e respostas.
**CA principais:** CA5.9–CA5.10.

| Nivel        | Descriptor                                                                                                                        |
| ------------ | --------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | Non explica decisións esenciais ou as respostas revelan carencias importantes de comprensión do traballo.                         |
| Básico       | Explica con orde a necesidade, solución e resultados e responde suficientemente ás aclaracións, con apoios axeitados.             |
| Adecuado     | Xustifica decisións relevantes, distingue realizado e previsto e responde con fundamento sobre proceso, resultados e límites.     |
| Avanzado     | Razoa sobre alternativas e consecuencias ante escenarios novos, recoñece límites e mantén unha explicación clara e proporcionada. |

Os nervios ou necesitar aclaración dunha pregunta non implican insuficiencia.
Sen exposición e respostas, cero en P2; P1 e os demais bloques mantéñense.

A exposición está prevista para todo o alumnado polo currículo. Esta regra
de puntuación non a converte en optativa: as incidencias de participación
tramítanse polo procedemento do centro, segundo a programación.

## 4. Demo — 2 puntos

### D1. Preparación da versión e demostración do MVP — 2 puntos

**Evidencias:** construción ou preparación desde unha etiqueta/commit,
arranque e demostración con datos ficticios e persistencia real.

É unha comprobación práctica complementaria do deseño e a validación
(CA2.8–CA2.9 e CA4.1–CA4.2), non unha segunda puntuación polos documentos
nin un criterio curricular novo.

| Nivel        | Descriptor                                                                                                                                                                                                                                                  |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Insuficiente | Mostra unha parte executable pero non permite relacionar o executado coa versión entregada, completar o percorrido esencial ou comprobar a persistencia; non explica suficientemente erros ou simulacións.                                                  |
| Básico       | Identifica a versión, móstraa construíndo ou preparando e arranca a aplicación; completa un percorrido esencial con datos ficticios, identifica o almacén e comproba persistencia entre execucións ou sesións; distingue partes reais, simuladas e límites. |
| Adecuado     | Ademais, comproba un erro ou límite pertinente, explica os resultados e permite seguir a relación entre operación e datos almacenados; o proceso de preparación e execución é claro e repetible.                                                            |
| Avanzado     | Contrasta os riscos ou supostos máis relevantes mediante comprobacións seleccionadas, interpreta resultados e responde a unha variación razoable da proba; mostra control do proceso, non máis funcionalidades nin infraestrutura máis complexa.            |

Nunha aplicación interpretada, preparar o contorno e iniciar a versión
identificada equivale á preparación executable; non se obriga a producir
un binario. O despregamento pode ser local. Se se utiliza unha versión
despregada, deberá identificarse e vincularse ao código entregado.

Pode prepararse antes a descarga inicial de dependencias, declarándoo.
Non é necesario reinstalar todo o contorno durante a demo. Non chega con
ensinar un binario de procedencia non comprobable ou unha URL sen versión.

**Sen demo avaliable: cero en D1.** Un fallo non determina un cero automático:
valórase o comprobado e os seus límites sen descontos adicionais improvisados.
As incidencias rexístranse coas evidencias comprobadas. Unha comprobación
adicional, se é necesaria, tramítase conforme ao procedemento do centro
e dentro dos prazos da convocatoria; non se garante unha segunda demo.

## 5. Aplicación común e revisión automatizada

- Sen evidencia avaliable, cero no indicador correspondente. Evidencia
  incompleta non equivale automaticamente a ausencia.
- Asígnase o nivel máis alto cuxos elementos esenciais estean acreditados,
  identificando os cumpridos e os ausentes. Non hai medias ocultas por CA.
- Cada nivel terá xustificación breve e evidencia localizable: ruta,
  sección, proba ou actuación. Non se aplicarán descontos fixos adicionais.
- A automatización propoñerá R1–R6 sobre a versión identificada, distinguindo
  comprobacións obxectivas e interpretación asistida; non inventará evidencias.
- Un aspecto non comprobable pola ferramenta pasa a revisión docente: non
  é automaticamente cero. A revisión manual coa mesma rúbrica cobre os
  aspectos non comprobados por ferramentas automatizadas validadas.
- A persoa responsable revisa; o tribunal refrenda ou corrixe razoadamente.
  P2 e D1 requiren observación humana; P1 valora a síntese, non só o formato.
- Os tres membros puntúan por separado; a titoría revisa e consolida sen
  outorgar unha cuarta puntuación. As discrepancias deben ter evidencias
  e xustificación, sen substituír a media por unha nota de consenso distinta.
- Non se executará código sen illamento e autorización nin se enviarán
  contidos persoais ou confidenciais a servizos externos sen autorización.
- Os informes e valoracións individuais son privados, non parte da plantilla.

R2 valora o deseño, R6 os procedementos e as evidencias documentadas e D1 a
execución observada. Compartir unha referencia curricular non autoriza a
contar dúas veces o mesmo mérito. Na folla deixarase constancia do aspecto
distinto comprobado en cada indicador.

A lista de CA da folla serve para comprobar cobertura, non para establecer
un aprobado independente en cada criterio. Unha carencia deberá quedar
visible na xustificación do nivel do indicador ao que pertence, sen crear
descontos fóra da escala.

## 6. Exemplos de cálculo

| Caso                                                          | Repositorio | Síntese | Exposición | Demo |    Total |
| ------------------------------------------------------------- | ----------: | ------: | ---------: | ---: | -------: |
| Básico en todos os indicadores                                |           3 |    0,25 |       0,75 |    1 |    **5** |
| Adecuado en todos                                             |         4,5 |   0,375 |      1,125 |  1,5 |  **7,5** |
| Repositorio e presentación adecuados, sen demo                |         4,5 |   0,375 |      1,125 |    0 |    **6** |
| Repositorio avanzado, síntese básica, sen exposición nin demo |           6 |    0,25 |          0 |    0 | **6,25** |

As notas son exemplos, non presuncións sobre un proxecto real. O último
caso ilustra o aprobado global sen mínimos, non que calquera texto ben
presentado mereza seis puntos.

Os totais da táboa son puntuacións internas antes de redondear: 5 → 5;
7,5 → 8; 6 → 6; 6,25 → 6. As valoracións por nivel representan casos nos
que os tres membros coinciden.

## 7. Organización e devolución

O [calendario](calendario.md) fixa a organización común: cinco minutos
iniciais de lectura, ata quince minutos de exposición **incluíndo a demo**
e ata dez minutos de preguntas.

O informe final identifica a versión avaliada, as tres puntuacións por
indicador, as medias, o total sen redondear, a cualificación oficial e as
melloras necesarias. As actuacións de recuperación céntranse nesas melloras
e nos prazos da convocatoria comunicados pola aula virtual.

Os rexistros cubertos consérvanse en formato dixital nun espazo privado.
As follas en papel, se se usan, son apoio temporal.
