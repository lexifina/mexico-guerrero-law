# Guerrero: law history in git

The law of the State of Guerrero (Estado Libre y Soberano de Guerrero, Mexico) as a git history: one file per article, one commit per publication that changed it, dated the day it took effect, with the decree as the commit's author. `git blame` names the decree behind every paragraph; `git log` lists every change to an article; checking out a date gives the text in force that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `mx-gro/`. Mexico's federal law is in [lexifina/mexico-law](https://github.com/lexifina/mexico-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

156 ordenamientos with 711 versions so far: the constitution first, then the codes and laws in force, added in parts. Regulations, decrees and repealed laws are not included yet.

| Folder | Ordenamiento | Versions | History |
| --- | --- | ---: | --- |
| `constitucion-politica/` | CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE GUERRERO -ANTES CONSTITUCION POLITICA DEL ESTADO LIBRE Y SOBERANO DE GUERRERO QUE DEROGA LA DE 29 DE NOVIEMBRE DE 1880- | 166 | as first published, then each reform: 3 November 1917 to 22 April 2026 |
| `codigo-civil/` | CODIGO CIVIL DEL ESTADO LIBRE Y SOBERANO DE GUERRERO NUMERO 358 | 33 | as first published, then each reform: 2 September 1993 to 8 April 2026 |
| `codigo-de-procedimientos-de-justicia-administrativa/` | CODIGO DE PROCEDIMIENTOS DE JUSTICIA ADMINISTRATIVA DEL ESTADO DE GUERRERO, NUMERO 763 | 1 | as first published: 15 August 2018 |
| `codigo-fiscal/` | CODIGO FISCAL DEL ESTADO DE GUERRERO NUMERO 420 | 4 | as first published, then each reform: 27 December 2022 to 1 January 2026 |
| `codigo-fiscal-municipal-numero-152/` | CODIGO FISCAL MUNICIPAL NUMERO 152 | 10 | as first published, then each reform: 30 December 1987 to 29 December 2009 |
| `codigo-penal/` | CODIGO PENAL PARA EL ESTADO LIBRE Y SOBERANO DE GUERRERO, NUMERO 499 | 54 | as first published, then each reform: 29 November 2014 to 23 May 2026 |
| `codigo-procesal-civil/` | CODIGO PROCESAL CIVIL DEL ESTADO LIBRE Y SOBERANO DE GUERRERO NUMERO 364 | 14 | as first published, then each reform: 26 September 1993 to 31 December 2022 |
| `ley-701-de-reconocimiento-derechos-y-cultura-de-los-pueblos/` | LEY 701 DE RECONOCIMIENTO, DERECHOS Y CULTURA DE LOS PUEBLOS Y COMUNIDADES INDIGENAS Y AFROMEXICANAS, DEL ESTADO DE GUERRERO --ANTES -- LEY NUMERO 701 DE RECONOCIMIENTO, DERECHOS Y CULTURA DE LOS PUEBLOS INDIGENAS Y COMUNIDADES AFROMEXICANAS -- ANTES -- LEY NUMERO 701 DE RECONOCIMIENTO, DERECHOS Y CULTURA DE LOS PUEBLOS Y COMUNIDADES INDIGENAS DEL ESTADO DE GUERRERO | 4 | as first published, then each reform: 9 April 2011 to 5 July 2022 |
| `ley-arancelaria-para-el-cobro-de-honorarios-de-los-abogados/` | LEY ARANCELARIA PARA EL COBRO DE HONORARIOS DE LOS ABOGADOS, DEPOSITARIOS, INTERPRETES, TRADUCTORES, PERITOS VALUADORES Y ARBITROS, NUMERO 47 | 1 | as first published: 21 June 1956 |
| `ley-de-abastecimiento-de-agua-potable-drenajes-y-pavimentaci/` | LEY DE ABASTECIMIENTO DE AGUA POTABLE DRENAJES Y PAVIMENTACION, DEL ESTADO DE GUERRERO NUMERO 50 | 1 | as first published: 1 June 1932 |
| `ley-de-aguas/` | LEY DE AGUAS PARA EL ESTADO LIBRE Y SOBERANO DE GUERRERO NUMERO 574 | 5 | as first published, then each reform: 4 January 2003 to 6 October 2021 |
| `ley-de-asociaciones-de-productores-agricolas/` | LEY DE ASOCIACIONES DE PRODUCTORES AGRICOLAS DEL ESTADO DE GUERRERO NUMERO 15 | 1 | as first published: 14 September 1960 |
| `ley-de-divorcio/` | LEY DE DIVORCIO DEL ESTADO DE GUERRERO | 6 | as first published, then each reform: 23 March 1990 to 12 April 2017 |
| `ley-de-fomento-economico-inversion-y-desarrollo/` | LEY DE FOMENTO ECONOMICO, INVERSION Y DESARROLLO DEL ESTADO DE GUERRERO NUMERO 487 | 6 | as first published, then each reform: 22 June 2002 to 27 May 2026 |
| `ley-de-justicia-en-materia-de-faltas-de-policia-y-buen-gobie/` | LEY DE JUSTICIA EN MATERIA DE FALTAS DE POLICIA Y BUEN GOBIERNO DEL ESTADO | 2 | as first published, then each reform: 28 February 1988 to 4 December 2010 |
| `ley-de-la-caja-de-prevision-de-los-agentes-del-ministerio-pu/` | LEY DE LA CAJA DE PREVISION DE LOS AGENTES DEL MINISTERIO PUBLICO, PERITOS, AGENTES DE LA POLICIA JUDICIAL, AGENTES DE LA POLICIA PREVENTIVA, CUSTODIOS Y DEFENSORES DE OFICIO DEL ESTADO DE GUERRERO | 2 | as first published, then each reform: 6 March 1989 to 29 November 1989 |
| `ley-de-obras-publicas-y-sus-servicios/` | LEY DE OBRAS PUBLICAS Y SUS SERVICIOS DEL ESTADO DE GUERRERO NUMERO 266 | 2 | as first published, then each reform: 1 January 2005 to 5 November 2016 |
| `ley-de-premios-civiles/` | LEY DE PREMIOS CIVILES DEL ESTADO DE GUERRERO NUMERO 434 | 3 | as first published, then each reform: 13 October 1999 to 25 October 2025 |
| `ley-de-premios-nacionales-guerrero/` | LEY DE PREMIOS NACIONALES GUERRERO | 2 | as first published, then each reform: 12 July 1989 to 22 April 1992 |
| `ley-de-prevencion-y-atencion-de-la-violencia-familiar/` | LEY DE PREVENCION Y ATENCION DE LA VIOLENCIA FAMILIAR DEL ESTADO DE GUERRERO NUMERO 280-- ANTES -- LEY DE ASISTENCIA Y PREVENCION DE LA VIOLENCIA INTRAFAMILIAR DEL ESTADO DE GUERRERO, NUM. 280 | 5 | as first published, then each reform: 14 April 1999 to 15 December 2023 |
| `ley-de-proteccion-y-fomento-a-las-artesanias/` | LEY DE PROTECCION Y FOMENTO A LAS ARTESANIAS DEL ESTADO DE GUERRERO | 4 | as first published, then each reform: 5 July 1989 to 15 May 2024 |
| `ley-de-reestructuracion-del-sector-educativo/` | LEY DE REESTRUCTURACION DEL SECTOR EDUCATIVO DEL ESTADO DE GUERRERO NUM. 243 | 4 | as first published, then each reform: 17 February 1996 to 15 March 2014 |
| `ley-de-regulacion-y-fomento-de-mercados-y-tianguis-populares/` | LEY DE REGULACION Y FOMENTO DE MERCADOS Y TIANGUIS POPULARES | 1 | as first published: 1 July 1989 |
| `ley-de-regulacion-y-fomento-del-sistema-de-tiempo-compartido/` | LEY DE REGULACION Y FOMENTO DEL SISTEMA DE TIEMPO COMPARTIDO DEL ESTADO DE GUERRERO | 6 | as first published, then each reform: 2 January 1990 to 31 December 2008 |
| `ley-de-trabajo-de-los-servidores-publicos/` | LEY DE TRABAJO DE LOS SERVIDORES PUBLICOS DEL ESTADO DE GUERRERO NUMERO 248 | 16 | as first published, then each reform: 6 January 1989 to 8 April 2026 |
| `ley-de-transporte-y-vialidad/` | LEY DE TRANSPORTE Y VIALIDAD DEL ESTADO DE GUERRERO | 11 | as first published, then each reform: 16 June 1989 to 1 January 2026 |
| `ley-de-vivienda-social/` | LEY DE VIVIENDA SOCIAL DEL ESTADO DE GUERRERO NUMERO 573 | 2 | as first published, then each reform: 15 December 2004 to 8 February 2023 |
| `ley-estatal-de-bibliotecas-numero-565/` | LEY ESTATAL DE BIBLIOTECAS NUMERO 565 | 1 | as first published: 22 January 2005 |
| `ley-no-685-de-conservacion-y-vigilancia/` | LEY NO. 685 DE CONSERVACION Y VIGILANCIA DE LA CIUDAD DE TAXCO DE ALARCON GUERRERO | 1 | as first published: 7 March 2015 |
| `ley-no-845-de-cambio-climatico/` | LEY NO. 845 DE CAMBIO CLIMATICO DEL ESTADO DE GUERRERO | 1 | as first published: 22 August 2015 |
| `ley-no-861-para-la-administracion-de-bienes-asegurados-decom/` | LEY NO. 861 PARA LA ADMINISTRACION DE BIENES ASEGURADOS, DECOMISADOS O ABANDONADOS DEL ESTADO DE GUERRERO | 1 | as first published: 29 August 2015 |
| `ley-num-101-para-la-proteccion-de-los-no-fumadores/` | LEY NUM. 101 PARA LA PROTECCION DE LOS NO FUMADORES DEL ESTADO DE GUERRERO | 1 | as first published: 1 February 2004 |
| `ley-num-463-para-el-bienestar-integral-de-los-periodistas/` | LEY NUM. 463 PARA EL BIENESTAR INTEGRAL DE LOS PERIODISTAS DEL ESTADO DE GUERRERO | 1 | as first published: 18 May 2002 |
| `ley-numero-026-para-el-bienestar/` | LEY NUMERO 026 PARA EL BIENESTAR DEL ESTADO DE GUERRERO | 1 | as first published: 15 January 2025 |
| `ley-numero-076-de-ciencia-tecnologia-e-innovacion/` | LEY NUMERO 076 DE CIENCIA, TECNOLOGIA E INNOVACION DEL ESTADO DE GUERRERO | 3 | as first published, then each reform: 4 April 2009 to 13 May 2026 |
| `ley-numero-1173-de-voluntad-anticipada/` | LEY NUMERO 1173 DE VOLUNTAD ANTICIPADA PARA EL ESTADO DE GUERRERO | 1 | as first published: 18 September 2012 |
| `ley-numero-1212-de-salud/` | LEY NUMERO 1212 DE SALUD DEL ESTADO DE GUERRERO | 21 | as first published, then each reform: 5 December 2012 to 8 July 2026 |
| `ley-numero-1256-para-la-promocion-de-la-convivencia-libre-de/` | LEY NUMERO 1256 PARA LA PROMOCION DE LA CONVIVENCIA LIBRE DE VIOLENCIA EN EL ENTORNO ESCOLAR DEL ESTADO DE GUERRERO | 2 | as first published, then each reform: 12 January 2013 to 12 March 2024 |
| `ley-numero-175-del-centro-de-conciliacion-laboral/` | LEY NUMERO 175 DEL CENTRO DE CONCILIACION LABORAL DEL ESTADO DE GUERRERO | 1 | as first published: 20 April 2022 |
| `ley-numero-179-del-sistema-de-seguridad-publica/` | LEY NUMERO 179 DEL SISTEMA DE SEGURIDAD PUBLICA DEL ESTADO LIBRE Y SOBERANO DE GUERRERO | 5 | as first published, then each reform: 14 April 2022 to 31 December 2025 |
| `ley-numero-18-de-remuneraciones-de-los-servidores-publicos/` | LEY NUMERO 18 DE REMUNERACIONES DE LOS SERVIDORES PUBLICOS DEL ESTADO DE GUERRERO | 3 | as first published, then each reform: 1 January 2019 to 8 April 2026 |
| `ley-numero-207-de-transparencia-y-acceso-a-la-informacion-pu/` | LEY NUMERO 207 DE TRANSPARENCIA Y ACCESO A LA INFORMACION PUBLICA DEL ESTADO DE GUERRERO | 5 | as first published, then each reform: 7 May 2016 to 13 March 2024 |
| `ley-numero-213-de-entrega-recepcion-de-las-administraciones/` | LEY NUMERO 213 DE ENTREGA RECEPCION DE LAS ADMINISTRACIONES PUBLICAS DEL ESTADO Y MUNICIPIOS DE GUERRERO | 1 | as first published: 20 July 2016 |
| `ley-numero-214-para-prevenir-combatir-y-eliminar-la-discrimi/` | LEY NUMERO 214 PARA PREVENIR, COMBATIR Y ELIMINAR LA DISCRIMINACION EN EL ESTADO DE GUERRERO | 5 | as first published, then each reform: 20 July 2016 to 8 July 2026 |
| `ley-numero-230-de-adquisiciones-enajenaciones-arrendamientos/` | LEY NUMERO 230 DE ADQUISICIONES, ENAJENACIONES, ARRENDAMIENTOS, PRESTACION DE SERVICIOS Y ADMINISTRACION DE BIENES MUEBLES E INMUEBLES DEL ESTADO DE GUERRERO | 2 | as first published, then each reform: 3 September 2016 to 30 July 2022 |
| `ley-numero-239-de-reconocimiento-y-derechos-de-las-personas/` | LEY NUMERO 239 DE RECONOCIMIENTO Y DERECHOS DE LAS PERSONAS DE LA COMUNIDAD LGBTTTIQ+ DEL ESTADO DE GUERRERO | 1 | as first published: 3 June 2025 |
| `ley-numero-239-para-el-fomento-y-desarrollo-de-la-cultura-y/` | LEY NUMERO 239 PARA EL FOMENTO Y DESARROLLO DE LA CULTURA Y LAS ARTES DEL ESTADO DE GUERRERO | 3 | as first published, then each reform: 6 November 2013 to 26 April 2017 |
| `ley-numero-240-de-propiedad-en-condominio/` | LEY NUMERO 240 DE PROPIEDAD EN CONDOMINIO PARA EL ESTADO DE GUERRERO | 1 | as first published: 28 May 2025 |
| `ley-numero-260-para-la-prevencion-y-atencion-del-cancer-de-m/` | LEY NUMERO 260 PARA LA PREVENCION Y ATENCION DEL CANCER DE MAMA DEL ESTADO DE GUERRERO | 2 | as first published, then each reform: 17 December 2016 to 9 December 2023 |
| `ley-numero-266-de-catastro-para-los-municipios/` | LEY NUMERO 266 DE CATASTRO PARA LOS MUNICIPIOS DEL ESTADO DE GUERRERO | 1 | as first published: 27 November 2019 |
| `ley-numero-278-para-la-prevencion-social-de-la-violencia-y-l/` | LEY NUMERO 278 PARA LA PREVENCION SOCIAL DE LA VIOLENCIA Y LA DELINCUENCIA CON PARTICIPACION CIUDADANA DEL ESTADO DE GUERRERO | 2 | as first published, then each reform: 25 January 2020 to 12 March 2024 |
| `ley-numero-304-de-ingresos-para-el-municipio-de-copala/` | LEY NUMERO 304 DE INGRESOS PARA EL MUNICIPIO DE COPALA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-306-de-ingresos-para-el-municipio-de-coyuca-de-be/` | LEY NUMERO 306 DE INGRESOS PARA EL MUNICIPIO DE COYUCA DE BENITEZ DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-307-de-ingresos-para-el-municipio-coyuca-de-catal/` | LEY NUMERO 307 DE INGRESOS PARA EL MUNICIPIO COYUCA DE CATALAN DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-308-de-ingresos-para-el-municipio-de-cuajinicuila/` | LEY NUMERO 308 DE INGRESOS PARA EL MUNICIPIO DE CUAJINICUILAPA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-311-de-ingresos-para-el-municipio-de-igualapa/` | LEY NUMERO 311 DE INGRESOS PARA EL MUNICIPIO DE IGUALAPA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-315-de-ingresos-para-el-municipio-olinala/` | LEY NUMERO 315 DE INGRESOS PARA EL MUNICIPIO OLINALA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-317-de-ingresos-para-el-municipio-de-pilcaya/` | LEY NUMERO 317 DE INGRESOS PARA EL MUNICIPIO DE PILCAYA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-323-de-ingresos-para-el-municipio-de-tlacoapa/` | LEY NUMERO 323 DE INGRESOS PARA EL MUNICIPIO DE TLACOAPA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-324-de-ingresos-para-el-municipio-de-tlalchapa/` | LEY NUMERO 324 DE INGRESOS PARA EL MUNICIPIO DE TLALCHAPA, DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-33-de-instituciones-de-asistencia-privada/` | LEY NUMERO 33 DE INSTITUCIONES DE ASISTENCIA PRIVADA PARA EL ESTADO DE GUERRERO | 2 | as first published, then each reform: 12 August 1981 to 29 January 1997 |
| `ley-numero-349-de-ingresos-para-el-municipio-de-ajuchitlan-d/` | LEY NUMERO 349 DE INGRESOS PARA EL MUNICIPIO DE AJUCHITLAN DEL PROGRESO DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-351-de-ingresos-para-el-municipio-de-alpoyeca/` | LEY NUMERO 351 DE INGRESOS PARA EL MUNICIPIO DE ALPOYECA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-352-de-ingresos-para-el-municipio-de-arcelia/` | LEY NUMERO 352 DE INGRESOS PARA EL MUNICIPIO DE ARCELIA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-353-de-ingresos-para-el-municipio-de-atenango-del/` | LEY NUMERO 353 DE INGRESOS PARA EL MUNICIPIO DE ATENANGO DEL RIO DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-358-de-ingresos-para-el-municipio-de-azoyu/` | LEY NUMERO 358 DE INGRESOS PARA EL MUNICIPIO DE AZOYU DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-359-de-ingresos-para-el-municipio-de-buenavista-d/` | LEY NUMERO 359 DE INGRESOS PARA EL MUNICIPIO DE BUENAVISTA DE CUELLAR DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-365-de-ingresos-para-el-municipio-de-eduardo-neri/` | LEY NUMERO 365 DE INGRESOS PARA EL MUNICIPIO DE EDUARDO NERI DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-366-de-ingresos-para-el-municipio-de-florencio-vi/` | LEY NUMERO 366 DE INGRESOS PARA EL MUNICIPIO DE FLORENCIO VILLARREAL DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-367-de-ingresos-para-el-municipio-de-general-canu/` | LEY NUMERO 367 DE INGRESOS PARA EL MUNICIPIO DE GENERAL CANUTO A. NERI DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-373-de-ingresos-para-el-municipio-de-juchitan/` | LEY NUMERO 373 DE INGRESOS PARA EL MUNICIPIO DE JUCHITAN DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-374-de-ingresos-para-el-municipio-de-la-union-de/` | LEY NUMERO 374 DE INGRESOS PARA EL MUNICIPIO DE LA UNION DE ISIDORO MONTES DE OCA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-379-de-ingresos-para-el-municipio-de-mochitlan/` | LEY NUMERO 379 DE INGRESOS PARA EL MUNICIPIO DE MOCHITLAN DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-381-de-ingresos-para-el-municipio-de-ometepec/` | LEY NUMERO 381 DE INGRESOS PARA EL MUNICIPIO DE OMETEPEC DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-382-de-ingresos-para-el-municipio-de-petatlan/` | LEY NUMERO 382 DE INGRESOS PARA EL MUNICIPIO DE PETATLAN DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-385-de-ingresos-para-el-municipio-de-san-luis-aca/` | LEY NUMERO 385 DE INGRESOS PARA EL MUNICIPIO DE SAN LUIS ACATLAN DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-386-de-ingresos-para-el-municipio-de-san-marcos/` | LEY NUMERO 386 DE INGRESOS PARA EL MUNICIPIO DE SAN MARCOS DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-387-de-ingresos-para-el-municipio-de-san-miguel-t/` | LEY NUMERO 387 DE INGRESOS PARA EL MUNICIPIO DE SAN MIGUEL TOTOLAPAN DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-389-de-ingresos-para-el-municipio-de-santa-cruz-d/` | LEY NUMERO 389 DE INGRESOS PARA EL MUNICIPIO DE SANTA CRUZ DEL RINCON DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-391-de-proteccion-de-los-defensores-de-los-derech/` | LEY NUMERO 391 DE PROTECCION DE LOS DEFENSORES DE LOS DERECHOS HUMANOS EN EL ESTADO DE GUERRERO | 1 | as first published: 2 September 2010 |
| `ley-numero-392-de-ingresos-para-el-municipio-tlalixtaquilla/` | LEY NUMERO 392 DE INGRESOS PARA EL MUNICIPIO TLALIXTAQUILLA DE MALDONADO DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-393-de-fomento-apicola/` | LEY NUMERO 393 DE FOMENTO APICOLA DEL ESTADO DE GUERRERO | 1 | as first published: 17 November 2007 |
| `ley-numero-396-de-ingresos-para-el-municipio-de-zapotitlan-t/` | LEY NUMERO 396 DE INGRESOS PARA EL MUNICIPIO DE ZAPOTITLAN TABLAS DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-397-de-ingresos-para-el-municipio-de-zirandaro/` | LEY NUMERO 397 DE INGRESOS PARA EL MUNICIPIO DE ZIRANDARO DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-417-para-prevenir-y-erradicar-la-trata-de-persona/` | LEY NUMERO 417 PARA PREVENIR Y ERRADICAR LA TRATA DE PERSONAS Y PARA LA PROTECCION, ATENCION Y ASISTENCIA DE LAS VICTIMAS, OFENDIDOS Y TESTIGOS DE ESTOS DELITOS EN EL ESTADO DE GUERRERO | 1 | as first published: 28 December 2016 |
| `ley-numero-419-de-hacienda/` | LEY NUMERO 419 DE HACIENDA DEL ESTADO DE GUERRERO | 17 | as first published, then each reform: 1 January 2017 to 1 January 2026 |
| `ley-numero-427-de-zonas-economicas-especiales/` | LEY NUMERO 427 DE ZONAS ECONOMICAS ESPECIALES DEL ESTADO DE GUERRERO | 1 | as first published: 24 December 2016 |
| `ley-numero-427-del-sistema-de-coordinacion-hacendaria/` | LEY NUMERO 427 DEL SISTEMA DE COORDINACION HACENDARIA DEL ESTADO DE GUERRERO | 8 | as first published, then each reform: 14 August 2010 to 1 January 2026 |
| `ley-numero-428-de-conservacion-y-vigilancia-de-olinala-guerr/` | LEY NUMERO 428 DE CONSERVACION Y VIGILANCIA DE OLINALA, GUERRERO | 1 | as first published: 8 January 1983 |
| `ley-numero-439-para-prevenir-sancionar-y-erradicar-la-tortur/` | LEY NUMERO 439 PARA PREVENIR, SANCIONAR Y ERRADICAR LA TORTURA EN EL ESTADO DE GUERRERO | 1 | as first published: 29 January 2014 |
| `ley-numero-444-para-la-proteccion-del-patrimonio-cultural-y/` | LEY NUMERO 444 PARA LA PROTECCION DEL PATRIMONIO CULTURAL Y NATURAL DEL ESTADO Y LOS MUNICIPIOS DE GUERRERO | 1 | as first published: 26 April 2017 |
| `ley-numero-449-que-regula-la-venta-y-el-consumo-de-bebidas-a/` | LEY NUMERO 449 QUE REGULA LA VENTA Y EL CONSUMO DE BEBIDAS ALCOHOLICAS DEL ESTADO DE GUERRERO | 1 | as first published: 7 July 2017 |
| `ley-numero-450-de-victimas/` | LEY NUMERO 450 DE VICTIMAS DEL ESTADO LIBRE Y SOBERANO DE GUERRERO | 3 | as first published, then each reform: 13 May 2017 to 13 March 2024 |
| `ley-numero-454-de-presupuesto-y-disciplina-fiscal/` | LEY NUMERO 454 DE PRESUPUESTO Y DISCIPLINA FISCAL DEL ESTADO DE GUERRERO | 4 | as first published, then each reform: 16 October 2010 to 12 November 2016 |
| `ley-numero-455-de-mejora-regulatoria/` | LEY NUMERO 455 DE MEJORA REGULATORIA PARA EL ESTADO DE GUERRERO Y SUS MUNICIPIOS | 2 | as first published, then each reform: 4 April 2020 to 15 February 2025 |
| `ley-numero-456-del-sistema-de-medios-de-impugnacion-en-mater/` | LEY NUMERO 456 DEL SISTEMA DE MEDIOS DE IMPUGNACION EN MATERIA ELECTORAL DEL ESTADO DE GUERRERO | 4 | as first published, then each reform: 3 June 2017 to 6 April 2022 |
| `ley-numero-458-para-impulsar-las-organizaciones-de-la-socied/` | LEY NUMERO 458 PARA IMPULSAR LAS ORGANIZACIONES DE LA SOCIEDAD CIVIL EN EL ESTADO DE GUERRERO | 1 | as first published: 27 July 2014 |
| `ley-numero-460-de-ingresos-para-el-municipio-de-acapulco-de/` | LEY NUMERO 460 DE INGRESOS PARA EL MUNICIPIO DE ACAPULCO DE JUAREZ DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-461-de-ingresos-para-el-municipio-de-chilapa-de-a/` | LEY NUMERO 461 DE INGRESOS PARA EL MUNICIPIO DE CHILAPA DE ALVAREZ DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-462-de-ingresos-para-el-municipio-de-chilpancingo/` | LEY NUMERO 462 DE INGRESOS PARA EL MUNICIPIO DE CHILPANCINGO DE LOS BRAVO, GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-463-de-ingresos-para-el-municipio-de-iguala-de-la/` | LEY NUMERO 463 DE INGRESOS PARA EL MUNICIPIO DE IGUALA DE LA INDEPENDENCIA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-464-de-educacion/` | LEY NUMERO 464 DE EDUCACION DEL ESTADO LIBRE Y SOBERANO DE GUERRERO | 14 | as first published, then each reform: 24 October 2020 to 15 August 2026 |
| `ley-numero-464-del-sistema-estatal-anticorrupcion-de-guerrer/` | LEY NUMERO 464 DEL SISTEMA ESTATAL ANTICORRUPCION DE GUERRERO | 1 | as first published: 18 July 2017 |
| `ley-numero-465-de-responsabilidades-administrativas/` | LEY NUMERO 465 DE RESPONSABILIDADES ADMINISTRATIVAS PARA EL ESTADO DE GUERRERO | 3 | as first published, then each reform: 1 January 2018 to 30 April 2025 |
| `ley-numero-466-de-ingresos-para-el-municipio-de-zihuatanejo/` | LEY NUMERO 466 DE INGRESOS PARA EL MUNICIPIO DE ZIHUATANEJO DE AZUETA DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-466-de-proteccion-de-datos-personales-en-posesion/` | LEY NUMERO 466 DE PROTECCION DE DATOS PERSONALES EN POSESION DE SUJETOS OBLIGADOS DEL ESTADO DE GUERRERO | 1 | as first published: 19 July 2017 |
| `ley-numero-466-de-responsabilidad-patrimonial/` | LEY NUMERO 466 DE RESPONSABILIDAD PATRIMONIAL DEL ESTADO DE GUERRERO Y MUNICIPIOS. | 1 | as first published: 1 March 2024 |
| `ley-numero-467-de-ingresos-general-para-los-municipios/` | LEY NUMERO 467 DE INGRESOS GENERAL PARA LOS MUNICIPIOS DEL ESTADO DE GUERRERO, PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-468-de-fiscalizacion-superior-y-rendicion-de-cuen/` | LEY NUMERO 468 DE FISCALIZACION SUPERIOR Y RENDICION DE CUENTAS DEL ESTADO DE GUERRERO | 7 | as first published, then each reform: 18 July 2017 to 15 June 2024 |
| `ley-numero-468-de-ingresos/` | LEY NUMERO 468 DE INGRESOS DEL ESTADO DE GUERRERO PARA EL EJERCICIO FISCAL 2026 | 1 | as first published: 1 January 2026 |
| `ley-numero-469-de-ganaderia/` | LEY NUMERO 469 DE GANADERIA DEL ESTADO DE GUERRERO | 1 | as first published: 3 July 2014 |
| `ley-numero-47-de-fomento-industrial/` | LEY NUMERO 47, DE FOMENTO INDUSTRIAL DEL ESTADO DE GUERRERO | 1 | as first published: 7 June 1967 |
| `ley-numero-474-de-ascensos-estimulos-y-reconocimientos-de-la/` | LEY NUMERO 474 DE ASCENSOS, ESTIMULOS Y RECONOCIMIENTOS DE LA POLICIA DEL ESTADO DE GUERRERO | 1 | as first published: 30 August 2017 |
| `ley-numero-479-del-sistema-para-el-desarrollo-integral-de-la/` | LEY NUMERO 479 DEL SISTEMA PARA EL DESARROLLO INTEGRAL DE LA FAMILIA DEL ESTADO DE GUERRERO | 1 | as first published: 3 August 1983 |
| `ley-numero-480-de-sujetos-protegidos/` | LEY NUMERO 480 DE SUJETOS PROTEGIDOS DEL ESTADO DE GUERRERO | 1 | as first published: 2 September 2014 |
| `ley-numero-483-de-instituciones-y-procedimientos-electorales/` | LEY NUMERO 483 DE INSTITUCIONES Y PROCEDIMIENTOS ELECTORALES DEL ESTADO DE GUERRERO | 13 | as first published, then each reform: 1 July 2014 to 3 June 2026 |
| `ley-numero-487-para-prevenir-y-atender-el-desplazamiento-int/` | LEY NUMERO 487 PARA PREVENIR Y ATENDER EL DESPLAZAMIENTO INTERNO EN EL ESTADO DE GUERRERO | 1 | as first published: 23 July 2014 |
| `ley-numero-488-de-desarrollo-forestal-sustentable/` | LEY NUMERO 488 DE DESARROLLO FORESTAL SUSTENTABLE DEL ESTADO DE GUERRERO | 1 | as first published: 6 February 2008 |
| `ley-numero-491-de-bienestar-animal/` | LEY NUMERO 491 DE BIENESTAR ANIMAL DEL ESTADO DE GUERRERO | 7 | as first published, then each reform: 27 December 2014 to 23 May 2026 |
| `ley-numero-492-de-hacienda-municipal/` | LEY NUMERO 492 DE HACIENDA MUNICIPAL DEL ESTADO DE GUERRERO | 2 | as first published, then each reform: 2 December 2017 to 14 December 2019 |
| `ley-numero-494-de-fomento-y-desarrollo-turistico/` | LEY NUMERO 494 DE FOMENTO Y DESARROLLO TURISTICO PARA EL ESTADO Y LOS MUNICIPIOS DE GUERRERO | 6 | as first published, then each reform: 11 December 2014 to 3 June 2026 |
| `ley-numero-494-para-la-igualdad-entre-mujeres-y-hombres/` | LEY NUMERO 494 PARA LA IGUALDAD ENTRE MUJERES Y HOMBRES DEL ESTADO DE GUERRERO | 6 | as first published, then each reform: 29 December 2010 to 13 May 2026 |
| `ley-numero-495-del-registro-civil/` | LEY NUMERO 495 DEL REGISTRO CIVIL DEL ESTADO DE GUERRERO | 14 | as first published, then each reform: 5 January 2011 to 13 June 2026 |
| `ley-numero-51-del-estatuto-de-los-trabajadores-al-servicio/` | LEY NUMERO 51 DEL ESTATUTO DE LOS TRABAJADORES AL SERVICIO DEL ESTADO, DE LOS MUNICIPIOS Y DE LOS ORGANISMOS PUBLICOS COORDINADOS Y DESCENTRALIZADOS DEL ESTADO DE GUERRERO | 14 | as first published, then each reform: 21 April 1976 to 8 April 2026 |
| `ley-numero-535-de-acuicultura-y-pesca-sustentables/` | LEY NUMERO 535 DE ACUICULTURA Y PESCA SUSTENTABLES DEL ESTADO DE GUERRERO | 4 | as first published, then each reform: 15 January 2015 to 25 October 2025 |
| `ley-numero-553-de-acceso-de-las-mujeres-a-una-vida-libre-de/` | LEY NUMERO 553 DE ACCESO DE LAS MUJERES A UNA VIDA LIBRE DE VIOLENCIA DEL ESTADO LIBRE Y SOBERANO DE GUERRERO | 17 | as first published, then each reform: 9 February 2008 to 27 May 2026 |
| `ley-numero-59-organica-de-division-territorial-del-estado/` | LEY NUMERO 59 ORGANICA DE DIVISION TERRITORIAL DEL ESTADO | 9 | as first published, then each reform: 20 December 1944 to 19 November 2022 |
| `ley-numero-593-de-aprovechamiento-y-gestion-integral-de-los/` | LEY NUMERO 593 DE APROVECHAMIENTO Y GESTION INTEGRAL DE LOS RESIDUOS DEL ESTADO DE GUERRERO | 5 | as first published, then each reform: 24 May 2008 to 15 October 2025 |
| `ley-numero-61-del-fondo-auxiliar-del-tribunal-de-lo-contenci/` | LEY NUMERO 61, DEL FONDO AUXILIAR DEL TRIBUNAL DE LO CONTENCIOSO ADMINISTRATIVO DEL ESTADO DE GUERRERO | 1 | as first published: 19 July 2003 |
| `ley-numero-616-de-deuda-publica/` | LEY NUMERO 616 DE DEUDA PUBLICA PARA EL ESTADO DE GUERRERO | 5 | as first published, then each reform: 12 November 2005 to 11 November 2017 |
| `ley-numero-652-para-la-eleccion-de-comisarias-municipales/` | LEY NUMERO 652, PARA LA ELECCION DE COMISARIAS MUNICIPALES DEL ESTADO DE GUERRERO | 1 | as first published: 20 February 2021 |
| `ley-numero-668-de-austeridad/` | LEY NUMERO 668 DE AUSTERIDAD DEL ESTADO DE GUERRERO | 1 | as first published: 30 December 2023 |
| `ley-numero-669-de-participacion-ciudadana/` | LEY NUMERO 669 DE PARTICIPACION CIUDADANA DEL ESTADO DE GUERRERO | 1 | as first published: 30 December 2023 |
| `ley-numero-679-de-gobernanza-digital/` | LEY NUMERO 679 DE GOBERNANZA DIGITAL DEL ESTADO DE GUERRERO | 1 | as first published: 30 December 2023 |
| `ley-numero-688-de-personas-jovenes/` | LEY NUMERO 688 DE PERSONAS JOVENES DEL ESTADO DE GUERRERO | 3 | as first published, then each reform: 21 February 2024 to 13 December 2025 |
| `ley-numero-690-de-entidades-paraestatales/` | LEY NUMERO 690 DE ENTIDADES PARAESTATALES DEL ESTADO DE GUERRERO | 1 | as first published: 23 July 2008 |
| `ley-numero-696-de-la-comision-de-los-derechos-humanos/` | LEY NUMERO 696 DE LA COMISION DE LOS DERECHOS HUMANOS DEL ESTADO DE GUERRERO | 5 | as first published, then each reform: 21 March 2015 to 1 May 2024 |
| `ley-numero-697-de-cultura-fisica-y-deporte/` | LEY NUMERO 697 DE CULTURA FISICA Y DEPORTE PARA EL ESTADO Y LOS MUNICIPIOS DE GUERRERO | 4 | as first published, then each reform: 28 February 2015 to 13 June 2026 |
| `ley-numero-698-de-escuela-para-padres/` | LEY NUMERO 698 DE ESCUELA PARA PADRES DEL ESTADO DE GUERRERO | 1 | as first published: 7 March 2015 |
| `ley-numero-699-que-establece-el-derecho-al-acceso-de-utiles/` | LEY NUMERO 699 QUE ESTABLECE EL DERECHO AL ACCESO DE UTILES ESCOLARES, ZAPATOS Y UNIFORMES GRATUITOS, PARA LAS NIÑAS Y LOS NIÑOS DE LOS NIVELES DE PREESCOLAR, PRIMARIA Y SECUNDARIA DEL ESTADO DE GUERRERO | 1 | as first published: 7 March 2015 |
| `ley-numero-727-que-regula-la-infraestructura-fisica-educativ/` | LEY NUMERO 727 QUE REGULA LA INFRAESTRUCTURA FISICA EDUCATIVA PARA EL ESTADO DE GUERRERO | 1 | as first published: 24 September 2008 |
| `ley-numero-760-de-responsabilidades-politica-penal-y-civil-d/` | LEY NUMERO 760 DE RESPONSABILIDADES POLITICA, PENAL Y CIVIL DE LOS SERVIDORES PUBLICOS DEL ESTADO DE GUERRERO | 1 | as first published: 1 August 2018 |
| `ley-numero-761-sobre-simbolos-de-identidad-y-pertenencia/` | LEY NUMERO 761 SOBRE SIMBOLOS DE IDENTIDAD Y PERTENENCIA DEL ESTADO DE GUERRERO | 2 | as first published, then each reform: 30 August 2018 to 26 October 2019 |
| `ley-numero-762-del-instituto-de-radio-y-television-de-guerre/` | LEY NUMERO 762 DEL INSTITUTO DE RADIO Y TELEVISION DE GUERRERO | 1 | as first published: 1 August 2018 |
| `ley-numero-787-de-vida-silvestre/` | LEY NUMERO 787 DE VIDA SILVESTRE PARA EL ESTADO DE GUERRERO | 2 | as first published, then each reform: 21 September 2011 to 26 April 2017 |
| `ley-numero-790-de-asentamientos-humanos-ordenamiento-territo/` | LEY NUMERO 790 DE ASENTAMIENTOS HUMANOS, ORDENAMIENTO TERRITORIAL Y DESARROLLO URBANO DEL ESTADO DE GUERRERO | 3 | as first published, then each reform: 1 September 2018 to 21 February 2026 |
| `ley-numero-794-de-archivos/` | LEY NUMERO 794 DE ARCHIVOS DEL ESTADO DE GUERRERO Y SUS MUNICIPIOS | 2 | as first published, then each reform: 24 July 2021 to 29 December 2023 |
| `ley-numero-801-de-asociaciones-publico-privadas/` | LEY NUMERO 801 DE ASOCIACIONES PUBLICO-PRIVADAS PARA EL ESTADO DE GUERRERO | 1 | as first published: 13 October 2011 |
| `ley-numero-810-para-la-prestacion-del-servicio-de-atencion-c/` | LEY NUMERO 810 PARA LA PRESTACION DEL SERVICIO DE ATENCION, CUIDADO Y DESARROLLO INTEGRAL INFANTIL PARA EL ESTADO DE GUERRERO | 2 | as first published, then each reform: 30 May 2015 to 13 March 2024 |
| `ley-numero-812-para-la-proteccion-de-los-derechos-de-ninas-n/` | LEY NUMERO 812 PARA LA PROTECCION DE LOS DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES DEL ESTADO DE GUERRERO | 6 | as first published, then each reform: 10 October 2015 to 22 March 2024 |
| `ley-numero-814-de-desarrollo-rural-sustentable/` | LEY NUMERO 814 DE DESARROLLO RURAL SUSTENTABLE DEL ESTADO DE GUERRERO | 4 | as first published, then each reform: 20 November 2011 to 10 June 2023 |
| `ley-numero-817-para-las-personas-con-discapacidad/` | LEY NUMERO 817 PARA LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE GUERRERO | 7 | as first published, then each reform: 21 December 2011 to 21 March 2026 |
| `ley-numero-830-de-atencion-a-desastres-reconstruccion-y-recu/` | LEY NUMERO 830 DE ATENCION A DESASTRES, RECONSTRUCCION Y RECUPERACION DEL ESTADO DE GUERRERO | 1 | as first published: 23 August 2024 |
| `ley-numero-831-de-consulta-a-las-personas-con-discapacidad/` | LEY NUMERO 831, DE CONSULTA A LAS PERSONAS CON DISCAPACIDAD DEL ESTADO DE GUERRERO | 1 | as first published: 17 July 2024 |
| `ley-numero-832-para-la-atencion-inclusion-y-proteccion-a-per/` | LEY NUMERO 832 PARA LA ATENCION, INCLUSION Y PROTECCION A PERSONAS CON LA CONDICION DEL ESPECTRO AUTISTA DEL ESTADO DE GUERRERO | 1 | as first published: 10 August 2024 |
| `ley-numero-833-registral/` | LEY NUMERO 833 REGISTRAL PARA EL ESTADO DE GUERRERO | 2 | as first published, then each reform: 14 December 2024 to 22 April 2026 |

## Source

The legislation compilation of Mexico's Supreme Court, the Suprema Corte de Justicia de la Nación (SCJN), at <https://legislacion.scjn.gob.mx/>. For each ordenamiento it lists every publication in the state's official gazette (Periódico Oficial) that changed it (decree, erratum, ruling), with the date of publication, the decree's extract and the whole consolidated text as it stood after that publication. Each version here is one of those texts.

## Dates

- Each commit is dated at **noon, America/Mexico_City, on the day the publication took effect**: the day its own transitorios name, as SCJN's extract quotes them (most often the day after publication). When a decree names none, 0 days after publication, the state rule SCJN cites.
- A consolidated text holds every change published before it, so it is never dated before the latest of their in-force days. Different in-force days for parts of one decree are not split.
- An act's first commit is its first publication when SCJN holds the original text; otherwise it is the oldest version SCJN holds.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<act>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 Bis; `encabezado.md` holds the title, the promulgation and preamble; `transitorios-original.md` the original transitory articles and `transitorios-<date>.md` those of the reform published that day. Section headings and editor's notes such as "(REFORMADO, P.O. ...)" stay in the file of the article they stand before. One paragraph per line.

## How it is checked

- Every version of every act is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of SCJN's own text of that version (read independently of the parser), and every unit's text appears in it in order.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## What "author" means

The author of a commit is the publication that changed the text (a decree, an erratum or a ruling), named by its category, gazette date and issue, with an e-mail address that cannot exist (`<key>@legislacion.scjn.gob.mx.invalid`). The committer is always Lexifina.

## Limits

This is not an official publication. The binding text is the one published in the state's official gazette (Periódico Oficial). The history starts with the oldest text SCJN holds for each ordenamiento, which for many is later than its enactment. Only the ordenamientos listed above are included.
