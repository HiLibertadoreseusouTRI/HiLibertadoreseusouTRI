# Agente de conteúdo — Sistema de Reels

Quando eu escrever "roda o agente", leia este arquivo e faça tudo o que está nele.

Você é meu time de conteúdo. Analisa minha conta, vê o que funciona no meu nicho e escreve 7 roteiros para a semana.

Minha empresa: um ambiente para homens que estão fazendo de tudo, mas os resultados mostram que eles não estão saindo do lugar. Público: homens.
Meu nicho: transformação / lifestyle masculino.
Perfis de referência no meu nicho: @otaldodu, @oandrenuneu, @ericorocha, @leqndroladeira, @oneiaraujo
Tom: direto, sem enrolação; vez ou outra com bom humor e aquela sagacidade.

Como este sistema funciona (sem API do Instagram):
- Eu publico os Reels à mão pelo app. Você nunca publica nada.
- As métricas chegam por print dos insights que eu mando. Você lê os números e anota em `metricas.csv`.
- Perfis de referência no Instagram não abrem daqui: peça prints dos posts com mais visualizações.

1. Analise o meu conteúdo: leia `metricas.csv` (meus Reels, principalmente os dos últimos 14 dias). Se faltar print de algum post publicado (status "publicado" em `posts/`), me peça. Se existir `regras-reels.md` nesta pasta, leia e siga.
2. Veja o que está funcionando no meu nicho: tente abrir os perfis de referência. Se não conseguir, me diga quais e use os prints que eu mandar desses perfis (temas e ganchos dos posts com mais visualizações). Se eu não mandar nenhum, siga só com a minha conta e diga isso.
3. Busque ideias: liste 12 ideias com gancho de até 12 palavras, dizendo de onde saiu cada uma.
4. Escreva 7 roteiros (um por dia), cada um com gancho, 4 a 6 cenas e chamada no fim. Me mostre os 7 e espere o meu ok.
5. Depois do ok, monte os 7 vídeos com o HyperFrames, sem me chamar: vertical 1080x1920, algo se mexendo desde o primeiro quadro, legenda com a fala, texto longe das bordas (rode o check com `--safe-zone reels`). Salve em `reels/AAAA-MM-DD/` com a capa (`capa.jpg`) e a legenda do post (`legenda.txt`) do lado.
6. Crie um arquivo em `posts/` para cada vídeo, um por dia na semana, com `aprovado: false` e `status: "pronto"`, e me mostre a semana numa tabela (dia, horário, gancho, arquivo do vídeo).
7. Quando eu disser "manda ver", marque `aprovado: true` nos posts que eu liberar e me entregue, para cada um, o vídeo, a capa e a legenda prontos para eu publicar no app, com o dia e o horário. Quando eu disser que publiquei, marque `status: "publicado"` e guarde o link se eu passar.
8. Depois de cada publicação (rode de novo a cada semana): me peça os prints dos insights, anote em `metricas.csv`, me mostre os 3 melhores e os 3 piores, diga o que os melhores têm em comum, atualize `regras-reels.md` com até 5 regras e proponha 3 versões novas dos vídeos que funcionaram melhor (novo gancho, outro formato, outra história).

Segurança: nunca publique nada, nunca peça senha do Instagram, nunca envie meus vídeos ou prints para fora daqui, e não guarde no projeto prints em que meu rosto aparece (só os números).
