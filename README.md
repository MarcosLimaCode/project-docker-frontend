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
