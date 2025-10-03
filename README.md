# 🎵 Spotify Songs Dashboard

Um **dashboard interativo em Python** desenvolvido com **Streamlit** e **Pandas**, que permite explorar músicas do Spotify a partir de um dataset em CSV.

Com ele, o usuário pode:
 Selecionar um **artista** no menu lateral.
 Visualizar um gráfico com o número de streams por música.
 Conferir os detalhes das faixas em uma tabela interativa.

---

## 🚀 Tecnologias utilizadas

* [Python](https://www.python.org/)
* [Pandas](https://pandas.pydata.org/)
* [Streamlit](https://streamlit.io/)

---

## 📂 Estrutura do projeto

```
📦 spotify-dashboard
 ┣ 📂 .git
 ┣ 📜 01 Spotify.csv   # Dataset com músicas e streams
 ┣ 📜 app.py           # Código principal da aplicação
 ┣ 📂 venv             # Ambiente virtual (não precisa subir pro GitHub)
 ┗ 📜 requirements.txt # Dependências do projeto
```

---

## ⚙️ Como executar o projeto

### 🔹 Pré-requisitos

Antes de começar, você precisa ter instalado na sua máquina:

* [Python 3.8+](https://www.python.org/downloads/)
* [pip](https://pip.pypa.io/en/stable/installation/)

---

### 🔹 Passo a passo

1. **Clonar o repositório**

```bash
git clone https://github.com/andrade044/streamlit-projeto.git
cd streamlit-projeto
```

2. **Criar ambiente virtual (opcional, mas recomendado)**

```bash
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

3. **Instalar as dependências**

```bash
pip install -r requirements.txt
```

4. **Executar a aplicação**

```bash
streamlit run app.py
```

---

## 📊 Exemplo de uso

* Selecione um artista no menu lateral.
* Veja o gráfico de **streams por música**.
* Explore a tabela com as informações detalhadas.

---

## 📝 Dataset

O dataset **`01 Spotify.csv`** contém informações de faixas, artistas e número de streams.
Exemplo de colunas:

* `Track` → Nome da música
* `Artist` → Nome do artista
* `Stream` → Número de streams

---

✨ *Projeto desenvolvido para fins de aprendizado e prática em análise de dados com Python + Streamlit.*
