FROM nginx:latest
RUN apt-get update && \
    apt-get install -y git
RUN git clone https://${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}@github.com/Irnyni/Gerenciador-de-atividades.git /usr/share/nginx/html/novapasta
COPY nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
