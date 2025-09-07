

🧪 Projeto HemolabRN

Este projeto foi desenvolvido na disciplina de Backend, com entrega em 18 de junho de 2025.
O objetivo é implementar um site institucional utilizando o framework Django, simulando uma plataforma de apresentação de serviços laboratoriais.

🎯 Objetivo

O sistema busca aplicar conceitos de desenvolvimento backend para construir um site funcional, com design fiel ao modelo de referência.

Requisitos atendidos:

Estrutura do projeto em Django, com nome hemolabrn.

Páginas dentro do app mainpage.

Uso de templates com extensão (extends), reaproveitando menus e rodapés.

Integração de arquivos estáticos (CSS, JS, imagens).

Implementação de rotas para navegação entre páginas.

Utilização de ícones do Font Awesome.

Páginas implementadas:

Página inicial: hemolabrn.com/index.html

Serviços: hemolabrn.com/servicos.html

Unidades: hemolabrn.com/unidades.html

⚙️ Funcionalidades

Estruturação backend com Django.

Navegação entre páginas através de rotas.

Reaproveitamento de código via template base.

Integração de arquivos estáticos.

Uso de ícones externos com Font Awesome.

📂 Estrutura do Projeto
hemolabrn/
│
├── mainpage/
│   ├── templates/
│   │   ├── base.html      # Template base (menus e rodapés)
│   │   ├── index.html     # Página inicial
│   │   ├── servicos.html  # Página de serviços
│   │   └── unidades.html  # Página de unidades
│   ├── static/            # Arquivos CSS, JS e imagens
│   └── views.py           # Controladores (funções de cada rota)
│
├── hemolabrn/
│   ├── settings.py
│   ├── urls.py            # Rotas principais
│   └── ...
└── manage.py

🎥 Apresentação

A apresentação do projeto deve ter pelo menos 5 minutos, mostrando:

Estrutura e organização do sistema em Django.

Funcionamento das rotas e templates.

Reaproveitamento de menus e rodapés com extends.

Demonstração das páginas implementadas.
