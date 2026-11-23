# Lâmina vs Mana — downloads e atualizações

Repositório **público de distribuição de instaladores Windows**. O código-fonte do jogo permanece no repositório privado do desenvolvedor.

## Versão atual para Windows

**[Baixar Lâmina vs Mana v0.1.6 (.exe)](https://github.com/Astros323/lamina-vs-mana-releases/releases/download/v0.1.6/lamina-vs-mana-setup-0.1.6.exe)**

- Atualização Windows baseada no conteúdo **v258 do ChatGPT Sites**, integrado por pull request.
- Corrige a ausência de Luigi e expande os sistemas de amizades de evento, Aizen, Isagi, cinematics, gráficos e habilidades integrados do backup mais recente.
- Mantém o novo ícone próprio no aplicativo, no instalador e no atalho.
- **Nova função:** no aplicativo Windows, abra **Login → Trazer progresso do jogo online para o Windows** e cole o código de registro mostrado no **Login** do site original. O aplicativo verifica o save, importa campanhas solo próprias, fichas, relíquias, amizades e conquistas, com backups do PC antes da operação. **Não transfere campanhas multiplayer compartilhadas nem rankings globais.**
- Prepara cadastro/login por e-mail e senha e snapshots criptografados. **A nuvem AINDA NÃO ESTÁ ATIVA.** O usuário não deve presumir que os dados estão armazenados online até o projeto Supabase e a tabela de usuários estarem conectados e testados.
- Continua salvando o progresso no aparelho; não apaga dados locais na atualização.
- Inclui o `latest.yml` e o `.blockmap` para atualizações Windows. A distribuição e a instalação não têm assinatura digital de produção.
- O Android fica adiado.

[Ver os arquivos da release v0.1.6](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.6).

Esta é uma **versão de avaliação**. Os testes automatizados e as verificações de interface Windows passaram, mas nem todas as cenas e partidas multiplayer foram verificadas manualmente em computadores de jogadores.

Não baixe os arquivos “Source code (zip)” ou “Source code (tar.gz)” para instalar. Baixe o instalador `.exe` indicado acima.

- **Atualizações pelo jogo, sem assistente de instalação:** o aplicativo baixa a nova versão em segundo plano. Ao clicar em **Atualizações → Atualizar e reiniciar**, instala silenciosamente e abre de novo. **Primeira transição:** versões anteriores à 0.1.6 podem exibir a janela do instalador mais uma vez, porque ainda usam o atualizador antigo. Em instalações com permissões administrativas, o Windows pode pedir confirmação.

## Histórico

- [Windows v0.1.5](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.5) — transferência de progresso do jogo online por código, com backups.
- [Windows v0.1.4](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.4) — novo ícone e preparação da nuvem.
- [Windows v0.1.3](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.3) — integração do Sites v258.
- [Windows v0.1.2](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.2) — primeira avaliação do aplicativo.

## Segurança e direitos de distribuição

Não compartilhe códigos de conta, tokens, senhas ou dados de jogadores por mensagens ou commits. Alguns personagens, imagens e músicas fazem referência a obras de terceiros; os direitos de redistribuição precisam ser verificados antes de uma distribuição ampla.
