# Overlay Preview

Fiz 2 versões, uma utiliza dos sensores PresentMon embutidos no RTSS pra apresentar o PC Latency, Present Mode e estatísticas de Display Time que são ideais para Frame Gen, e o outro usa somente os sensores nativos do RTSS.

Arquivo .ovx usado para importar no OverlayEditor do RTSS, use a opção "Layouts", depois "Import" e selecione o arquivo .ovx

## Versão sem PresentMon: [Download](https://github.com/Warkratos/dlssinspector/raw/main/RTSS%20Overlay/renanmpv2.ovx)

<img width="363" height="169" alt="Captura de tela 2026-10-17 222748" src="https://github.com/user-attachments/assets/7f938211-a944-4810-943a-794a09acaa83" /><br/>
Nessa versão, as métricas de "FPS Average" e de "FPS 1% Low" aparecem somente no quando o modo benchmark é ativado.

## Versão com PresentMon: [Download](https://github.com/Warkratos/dlssinspector/raw/main/RTSS%20Overlay/renanmpv2PM.ovx)

<img width="359" height="222" alt="Captura de tela 2026-10-17 222701" src="https://github.com/user-attachments/assets/c2f76628-a0c4-4ad9-9b70-db8db12e9363" /><br/>
Nessa versão os frames são apresentados em Display Time, melhores para o uso de Frame Gen.<br/>
**Importante:** A versão PresentMon requer no mínimo a versão 7.3.8 Beta 1 para funcionamento correto, pois utiliza o novo sensor "PC Latency".
