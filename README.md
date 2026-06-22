# Consultório da Mari · Análise Clínica

Ferramenta de análise clínica da nutricionista Mariana Borges — processamento de formulários pré-consulta e exames laboratoriais via IA.

🔗 **Site:** https://marianaborgesnutri.github.io/site/

---

## Funcionalidades

| Aba | O que faz |
|---|---|
| Formulário Pré-consulta | Upload do PDF exportado do Google Forms → análise estruturada por seções (dados pessoais, rotina, histórico, hábitos alimentares) com cálculo de IMC, água recomendada e análise de medicamentos |
| Exames Laboratoriais | Upload do laudo → classificação em quartis (Q1–Q4) e tercis para tireoide (T1–T3), com badges coloridos e resumo de pontos de atenção clínica |

---

## Setup

### 1. Inserir a API Key do Gemini

Abra o `index.html` e substitua na linha:

```js
const GEMINI_KEY = 'SUA_API_KEY_AQUI';
```

pela sua key gerada em [aistudio.google.com/apikey](https://aistudio.google.com/apikey).

### 2. Ativar o GitHub Pages

1. Vá em **Settings → Pages**
2. Em *Source*, selecione **GitHub Actions**
3. Salve

O deploy acontece automaticamente a cada `push` na branch `main`.

---

## Stack

- HTML / CSS / JS puro · GitHub Pages · Gemini API
