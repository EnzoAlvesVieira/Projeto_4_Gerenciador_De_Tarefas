# 🧩 **Projeto Pokédex**

Uma aplicação web interativa desenvolvida com **Python** e **Streamlit** que consome dados da **PokéAPI**, exibindo informações detalhadas sobre qualquer Pokémon, incluindo imagens, sons, tipos, habilidades e muito mais.  
O projeto foi criado com o objetivo de praticar o consumo de **APIs públicas**, o uso de **requisições HTTP**, e a construção de **interfaces lowcode** com Streamlit.

---

## 🧠 **Situação-Problema**

Você foi contratado por um **Centro de Pesquisa Pokémon** para desenvolver uma ferramenta moderna e acessível que permita aos treinadores e pesquisadores consultar informações detalhadas sobre Pokémons diretamente pelo navegador.  
O sistema deve exibir dados oficiais da PokéAPI, incluindo imagens padrão e shiny, habilidades, status, tipos, sons e locais onde o Pokémon pode ser encontrado.  
O objetivo é criar uma ferramenta educativa, intuitiva e visualmente agradável que facilite a consulta e análise dos Pokémons em tempo real.

---

## 🎯 **Objetivo Educacional**

- Aprender a **consumir APIs públicas** com Python.  
- Utilizar **requisições HTTP** com a biblioteca `requests`.  
- Criar **interfaces interativas** utilizando o Streamlit.  
- Exibir **dados visuais e de áudio** a partir de uma API externa.  
- Compreender conceitos de **frontend lowcode** e integração com **dados dinâmicos**.

---

## ⚙️ **Funcionalidades Principais**

- 🔎 Pesquisa de Pokémons por nome.  
- 📸 Exibição das imagens padrão e shiny do Pokémon.  
- 📏 Exibição de métricas como **altura**, **peso**, **IMC** e **geração**.  
- 🎧 Reprodução dos sons característicos (**cries**) de cada Pokémon.  
- 🧬 Exibição dos **tipos** e **habilidades**.  
- 📊 Mostra os **status base** (HP, ataque, defesa, etc.).  
- 🗺️ Lista os **locais onde o Pokémon pode ser encontrado**.  
- 🚨 Mensagens de aviso caso o nome seja digitado incorretamente.

---

## 💻 **Como Executar**

### 🧩 Pré-requisitos

- Python **3.8** ou superior instalado.  
- Biblioteca **Streamlit** e demais dependências instaladas (arquivo `requirements.txt` incluso).

### 🚀 Passos de execução

1. Clone este repositório ou baixe os arquivos:

   ```bash
   git clone https://github.com/TJfiles/projeto_pokedex.git
   cd projeto_pokedex
    ```

2. Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

3. Execute o aplicativo Streamlit:

```bash
streamlit run app.py
```

4. Abra o navegador e acesse o endereço fornecido pelo Streamlit (geralmente http://localhost:8501).

Pronto! Agora você pode explorar o universo Pokémon diretamente no navegador! 🎮

---

# Exemplo de Uso

1. O usuário digita o nome do Pokémon desejado ou o seleciona na lista.

2. O sistema faz uma requisição à PokéAPI e retorna suas informações completas.

Exemplo:

```
Selecionando Pikachu, a aplicação exibe sua imagem, altura (0.4 m), peso (6 kg), IMC, tipo (Electric), status base, habilidades e locais onde pode ser encontrado.
```

---

# 🧠 Conceitos Trabalhados

- Consumo de APIs públicas com requests.
- Manipulação e exibição de dados com Streamlit.
- Uso de condicionais para controle de exibição.
- Apresentação de mídias interativas (imagens e sons).
- Interface web lowcode com Python.

---

# 🧾 Licença

Este projeto está sob a licença MIT — sinta-se à vontade para usar, modificar e distribuir. ✨

--- 

# 🔧 Tecnologias Utilizadas

🐍 Python 3.x

🖥️ Streamlit

🌐 Requests

🔢 Pandas