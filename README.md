# SAP ABAP FI Document Management

## Description
Complete ABAP solution for managing financial documents in SAP, including manual creation, consultation, printing, and process automation.

## Project Components

- **ZFIP_FB01 (Module Pool)**  
  Transaction for manually creating financial documents, including data validations and business logic.  
  Folder: `/1_src/ZFIP_FB01`

- **ZFIR_BUSCAR_DOC (ALV Report)**  
  Selection screen report to consult created documents and display them in an ALV grid.  
  Folder: `/1_src/ZFIR_BUSCAR_DOC`

- **SmartForms**  
  Forms for printing documents from the ALV.  
  Folders:  
  - `/2_smartforms/ZFISF_DOC_KR_KZ`  
  - `/2_smartforms/ZFISF_DOC_SA`

- **ZFIP_FB01_AUTOM (Batch Input)**  
  Automation process to simulate mass posting of financial documents.  
  Folder: `/1_src/ZFIP_FB01_AUTOM`

## Technologies
- ABAP  
- Module Pool  
- ALV  
- SmartForms  
- Batch Input  

## Functional Scenario
1. Manually create financial documents.  
2. Consult generated documents via ALV.  
3. Print documents using SmartForms.  
4. Automate mass document postings.

## Screenshots
"!!!

## Author
Fiorella Petrillo

------------------------------------------

# Gestión de Documentos Financieros en ABAP

## Descripción
Solución completa en ABAP para la gestión de documentos financieros en SAP, incluyendo carga manual, consulta, impresión y automatización de procesos.

## Componentes del proyecto

- **ZFIP_FB01 (Module Pool)**  
  Transacción para la carga manual de documentos financieros, con validaciones de datos y lógica de negocio.  
  Archivo: `/src/ZFIP_FB01.abap`

- **ZFIR_BUSCAR_DOC (Reporte ALV)**  
  Reporte con pantalla de selección para consultar documentos y visualizarlos en un ALV.  
  Archivo: `/src/ZFIR_BUSCAR_DOC.abap`

- **SmartForms**  
  Formularios para imprimir los documentos desde el ALV.  
  Archivos:  
  - `/smartforms/ZFISF_DOC_KR_KZ.abap`  
  - `/smartforms/ZFISF_DOC_SA.abap`

- **ZFIP_FB01_AUTOM (Batch Input)**  
  Proceso de automatización para la carga masiva de documentos.  
  Archivo: `/src/ZFIP_FB01_AUTOM.abap`

## Tecnologías
- ABAP  
- Module Pool  
- ALV  
- SmartForms  
- Batch Input  

## Escenario funcional
1. Crear documentos manualmente.  
2. Consultar documentos generados mediante ALV.  
3. Imprimir documentos con SmartForms.  
4. Automatizar cargas masivas de documentos.

## Capturas
"!!!

## Autor
Fiorella Petrillo
