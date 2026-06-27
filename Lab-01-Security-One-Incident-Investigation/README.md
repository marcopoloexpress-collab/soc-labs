# 🛡️ Lab 01 - Investigação de Incidente utilizando Security One

## 🎯 Objetivo

Investigar um incidente utilizando uma plataforma Security Operations Center (SOC), identificando sua severidade, analisando evidências e compreendendo seu impacto.

---

## 🖥️ Ambiente

| Item | Valor |
|------|-------|
| Plataforma | Security One |
| Tipo | Ambiente de treinamento |
| Área | Security Operations Center (SOC) |

---

## 📖 Cenário

Neste laboratório foi realizada a investigação do incidente **#12882**, disponibilizado no ambiente de treinamento da plataforma Security One.

O objetivo foi compreender o fluxo inicial de investigação executado por um Analista SOC.

---

## 🔍 Passo 1 – Acessando o Dashboard

O Dashboard apresenta uma visão geral do ambiente, incluindo indicadores de risco, mapa de ataques, incidentes recentes e estatísticas de monitoramento.

**Figura 1 – Dashboard da plataforma**

![Dashboard](images/01-dashboard-home.jpg)

---

## 🔍 Passo 2 – Localizando o incidente

Foi realizada a pesquisa pelo incidente **#12882**, identificado com severidade **Crítica** e status **Fechado**.

**Figura 2 – Pesquisa do incidente**

![Pesquisa](images/02-incident-search.jpg)

---

## 🔍 Passo 3 – Análise dos detalhes

Na tela de detalhes foi possível analisar:

- Resumo do incidente
- Evidências
- Impacto
- Classificação
- Escopo afetado
- Linha do tempo

**Figura 3 – Detalhes do incidente**

![Detalhes](images/03-incident-details.png)

# 🛡️ MITRE ATT&CK

Durante a investigação foi possível identificar técnicas associadas ao framework **MITRE ATT&CK**, utilizadas para classificar o comportamento observado no incidente.

| Tática | Técnica | Descrição |
|---------|----------|-----------|
| TA0001 | T1078 | Valid Accounts |
| TA0001 | T1550 | Use of Session Tokens |

## Interpretação

O incidente demonstra uma tentativa de utilização indevida de uma sessão autenticada para realizar uma transação financeira não autorizada. O uso de credenciais válidas e tokens de sessão caracteriza técnicas frequentemente observadas em ataques de **Account Takeover (ATO)** e **Session Hijacking**.

---

# 🎯 Impacto

O incidente representa uma tentativa de fraude financeira utilizando uma sessão comprometida.

Embora a transação tenha sido bloqueada pelo mecanismo antifraude, a investigação evidenciou indícios de comprometimento da sessão autenticada, justificando a classificação de severidade **Crítica**.

---

# 🧠 Competências Desenvolvidas

- Investigação de Incidentes
- Incident Triage
- Análise de Evidências
- Classificação de Incidentes
- Correlação de Eventos
- MITRE ATT&CK
- SOC Operations

---

# 📚 Lições Aprendidas

Este laboratório permitiu compreender o fluxo inicial de investigação de um incidente em uma plataforma SOC, desde a identificação do alerta até a análise das evidências, impacto e classificação segundo o framework MITRE ATT&CK.

---

# ✅ Conclusão

Este laboratório demonstrou como um Analista SOC realiza a investigação inicial de um incidente em uma plataforma de monitoramento, analisando evidências, impacto, classificação e técnicas associadas ao MITRE ATT&CK. A atividade reforçou conceitos fundamentais de triagem, investigação e documentação utilizados em operações de Blue Team.

