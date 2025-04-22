# Hackathon-FIAP Fase-5 IA-para-Devs
Hackathon desenvolvido como método de avaliação da fase 5 para pôs-graduação no curso de IA para devs na FIAP 2025

# Download do modelo treinado

[Acesse o drive para o download do .zip com o modelo](https://drive.google.com/drive/folders/1vNYolJaNf7JmS9cezAIX1bLyKb4TqG3-?usp=sharing)

## Detecção de Objetos Cortantes em Vídeos

Este projeto utiliza um modelo treinado (YOLOv5) para detectar objetos cortantes como facas, tesouras e similares em vídeos.

## O que você precisa fazer

1 Acesse o notebook no Google Colab.

2 Faça upload do vídeo que deseja analisar (o nome do arquivo deve estar como video.mp4).

3 Faça upload do arquivo model.zip contendo o modelo treinado.

4 Execute os códigos presentes na seção "Inclusão de dependencias" em seguida  execute os codigtos na seção "Implementação" do notebook.

5 Caso deseje realizar o envio de e-mails essa parte da função send_email deve ser descomentada e configurada com uma conta valida da Mailtrap:

#with smtplib.SMTP("sandbox.smtp.mailtrap.io", 2525) as smtp:
#smtp.starttls()
#smtp.login("9255552ad395dd", "5fcb1b5afa7664")
#smtp.send_message(msg)

O notebook irá descompactar o modelo, carregar os dados e processar o vídeo automaticamente, mostrando os resultados com as detecções marcadas.
