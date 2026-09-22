# Rota do Patrimônio · site da equipe

Arquivos: `index.html` (o site inteiro) e `vercel.json` (cabeçalhos de segurança).

Banco: Supabase, projeto **rota-do-patrimonio** (região São Paulo).

## Publicar na Vercel
1. Acesse vercel.com, clique em **Add New → Project**.
2. Suba esta pasta (por um repositório no GitHub ou pela CLI: `npx vercel --prod` dentro da pasta).
3. Framework: **Other**. Sem build. Pode publicar.

## Configurar o login no Supabase
Painel do Supabase → projeto rota-do-patrimonio → **Authentication → URL Configuration**:
- **Site URL**: o endereço do site na Vercel (ex.: https://rota-do-patrimonio.vercel.app)
- **Redirect URLs**: o mesmo endereço

## Ativar a leitura com IA (opcional)
**Edge Functions → Secrets** → adicionar `ANTHROPIC_API_KEY` com uma chave da API da Anthropic (console.anthropic.com). O uso é cobrado por leitura.

## Liberar acesso
Quem é administrador entra no site e usa a aba **Equipe** para liberar os e-mails dos treinadores.
