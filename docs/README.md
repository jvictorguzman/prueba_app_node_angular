#     Instalar y Habilitar Sequelize y Sequelize-CLI
- Para migraciones, modelos, seaders y conexion con BD

## 1. Instalar Sequelize
``` bash
npm install --save sequelize
```
## 2. Instalar Sequelize cli
```bash
npm install --save-dev sequelize-cli
```

### 3. Configurar .sequelizerc
```js
const path = require('path');

module.exports = {
  'config': path.resolve('src/config', 'database.json'),
  'models-path': path.resolve('src', 'models'),
  'seeders-path': path.resolve('src', 'seeders'),
  'migrations-path': path.resolve('src', 'migrations')
};

```

## 4. Iniciar un nuevo proyecto con sequelize-cli
```bash
npx sequelize-cli init
```

----------------------------
 ## Inicializar un nuevo repositorio local
 ```bash
 git init 
 ```

 ## Para ignorar archivos y o carpetas
```
- creamos un archivo (.gitignore) y registramos los achivos o carpetas
```
```
/node_modules
/dist
package-lock.json
.env
```
## Registrar el repositorio remoto GITHUB , GITLAB, GITBUCKET
 git remote add origin (direccion url)


