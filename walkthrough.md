# Walkthrough de revisão local — 29/09/2026

## Escopo

Revisão local de `index.html` da landing page da CC Projetos. Não houve publicação, deploy, commit, push ou alteração de integrações, UTMs, conversões, chaves, webhooks ou arquivos externos à landing.

## Conteúdo revisado

- Título: `Regularização de Obras e Imóveis em Araras | CC Projetos`.
- Não há ocorrências de `Técnico em Edificações` nem de `CRT/SP`.
- Os seis serviços exibidos são: Regularização de obras; Habite-se / Aceite; Averbação da construção; CNO / SERO / INSS da obra; Desdobro ou unificação; Consultoria e viabilidade.

## Verificação de WhatsApp

- Foram conferidos os 12 CTAs com a classe `.js-whatsapp` e o redirecionamento do formulário.
- Todas as 13 URLs de abertura usam exclusivamente `https://wa.me/5519997959587`.
- Os CTAs abrem em nova aba com `target="_blank"` e `rel="noopener"`.
- O formulário monta a mensagem e abre o mesmo número; não foi enviado formulário nem iniciada conversa real.

## Verificação mobile

- Até `900px`, a navegação principal e o CTA do cabeçalho são ocultados, o menu móvel é disponibilizado e os grids passam a uma ou duas colunas conforme a seção.
- Até `600px`, ações do hero ocupam 100% da largura, e os grids de formulário, serviços, casos e dúvidas passam a uma coluna.
- A inspeção visual da cópia local por navegador não foi executada porque a política do navegador controlado bloqueia URLs `file:`. Esta verificação registra a análise estática das regras responsivas atuais; não afirma uma captura visual que não foi realizada.

## Sincronização

Os arquivos `index.html` das pastas `ccprojetos-landing-publish` e `ccprojetos-landing-main` foram comparados byte a byte e estão idênticos nesta revisão.
