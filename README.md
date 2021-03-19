# Hackle App
SafeTech Hackle App

## Application Vulnerabilities
 1. Open redirect
 2. Cross-site request forgery
 3. Insecure direct object reference
 4. XSS
 5. SQL Injection (various types)
 6. Security misconfiguration 

## Docker-based deployment

### Build and run docker image
```
docker build -t hackle-app/hackle-app:latest .
docker run -d -p 8080:8080 hackle-app/hackle-app 
```

## Verifying deployment
```
curl -X GET 0.0.0.0:8080
```