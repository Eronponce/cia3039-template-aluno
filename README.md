# Template inicial — Projeto CIA@3039

Este repositório é o ponto de partida da atividade. O `app.py` já cria as quatro abas do Streamlit, mas deixa as análises para o grupo implementar.

Leia primeiro o [enunciado da atividade](ATIVIDADE.md). Use o arquivo `data/sensores.csv` fornecido e complete as tarefas indicadas em cada aba.

## Executar

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
streamlit run app.py
```

## Arquivos

- `app.py`: página inicial com as quatro abas e orientações sobre o que implementar.
- `ATIVIDADE.md`: enunciado, entregáveis e critérios de avaliação.
- `data/sensores.csv`: leituras simuladas para usar no projeto.
- `requirements.txt`: dependências iniciais.

O template não contém o modelo treinado nem as visualizações prontas. O grupo deve implementar essas partes, testar a aplicação e explicar as decisões no README.
