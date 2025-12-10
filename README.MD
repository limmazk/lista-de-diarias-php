## Projeto PHP OO – Lista de Diárias

Este projeto foi desenvolvido com o objetivo de praticar conceitos fundamentais de PHP Orientado a Objetos, organização de código utilizando namespaces e carregamento automático com Composer (PSR-4).

A aplicação segue uma estrutura simples inspirada no padrão MVC:

Modelo: classes que representam as entidades do sistema, como Diária, Cliente e Diarista.

Controlador: responsável por obter os dados e encaminhá-los para a visualização.

Visualização: página em PHP com HTML e Bootstrap utilizada para exibir a lista de diárias.

O projeto também aplica conceitos de composição, onde uma diária contém um objeto Cliente e um objeto Diarista, permitindo maior modularidade e clareza na estrutura.

A listagem exibida na interface é gerada a partir de dados simulados pelo método estático obterTodas(), servindo como base para estudos futuros com banco de dados e funcionalidades mais avançadas.

Este repositório representa os primeiros passos no aprendizado de PHP OO e estruturação de aplicações de forma organizada e escalável.