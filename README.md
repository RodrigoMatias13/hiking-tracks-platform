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

### Configurações Iniciais
Na pasta principal
- .\venv\Scripts\Activate.ps1
- python manage.py migrate
- python seed_db.py

### Para correr backend
Na pasta principal:
- python manage.py runserver


### Para correr frontend
Na pasta frontend:
- npm run dev


### Contas já existentes, para testar
| CONTA         | USERNAME | PASSWORD |
| -----         | -------- | -------- |
| Administrador | admin    | admin    |
| Moderador     | mod1     | mod1     |
| Moderador     | mod2     | mod2     |
| Moderador     | mod3     | mod3     |
| Utilizador    | user1    | user1    |
| Utilizador    | user2    | user2    |
