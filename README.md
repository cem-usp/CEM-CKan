# CEM-CKan

Implantação automatizada do CKAN com dados extraídos da seção Download de Dados do site do CEM

## Motivação

O [CKAN](https://ckan.org/) é um projeto de software livre e código aberto amplamente utilizado por governos e diverssas organizações para publicação de conjutos de dados abertos. É um projeto de fácil implantação e manutenção e possibilita a integração com outros sistemas, como os de informações espaciais. Desssa maneira é possível que a implantação do CKAN possa trazer vantagens em relação a sistemas proprietários.

## Objetivo

Esse repositório tem como objetivo desenvolver e publicar uma forma automatizada de insstalar e instanciar uma instancia do CKAN com os dados disponibilizados na seção de [Download de Dados do site do CEM](https://centrodametropole.fflch.usp.br/pt-br/download-de-dados) e assim poder comparar e decidir pela implantação ou não o CKAN como ferramenta de publicação dos dados abertos produzidos e mantidos pelo CEM

## Materiais e Métodos

A partir do Inventário de dados da seção de download de dados no site do CEM os arquivos são baixados para poder ser implantada uma nova instância do CKAN é implantada e configurada com a finalidade de uso em máquinas locais

Os processamentos estão organizados em Jupyter NoteBooks com código em Python,  disponibilizados de forma enumerada de forma sequencial.

Esse método está em processo de desenvolvimento e atualização devem ser refletidas aqui.

## Resultados

O primeiro resultado prático desse trabalho é a documentação do inventário de arquivos disponíveis para download no site do CEM, disponível na pasta `resultados` em formato `json`. Isso permite por exemplo a documentação de uma forma automatizada para repetir esse procedimento quando necessário, além de possibilitar o download automatizado de toda a base a outros pesquisadores.

Espera-se a partir do compartilhamento do processo de automatização e da construção de uma base do CKAN a partir de dados existentes a persitência da metodologia para além da análise na tomada de decisão de utilização de uma ferramenta. Mas sobretudo o fomento da discussão sobre a facilitação do uso de ferramentas livres e abertas existentes como forma de valorização do patrimônio coletivo que é o Software Livre.
