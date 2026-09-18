# Planos de Tráfego · páginas estáticas

Cada planejamento é uma página HTML independente neste repositório. Depois do deploy, cada uma fica disponível no seu próprio caminho, sob o mesmo domínio do projeto:

| Cliente | Arquivo | URL após o deploy |
|---|---|---|
| Loja Magnífica | `index.html` | `https://<projeto>.vercel.app/` |
| Joliv Estética | `joliv-estetica.html` | `https://<projeto>.vercel.app/joliv-estetica.html` |
| Camis Tênis Premium | `camis-tenis.html` | `https://<projeto>.vercel.app/camis-tenis.html` |
| Dhayanne (corretora) | `dhayanne-corretora.html` | `https://<projeto>.vercel.app/dhayanne-corretora.html` |
| Jessica Jesus (depilação a laser) | `jessica-depilacao.html` | `https://<projeto>.vercel.app/jessica-depilacao.html` |

## Publicar na Vercel

Este repositório não está conectado a nenhuma conta Vercel a partir desta sessão — o deploy precisa ser feito pela conta do responsável pelo projeto:

1. Acesse [vercel.com/new](https://vercel.com/new) e importe este repositório GitHub (`Pedrosamkt/site-`, branch `claude/planejamento-profissional-09ktcz`).
2. Nomeie o projeto como preferir (ex.: `planejamento-magnifica`) — a Vercel gera automaticamente `<nome-do-projeto>.vercel.app`.
3. Não é necessário configurar build command nem output directory: são arquivos `.html` estáticos na raiz.
4. Deploy. Cada link da tabela acima fica pronto em menos de um minuto.

**Pra tirar do ar depois (hospedagem temporária):** em **Project Settings → General**, no final da página tem a opção **Delete Project** — remove o deploy e libera o domínio.

Se preferir um domínio próprio, isso é feito em **Project Settings → Domains**, dentro da própria Vercel.
