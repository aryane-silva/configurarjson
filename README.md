# configurarjson
Passo a passo de como configurar/baixar o arquivo. O JSON é um cartão de identidade digital que o Google gera para o seu projeto. Ele serve para provar para o Google que o script Python tem permissão para acessar APIs (como Sheets, Drive, Gmail, etc).

---🔹 1. Criar ou obter o credentials.json ---
Esse é o arquivo de credenciais que o Google gera quando você habilita APIs (ex: Google Sheets, Drive, Gmail).
Acesse o Google Cloud Console
Crie um projeto (se ainda não tiver).
Vá em APIs e Serviços > Tela de consentimento OAuth → configure como Interno ou Externo.
Vá em APIs e Serviços > Credenciais.
Clique em Criar credencial > ID do cliente OAuth.
---Configurar cliente OAuth---
> Tipo: Aplicativo WEB
Tipo de aplicativo: Área de trabalho.
Baixe o arquivo JSON → ele terá um nome como client_secret_1234.json.
Renomeie para credentials.json. ##
