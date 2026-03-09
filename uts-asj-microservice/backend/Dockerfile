FROM node:18-slim

WORKDIR /app

# Copy manifest dan install library
COPY package.json .
RUN npm install

# Copy source code API
COPY . .

# Expose port sesuai soal [cite: 30]
EXPOSE 8080

CMD ["node", "index.js"]

