# Noções Básicas para RPA Developers

Este repositório contém um projeto de automação desenvolvido com UiPath, focado na recuperação de emails do Outlook e no salvamento de anexos.

## Descrição do Projeto

Neste projeto, você aprenderá a:

- Recuperar emails do Outlook.
- Usar expressões de filtragem na propriedade "Filter".
- Criar variáveis.
- Usar a atividade "For Each" para iterar pelos dados e processar cada informação separadamente.
- Usar a atividade "Save Attachments" para salvar os anexos das mensagens de email em uma pasta específica.

## Cenário de Demonstração

Para ilustrar o cenário, utilizamos o aplicativo web "ACME" e uma conta de email do Outlook.
## Etapas do Desenvolvimento

1. **Criar um Novo Processo**: Inclua um nome, local e descrição.
2. **Adicionar a Atividade "Get Outlook Mail Messages"**: Configure as propriedades necessárias, como:
   - Conta do Outlook (deixe em branco se já estiver conectado)
   - Pasta do email (use "Inbox")
   - Filtros (pesquise emails com "Course Invoices" no assunto)
   - Marcar como lida
   - Mensagens não lidas
3. **Criar Variáveis**: Armazene os emails recuperados em uma variável chamada `CourseEmails`.
4. **Log de Mensagens**: Adicione uma atividade para determinar quantas mensagens foram recuperadas.
5. **Iteração com "For Each"**: Processe cada email usando `For Each` e configure o tipo como `System.Net.Mail.MailMessage`.
6. **Salvar Anexos**: Adicione a atividade "Save Attachments" para salvar os anexos em uma pasta chamada "Invoices".

## Execução do Projeto

Execute o projeto no modo de depuração para observar o fluxo de trabalho. Você verá uma nova pasta "Invoices" criada, onde os anexos serão salvos.

## Conclusão

Neste projeto, você aprendeu a:

- Recuperar emails do Outlook e aplicar filtros.
- Criar e usar variáveis.
- Iterar através de uma coleção de emails.
- Salvar anexos em uma pasta específica.

Agradecemos por acompanhar o curso. Boa automação!

## Licença

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
# Para-RPA-Developers
