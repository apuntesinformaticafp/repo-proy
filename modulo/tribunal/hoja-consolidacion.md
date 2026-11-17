# Folla de consolidación de Proxecto DAM

**Rexistro consolidado · repo-proy · Curso 2026–2027**

Crear unha copia deste modelo e aplicar a [rúbrica](../rubrica.md), sen
criterios nin pesos adicionais. A copia cuberta é privada: non se incorpora
ao repositorio público nin ao do estudante.

Reunir as [follas individuais](hoja-individual.md), conservar as correccións
xustificadas e consolidar as puntuacións na folla de cálculo privada.
Este rexistro non é unha valoración adicional. O
[fluxo da guía](../guia.md#fluxo-de-traballo) explica o procedemento.

O arquivo é dixital e privado; o papel é apoio temporal. A validación
segue o procedemento institucional, sen obriga de arquivo permanente en papel.

## 1. Referencia da avaliación

| Campo                                                              | Valor por completar |
| ------------------------------------------------------------------ | ------------------- |
| Código non identificativo do proxecto                              |                     |
| Período / data da avaliación                                       |                     |
| Versión da programación e da rúbrica aplicadas (commit ou edición) |                     |
| Versión do repositorio avaliado (etiqueta e commit resolto)        |                     |
| Versión da síntese e correspondencia co repositorio                |                     |
| Referencia privada do informe automatizado, se existe              |                     |
| Estado do rexistro: proposta / revisión / valoración final         |                     |

Non se incorporan nomes, correos, URLs privadas nin credenciais a este modelo.
As correspondencias de identidade e a formalización nominal do tribunal
consérvanse polos procedementos institucionais restrinxidos que correspondan.

## 2. Escala común

| Nivel                   | Coeficiente |
| ----------------------- | ----------: |
| Sen evidencia avaliable |           0 |
| Insuficiente            |        0,25 |
| Básico                  |        0,50 |
| Adecuado                |        0,75 |
| Avanzado                |           1 |

Puntos = máximo × coeficiente. Marcar como **pendente** o que aínda non foi
revisado ou observado: pendente non significa cero. Usar cero só cando
corresponda a ausencia de evidencia avaliable segundo a rúbrica.

## 3. Proposta automatizada do repositorio

Usar esta táboa se hai unha proposta automatizada validada. Noutro caso,
revisar manualmente coa mesma rúbrica. A ausencia ou o fallo da ferramenta
non penaliza o alumnado.

| Indicador                                       | Máximo | Nivel proposto | Puntos propostos | Evidencia localizable e xustificación | Límites / pendente de revisión |
| ----------------------------------------------- | -----: | -------------- | ---------------- | ------------------------------------- | ------------------------------ |
| R1 · Contexto, necesidade e alcance             |      1 |                |                  |                                       |                                |
| R2 · Deseño técnico e datos                     |      1 |                |                  |                                       |                                |
| R3 · Recursos, custos e condicionantes          |      1 |                |                  |                                       |                                |
| R4 · Planificación, execución e riscos          |      1 |                |                  |                                       |                                |
| R5 · Seguimento, decisións e cambios            |      1 |                |                  |                                       |                                |
| R6 · Validación documentada e reproducibilidade |      1 |                |                  |                                       |                                |
| **Subtotal proposto, non definitivo**           |  **6** |                |                  |                                       |                                |

O informe identificará a versión, as comprobacións realizadas, os resultados
e os seus límites. Non se trasladan automaticamente os puntos á nota final.

## 4. Valoración revisada polo profesorado e polo tribunal

Trasladar as puntuacións das follas individuais de **T1, T2 e T3**,
con referencia ao nivel, descriptor e evidencia de cada unha. Se difiren da
proposta automatizada, xustificar a diferenza. A proposta non se suma nin
se promedia como unha cuarta valoración. **A persoa titora non puntúa.**

| Indicador                                         | Máximo | Puntos T1 | Puntos T2 | Puntos T3 | Media | Evidencia / referencias ás follas e correccións |
| ------------------------------------------------- | -----: | --------- | --------- | --------- | ----- | ----------------------------------------------- |
| R1 · Contexto, necesidade e alcance               |      1 |           |           |           |       |                                                 |
| R2 · Deseño técnico e datos                       |      1 |           |           |           |       |                                                 |
| R3 · Recursos, custos e condicionantes            |      1 |           |           |           |       |                                                 |
| R4 · Planificación, execución e riscos            |      1 |           |           |           |       |                                                 |
| R5 · Seguimento, decisións e cambios              |      1 |           |           |           |       |                                                 |
| R6 · Validación documentada e reproducibilidade   |      1 |           |           |           |       |                                                 |
| P1 · Síntese escrita                              |    0,5 |           |           |           |       |                                                 |
| P2 · Exposición e respostas                       |    1,5 |           |           |           |       |                                                 |
| D1 · Preparación da versión e demostración do MVP |      2 |           |           |           |       |                                                 |

`media_i = (puntos_T1_i + puntos_T2_i + puntos_T3_i) / 3`.
Non converter a media a un nivel discreto nin redondeala. As follas individuais
conservan os niveis e coeficientes orixinais. Unha casilla pendente debe
resolverse antes de pechar a nota; non se substitúe por cero nin pola
valoración do tutor ou da ferramenta.

### Resumo da puntuación

| Bloque                                        | Máximo | Puntos finais            |
| --------------------------------------------- | -----: | ------------------------ |
| Repositorio: suma R1–R6                       |      6 |                          |
| Presentación: P1 + P2                         |      2 |                          |
| Demo: D1                                      |      2 |                          |
| **Puntuación interna total**                  | **10** |                          |
| Cualificación oficial enteira                 |        | `max(1, floor(S + 0.5))` |
| Resultado: nota oficial igual ou superior a 5 |        |                          |

S é a suma das nove medias. Só se redondea ese total ao enteiro máis próximo,
co medio punto cara arriba: 4,49 → 4; 4,50 → 5; 7,50 → 8. Non usar `ceil`
nin redondeo bancario. Non calcular unha nota final con indicadores pendentes.
O aprobado compróbase sobre a nota oficial, non esixindo 5 antes de redondear.

## 5. Rexistro de presentación e demo

Estas observacións sustentan os indicadores, non crean subpuntos nin
penalizacións novas.

| Actuación observada                                           | Evidencia e observación |
| ------------------------------------------------------------- | ----------------------- |
| Síntese: versión, extensión e correspondencia documental      |                         |
| Exposición: explicación e comprensión das decisións           |                         |
| Preguntas formuladas e fundamento das respostas               |                         |
| Demo: versión concreta e relación co código entregado         |                         |
| Construción ou preparación e arranque; pasos preparados antes |                         |
| Percorrido funcional esencial                                 |                         |
| Almacén real e persistencia con datos ficticios               |                         |
| Comprobación de erro, límite ou variación, cando se mostre    |                         |
| Partes simuladas, limitacións e resultados non comprobados    |                         |
| Incidencias e comprobacións que si se puideron realizar       |                         |

Unha incidencia debe describirse antes de asignar o nivel. Non implica un
cero automático, unha segunda oportunidade automática nin un desconto fixo.
Non facer demo e non facer exposición rexístranse separadamente.

## 6. Comprobación de cobertura dos criterios

Para cada CA anotar **evidencia e grao de cobertura**: acreditado,
parcial, sen evidencia ou pendente. Estas etiquetas son un apoio de revisión,
non niveis de nota adicionais nin condicións independentes de superación.

Os literais completos figuran no [anexo curricular](../programacion.md#anexo-curricular). Todos
teñen un indicador principal. En D1 rexístrase a execución práctica, non
unha segunda nota polo mesmo documento.

| CA     | Indicador principal | Evidencia / grao de cobertura / carencia relevante |
| ------ | ------------------- | -------------------------------------------------- |
| CA1.1  | R1                  |                                                    |
| CA1.2  | R1                  |                                                    |
| CA1.3  | R1                  |                                                    |
| CA1.4  | R1                  |                                                    |
| CA1.5  | R1                  |                                                    |
| CA1.6  | R1                  |                                                    |
| CA1.7  | R3                  |                                                    |
| CA1.8  | R3                  |                                                    |
| CA1.9  | R4                  |                                                    |
| CA2.1  | R1                  |                                                    |
| CA2.2  | R1                  |                                                    |
| CA2.3  | R1                  |                                                    |
| CA2.4  | R1                  |                                                    |
| CA2.5  | R3                  |                                                    |
| CA2.6  | R3                  |                                                    |
| CA2.7  | R3                  |                                                    |
| CA2.8  | R2                  |                                                    |
| CA2.9  | R2                  |                                                    |
| CA3.1  | R4                  |                                                    |
| CA3.2  | R4                  |                                                    |
| CA3.3  | R4                  |                                                    |
| CA3.4  | R4                  |                                                    |
| CA3.5  | R4                  |                                                    |
| CA3.6  | R4                  |                                                    |
| CA3.7  | R3                  |                                                    |
| CA3.8  | R4                  |                                                    |
| CA4.1  | R6                  |                                                    |
| CA4.2  | R6                  |                                                    |
| CA4.3  | R5                  |                                                    |
| CA4.4  | R5                  |                                                    |
| CA4.5  | R6                  |                                                    |
| CA4.6  | R6                  |                                                    |
| CA4.7  | R6                  |                                                    |
| CA5.1  | P1                  |                                                    |
| CA5.2  | P1                  |                                                    |
| CA5.3  | P1                  |                                                    |
| CA5.4  | P1                  |                                                    |
| CA5.5  | P1                  |                                                    |
| CA5.6  | P1                  |                                                    |
| CA5.7  | P1                  |                                                    |
| CA5.8  | P1                  |                                                    |
| CA5.9  | P2                  |                                                    |
| CA5.10 | P2                  |                                                    |

## 7. Peche e devolución

- [ ] Revisouse a versión declarada e identificouse a rúbrica aplicable.
- [ ] Cada indicador ten as tres valoracións individuais e a súa xustificación.
- [ ] Contrastouse a proposta automatizada e xustificáronse as correccións.
- [ ] Revisáronse os 43 CA sen introducir mínimos por criterio.
- [ ] Diferenciáronse deseño, validación documentada e execución demostrada.
- [ ] Calculáronse as medias T1–T3 e a suma 6 + 2 + 2 sen redondeos intermedios.
- [ ] A titoría e a proposta automatizada non contan como puntuacións adicionais.
- [ ] Non se introduciron descontos nin requisitos non publicados.
- [ ] As incidencias, discrepancias e actuacións pendentes quedaron rexistradas.
- [ ] Só se redondeou o total ao enteiro máis próximo, co medio punto cara arriba.
- [ ] O aprobado comprobouse coa nota oficial igual ou superior a 5.
- [ ] A copia cuberta gardouse no espazo docente privado.

### Devolución breve

| Aspecto                                                                 | Observación |
| ----------------------------------------------------------------------- | ----------- |
| Fortalezas acreditadas                                                  |             |
| Melloras prioritarias e evidencias necesarias                           |             |
| Actuacións de recuperación, se proceden conforme ao calendario aprobado |             |

A devolución individual revisarase antes de comunicala. Esta folla non se
publicará nin se enviará automaticamente a terceiros.
