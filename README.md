# Assistente de Diagnóstico e Resolução de Falhas

Protótipo que identifica a causa de uma falha em máquinas, decide se dá para resolver por software e, se não der, orienta a abertura da ordem de serviço certa.

**Demo:** https://orezzende.github.io/assistente-diagnostico-falhas/

## Funcionalidades

- Simulação da conexão com o equipamento (cabo USB ou Bluetooth)
- Diagnóstico que cruza códigos de falha e sintomas com uma base de problemas conhecidos e manuais cadastrados, com nível de confiança
- Classificação da falha como técnica/sistêmica (correção automática) ou física (manutenção)
- Cadastro de novos problemas e manuais, e histórico de diagnósticos exportável em CSV

## Tecnologias

HTML, CSS, JavaScript

## Como usar

Conecte o equipamento simulado, execute o diagnóstico e use o botão de resolução.

Também dá para baixar o repositório e abrir o `index.html` direto no navegador, sem instalar nada.

## Observações

Protótipo de estudo/portfólio: motor de correspondência por regras e palavras-chave, tudo em memória no navegador. A conexão USB/Bluetooth é simulada.

## Autor

Daniel da Silva Rezende · [GitHub](https://github.com/orezzende) · [LinkedIn](https://www.linkedin.com/in/daniel-da-silva-rezende-711ab1195/)
