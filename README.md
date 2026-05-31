# Reportes-SIGEP-PYTHON-Dir-planificacion-GAMs
En este repositorio se encuentran programas en python para ejecutarse en google coolab, para facilitar la limpieza de reportes

Ejecutar "Limpieza_inf_presupuestos" sobre dos tipos de informes descargados en excel plano desde el sigep: 
(1) Reporte de ejecucion presupuestaria N°12 para cargar generar el diccionario de categorias
(2) Reporte de ejecucion presupuestaria N°1 para obtener el archivo sobre el que trabajar

Ejecutar "Informe_presupuestario"  cargando el archivo sobre el que trabajr y el diccionario de datos
Generarar diferentes pestañas en excel:
(1) PRINCIPAL
Entidad	TIPO	DA	UE	FTE	Org.	Cat. Prg.	Descripción Cat. Prg.	Objeto	Descripcion Objeto Del Gasto	Presupuesto Inicial	Mod. Aprobadas	Presup. Vig.	Preventivo	Compromiso	Devengado	Pagado	Saldo Por Pagar	Porcen.	Saldo Deveng.	Diferencia Vig-Prev

(2) INFORMES ORIGINALES

(3) TABLA FILTRADA
										
(4) INF.F.1
PERCENTILES BY CAT. PRG. (1-10-25-50-75-90-99)			
Cat. Prg.	Descripción Cat. Prg.	Diferencia_Vig_Prev	P

(5) INF.F.2
PERCENTILES BY OBJETO (1-10-25-50-75-90-99)					
Cat. Prg.	Descripción Cat. Prg.	Objeto	Descripcion Objeto Del Gasto	Diferencia_Vig_Prev	P

(6) SALDOS CAT
SALDOS POR TIPO Y CAT. PRG. (RESUMEN)					
TIPO	Cat. Prg.	Descripción Cat. Prg.	Presup. Vig.	Preventivo	Diferencia Vig-Prev

(7) SALDOS Obj
SALDOS POR TIPO, CAT. PRG. Y OBJETO (DETALLE)							
TIPO	Cat. Prg.	Descripción Cat. Prg.	Objeto	Descripcion Objeto Del Gasto	Presup. Vig.	Preventivo	Diferencia Vig-Prev

#FINALIDAD#
Al usar **SALDOS Obj** se obtendra partidas presupuestaria por objeto de gasto que pueden ser modificadas en la reformulaciones de los POAs dentro cada municipio, siguiendo los filtros de:
1. Org financiadora
2. Gastos recurrentes: 
3. Gastos asignados por ley, eliminando las plabras clave:  'NIÑO' , 'NIÑEZ' , 'VIOLENCIA' , 'ZOONOSIS' , 'SEDES' , 'VIH' , 'CONTROL' , 'TRATA' , 'FELCV' , 'CAMBIO CL' , 'DRAGADO' , 'DESASTRE' , 'DISCAPACIDAD' , 'Dignidad' , 'ADULTO'

   
