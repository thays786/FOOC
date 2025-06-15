# Usa una imagen base oficial de OpenJDK
FROM openjdk:8-jdk-alpine

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia el archivo JAR al contenedor
COPY backend-0.0.1-SNAPSHOT.jar app.jar

# Expone el puerto que usa la aplicación (ajústalo si es necesario)
EXPOSE 8081

# Ejecuta la aplicación
ENTRYPOINT ["java", "-jar", "app.jar"]
