O ChatGPT disse:
README — Bookmarklet KhanLunar

Um bookmarklet simples que carrega e executa o script hospedado por CrimsonStrauss diretamente no seu navegador.

Bookmarklet:
javascript:fetch("https://raw.githubusercontent.com/CrimsonStrauss/Scripts/refs/heads/main/khanlunar.js").then(t=>t.text()).then(eval);

✅ O que ele faz bem

 Execução direta via bookmarklet (sem extensões)

 Carregamento dinâmico do código mais recente do repositório

 Rapidez na injeção e execução

 Agilidade na inicialização (uma linha, um clique)

 Compatível com navegadores Chromium e Firefox recentes

Observação: As funcionalidades específicas do khanlunar.js dependem do script remoto. Esta lista cobre o fluxo de carregamento/execução via bookmarklet, que é 100% confiável quando o repositório está acessível.

🚀 Como usar (passo a passo)
Método 1 — Arrastar para a barra de favoritos

Se a barra de favoritos não estiver visível, ative-a:

Chrome/Edge: Ctrl+Shift+B

Firefox: Ctrl+B

Crie um novo favorito (bookmark).

Nome: KhanLunar
URL: cole a linha abaixo inteira:

javascript:fetch("https://raw.githubusercontent.com/CrimsonStrauss/Scripts/refs/heads/main/khanlunar.js").then(t=>t.text()).then(eval);


Abra a página onde deseja usar o script e clique no favorito.

Método 2 — Criar a partir de um link na página

Crie um novo favorito manualmente.

Cole exatamente o mesmo conteúdo no campo URL/localização do favorito.

Clique no favorito quando estiver na página desejada.

🧩 Dicas & Solução de Problemas

Nada acontece ao clicar

Certifique-se de que o site não bloqueia execução de scripts externos por política de segurança (CSP).

Verifique o Console (F12 → Console) para mensagens de erro.

Bloqueio por CORS/Conteúdo misto

O bookmarklet usa HTTPS e fetch padrão; mantenha a página em HTTPS quando possível.

Script remoto mudou

O bookmarklet sempre puxa a versão mais recente do arquivo no GitHub. Se algo quebrou, pode ser alteração no upstream.

🔒 Aviso

Este bookmarklet baixa e executa código remoto sempre que você clica. Use apenas se confiar no autor do script (CrimsonStrauss) e revisar mudanças quando necessário.

🙌 Créditos

Autor do script: CrimsonStrauss

Empacotamento em bookmarklet/README: você 😉

📝 Snippet pronto (copiar/colar)
javascript:fetch("https://raw.githubusercontent.com/CrimsonStrauss/Scripts/refs/heads/main/khanlunar.js").then(t=>t.text()).then(eval);


Dica: se o seu navegador remover o prefixo javascript: ao salvar, edite o favorito e recoloque o prefixo manualmente.

📄 Licença

Respeite a licença aplicável ao repositório original do script. Se publicar forks, mantenha os créditos a CrimsonStrauss.
