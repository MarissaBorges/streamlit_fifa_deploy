####

<!-- BADGES -->

[PYTHON_BADGE]: https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54
[PANDAS_BADGE]: https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white
[STREAMLIT_BADGE]: https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white

<!-- BADGES DEPLOY -->

[STREAMLITCLOUD_DEPLOY_BADGE]: https://img.shields.io/badge/Deployed%20on-Streamlit%20Cloud-FF4B4B?logo=streamlit&style=for-the-badge

<!-- PROJECT -->
<h1 align="center" style="font-weight: bold;">FIFA Official Dataset Viewer ⚽</h1>

<p align="center">
  <!-- Adicione aqui os badges das tecnologias que você usou -->
  <a href="https://www.python.org" target="_blank"><img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"></a>
  <a href="https://streamlit.io" target="_blank"><img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"></a>
  <a href="https://pandas.pydata.org" target="_blank"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"></a>
</p>

<p align="center">
  <a href="https://fifa-dep.streamlit.app/" target="_blank">
    <img src="https://img.shields.io/badge/Deployed%20on-Streamlit%20Cloud-FF4B4B?logo=streamlit&style=for-the-badge" alt="Deployed on Streamlit Cloud">
  </a>
</p>

<p align="center">
 <a href="#-descrição">Descrição</a> • 
 <a href="#-funcionalidades">Funcionalidades</a> • 
 <a href="#-começando">Como Executar</a> • 
 <a href="#️-demonstrações-capturas-de-tela">Demonstrações</a> • 
 <a href="https://fifa-dep.streamlit.app/">Ver na Web</a>
</p>

---

## 📌 Descrição

Este projeto oferece uma **visualização interativa** dos dados oficiais da FIFA, obtidos do Kaggle ([FIFA 23 Official Dataset](https://www.kaggle.com/datasets/kevwesophia/fifa23-official-datasetclean-data)). Desenvolvido com **Python** e **Streamlit**, ele permite explorar dados de jogadores de 2017 a 2023 através de uma interface intuitiva e responsiva.

O sistema é dividido em três seções principais: uma **página inicial** com uma breve introdução aos dados, uma **página de detalhe** onde é possível visualizar informações individuais de cada jogador (foto, peso, altura, valor de contrato, etc.) utilizando filtros de clube e jogador, e uma **página de tabela** que apresenta um resumo tabular com nome, idade, foto, preço e clube dos atletas.

---

## 🚀 Funcionalidades

- **Página Inicial:** Breve descrição e contextualização dos dados do FIFA.
- **Visualização Individual:** Filtros por **clube e jogador** para exibir detalhes específicos (foto, peso, altura, valor, etc.).
- **Visualização em Tabela:** Tabela consolidada com nome, idade, foto, preço e clube dos jogadores.
- **Análise de Dados:** Permite a análise de dados de jogadores da FIFA de **2017 a 2023**.

---

## 🔒 Destaques Técnicos

- ⚡ **Performance Otimizada**: Uso inteligente de **cache** (`@st.cache_data`) para evitar recarregamento desnecessário dos dados, agilizando a experiência do usuário.
- 🔒 **Controle de Acesso**: Verificação implementada para garantir que as páginas de visualização individual e tabela só sejam acessíveis após o usuário passar pela página inicial.
- 📏 **Simplicidade do Código**: Aproveitamento da simplicidade e eficiência do **Streamlit** para manter o código conciso e legível.

---

## 📍 Como Executar Localmente

Siga as instruções abaixo para executar o projeto em seu ambiente local.

### Pré-requisitos

- [Python](https://www.python.org/downloads/) (versão 3.8 ou superior)
- [Git](https://git-scm.com/)

### Clonando o Repositório

```bash
# Clone o projeto para a sua máquina local
git clone https://github.com/MarissaBorges/streamlit_fifa_deploy.git

# Entre no diretório do projeto
cd streamlit_fifa_deploy
```

### Ambiente Virtual

É uma boa prática isolar as dependências do projeto.

```bash
# Crie o ambiente virtual
python -m venv .venv

# Ative o ambiente
# No Windows:
.venv\\Scripts\\activate

# No macOS/Linux:
source .venv/bin/activate
```

### Instale as Dependências

Com o ambiente virtual ativo, use o arquivo `requirements.txt` para instalar as dependências.

```bash
pip install -r requirements.txt
```

### Iniciando o Projeto

Inicie a aplicação com o servidor do Streamlit

```bash
streamlit run 1_🏠_home.py
```

### Como Interagir

- Navegue pelo menu na barra lateral para acessar as diferentes seções: `Home`, `Detalhes do Jogador` e `Tabela de Jogadores`.
- Na página de detalhes, use os menus suspensos para filtrar por clube e, em seguida, selecionar um jogador específico.

---

## 🖼️ Demonstrações (capturas de tela)

![Página Inicial do Projeto](https://i.postimg.cc/d00Dx99g/pagina-inicial.png)
_Tela inicial com a apresentação do projeto._

![Página de Detalhes do Jogador](https://i.postimg.cc/4d9fD2H2/detalhes-jogador.png)
_Visualização detalhada das informações de um jogador específico._

![Página com Tabela de Jogadores](https://i.postimg.cc/nrfFpKvF/tabela.png)
_Tabela resumida com os principais dados dos atletas._

---

## 📫 Como Contribuir

1. Faça um **Fork** do projeto.
2. Crie uma nova branch para sua Feature (`git checkout -b feature/AmazingFeature`).
3. Faça o **Commit** de suas mudanças (`git commit -m 'Add some AmazingFeature'`).
4. Faça o **Push** da sua branch (`git push origin feature/AmazingFeature`).
5. Abra um **Pull Request**.

### Documentações Úteis

- [📝 Como criar um Pull Request](https://www.atlassian.com/br/git/tutorials/making-a-pull-request)
- [💾 Padrão de Commits (Conventional Commits)](https://www.conventionalcommits.org/en/v1.0.0/)

####
