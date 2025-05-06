Resumo da Simulação: Prática com Azure Speech Studio e Language Studio
Passos Executados
Configuração dos Serviços no Azure:

Criou-se recursos Speech e Language Service no Azure, obtendo chaves de API e endpoints.

Speech Studio: Usado para testes de "Speech to Text" (transcrição de áudio) e "Text to Speech" (síntese de voz).

Language Studio: Aplicou-se "Análise de Sentimento" e "Extração de Frases-Chave" em textos.

Testes Práticos:

Speech to Text: Carregou-se um arquivo de áudio e verificou-se a precisão da transcrição.

Análise de Sentimento: Inseriu-se um texto e obteve-se classificação de polaridade (positivo/negativo/neutro).

Automação: Desenvolveu-se um script Python para integrar os serviços (transcrição + análise de sentimento).

Documentação no GitHub:

Repositório organizado com:

README.md: Detalhando configuração, fluxo de trabalho e aprendizados.

Pasta /code: Script Python de exemplo.

Pasta /images: Capturas de tela das interfaces e resultados.

Desafios e Soluções
Problema de Autenticação: Endpoint incorreto no Speech Studio.

Solução: Revisão minuciosa das credenciais e correção do endpoint.

Melhoria de Precisão: Exploração de ajustes de parâmetros e modelos personalizados nos estúdios.
