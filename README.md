# SonarQube Docker Compose Setup

Este repositorio contiene configuraciones de Docker Compose para levantar instancias de SonarQube en dos versiones diferentes: la **Community Edition** y la **LTS Community Edition**.

## Estructura del Repositorio

- **community/**
  - Contiene el `docker-compose.yml` para levantar una instancia de SonarQube Community Edition.
  
- **lts-community/**
  - Contiene el `docker-compose.yml` para levantar una instancia de SonarQube LTS (Long Term Support) Community Edition.

## Requisitos

- Docker
- Docker Compose

## Instrucciones


1. **Clona este Repositorio:**

   ```bash
   git clone https://github.com/NicoDQ/sonarqube-docker.git
   cd sonarqube-docker
  
2. **Levanta la Instancia Deseada:**


- ****Para la Community Edition:****

   ```bash
   cd community
   docker-compose up -d 

- ****Para la LTS Community Edition:****

   ```bash
   cd lts-community
   docker-compose up -d

3. **Accede a SonarQube:**

Abre tu navegador y ve a http://localhost:9000.
Las credenciales por defecto son:

    Usuario: admin
    Contraseña: admin

## Notas

    Asegúrate de que el puerto 9000 no esté siendo utilizado por otro servicio.
    Puedes modificar los archivos docker-compose.yml según tus necesidades.

## Recursos

[Documentación oficial de SonarQube](https://docs.sonarsource.com/sonarqube/latest/)

[Documentación Oficial de SonarQube - Docker](https://docs.sonarsource.com/sonarqube/latest/setup-and-upgrade/install-the-server/installing-sonarqube-from-docker/)
