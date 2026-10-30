# Guia de contribucion
 
Gracias por querer mejorar **Gestor de Tareas**. Esta guia explica como
reportar errores, proponer mejoras y enviar cambios.
 
## Reportar un error
 
1. Revisa en la pestana **Issues** que el error no este reportado.
2. Abre un issue nuevo con el titulo `Error: descripcion corta`.
3. Incluye:
   - Que hiciste (pasos para reproducirlo).
   - Que esperabas que pasara.
   - Que paso en realidad.
   - Navegador y sistema operativo.
 
## Proponer una mejora
 
Abre un issue con el titulo `Mejora: descripcion corta` y explica que
problema resuelve y como imaginas la solucion.
 
## Enviar cambios
 
```bash
git checkout -b mejora/nombre-del-cambio
git add .
git commit -m "Agrega filtro por fecha"
git push origin mejora/nombre-del-cambio
```
 
Despues abre un **Pull Request** hacia la rama `main`.
 
## Convenciones
 
| Elemento | Regla | Ejemplo |
|:---------|:------|:--------|
| Ramas | `tipo/descripcion` | `mejora/modo-oscuro` |
| Commits | Verbo en presente | `Corrige el filtro de tareas` |
| Codigo | camelCase en JavaScript | `agregarTarea()` |
 
## Antes de enviar tu Pull Request
 
- [ ] El proyecto funciona al abrir `index.html`.
- [ ] No hay errores en la consola del navegador.
- [ ] Actualizaste el README si agregaste una funcion.
- [ ] Los mensajes de commit explican el cambio.
