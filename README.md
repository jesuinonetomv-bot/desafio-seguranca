# Desafio Segurança

Quiz online de Segurança do Trabalho com cadastro e ranking dos cinco melhores resultados.

## Configurar o Firebase

1. Crie um projeto no Firebase Console.
2. Ative **Authentication > Sign-in method > Anônimo**.
3. Crie um **Realtime Database**.
4. Em **Realtime Database > Regras**, use `database.rules.json` e publique.
5. Em **Configurações do projeto > Seus aplicativos**, adicione um aplicativo Web.
6. Copie a configuração fornecida para `dist/firebase-config.js`.
7. Em **Authentication > Settings > Authorized domains**, adicione o domínio do GitHub Pages.

O telefone fica em `privateContacts`, sem leitura pública. O ranking mostra nome, empresa, área e somente a melhor pontuação vinculada ao hash do telefone.

## Publicar no GitHub Pages

1. Crie um repositório novo no GitHub.
2. Envie todos os arquivos deste projeto para a branch `main`.
3. Abra **Settings > Pages** e escolha **GitHub Actions** em *Source*.
4. A publicação será executada automaticamente.
