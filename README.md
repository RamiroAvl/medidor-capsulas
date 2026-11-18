# Medidor de cápsulas · Cryptococcus

Página que detecta células de *Cryptococcus* coradas com tinta nanquim e mede, célula a célula, o diâmetro total, o diâmetro do corpo e a espessura da cápsula.

- Tudo roda no navegador: as imagens não são enviadas para nenhum servidor.
- Aceita JPG, PNG e TIF (inclusive 16 bits).
- Site estático: não precisa de build. Na Vercel, importe o repositório e mantenha as configurações padrão.

Bibliotecas incluídas em `lib/`: [UTIF.js](https://github.com/photopea/UTIF.js) (MIT) e [pako](https://github.com/nodeca/pako) (MIT/Zlib), usadas para ler arquivos TIF.
