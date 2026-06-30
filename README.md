# Implementando sua Primeira Stack com AWS CloudFormation

Repositório desenvolvido para o desafio prático da plataforma DIO (Digital Innovation One). O objetivo principal deste projeto é demonstrar o entendimento prático de Infraestrutura como Código (IaC) utilizando o AWS CloudFormation.

# Objetivos do Projeto
* Aplicar conceitos de Infraestrutura como Código (IaC) em um ambiente prático.
* Automatizar o provisionamento de recursos na AWS.
* Documentar os processos técnicos e insights adquiridos durante o aprendizado.

# Tecnologias Utilizadas
* **AWS CloudFormation:** Para a escrita do template e gerenciamento da Stack.
* **AWS EC2:** Recurso computacional provisionado automaticamente.
* **GitHub:** Para versionamento e compartilhamento da documentação técnica.

# Processo de Implementação e Insights

### O que é CloudFormation?
O AWS CloudFormation permite modelar e configurar seus recursos da AWS de forma declarativa utilizando arquivos de texto (YAML ou JSON). Isso elimina a necessidade de criar recursos manualmente pelo console da AWS, garantindo repetibilidade e consistência.

### Passos Realizados:
1. **Modelagem:** Criação do arquivo `template.yaml` definindo uma instância EC2 (`t2.micro`).
2. **Validação:** Verificação da sintaxe do arquivo para garantir que a estrutura declarada respeita os padrões da AWS.
3. **Provisionamento:** Upload do template no console do CloudFormation para a criação e inicialização automatizada da Stack.

### Principais Aprendizados (Insights):
* **Padronização:** A infraestrutura tratada como código reduz drasticamente falhas humanas de configuração manual.
* **Controle de Estado:** Se um recurso falhar durante a criação da Stack, o CloudFormation realiza o *rollback* automático, deixando o ambiente seguro e sem custos residuais inesperados.
* **Evolução:** Compreender o CloudFormation é a base para evoluir para arquiteturas mais robustas e pipelines de CI/CD focados em Cloud DevOps.

---
Desenvolvido como parte de estudos na plataforma DIO.
