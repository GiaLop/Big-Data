Sentiment Analysis su crypto markets.

Ho verificato se il sentiment su Twitter può anticipare movimenti Bitcoin.

Cosa ho fatto:
- 50K+ tweets filtrati (LangDetect per lingua, TextBlob per sentiment)
- Prezzi BTC aggregati daily
- Correlazione sentiment score vs price variation (lag 0-3 giorni)
- Spark e Pandas per preprocessing, data cleaning, aggregazioni e  vizs, SQL per insight veloci

Risultato:
Correlazione debole ma presente (0.13) con lag 1-month/year.
Il rumore è alto - troppi fattori esterni influenzano BTC.
