# NeuroLume

Landing page estática do NeuroLume Instituto da Dor e Fisioterapia Regenerativa, hospedada na Vercel.

## Arquivos públicos

- `index.html`: página principal, metadados sociais, SEO local e dados estruturados.
- `robots.txt`: libera mecanismos de busca e o `OAI-SearchBot`, usado pelo ChatGPT Search.
- `sitemap.xml`: informa a URL canônica da página.

## Privacidade da localização

O site deve exibir somente `Recanto das Emas/DF` e a referência geral ao Centro Olímpico e Paraolímpico. O endereço completo, o link exato do mapa e o ponto de referência exato não devem ser publicados: são enviados após a confirmação do agendamento.

## Conversões

Os links do WhatsApp já disparam os eventos `whatsapp_click` no `dataLayer` e `Contact` no Meta Pixel quando essas ferramentas estiverem instaladas. Ainda é necessário configurar no site o ID oficial do Meta Pixel para que os eventos sejam enviados à conta de anúncios.

## Publicação

A Vercel publica automaticamente após um push na branch conectada ao projeto. Depois da publicação, confirmar que `/robots.txt` e `/sitemap.xml` respondem com status 200.
