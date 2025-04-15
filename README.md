# Inventário de Equipamentos de TI

Este projeto consiste em um sistema web para gerenciamento do inventário de equipamentos de TI, desenvolvido para o TG I com o tema “Verificação e Análise da Segurança da Informação na Fatec Arthur de Azevedo”. O sistema possibilita o cadastro, visualização, alteração e remoção de equipamentos, além de funcionalidades como exportação para CSV e envio de mensagens através do formulário de contato. Ele também conta com uma área de login para acesso restrito.

## 💼 Informações sobre o Projeto

**Faculdade de Tecnologia de Mogi Mirim**

**Curso:** Análise e Desenvolvimento de Sistemas (Noturno)

**Aula:**

* 🖥️ Eletiva - Programação de Scripts
  
**Professor Orientador:**

* 👨🏻‍🏫 Francisco Adão Eloy Junior

**Autores:**

- **Ian Camargo** - [@IanCamargo](https://github.com/IanCamargo)

## Sumário

- [Descrição do Projeto](#descrição-do-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Estrutura de Arquivos](#estrutura-de-arquivos)
- [Como Executar o Projeto](#como-executar-o-projeto)
- [Credenciais de Acesso](#credenciais-de-acesso)
- [Considerações Finais](#considerações-finais)

## Descrição do Projeto

O sistema tem o objetivo de facilitar o gerenciamento de equipamentos de TI, permitindo a organização e controle do inventário. Com foco em responsividade, acessibilidade e usabilidade, o sistema exibe uma interface intuitiva para cadastramento e consulta dos equipamentos, e um formulário de contato que valida os dados de entrada do usuário.

A ideia é oferecer uma ferramenta prática para fins acadêmicos e de análise de segurança da informação, facilitando o gerenciamento dos equipamentos e garantindo a integridade dos dados inseridos.

## Funcionalidades

- **Login Seguro:** Tela de login para acesso restrito ao sistema.
- **Cadastro de Equipamentos:** Formulário para inclusão de equipamentos com informações como patrimônio, categoria, subcategoria, marca e modelo.
  - Validação para inserção numérica do campo patrimônio.
  - Validação e controle de duplicidade do patrimônio.
- **Consulta e Edição:** Exibição dos equipamentos cadastrados em tabela, com opções para alterar ou remover cada registro.
- **Exportação para CSV:** Possibilidade de exportar os dados cadastrados para um arquivo CSV.
- **Formulário de Contato:** Área para envio de mensagens com validação de CPF, e-mail e nome, com feedback visual de erros.
- **Design Responsivo:** O layout se adapta a diferentes tamanhos de tela, garantindo uma boa experiência de uso em dispositivos móveis e desktops.
- **Acessibilidade:** Boas práticas para acessibilidade, como uso adequado de _roles_, textos alternativos para imagens e _labels_ ocultas para leitores de tela.

## Tecnologias Utilizadas

- **HTML5:** Estruturação semântica das páginas.
- **CSS3:** Estilização customizada, responsividade e efeitos visuais simples.
- **JavaScript:** Validação de formulários, lógica de cadastro de equipamentos, manipulação dinâmica da tabela e exportação dos dados.

## Estrutura de Arquivos

A estrutura do projeto é composta pelos seguintes arquivos principais:

- **index.html:** Página principal que contém a interface do sistema, com as seções de descrição, inventário (cadastro, listagem, filtros e exportação CSV) e contato.
- **login.html:** Página de login onde o usuário deve se autenticar para acessar o sistema. Caso o login seja efetuado com sucesso, o usuário é redirecionado para a página principal (index.html).

Outros recursos que podem ser encontrados no projeto:
- Arquivo de imagem para o logo (_logoFatec.png_), utilizado no cabeçalho.
- Arquivo de imagem ilustrativa (_inventario.jpg_) para complementar a interface do sistema.

## Como Executar o Projeto

Como este é um sistema web estático, para executar o projeto basta:

1. Fazer o download ou clonar os arquivos do repositório.
2. Abrir o arquivo **login.html** no navegador.
3. Efetuar o login para ser redirecionado para o **index.html**, onde todas as funcionalidades serão exibidas.

Caso queira rodar localmente utilizando um servidor web (para testar funcionalidades como a navegação entre páginas), você pode utilizar servidores simples, como:

```bash
# Usando Python (versão 3.x)
python -m http.server 8000
```

## Como Executar o Projeto

Em seguida, acesse [http://localhost:8000/login.html](http://localhost:8000/login.html) pelo seu navegador.

## Credenciais de Acesso

Para fins de teste, as credenciais configuradas na área de login são:

- **Usuário:** teste@teste
- **Senha:** teste

> **Atenção:** Em um ambiente de produção, as credenciais devem ser armazenadas de forma segura e o sistema deve ser integrado a uma solução de autenticação robusta.

## Considerações Finais

Este sistema foi desenvolvido com foco em qualidade e usabilidade para facilitar a organização e gerenciamento dos equipamentos de TI. Por ser um projeto acadêmico, pode ser customizado e expandido conforme novas necessidades ou funcionalidades sejam identificadas.

Sinta-se à vontade para contribuir com melhorias, relatar problemas ou sugerir novas funcionalidades.
