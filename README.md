Por que o arquivo .env não deve ser versionado?
O arquivo .env guarda informações sensíveis, como senhas e chaves secretas. Se ele for para o GitHub, qualquer pessoa pode acessar esses dados, o que pode causar problemas de segurança no sistema.

Qual a função do pip freeze no desenvolvimento em equipe?
O pip freeze serve para listar todas as bibliotecas e versões usadas no projeto. Isso ajuda a equipe a instalar exatamente as mesmas dependências, evitando erros por diferenças de versões.

O que pode acontecer se a SECRET_KEY for exposta?
Se a SECRET_KEY vazar, alguém pode comprometer a segurança do sistema, como falsificar sessões, acessar dados ou até assumir controle da aplicação.

Qual o papel do .gitignore em projetos colaborativos?
O .gitignore serve para impedir que arquivos desnecessários ou sensíveis (como .env e arquivos temporários) sejam enviados para o repositório, mantendo o projeto organizado e seguro.
