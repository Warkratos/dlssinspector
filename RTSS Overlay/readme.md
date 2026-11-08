# Overlay Preview

Fiz 2 versões, uma utiliza dos dados PresentMon embutidos no RTSS pra apresentar o PC Latency, Present Mode e estatísticas de Frametime em Display Time que são ideais para Frame Gen, e o outro usa somente os dados nativos do RTSS.

Arquivo .ovl pra colocar na pasta "..\RivaTuner Statistics Server\Plugins\Client\Overlays"

## Versão sem dados do PresentMon: [Download](https://github.com/Warkratos/dlssinspector/raw/main/RTSS%20Overlay/renanmpv3.ovl)

<img width="363" height="169" alt="Captura de tela 2026-10-17 222748" src="https://github.com/user-attachments/assets/7f938211-a944-4810-943a-794a09acaa83" /><br/>
Nessa versão, as métricas de "FPS Average", "FPS 1% Low" e "FPS 0.1% Low" aparecem somente no quando o modo benchmark é ativado.

## Versão com dados do PresentMon: [Download](https://github.com/Warkratos/dlssinspector/raw/main/RTSS%20Overlay/renanmpv3PM.ovl)

<img width="331" height="331" alt="image" src="https://github.com/user-attachments/assets/05bb1a12-af48-4c8f-bc9b-cd2919f37142" /><br/>
Funcionalidades dessa versão: 
- Mostra o frametime em "msBetweenPresent" e "msBetweenDisplayChange", a versão Present mostra o cálculo em tempo real se está em "Start-to-Start" (novo) ou "Present-to-Present".
- Mostra o tipo de presentation model utilizado pelo jogo atualmente, veja mais sobre os modelos de apresentação e porque é recomendado ficar no "Independent Flip" [clicando aqui](https://github.com/Warkratos/dlssinspector/blob/main/Dicas/presentationmodel.md)
- Mostra se está sendo limitado pela GPU ou CPU (gargalo).<br/><br/>
**Importante:** Instale ao menos a versão 7.3.8 do RTSS para funcionamento correto, pois utiliza o novo dado "PC Latency" do PresentMon embutido no RTSS.
