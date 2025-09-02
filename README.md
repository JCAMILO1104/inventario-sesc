
# Inventário Patrimonial - SESC Administração Central

Aplicação interativa em Dash para análise gerencial do inventário patrimonial.

## Funcionalidades
- Dashboards interativos com gráficos de valor, UO, ano de aquisição, localização, tipo, empresa, etc.
- Upload de novos arquivos Excel para atualização dos dados.
- Relatório conclusivo integrado.

## Instalação
```bash
pip install -r requirements.txt
```

## Execução
```bash
python inventario_sesc_dash.py
```

## Publicação no Render
1. Crie um repositório no GitHub com os arquivos:
   - inventario_sesc_dash.py
   - requirements.txt
   - Relatório Conclusivo SESC Administração Central (1).xlsx

2. Acesse https://render.com, clique em "New Web Service" e selecione "Deploy from GitHub".

3. Configure:
   - Environment: Python
   - Build Command: `pip install -r requirements.txt`
   - Start Command: `python inventario_sesc_dash.py`
   - Instance Type: Free

4. Clique em "Create Web Service" e aguarde o deploy.

5. Acesse o link gerado para visualizar o painel.
