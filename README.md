# Roleta Europeia — Deslocamento

Painel web compacto para celular e uso em tela dividida.

## Como usar
1. Abra o endereço publicado pelo GitHub Pages.
2. Toque em três números na ordem em que saíram.
3. Toque em **ANALISAR** para ver três números calculados.
4. Use **DESFAZER** ou **LIMPAR** para corrigir a sequência.

## Regra matemática
A aplicação usa a ordem física oficial da roda europeia (37 casas). Calcula os dois deslocamentos assinados mais curtos entre os três resultados, tira a média aritmética e arredonda para a casa inteira mais próxima. Em seguida, aplica esse passo repetidamente a partir do terceiro resultado para exibir três casas.

**Aviso:** isso é apenas uma transformação matemática da sequência informada. A roleta é um jogo de resultados independentes; o cálculo não prevê resultados nem aumenta a chance de acerto.

## Publicar
No GitHub, abra **Settings → Pages**, escolha **Deploy from a branch**, selecione **main** e a pasta **/(root)** e salve. O arquivo principal é `index.html`.
