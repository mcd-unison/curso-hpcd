# Inicia seleccionando la imagen de base
FROM ubuntu

LABEL Julio Waissman <ajulio.waissman@unison.mx>

WORKDIR /root

RUN  apt-get -y update && \
     apt-get install -yq curl nano vim unzip git

COPY data-shell.zip data-shell.zip

RUN  unzip data-shell.zip && \
     rm data-shell.zip && \
     rm -rf __MACOSX

CMD ["bash"]