# Resumen
API Total: 27 / 84

# Avances en los endpoints

- API Contribuyentes
	- Consultas públicas
		- GET
			- Situación Tributaria de un Contribuyente ✅✅
			- Verificación de Cédula RUT 🚧🚧⌚ (se necesita un RUT y serie de una empresa para probar)
		- Actividades Económicas ✅✅
	- Consultas MiSii
		- POST
			- Datos del contribuyente ✅✅
- API SII
	- GET
		- Unidad de fomento (UF) ❌
		- Corrección monetaria ❌
		- Impuesto de segunda categoría ❌
- API DTE
	- Código de Asignación de Folios (CAF)
		- POST
			- Solicitar CAF 🚧
			- Descargar XML 🚧
			- Consultar Estado de un Folio 🚧
			- Anulación de Folios 🚧
			- Listado de Folios Solicitados 🚧
			- Listado de Folios por Estado 🚧
	- Contribuyentes
		- POST
			- Listado Contribuyentes Autorizados ❌
		- GET
			- Estado Autorización de un Contribuyente ❌
		- POST
			- Estado Autorización de un Contribuyente (incluye email) ❌
			- Datos Privados de un Contribuyente ❌
			- Asignar Datos Privados de un Contribuyente ❌
			- Usuarios Autorizados de un Contribuyente ❌
			- Asignar Usuarios Autorizados a un Contribuyente ❌
	- Documentos Emitidos
		- POST
			- Estado de un envío de XML al SII 🚧
			- Verificación Avanzada de un Documento en SII 🚧
	- Información Electrónica de Compras y Ventas
		- POST
			- Obtener Código de Reemplazo de Libro ❌
- API RCV
	- Registro de Compras
		- POST
			- Resumen de Compras ✅✅
			- Detalle de Compras ✅✅
			- Asignación Tipo de Transacción de una Compra 🚧🚧
	- Registro de Ventas
		- POST
			- Resumen de Ventas ✅✅
			- Detalle de Ventas ✅✅
			- Asignación de Resumen de Ventas por Documento 🚧🚧
- API RTC
	- POST
		- Obtener Certificado de Cesión Electrónica ❌
		- Estado de Envío de Cesión Electrónica ❌
		- Estado de Cesión de un DTE ❌
		- Listado de Cesiones ❌
- API BHE
	- Boletas de Honorarios Emitidas
		- POST
			- Listado de Boletas de Honorarios Emitidas ✅✅
			- Emitir Boleta de Honorarios 🚧🚧🚀
			- Descargar PDF Boleta de Honorarios Emitida ✅✅
			- Enviar Email con la Boleta de Honorarios Emitida ✅✅
			- Anular Boleta de Honorarios Emitida 🚧🚧🚀
	- Boletas de Honorarios Recibidas
		- POST
			- Listado de Boletas de Honorarios Recibidas ✅
			- Descargar PDF Boleta de Honorarios Recibida ✅
			- Observar Boleta de Honorarios Recibida 🚧🚧🚀
- API BTE
	- Boletas de Terceros Emitidas
		- POST
			- Resumen Mensual y Anual de Boletas de Terceros Emitidas ✅✅
			- Listado de Boletas de Terceros Emitidas ✅✅
			- Emitir Boleta de Terceros ✅✅
			- Descargar HTML Boleta de Terceros ✅✅
			- Anular Boleta de Terceros Emitida ✅✅
			- Buscar datos Boleta de Terceros ✅✅
			- Obtener la tasa del receptor de una BTE ✅✅
	- Boletas de Terceros Recibidas
		- POST
			- Listado de Boletas de Terceros Recibidas ✅✅
			- Descargar HTML Boleta de Terceros Recibida ✅✅
- API Vehículos
	- POST
		- Buscar Tasación Vehicular ❌
	- GET
		- Tipos de Vehículos según Categoría ❌
		- Marcas de Vehículos según Categoría ❌
		- Características de Vehículos según Categoría ❌
- API Software MIPYME SII
	- Contribuyentes
		- POST
			- Información Pública de un Contribuyente ✅✅
	- Documentos Borradores
		- POST
			- Listado de Documentos Borradores 🚧
			- Emitir Documento Borrador 🚧
			- Eliminar Documento Borrador 🚧
			- Descargar PDF de un Documento Borrador 🚧
	- Documentos Emitidos
		- POST
			- Listado de Documentos Emitidos ✅✅
			- Descargar PDF de un DTE Emitido ✅✅
			- Descargar XML de un DTE emitido 🚧🚀🚀
	- Documentos Recibidos
		- POST
			- Listado de Documentos Recibidos ✅✅
			- Descargar PDF de un DTE Recibido ✅✅
			- Descargar XML de un DTE Recibido ✅✅
- API Certificación DTE
	- Contribuyentes
		- POST
			- Datos del contribuyente 🚧
	- Certificación de Facturas y otros documentos
		- POST
			- Postulación a Software de Mercado 🚧
			- Solicitar Set de Pruebas 🚧
	- Certificación de Boletas
		- POST
			- Solicitar Set de Pruebas de Boletas 🚧
- API Facturación
	- Documentos Tributarios
		- POST
			- Generar XML de un DTE 🚧
			- Generar PDF a partir del XML del DTE 🚧
			- Generar ESCPOS a partir del XML del DTE 🚧
			- Normalizar DTE al formato estándar del SII 🚧
			- Generar XML de RVD de Boletas (ex RCOF) 🚧
			- Generar XML de Cesión de DTE (AEC) 🚧
	- Envíos al SII
		- POST
			- Enviar XML al SII 🚧
			- Consultar Envio de XML al SII 🚧
	- Intercambios de DTE
		- POST
			- Registrar Respuesta de Intercambio de DTE en el SII 🚧
			- Fecha de Recepción de un DTE en el SII 🚧
			- Historial de Eventos de un DTE 🚧
			- Información para Cesión de un DTE 🚧
	- Back Office
		- GET
			- Información del Usuario ❌
		- POST
			- Notificar pago ❌
		- GET
			- Tasks Beat ❌
