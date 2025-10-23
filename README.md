# Configuração de uma Instância de Banco de Dados na Azure

Este repositório documenta o processo de criação e configuração de uma instância de **Banco de Dados na Azure** como parte do desafio proposto pela **Digital Innovation One (DIO)**. O objetivo é aplicar os conceitos aprendidos nas aulas, documentar a experiência prática e criar um material de apoio para futuros estudos e implementações.

---

## 🎯 Objetivos do Desafio

- Aplicar os conceitos teóricos em um ambiente prático na nuvem.
- Configurar uma instância de Banco de Dados SQL no Microsoft Azure.
- Documentar todo o processo de forma clara e estruturada.
- Utilizar o GitHub como ferramenta de compartilhamento de conhecimento técnico.

---

## 📚 Conteúdo Aprendido

Durante as vídeo-aulas e na execução deste laboratório, foram abordados os seguintes tópicos:

- Tipos de serviços de nuvem (IaaS, PaaS, SaaS)
- Visão geral do **Azure SQL Database**
- Diferenças entre **Banco de Dados Único**, **Pool Elástico** e **Instância Gerenciada**
- Criação de um **Grupo de Recursos** no Azure
- Configuração de regras de firewall e conectividade
- Boas práticas de segurança e gerenciamento de custos

---

## 🛠️ Passo a Passo da Configuração

1. **Acesse o [Portal do Azure](https://portal.azure.com)**
2. Crie um **Grupo de Recursos** (ex: `rg-banco-dados-dio`)
3. Navegue até **"Criar um recurso" > Banco de Dados > SQL Server**
4. Preencha os dados obrigatórios:
   - Nome do servidor
   - Credenciais de administrador (login e senha)
   - Região
5. Após criar o servidor, acesse-o e clique em **"Novo banco de dados"**
6. Escolha o tipo **"Banco de dados único"**
7. Configure o **nível de desempenho** (ex: Standard S0)
8. Revise e crie o banco de dados
9. Configure as **regras de firewall** para permitir acesso do seu IP ou de outros serviços
10. Conecte-se ao banco usando o **SQL Server Management Studio (SSMS)** ou outra ferramenta compatível

> 💡 **Dica**: Sempre revise os custos associados ao nível de serviço escolhido. Para estudos, prefira camadas gratuitas ou de baixo custo.

---

## 📌 Considerações Finais

Este laboratório foi essencial para entender como provisionar e gerenciar bancos de dados na nuvem de forma segura e escalável. A plataforma Azure oferece uma interface intuitiva e recursos avançados que facilitam a administração de ambientes de dados.

---

## 🔗 Recursos Úteis

- [Documentação Oficial do Azure SQL Database](https://learn.microsoft.com/pt-br/azure/azure-sql/database/)
- [GitHub Markdown Guide](https://docs.github.com/pt/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Formação GitHub Certification - DIO](https://github.com/dio)
