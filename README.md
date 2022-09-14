# Back-end

## Entidades
- Games
- Anúncions
(Relação de 1 para muitos)

### GAME
- id
- title
- bannerUrl

CDN (Amazon S3) (Content Delivery Network) => Faz o upload para um CDN que nos retorna uma URL - Não é o que faremos aqui, utilizaremos a url dos banners dos jogos da própria Twitch

### Ad
- id
- gameId
- name
- yearsPlaying
- discord
- weekDays
- hourStart
- hourEnd
- useVoiceChannel
- createdAt

1:30h -> 90min
R$ 179,89 -> 17989

Datas (fuso horário / formatos diferentes i18n)
Pontos flutuantes

## Casos de Uso
- Listagem de games com contagem de anúncios
- Criação de novo anúncio
- Listagem de anúncios por game
- Buscar discord pelo ID do anúncio
