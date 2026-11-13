# Comprobación pública del portal

Este repositorio contiene una prueba de disponibilidad de https://ucsg-calidad.onrender.com.

GitHub Actions consulta la comprobación de salud y verifica que se muestre el formulario de ingreso. El horario configurado es cada cinco minutos. Las ejecuciones y sus tiempos pueden consultarse en la pestaña Actions.

El monitor se ejecuta en runners estándar de un repositorio público. Su ejecución está incluida gratuitamente en GitHub Actions para este tipo de repositorio. La aplicación institucional, sus documentos y sus credenciales se administran en su repositorio privado y en los servicios correspondientes.

Las comprobaciones periódicas generan tráfico de entrada al portal. GitHub puede retrasar u omitir ejecuciones programadas y Render puede reiniciar servicios gratuitos. La comprobación registra el estado observado.

Fuentes de operación y costes disponibles en la [documentación de GitHub Actions](https://docs.github.com/en/actions/concepts/billing-and-usage) y en las [condiciones de Render Free](https://render.com/docs/free).
