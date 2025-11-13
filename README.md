# 🛒 Projeto Mercado Dash

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Architecture](https://img.shields.io/badge/Architecture-MVC-green)
![Status](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)

> Aplicação web para análise de dados de mercado, estruturada seguindo o padrão de arquitetura MVC (Model-View-Controller).

## 📄 Sobre o Projeto

O **Projeto Mercado Dash** é uma ferramenta de visualização de dados projetada para oferecer insights sobre vendas e indicadores de mercado.

Este é um projeto de exemplo criado para demonstrar o uso do Dash em um contexto de análise de dados. Foi desenvolvido para servir como material de apoio para estudantes de graduação na disciplina de Tópicos de Big Data em Python.

Diferente de scripts de análise simples, este projeto foi construído com uma arquitetura robusta, separando a lógica de dados, a interface visual e o controle da aplicação, facilitando a manutenção e a expansão de novas funcionalidades.

## 📂 Estrutura do Projeto

O projeto segue a organização MVC para garantir modularidade:

```bash
ProjetoMercadoDash/
├── app.py                  # Ponto de entrada da aplicação (Main file)
├── requirements.txt        # Lista de dependências
├── assets/                 # Arquivos estáticos (CSS, Imagens, Logos)
├── model/                  # Lógica de acesso e tratamento de dados (Pandas, SQL)
├── view/                   # Componentes visuais e Layout do Dashboard
├── controller/             # Lógica de controle e callbacks (Interatividade)
└── .gitignore              # Arquivos ignorados pelo Git
````

### Detalhes dos Módulos

- **Model:** Responsável por carregar os dados (CSV, Excel ou Banco de Dados) e realizar o processamento inicial.
- **View:** Define a estrutura visual da página, gráficos e componentes de interface.
- **Controller:** Gerencia as interações do usuário (filtros, cliques) e atualiza a View baseada nos dados do Model.

## 🛠️ Tecnologias Utilizadas

- **Python** - Linguagem base.
- **Dash / Plotly**  - Framework para criação do dashboard interativo.
- **Pandas** - Manipulação e análise de dados.

## 🚀 Como Executar

Siga os passos abaixo para rodar o projeto localmente.

### 1\. Clone o repositório

```bash
git clone [https://github.com/Hargenx/ProjetoMercadoDash.git](https://github.com/Hargenx/ProjetoMercadoDash.git)
cd ProjetoMercadoDash
```

### 2\. Crie e ative um ambiente virtual

```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# Linux/Mac
python3 -m venv venv
source venv/bin/activate
```

### 3\. Instale as dependências

```bash
pip install -r requirements.txt
```

### 4\. Execute a aplicação

```bash
python app.py
```

O dashboard estará disponível no seu navegador, geralmente em `http://127.0.0.1:8050/`.

## 🤝 Contribuição

O projeto está aberto para melhorias\! Se você quiser contribuir:

1. Faça um Fork.
2. Crie uma Branch (`git checkout -b feature/NovaFeature`).
3. Se necessário, adicione novos componentes na pasta `view` ou lógica no `controller`.
4. Faça o Commit e Push.
5. Abra um Pull Request.

-----

Autor: [Raphael Mauricio Sanches de jesus](https://github.com/Hargenx)
