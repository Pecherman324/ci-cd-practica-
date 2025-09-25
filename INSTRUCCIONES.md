# Instrucciones para completar la Práctica CI/CD

## ✅ **COMPLETADO LOCALMENTE:**

1. ✅ Estructura del proyecto creada
2. ✅ Aplicación Node.js con Express
3. ✅ Pipeline CI/CD configurado
4. ✅ Dockerfile y docker-compose.yml
5. ✅ Repositorio Git inicializado
6. ✅ Pruebas locales ejecutadas

## 📋 **PASOS RESTANTES:**

### 1. Crear repositorio en GitHub
1. Ve a https://github.com
2. Haz clic en "New repository"
3. Nombra el repositorio: `ci-cd-practica`
4. Marca "Add a README file"
5. Haz clic en "Create repository"

### 2. Conectar repositorio local con GitHub
```bash
git remote add origin https://github.com/TU_USUARIO/ci-cd-practica.git
git push -u origin main
```

### 3. Verificar pipeline en GitHub Actions
1. Ve a tu repositorio en GitHub
2. Haz clic en la pestaña "Actions"
3. Verifica que el workflow se ejecute correctamente

### 4. Probar rollback (simular error)
1. Edita `app/index.js` y borra una llave `}`
2. Haz commit y push
3. Verifica que el pipeline falle
4. Repara el error y vuelve a hacer push

### 5. Capturar evidencias
Guarda capturas de pantalla en la carpeta `evidencias/`:
- Pipeline ejecutándose exitosamente
- Pipeline fallando (rollback)
- Pipeline reparado

## 🎯 **ENTREGABLES FINALES:**
1. Repositorio en GitHub con código fuente
2. Pipeline CI/CD funcionando
3. Evidencias en carpeta `evidencias/`
4. Informe técnico en PDF

## 🚀 **COMANDOS ÚTILES:**
```bash
# Probar localmente
cd app
npm install
npm start

# Probar con Docker (requiere Docker Desktop)
docker-compose up --build

# Verificar estado Git
git status
git log --oneline
```
