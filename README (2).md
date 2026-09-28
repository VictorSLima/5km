# Rumo aos 5 km

Tracker da família para os 5 km da Maratona Internacional de São Paulo (27/01/2027).

## 1. Planilha (onde os checks ficam salvos)

1. Crie uma planilha Google nova.
2. Vá em **Extensões > Apps Script**, apague o conteúdo e cole o `apps-script.gs`.
3. Clique em **Implantar > Nova implantação**, tipo **App da Web**.
   - Executar como: **Eu**
   - Quem pode acessar: **Qualquer pessoa**
4. Autorize e copie a URL que termina em `/exec`.

## 2. Site

1. Abra o `index.html` e cole a URL na linha `const SCRIPT_URL = "";`.
2. Crie um repositório no GitHub (ex.: `corrida-5k`) e suba o `index.html`.
3. Em **Settings > Pages**, escolha a branch `main` e a pasta `/ (root)`.
4. O site fica em `https://SEU-USUARIO.github.io/corrida-5k/`.

Sem a URL configurada, o site funciona em modo teste (checks salvos só no aparelho).

## Pontuação

- Corrida ou treino: 10
- Fortalecimento: 5
- Treino em família: 15
- Semana completa: +10 de bônus
