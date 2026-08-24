# Karakura Store

## Sobre o projeto

O **Karakura Store** é um projeto de loja virtual desenvolvido como aplicação web, inspirado no universo de *Bleach*. A proposta é criar uma interface de e-commerce para apresentação e comercialização de produtos relacionados ao anime.

O projeto possui páginas para navegação, cadastro e login de usuários, catálogo de produtos, visualização individual dos produtos, carrinho de compras e pagamento.

## Funcionalidades

- Página inicial com apresentação da loja.
- Catálogo de produtos.
- Organização dos produtos por categorias.
- Página individual para visualização de produtos.
- Cadastro de usuários.
- Página de login.
- Carrinho de compras.
- Página de pagamento.
- Navegação entre as diferentes áreas da loja.
- Utilização de imagens, fontes personalizadas e elementos visuais relacionados ao universo de *Bleach*.
- Reprodução de recurso de áudio utilizado pela aplicação.

## Páginas

### Home
![image URL](https://github.com/josecardozoif/karakura-store/blob/main/home.png?raw=true)

Página principal da loja, responsável por apresentar o conteúdo inicial, banners, categorias e produtos disponíveis.

### Login e Cadastro
![image URL](https://github.com/josecardozoif/karakura-store/blob/main/login.png?raw=true)

Área destinada à autenticação e ao cadastro de usuários.

A aplicação possui páginas específicas para:

- Login;
- Cadastro de novos usuários.

### Produtos

Página responsável pela apresentação dos produtos disponíveis na loja, permitindo ao usuário navegar pelo catálogo.

Também existe uma página específica para exibição dos detalhes de cada produto.

### Carrinho
![image URL](https://github.com/josecardozoif/karakura-store/blob/main/carrinho.png?raw=true
)

Página responsável por apresentar os produtos selecionados pelo usuário antes da finalização da compra.

### Pagamento

Página destinada à etapa de finalização da compra, contendo as informações necessárias para o processo de pagamento.

## Tecnologias utilizadas

- **Python**
- **Flask**
- **HTML5**
- **CSS3**
- **Jinja2**
- **Fontes personalizadas**
- **Arquivos de imagem**
- **Áudio**

O HTML utiliza templates para permitir a integração das páginas com a aplicação Flask.

## Estrutura do projeto

```text
karakura-store/
│
├── static/
│   ├── fonts/
│   │   ├── AvanteBold.ttf
│   │   ├── AvanteMid.ttf
│   │   ├── Geizer.otf
│   │   └── LemonMilk.otf
│   │
│   ├── img/
│   │   ├── acs1.png
│   │   ├── acs2.png
│   │   ├── ...
│   │   ├── limp1.png
│   │   ├── mov1.png
│   │   ├── tech1.png
│   │   └── tenis1.png
│   │
│   ├── sounds/
│   │   └── numberone.mp3
│   │
│   ├── style.css
│   ├── style-cad.css
│   ├── style-car.css
│   ├── style-pag.css
│   └── style-prod.css
│
├── templates/
│   ├── index.html
│   ├── cadastro.html
│   ├── produtos.html
│   ├── produto.html
│   ├── carrinho.html
│   └── pagamento.html
│
└── ...
```

## Organização dos arquivos

### `templates/`

Contém as páginas HTML utilizadas pela aplicação:

| Arquivo | Função |
|---|---|
| `index.html` | Página inicial |
| `cadastro.html` | Cadastro de usuários |
| `produtos.html` | Catálogo de produtos |
| `produto.html` | Detalhes de um produto |
| `carrinho.html` | Carrinho de compras |
| `pagamento.html` | Finalização da compra |

### `static/`

Contém os arquivos estáticos utilizados pela aplicação.

#### `static/img/`

Armazena as imagens dos produtos, banners e demais elementos gráficos da loja.

#### `static/fonts/`

Contém as fontes personalizadas utilizadas na interface.

#### `static/sounds/`

Armazena os arquivos de áudio utilizados pelo projeto.

#### Arquivos CSS

Cada página possui estilos específicos, além do arquivo principal:

- `style.css` — estilos gerais;
- `style-cad.css` — cadastro;
- `style-car.css` — carrinho;
- `style-pag.css` — pagamento;
- `style-prod.css` — produtos.

## Categorias de produtos

O catálogo apresenta diferentes categorias de produtos, incluindo:

- Acessórios;
- Limpeza;
- Moda;
- Tecnologia;
- Tênis.

Os produtos são representados por imagens próprias e organizados dentro da estrutura de arquivos estáticos da aplicação.

## Como executar o projeto

### 1. Clonar o repositório

```bash
git clone <URL_DO_REPOSITORIO>
```

### 2. Entrar na pasta do projeto

```bash
cd karakura-store
```

### 3. Criar um ambiente virtual

```bash
python -m venv venv
```

### 4. Ativar o ambiente virtual

No Windows:

```bash
venv\Scripts\activate
```

No Linux/macOS:

```bash
source venv/bin/activate
```

### 5. Instalar as dependências

Caso o projeto possua um arquivo `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 6. Executar a aplicação

Execute o arquivo principal da aplicação Flask:

```bash
python app.py
```

Depois, acesse no navegador o endereço disponibilizado pelo Flask, normalmente:

```text
http://127.0.0.1:5000
```

## Objetivo acadêmico

O projeto foi desenvolvido como uma aplicação prática de desenvolvimento web, permitindo trabalhar conceitos como:

- Desenvolvimento de interfaces web;
- Estruturação de páginas HTML;
- Estilização com CSS;
- Templates com Jinja2;
- Desenvolvimento com Flask;
- Organização de arquivos estáticos;
- Navegação entre páginas;
- Catálogo de produtos;
- Carrinho de compras;
- Fluxo de cadastro, login e pagamento.

## Status do projeto

Projeto desenvolvido para fins acadêmicos e de aprendizado em desenvolvimento web.

## Autores

Projeto desenvolvido como atividade acadêmica.
