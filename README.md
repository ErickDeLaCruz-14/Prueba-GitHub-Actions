# Prueba-GitHub-Actions
Probando GitHub Actions utilizando Node.js y jest para las pruebas

La estructura del proyecto:

sum.js: función simple

sum.test.js: prueba unitaria con Jest

package.json

.github/workflows/ci.yml: configuración del workflow



Practicas utilizadas:

Se añadió .gitignore para no subir node_modules

Se usó npx en lugar de jest directo para evitar errores de permisos

Aseguramos que el pipeline solo necesita: npm install y npx jest
