# 🗺️ Comparador de Redes Geoespaciais — Águas do Rio

Aplicação web para comparar duas versões de camadas vetoriais (shapefile ou GeoPackage).

## Funcionalidades
- Upload de `.gpkg`, `.zip` (shapefile ou gpkg)
- Detecta feições **removidas**, **adicionadas** e com **atributos alterados**
- Valida geometrias inválidas ou nulas
- Gera **mapa interativo** colorido com as diferenças
- Exporta **relatório Excel** com 5 abas detalhadas

## Como publicar no Streamlit Cloud (gratuito)

### 1. Criar conta no GitHub
Acesse github.com e crie uma conta gratuita.

### 2. Criar repositório
- Clique em "New repository"
- Nome: `comparador-redes`
- Visibilidade: **Private** (recomendado)
- Clique em "Create repository"

### 3. Fazer upload dos arquivos
Suba os 3 arquivos para o repositório:
- `app.py`
- `requirements.txt`
- `README.md`

### 4. Publicar no Streamlit Cloud
- Acesse share.streamlit.io
- Faça login com sua conta Google ou GitHub
- Clique em "New app"
- Selecione o repositório `comparador-redes`
- Branch: `main`
- Main file: `app.py`
- Clique em "Deploy"

### 5. Compartilhar
Após o deploy (2-3 minutos), você recebe um link público.
Compartilhe com quem precisar usar — não precisa instalar nada.

## Uso
1. Acesse o link da aplicação
2. Configure o tipo de rede e município
3. Faça upload do arquivo **antigo** e do **novo**
4. Clique em **Comparar**
5. Veja o resultado e baixe o Excel + mapa
