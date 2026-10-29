# Bichopédia

Enciclopédia de animais.

Site: https://bichopedia-mundo-descobertas.vercel.app/

## Abrir localmente

Com Node.js instalado, execute `npm start` e abra http://127.0.0.1:4173.

## Hospedar

O site é estático e não exige instalação de dependências nem etapa de compilação. Publique a pasta `dist` em um serviço de hospedagem estática. A configuração `vercel.json` usa a pasta `dist` para a hospedagem na Vercel. A publicação atual é feita por envio direto dos arquivos.

## Conteúdo

- `dist/index.html`: estrutura da página.
- `dist/style.css`: visual e adaptação a celulares.
- `dist/app.js`: catálogo original, filtros, fichas e favoritos.
- `dist/extra-animals.js`: 24 fichas adicionais.
- `extra-animals.json`: dados editáveis das fichas adicionais.
- `dist/assets`: fotografias locais e créditos.
- `dist/creditos.html`: autoria e licenças das imagens.

Os dados são educativos e aproximados. O catálogo inclui espécies, grupos e animais domésticos, e não representa todos os animais existentes. Informações de cuidado não substituem orientação veterinária. Cada ficha contém links para leitura adicional. As imagens da Wikimedia Commons mantêm suas licenças individuais; consulte `dist/creditos.html` antes de reutilizar. As fontes Google Fonts são carregadas externamente, com fontes locais alternativas.

