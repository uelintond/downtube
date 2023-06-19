# DownTube - Baixador de Vídeos do YouTube

DownTube é uma ferramenta simples e eficaz que permite baixar vídeos do YouTube. Os usuários podem escolher baixar o vídeo nos formatos mp3, mp4 ou mkv.

## Requisitos

Para usar o DownTube, você precisa ter Python instalado em seu computador. As bibliotecas Python necessárias são listadas no arquivo `requirements.txt`.

## Como instalar

1. Clone o repositório ou faça o download do código fonte.
2. Instale as bibliotecas necessárias usando pip:
   ```
   pip install -r requirements.txt
   ```
3. Execute o script `downTube.py`.

## Como usar

Ao executar o DownTube, você será solicitado a inserir a URL do vídeo do YouTube que deseja baixar. Em seguida, escolha o formato de saída (mp3, mp4 ou mkv). O DownTube fará o download do vídeo e o converterá para o formato escolhido.

## Compilando para .exe

Se você deseja compilar o script Python para um arquivo .exe, pode fazer isso usando PyInstaller.

1. Primeiro, instale PyInstaller usando pip:
   ```
   pip install pyinstaller
   ```
2. Navegue até o diretório do projeto e execute o seguinte comando:
   ```
   pyinstaller --onefile --windowed downTube.py
   ```
3. Após a conclusão do comando, você encontrará o arquivo .exe no diretório `dist` que foi criado.

## Contribuindo

Contribuições são bem-vindas! Por favor, leia as diretrizes de contribuição antes de enviar um pull request.

PIX: uelintond25@gmail.com
Deixe uma estrelinha! Hehe

## Licença

Este projeto está licenciado sob a licença MIT. Consulte o arquivo `LICENSE` para mais detalhes.
