FROM node:18

# Establecer el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copiar los archivos necesarios
COPY package.json ./
COPY . . 

# Instalar las dependencias
RUN npm install

# Exponer el puerto 4000 para conexiones TCP
EXPOSE 4000

# Comando para ejecutar el servidor TCP
CMD ["node", "server.js"]
