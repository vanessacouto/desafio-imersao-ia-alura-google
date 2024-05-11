# desafio-imersao-ia-alura-google
Código em Python utilizando a API de IA do Google, o GEMINI. A aplicação gera sugestões de nomes para um novo sistema com base em uma descrição, inspirando-se em uma lista de sistemas preexistentes.

##  Sistema de busca e geração de nomes para sistemas

Este projeto utiliza inteligência artificial para te auxiliar na busca e geração de nomes criativos e relevantes para os sistemas da sua empresa! 

**Como funciona?**

1. **Embeddings de documentos:** 
    * A descrição de cada sistema é convertida em um vetor de representação (embedding) usando um modelo de linguagem da Google AI. 
    * Essa representação captura o significado do texto e permite que o sistema compare a descrição do novo sistema com as descrições dos sistemas existentes. 

2. **Busca de sistemas semelhantes:** 
    * A descrição do novo sistema é também convertida em um embedding.
    * O sistema calcula a similaridade entre o embedding da descrição do novo sistema e os embeddings dos sistemas existentes.
    * O sistema retorna o sistema mais similar como sugestão. 

3. **Geração de nomes de novos sistemas:** 
    * Você fornece uma descrição do novo sistema.
    * A IA usa um modelo de linguagem para gerar sugestões de nomes para o sistema, com base na função descrita e nos nomes dos sistemas existentes. ✍️

**Exemplo de uso:**
*  Pergunte sobre a lista de sistemas já existentes:
* **Busca:** "A prefeitura de Santos tem um sistema que gerencia a educação?" 
* **Resultado:** "Sistema integrado de gestão escolar. Permite o cadastramento de alunos, com vagas, matrículas, transferências, localização de escolas, atribuições de aulas, entre outras funções." (SIGES) 

*  Gere sugestões de nome para novos sistemas:
* **Geração de nomes:** "Qual a descrição do novo sistema? (Digite 'fim' para encerrar):" "Sistema para agendar consultas médicas." 
* **Resposta:** "Agendamento Fácil, Consulta Rápida, Saúde na Hora, Sua Saúde em Foco, Agenda+Saúde" 

**Tecnologias utilizadas:**

*  Google AI Generative Language Models
*  Pandas
*  Numpy

**Requisitos:**

* ☁️ Conta na Google Cloud Platform
*  Instalar o pacote `google-generativeai`

**Para executar o código:**

1.  Clone o repositório.
2.  Instale o pacote `google-generativeai` usando o comando `pip install -q -U google-generativeai`.
3.  Crie um arquivo `SECRET_KEY.txt` e coloque nele a sua chave API da Google Cloud Platform.
4.  Execute o código Python.

**Observações:**

* ⚠️ Este é um projeto de exemplo. Você pode adaptá-lo para atender às suas necessidades específicas.
*  A qualidade dos resultados depende da qualidade dos embeddings e dos dados de treinamento.
* ⚖️ É importante usar a inteligência artificial de forma responsável e ética.

**Links úteis:**

* ➡️ Google AI Generative Language Models [https://es.wiktionary.org/wiki/removido](https://es.wiktionary.org/wiki/removido)
* ➡️ [Pandas](https://pandas.pydata.org/)
* ➡️ [Numpy](https://numpy.org/)

##  Contribuições

Sinta-se à vontade para contribuir com este projeto! Você pode:

*  Sugerir melhorias no código.
*  Criar novos casos de uso.
*  Traduzir o README.md para outros idiomas.

## ⚖️ Licença

Este projeto está licenciado sob a licença MIT.
