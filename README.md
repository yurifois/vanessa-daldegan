# NeuroLume

Landing page estática do NeuroLume Instituto da Dor e Fisioterapia Regenerativa, hospedada na Vercel.

## Arquivos públicos

- `index.html`: página principal, metadados sociais, SEO local e dados estruturados.
- `robots.txt`: libera mecanismos de busca e o `OAI-SearchBot`, usado pelo ChatGPT Search.
- `sitemap.xml`: informa a URL canônica da página.

## Localização e agendamento

O site informa a região de atendimento e exibe o mapa aprovado da NeuroLume, com botão para abrir a rota no Google Maps. O atendimento é realizado somente com hora marcada; as orientações complementares de chegada são enviadas após a confirmação do agendamento.

## Conversões

Os links do WhatsApp já disparam os eventos `whatsapp_click` no `dataLayer` e `Contact` no Meta Pixel quando essas ferramentas estiverem instaladas. Ainda é necessário configurar no site o ID oficial do Meta Pixel para que os eventos sejam enviados à conta de anúncios.

## Publicação

A Vercel publica automaticamente após um push na branch conectada ao projeto. Depois da publicação, confirmar que `/robots.txt` e `/sitemap.xml` respondem com status 200.
