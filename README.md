# Lâmina vs Mana — downloads e atualizações

Repositório **público de distribuição de instaladores Windows**. O código-fonte do jogo permanece no repositório privado do desenvolvedor.

## Versão atual para Windows

**[Baixar Lâmina vs Mana v0.1.10 (.exe)](https://github.com/Astros323/lamina-vs-mana-releases/releases/download/v0.1.10/lamina-vs-mana-setup-0.1.10.exe)**

- **Windows v0.1.10:** Login por e-mail é lembrado entre aberturas usando o cofre criptografado do Windows; o jogo inicia em tela cheia (F11 alterna); o endereço local é estável, evitando que dados do navegador interno comecem zerados a cada reinício; eventos Aizen, Luigi, Ainz, Goku, Morte Espiral e trailer não entram automaticamente numa fila ao abrir o aplicativo, mas continuam disponíveis pelos botões de replay.
- **Segurança na reconexão:** a sincronização automática só é retomada quando a cópia do PC corresponde à versão confirmada na nuvem. Se não corresponder, o jogo pede uma escolha explícita para não sobrescrever um save diferente.
- **Atenção ao atualizar das versões 0.1.8 ou anteriores:** antes de atualizar, abra a versão antiga, copie seu código de registro e clique em **Sincronizar agora**. As versões anteriores usavam uma porta local aleatória; dados guardados apenas nessa origem anterior podem precisar ser recuperados pelo código de registro ou por **Restaurar da nuvem**. **Não desinstale apagando os dados do jogo** e não sobrescreva backups antes de confirmar seus itens e personagens.
- Atualização Windows baseada no conteúdo **v258 do ChatGPT Sites**, integrado por pull request.
- Corrige a ausência de Luigi e expande os sistemas de amizades de evento, Aizen, Isagi, cinematics, gráficos e habilidades integrados do backup mais recente.
- Mantém o novo ícone próprio no aplicativo, no instalador e no atalho.
- **Nova função:** no aplicativo Windows, abra **Login → Trazer progresso do jogo online para o Windows** e cole o código de registro mostrado no **Login** do site original. O aplicativo verifica o save, importa campanhas solo próprias, fichas, relíquias, amizades e conquistas, com backups do PC antes da operação. **Não transfere campanhas multiplayer compartilhadas nem rankings globais.**
- **Conta na nuvem ativada na v0.1.8:** cadastro por e-mail/senha, backups criptografados de progresso do navegador e de campanhas solo/fichas/amizades/conquistas do banco local. Quando a conta ainda não tem um save, o primeiro backup é criado automaticamente. Depois há sincronização periódica enquanto o jogo estiver aberto e autenticado.
- **Segurança:** histórico das 15 versões anteriores, backups locais antes de restaurar, RLS por jogador e bloqueio de sobrescrita de campanhas mais recentes. Não migra salas multiplayer nem rankings globais. **Guarde o código de registro e um backup local:** mudar a senha sem migrar os saves criptografados pode tornar backups antigos ilegíveis.
- Continua salvando o progresso no aparelho; não apaga dados locais na atualização.
- Inclui o `latest.yml` e o `.blockmap` para atualizações Windows. A distribuição e a instalação não têm assinatura digital de produção.
- O Android fica adiado.

[Ver os arquivos da release v0.1.10](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.10).

Esta é uma **versão de avaliação**. Os testes automatizados e as verificações de interface Windows passaram, mas nem todas as cenas e partidas multiplayer foram verificadas manualmente em computadores de jogadores.

Não baixe os arquivos “Source code (zip)” ou “Source code (tar.gz)” para instalar. Baixe o instalador `.exe` indicado acima.

- **Atualizações pelo jogo, sem assistente de instalação:** o aplicativo baixa a nova versão em segundo plano. Ao clicar em **Atualizações → Atualizar e reiniciar**, instala silenciosamente e abre de novo. **Primeira transição:** versões anteriores à 0.1.6 podem exibir a janela do instalador mais uma vez, porque ainda usam o atualizador antigo. Em instalações com permissões administrativas, o Windows pode pedir confirmação.

## Histórico

- [Windows v0.1.9](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.9) — tela cheia e correções de sessão/intro; substituída pela v0.1.10 com proteção extra de backups.
- [Windows v0.1.8](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.8) — ativação do Supabase e backups do progresso.
- [Windows v0.1.7](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.7) — correções de História e importação no Windows.
- [Windows v0.1.6](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.6) — atualização silenciosa dentro do jogo.
- [Windows v0.1.5](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.5) — transferência de progresso do jogo online por código, com backups.
- [Windows v0.1.4](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.4) — novo ícone e preparação da nuvem.
- [Windows v0.1.3](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.3) — integração do Sites v258.
- [Windows v0.1.2](https://github.com/Astros323/lamina-vs-mana-releases/releases/tag/v0.1.2) — primeira avaliação do aplicativo.

## Segurança e direitos de distribuição

Não compartilhe códigos de conta, tokens, senhas ou dados de jogadores por mensagens ou commits. Alguns personagens, imagens e músicas fazem referência a obras de terceiros; os direitos de redistribuição precisam ser verificados antes de uma distribuição ampla.
