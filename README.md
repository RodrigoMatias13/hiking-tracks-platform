# TrailGuide - Plataforma Web de Trilhos (Django & React) 🥾🗺️

Este projeto consiste no desenvolvimento de uma aplicação web interativa e *fullstack* concebida para entusiastas de caminhadas e atividades ao ar livre. A plataforma funciona como um guia digital onde os utilizadores podem explorar trilhos, consultar informações detalhadas e interagir com a comunidade[cite: 5].

A aplicação foi construída utilizando uma arquitetura desacoplada com **Django** no backend e **React** no frontend, implementando regras de negócio e permissões específicas para Administradores, Moderadores e Utilizadores comuns[cite: 5].

Trabalho desenvolvido no âmbito da unidade curricular de **Desenvolvimento para a Internet e Aplicações Móveis (DIAM)** no **ISCTE-IUL**[cite: 5].

---

## 🌟 Funcionalidades Principais do Sistema

*   **Exploração de Trilhos:** Visualização de rotas, distâncias, níveis de dificuldade, durações estimadas e pontos de interesse de cada trilho[cite: 5].
*   **Sistema de Feedback:** Espaço para utilizadores registados deixarem comentários, avaliações e partilharem a sua experiência sobre os trilhos[cite: 5].
*   **Moderação de Conteúdo:** Painel dedicado para Moderadores gerirem os comentários da comunidade e garantirem o bom ambiente da plataforma[cite: 5].
*   **Gestão Administrativa:** Controlo total por parte dos Administradores para adicionar, editar ou remover trilhos e gerir contas de utilizadores[cite: 5].

## 🚀 Como Executar

### 1. Configurações Iniciais
*(Passo necessário apenas na primeira inicialização para criar o ambiente virtual e popular a base de dados)*

Abra o terminal na pasta principal do projeto e execute:
```bash
# Ativar o ambiente virtual (Windows)
.\venv\Scripts\Activate.ps1
```
# Executar as migrações da base de dados
```bash
python manage.py migrate
```
# Popular a base de dados com dados de teste (Seed)
```bash
python seed_db.py
```

2. Iniciar o Backend (Django)

Na pasta principal do projeto, execute:
```bash
python manage.py runserver
```
O servidor ficará ativo em http://127.0.0.1:8000/.

3. Iniciar o Frontend (React)
Abra um novo terminal, navegue até à pasta frontend e execute:
```bash
- npm run dev
```
A interface gráfica ficará disponível no endereço indicado pelo terminal (geralmente http://localhost:5173/).

🔑 Contas de Teste (Credenciais)
Para testar as diferentes permissões, funcionalidades e painéis do site, utilize as seguintes contas previamente populadas na base de dados[cite: 5]:
```bash
| CONTA         | USERNAME | PASSWORD |
| -----         | -------- | -------- |
| Administrador | admin    | admin    |
| Moderador     | mod1     | mod1     |
| Moderador     | mod2     | mod2     |
| Moderador     | mod3     | mod3     |
| Utilizador    | user1    | user1    |
| Utilizador    | user2    | user2    |
```

## 👤 Autor
* Rodrigo Matias
