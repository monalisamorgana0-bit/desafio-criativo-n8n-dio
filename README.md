# desafio-criativo-n8n-dio
Desafio referente ao curso de Power BI do DIO

esafio Criativo N8N DIO


Quero criar uma automação no N8N para envio de e-mails para análise de crédito.

Público ou responsável:
Equipe comercial

Resultado esperado:
Salvar os dados em uma planilha referente a análise de crédito feito sobre os consultores.






Ferramentas envolvidas:
Gmail, Excel e SocialHUB

Fluxo desejado:
1. Receber email sobre os status do consultor
2. Registrar os dados na planilha
3. Enviar e-mail referente aprovação ou crédito negado ao consultor











Público:
Equipe Comercial

Ferramentas envolvidas:
Gmail, Excel e SocialHUB

Fluxo:
Receber email sobre os status do consultor
, registrar os dados na planilha e enviar e-mail referente aprovação ou crédito negado ao consultor

Regras:
Ignorar emails com pendências

Explique quais nós do N8N devem ser utilizados e a lógica de funcionamento do workflow.



N8N nós:

A montagem do workflow seria como um fluxo de leitura, validação, registro, decisão e comunicação.

Nós que seria utilizado:
- Gmail Trigger
- Edit Fields/ Code - Extrair os dados
- IF - Ignorar pendências
- Excel - Registrar o resultado
- IF - Identificar o resultado (Rota A - Aprovado e Rota B - Reprovado)
- Switch - Separar os status
- Gmail - Enviar aprovação
- Gmail - Enviar crédito negado

