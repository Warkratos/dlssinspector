# Global Driver Streamline DLLs Override

Essa ferramenta faz a substituição das DLLs do Frame Generation, Super Resolution, Ray Reconstruction e Streamline de forma global no sistema.


Roda de forma portátil, ou seja, não requer instalação, ela substitui as DLLs na pasta ProgramData\NVIDIA\NGX, fazendo o driver carregar elas nos jogos.

## Como usar

Baixe a última versão dessa ferramenta (nvidiaDlssGlom.exe) no repositório do desenvolvedor 
https://github.com/SimonMacer/AnWave/releases/tag/AnWave-DLSS


<img width="402" height="705" alt="image" src="https://github.com/user-attachments/assets/ea426fcc-072e-499e-8bea-888c240abbe7" />


Marque a caixa **"Enable NVIDIA Streamline Override Mode"**

A caixa **"Force Enable DLSS Override on All DLSS Titles"** força o DLSS Override em todos os jogos, com ela **MARCADA** todos os jogos terão suas DLLs substituidas pela última, com ela **DESMARCADA**, você controla quando substituir a DLL pelo Profile Inspector.

A caixa **"Show DLSS Indicator"** ativa o overlay do DLSS no jogo alterando o registro (o mesmo que faz o DLSS Overlay Toggle)

Minha recomendação é deixar igual ao da screenshot acima, apenas desmarcar o Show DLSS Indicator depois que confirmar que funcionou.

Existem **2 formas** de usar esse override, a primeira usa os próprios arquivos que estão sendo disponibilizados por OTA pela NVIDIA, e a outra é baixar manualmente que serve quando você quer usar outras versões que podem ser mais atuais que o OTA.

**Forma 1:** Só clicar em "Download from Server" e pronto, ele vai baixar tudo do OTA NVIDIA.

**Forma 2:** Baixe todos os arquivos do streamline e coloque na mesma pasta do executável do DLSSGlom, abra o programa e use o botão "Update"

**Para desfazer tudo e voltar ao normal, vá até a pasta ProgramData (Windows + R, %ProgramData%), encontre a pasta NVIDIA e apague a pasta NGX.**
