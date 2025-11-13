# Seleccionar la imagen base de Ubuntu
FROM ubuntu:latest

# Ejecutar actualizaciones e instalaciones
COPY script.sh /usr/local/bin/script.sh
RUN chmod +x /usr/local/bin/script.sh
RUN /usr/local/bin/script.sh

# Ejecutar comandos adicionales
RUN echo "Inicio de script" && \
    echo "Ejecutando comandos adicionales..."