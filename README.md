# 🚀Install project 
**mvn clean install**

###🚀 Ejecutar con el runner general "ManagementTest"
**mvn clean test**

### 🚀Lanzar por etiquetas

**mvn test "-Dkarate.options=--tags @debug"**


###🚀Lanzar por etiquetas y entornos

** mvn test "-Dkarate.options=--tags @debug" -DKarate.env="dev"**
