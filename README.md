# Nombre del Proyecto

Breve descripción de qué hace el proyecto y para quién está pensado.

## Características

- Característica 1
- Característica 2
- Característica 3

## Requisitos

- [Node.js](https://nodejs.org/) >= 18.x
- npm >= 9.x (o pnpm / yarn)

## Instalación

```bash
# Clonar el repositorio
git clone https://github.com/usuario/nombre-del-proyecto.git
cd nombre-del-proyecto

# Instalar dependencias
npm install
```

## Variables de entorno

Copia el archivo de ejemplo y ajusta los valores:

```bash
cp .env.example .env
```

| Variable   | Descripción              | Ejemplo        |
| ---------- | ------------------------ | -------------- |
| `PORT`     | Puerto del servidor      | `3000`         |
| `NODE_ENV` | Entorno de ejecución     | `development`  |

## Uso

```bash
# Desarrollo (con recarga automática, si aplica)
npm run dev

# Producción
npm start
```

## Scripts disponibles

| Script          | Descripción                         |
| --------------- | ----------------------------------- |
| `npm start`     | Inicia la aplicación                |
| `npm run dev`   | Inicia en modo desarrollo           |
| `npm test`      | Ejecuta las pruebas                 |
| `npm run lint`  | Revisa el estilo del código         |
| `npm run build` | Compila / prepara para producción   |

## Estructura del proyecto

```text
.
├── src/
│   ├── index.js          # Punto de entrada
│   ├── routes/           # Rutas / controladores
│   ├── services/         # Lógica de negocio
│   └── utils/            # Utilidades
├── tests/                # Pruebas
├── .env.example          # Variables de entorno de ejemplo
├── package.json
└── README.md
```

## API (opcional)

Documenta aquí los endpoints principales si el proyecto es una API.

### `GET /`

| Campo    | Valor                |
| -------- | -------------------- |
| Método   | `GET`                |
| Ruta     | `/`                  |
| Respuesta| `{ "status": "ok" }` |

## Pruebas

```bash
npm test
```

## Contribución

1. Haz un fork del proyecto
2. Crea una rama: `git checkout -b feature/mi-cambio`
3. Confirma los cambios: `git commit -m "Describe el cambio"`
4. Sube la rama: `git push origin feature/mi-cambio`
5. Abre un Pull Request

## Licencia

Este proyecto está bajo la licencia MIT. Ver el archivo `LICENSE` para más detalles.

## Autor

- Nombre — [GitHub](https://github.com/usuario)
