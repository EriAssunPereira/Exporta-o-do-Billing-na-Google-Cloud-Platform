# Exporta-o-do-Billing-na-Google-Cloud-Platform
Vou explicar o processo passo a passo de como exportar o faturamento da organização para o **BigQuery** e, em seguida, vou fornecer instruções sobre como criar um repositório no GitHub com prints e um README detalhando o processo executado.

## Passos para Exportar o Faturamento para o BigQuery:

1. **Acesse o Console da GCP**:
   - Faça login na sua conta da GCP.
   - Acesse o [Console da GCP](https://console.cloud.google.com/).

2. **Navegue até a página de Faturamento**:
   - No painel de navegação à esquerda, clique em "Faturamento".
   - Você verá informações sobre os custos atuais e detalhes de faturamento.

3. **Configuração do BigQuery Export**:
   - Clique na guia "Exportar para o BigQuery".
   - Selecione a organização ou projeto para o qual deseja exportar os dados de faturamento.
   - Escolha um dataset existente no BigQuery ou crie um novo dataset para receber os dados exportados.

4. **Configurações Avançadas**:
   - Você pode definir opções avançadas, como o formato dos dados (CSV, JSON, etc.), a frequência de exportação (diária, mensal) e o horário de execução.
   - Configure as opções conforme suas necessidades.

5. **Criação de Credenciais**:
   - Se você ainda não tiver credenciais de serviço, crie uma nova chave de conta de serviço no formato JSON.
   - Essa chave será usada para autenticar o acesso ao BigQuery.

6. **Conclua a Configuração**:
   - Clique em "Salvar" para concluir a configuração de exportação.
   - Os dados de faturamento serão exportados para o dataset especificado no BigQuery.

## Criação do Repositório no GitHub:

1. **Crie um Novo Repositório**:
   - Acesse o [GitHub](https://github.com/).
   - Faça login na sua conta.
   - Clique em "Novo" para criar um novo repositório.
   - Escolha um nome, descrição e outras configurações.

2. **Adicione os Prints e o README**:
   - No seu repositório, clique em "Adicionar arquivo" e escolha "Upload files".
   - Faça upload dos prints/screenshots do processo de configuração de exportação para o BigQuery.
   - Crie um arquivo README.md com informações sobre o desafio, os passos seguidos e qualquer outra observação relevante.

3. **Commit e Push**:
   - Adicione uma mensagem de commit (por exemplo, "Adicionando prints e README").
   - Clique em "Commit" e, em seguida, em "Push".

4. **Compartilhe o Link do Repositório**:
   - Copie o link do seu repositório e compartilhe com quem solicitou o desafio.
