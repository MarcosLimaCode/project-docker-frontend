# Projeto Docker

## **- Para subir o projeto utilize o comando para criar a imagem:**

```javascript
docker build -t frontend .

```

## **- Construa o container com o comando:**

```javascript
docker run -d \
	--name frontend \
	-p 8080:80 \
frontend
```

---

## **Ou utilize o Docker compose com o comando:**

```javascript
docker compose up -d
```

---

## Comando via Docker Hub:

```javascript
docker push mrcoosv/project-docker-frontend:tagname

```

## Link do deploy na Vercel:

https://project-docker-frontend.vercel.app
