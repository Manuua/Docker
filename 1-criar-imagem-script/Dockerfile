# Base da imagem Docker a ser utilizada
FROM python:3.9-alpine

# Copie arquivos ou pastas da origem para o caminho de destino no sistema de arquivos da imagem.
#copia da origem para o container/imagem

COPY . .

# Configura o contêiner para ser executado como um executável.
# agurmentos em formato string
# vou executar esse escript dentro da imagem
ENTRYPOINT ["python","script.py"]