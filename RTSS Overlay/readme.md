# Overlay Preview

Fiz 2 versões, uma utiliza dos dados PresentMon embutidos no RTSS pra apresentar o PC Latency, Present Mode e estatísticas de Frametime em Display Time que são ideais para Frame Gen, e o outro usa somente os dados nativos do RTSS.

Arquivo .ovl pra colocar na pasta "..\RivaTuner Statistics Server\Plugins\Client\Overlays"

## Versão sem dados do PresentMon: [Download](https://github.com/Warkratos/dlssinspector/raw/main/RTSS%20Overlay/renanmpv4.ovl)

<img width="334" height="167" alt="image" src="https://github.com/user-attachments/assets/4aef9b3b-6e62-402e-a05a-51c8b7967326" /><br/>
Nessa versão, as métricas de "FPS Average", "FPS 1% Low" e "FPS 0.1% Low" aparecem somente no quando o modo benchmark é ativado.

## Versão com dados do PresentMon: [Download](https://github.com/Warkratos/dlssinspector/raw/main/RTSS%20Overlay/renanmpv4PresentMon.ovl)

<img width="330" height="328" alt="image" src="https://github.com/user-attachments/assets/d77f2450-f67f-4e12-9172-60ff6ceb31ca" /><br/>
Funcionalidades dessa versão: 
- Mostra o frametime em "msBetweenPresent" e "msBetweenDisplayChange", a versão Present mostra o cálculo em tempo real e informa se está em "Start-to-Start" ou "Present-to-Present", para alterar o modo pressiona a tecla 'F', precisa do "HotkeyHandler.dll" ativo nos plugins do RTSS.
- Mostra o tipo de presentation model utilizado pelo jogo atualmente, veja mais sobre os modelos de apresentação e porque é recomendado ficar no "Independent Flip" [clicando aqui](https://github.com/Warkratos/dlssinspector/blob/main/Dicas/presentationmodel.md)
- Mostra se está sendo limitado pela GPU ou CPU (gargalo).<br/><br/>
**Importante:** Instale ao menos a versão 7.3.8 do RTSS para funcionamento correto, pois utiliza o novo dado "PC Latency" do PresentMon embutido no RTSS.
