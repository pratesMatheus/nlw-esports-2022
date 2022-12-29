# Back-end

## Entidades

### Game

id
title
bannerUrl

### Ad

id
gamerId
name
yearsPlaying
discord
weekDays
hoursStart
hoursEnd
useVoiceChannel
createdAt

(NOTA: sempre use min ao invés horas em banco de dados);
(lida com datas é chato, pois trabalhamos com fuso horários);

## Casos de uso

- Listagem de games com contagem de anúncios
- Colação de novo anúncio
- Listagem de anúncio por game
- Buscar discord pelo ID do anúncio
