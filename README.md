# Mari Nutrição · Análise Clínica

Site de análise clínica para nutricionista — formulários pré-consulta e exames laboratoriais via IA (Gemini).

🔗 **Site:** https://fakefelps.github.io/mari-nutri/

---

## Setup

### 1. Inserir a API Key do Gemini

Abra o `index.html` e substitua na linha:

```js
const GEMINI_KEY = 'SUA_API_KEY_AQUI';
```

pela sua key gerada em [aistudio.google.com/apikey](https://aistudio.google.com/apikey) (começa com `AIzaSy...`).

### 2. Ativar o GitHub Pages

1. Vá em **Settings → Pages**
2. Em *Source*, selecione **GitHub Actions**
3. Salve

O deploy acontece automaticamente a cada `push` na branch `main`.

---

## Funcionalidades

| Aba | O que faz |
|---|---|
| Formulário Pré-consulta | Upload do PDF → análise estruturada do paciente (objetivos, histórico, hábitos, pontos de atenção) |
| Exames Laboratoriais | Upload do laudo → classificação em quartis/tercis com badges coloridos por seção |

---

## Stack

- HTML/CSS/JS puro · GitHub Pages · Gemini 1.5 Flash API
