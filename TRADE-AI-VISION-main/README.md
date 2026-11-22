# TRADE AI VISION 3.0

Painel web experimental para leitura visual de capturas de gráficos.

## Publicação
O site é publicado pelo GitHub Actions em GitHub Pages a cada atualização da branch `main`.

## Recursos desta primeira publicação
- Interface responsiva para desktop e celular.
- Importação de imagem e captura pela câmera do navegador.
- Heurística simples de predominância de pixels verdes/vermelhos.
- Histórico local e exportação CSV.
- Preferências locais para notificações e avisos sonoros.

## Limitações importantes
- Não fornece cotações ao vivo nem conexão com corretoras.
- A leitura de cores não reconhece candles com confiabilidade e não calcula indicadores técnicos reais.
- A pontuação exibida é heurística, não probabilidade de acerto.
- O histórico fica no navegador/dispositivo e não sincroniza na nuvem.
- Não executa ordens. Não é recomendação financeira.
- A captura de outros aplicativos em segundo plano exige o app Android nativo e autorização explícita do Android; GitHub Pages não oferece essa função.

## Uso
Abra o site, selecione ativo e horizonte, envie uma captura do gráfico e clique em **Analisar imagem**.
