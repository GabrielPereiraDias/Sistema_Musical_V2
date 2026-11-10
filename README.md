<!-- Banner animado -->
<p align="center">
  <img src="https://media.giphy.com/media/g2onDlYL88KWFCJKlR/giphy.gif" width="400" alt="Elden Ring" />
</p>

<h1 align="center">🎵 Sistema Musical V2</h1>

<p align="center">
  <strong>Uma biblioteca musical para cadastrar, organizar e explorar músicas e artistas.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PHP-Backend-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP" />
  <img src="https://img.shields.io/badge/MySQL-Banco_de_dados-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
  <img src="https://img.shields.io/badge/CSS-Estilização-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/Status-Projeto_acadêmico-8b5cf6?style=for-the-badge" alt="Projeto acadêmico" />
</p>

---

## 🎧 Sobre o projeto

O **Sistema Musical V2** é uma aplicação web desenvolvida para gerenciar uma biblioteca de músicas e artistas. O sistema permite manter os registros organizados em um banco de dados e acessar as principais informações por meio de uma interface simples e intuitiva.

O projeto reúne conceitos de desenvolvimento back-end, integração com banco de dados, operações CRUD, autenticação de usuários e manipulação de arquivos.

## ✨ Funcionalidades

<table>
  <tr>
    <td width="50%">
      <h3>🎤 Gerenciamento de artistas</h3>
      Cadastro, edição, listagem e exclusão de artistas, com nome, gênero, país e foto.
    </td>
    <td width="50%">
      <h3>🎼 Gerenciamento de músicas</h3>
      Cadastro e edição de músicas com título, álbum, gênero, letra, artista relacionado e capa.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔎 Biblioteca com filtros</h3>
      Pesquisa por título, álbum ou artista, além de filtros por artista e gênero musical.
    </td>
    <td width="50%">
      <h3>▶️ Integração com YouTube</h3>
      Armazenamento de links de vídeos e acesso às músicas diretamente pelo YouTube.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🔐 Login e sessões</h3>
      Autenticação de usuários e proteção das páginas internas para usuários logados.
    </td>
    <td width="50%">
      <h3>🖼️ Upload de imagens</h3>
      Envio de fotos de artistas e capas de músicas, com validação e redimensionamento.
    </td>
  </tr>
</table>

## 🛠️ Tecnologias utilizadas

| Tecnologia | Aplicação no projeto |
|:--|:--|
| **PHP** | Regras do sistema, formulários, autenticação e operações CRUD |
| **MySQL** | Armazenamento de usuários, artistas e músicas |
| **HTML5** | Estrutura das páginas |
| **CSS3** | Layout, componentes e identidade visual |
| **MySQLi** | Comunicação entre PHP e banco de dados |
| **Biblioteca GD** | Processamento e redimensionamento das imagens |

## 🗂️ Estrutura do projeto

```
Sistema_Musical_V2/
│
├── README.md
│
└── Sistema_Musical_V2/
    ├── bd.sql
    ├── conexao.php
    ├── index.php
    ├── login.php
    ├── logout.php
    ├── valida_sessao.php
    ├── geraSenha.php
    ├── cadastro_artista.php
    ├── cadastro_musica.php
    ├── listagem_musicas.php
    └── styles.css
```

## 🗃️ Banco de dados

O banco utilizado se chama `sistema_musical_v2` e possui três tabelas principais:

- **usuarios:** armazena os dados de acesso;
- **artistas:** guarda informações dos artistas;
- **musicas:** registra as músicas e seu relacionamento com os artistas.

O script de criação está disponível em `Sistema_Musical_V2/bd.sql`.

## 🔒 Segurança e validações

O projeto utiliza consultas preparadas (*prepared statements*) para operações com o banco, verificação de senha com hash, controle de sessão e validação dos arquivos de imagem enviados.

> **Atenção:** as credenciais configuradas em `conexao.php` são específicas do ambiente de desenvolvimento. Altere-as para o seu ambiente e não publique senhas reais no repositório.

## 🏫 Contexto acadêmico

Projeto desenvolvido como atividade do curso de **Desenvolvimento de Sistemas**.

<p align="center">
  <strong>SENAI A. Jacob Lafer</strong><br />
  Turma: <strong>1ID-DS</strong>
</p>

## 👨‍💻 Autor

<p align="center">
  <strong>Gabriel Pereira Dias</strong>
</p>

---

<p align="center">
  <i>Organizando músicas, artistas e ideias em um só lugar.</i> 🎶
</p>
