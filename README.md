Projeto: Analisador Automático de Logs com Relatório Word

Este projeto foi proposto no curso de python na plataforma Udemy, para fins de treinar lógica de programação e utilização de bibliotecas aprendidas no curso.

Enunciado:
Objetivo
Desenvolver um sistema em Python que leia, analise e gere um relatório formatado em Word a partir de arquivos de log de servidor. O projeto deve extrair informações relevantes usando expressões regulares (regex) e apresentar os dados em um documento organizado e fácil de entender.

Descrição
Você receberá um arquivo de log no formato texto contendo registros variados, com data, hora, nível do log (INFO, ERROR, WARNING, DEBUG) e mensagens diversas. Seu programa deverá:

Ler o arquivo de log completo.

Extrair, usando expressões regulares, os seguintes dados de cada linha:

Data e hora (exemplo: 2025-07-01 15:24:01)

Tipo do log (INFO, ERROR, WARNING, DEBUG)

Mensagem do log

Gerar um relatório em documento Word (.docx) contendo:

Um título claro e descritivo (ex: "Relatório de Análise de Logs").

Um parágrafo resumo com o total de ocorrências de cada tipo de log.

Uma lista detalhada com todas as mensagens de erro.

Uma tabela que mostra a quantidade de registros por dia, divididos por nível de log.

Requisitos Técnicos
Utilizar expressões regulares para extrair informações do texto.

Trabalhar com leitura de arquivos texto.

Utilizar a biblioteca python-docx para gerar o relatório Word.

Aplicar conceitos de agrupamento, contagem e formatação em tabelas no Word.

Dicas
Teste suas expressões regulares com exemplos reais antes de aplicar no arquivo completo.

Utilize dicionários para armazenar contagens por tipo e por data.

Salve o documento com um nome que contenha a data da geração do relatório, por exemplo: relatorio_logs_2025-07-01.docx.