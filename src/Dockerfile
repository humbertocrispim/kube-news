# Use a base image do Nginx
FROM nginx:latest

# Copie o arquivo de configuração personalizado para o diretório de configuração do Nginx
#COPY nginx.conf /etc/nginx/nginx.conf

# Exponha a porta 80 para acesso externo
EXPOSE 80

# Comando para iniciar o servidor Nginx quando o contêiner for iniciado
CMD ["nginx", "-g", "daemon off;"]
