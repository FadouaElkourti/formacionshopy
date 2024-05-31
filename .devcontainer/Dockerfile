# Usar una imagen base de Node.js
FROM node:18.16.0

# Actualizar e instalar dependencias
RUN apt-get update && apt-get upgrade -y && \
    apt-get install -y curl gcc g++ make ruby-full ruby-dev git xdg-utils

# Instalar Bundler
RUN gem install bundler

# Instalar Shopify CLI
RUN npm install -g @shopify/cli
