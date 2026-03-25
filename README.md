# Criando sites com Distill
O Primeiro passo foi instalar o pacote 'distill' do R , e criar um repositório no Git com o projeto e depois passo url pro Rstudio. 

```R
library(distill)
create_website(dir = ".", title = "Encontros com a estatística", gh_pages = TRUE)
```
Depois faz o push do que você fez pro git e reinicia a sua sessão no R por que tem que aparecer uma aba Build no canto superior no lado direito . E quando você reiniciar a sua sessão clica em build website nessa aba.
Um dos grandes problemas que eu encontrei ao fazer site com distill foi com o arquivo "about.rmd" e eu vi um conselho de assim que for criado o site você apagar e recria essa página e dá tudo certo 

