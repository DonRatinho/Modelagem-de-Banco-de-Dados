📘 Sistema de Gestão – Diagramas e Estruturas de Banco de Dados

Este repositório reúne diagramas, modelos conceituais e comandos SQL referentes ao desenvolvimento de sistemas e bancos de dados voltados a diferentes domínios (biblioteca, mapas urbanos, monitoramento e eventos).

📚 1. Modelo Entidade-Relacionamento – Sistema de Biblioteca

Imagem do diagrama E-R:

Entidades e Atributos Principais

Biblioteca

Livros

Ano

Títulos

Editores

ISBN

Autores

Nome

Nacionalidade

Categoria

Código

Descrição

Relacionamentos

Informação – Biblioteca ↔ Livros

Pertence – Livros ↔ Categoria

Ter – Livros ↔ Autores

Cadastro – Biblioteca ↔ Categoria

🗺️ 2. Modelo Conceitual – Sistema de Mapeamento e Monitoramento Urbano

Imagem do diagrama:

![Diagrama Mapa](/mnt/data/Captura de tela 2025-09-11 204648.png)

Entidades

Mapa ( Usuários, veículos, rotas, eventos, local )

Usuários ( id_usuario, telefone, nome, cpf )

Veículos ( id_veiculos, tipo_uso, tipo_veic )

Monitoramento ( id_monit, status, tipo_equip )

Rotas ( duração, veículo, num_rota, destino, origem )

Eventos ( id_evento, data, status, responsável, impacto )

Local ( id_via, endereço )

Comercios ( tipo, cnpj, endereço )

Infraestrutura ( status, manutenção, org_resp )
