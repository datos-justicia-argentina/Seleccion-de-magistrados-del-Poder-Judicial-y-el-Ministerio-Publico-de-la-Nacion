Selección de Magistrados del Poder Judicial y el Ministerio Público de la Nación
================================================================================

En este conjunto de datos se detalla la cantidad de vacantes a cubrir en el Poder Judicial y Ministerios Públicos de la Nación, los concursos abiertos a tal fin, la integración de las respectivas ternas, los puntajes obtenidos por los profesionales propuestos en las etapas de evaluación cumplidas, y el Curriculum Vitae de cada uno de ellos.

El Presidente de la Nación, de acuerdo a las facultades que le otorga el artículo 99, inciso 4) de la Constitución Nacional, nombra a los magistrados de la Corte Suprema de Justicia de la Nación con acuerdo del Senado por dos tercios de sus miembros presentes, en sesión pública convocada al efecto. Asimismo, por las facultades que le otorgan las leyes [27.148](http://servicios.infoleg.gob.ar/infolegInternet/anexos/245000-249999/248194/texact.htm) y [27.149](http://servicios.infoleg.gob.ar/infolegInternet/anexos/245000-249999/248189/texact.htm) del Ministerio Público Fiscal y Ministerio Público de la Defensa, respectivamente; nombra, mediante el mismo procedimiento, al Procurador General de la Nación y al Defensor General de la Nación.

En cuanto a los demás jueces de los tribunales federales inferiores, los nombra en base a una propuesta vinculante en terna remitida por el Consejo de la Magistratura, con acuerdo del Senado, en sesión pública, en la que se tendrá en cuenta la idoneidad de los candidatos. En idéntico sentido, nombra a los magistrados de los Ministerios Públicos Fiscal y de la Defensa.

Características
---------------

-   **Fecha de Publicación:** 15/05/2017

-   **Tags o Etiquetas:** juez, fiscal, defensor, magistrado, vacante, cargo, concurso, justicia, poder judicial, ministerio público, curriculum.

-   **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios.

-   **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios. Oficina Decretos.

-   **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios. Oficina Decretos.

-   **Grupo:** Poder Judicial.

-   **Frecuencia de Actualización:** Eventual.

Recursos disponibles
--------------------

### Curriculums Vitae de magistrados para cubrir vacantes en el Poder Judicial y el Ministerio Público de la Nación

-   **Nombre:** cv-magistrados-poder-judicial-ministerio-publico.csv

-   **Descripción:** Curriculums vitae de los Magistrados postulados para cubrir vacantes en el Poder judicial de la Nación y el Ministerio Público. Puede haber más de un curriculum por magistrado en aquellos casos en que el magistrado se haya presentado en más de un concurso.

-   **Formato:** CSV delimitado por coma

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **id\_curriculum (string):** Código de magistrado, permite relacionarlo con el concurso al que se presentó

-   **nombre\_magistrado (string):** Nombre del magistrado al que pertenece el curriculum vitae

-   **dni\_magistrado (int):** DNI del magistrado al que pertenece el curriculum vitae

-   **fecha\_nacimiento\_magistrado (date):** Fecha de nacimiento del magistrado que presentó el curriculum vitae

-   **nacionalidad\_magistrado (string):** Nacionalidad del magistrado que presentó el curriculum vitae

-   **localidad\_nacimiento\_magistrado (string):** Localidad en la que nació del magistrado que presentó el curriculum vitae

-   **provincia\_nacimiento\_magistrado (string):** Provincia en la que nació el magistrado que presentó el curriculum vitae

-   **universidad (string):** Universidad a la que asistió el magistrado que presentó el curriculum vitae

-   **facultad (string):** Facultad a la que asistió el magistrado que presentó el curriculum vitae

-   **fecha\_titulo (date):** Fecha de expedición del título de grado del magistrado que presentó el curriculum vitae

-   **fecha\_certificado\_reincidencia (date):** Fecha en la que fue expedido el certificado de reincidencia del magistrado que presentó el curriculum vitae

-   **link\_txt\_curriculum\_magistrado (string):** Link al curriculum vitae del magistrado

-   **link\_html\_curriculum\_magistrado (string):** Link al curriculum vitae del magistrado

### Curriculums Vitae de magistrados anexo texto

-   **Nombre:** cv-magistrados-anexo-texto.csv

-   **Descripción:** Curriculums vitae de los Magistrados. Puede haber más de un curriculum por magistrado en aquellos casos en que el magistrado se haya presentado en más de un concurso. Texto completo.

-   **Formato:** CSV delimitado por coma

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **id\_curriculum (string):** Código de magistrado, permite relacionarlo con el concurso al que se presentó

-   **nombre\_magistrado (string):** Nombre del magistrado al que pertenece el curriculum vitae

-   **texto\_curriculum (string):** Texto del curriculum vitae presentado por el magistrado. (El símbolo | representa el salto de línea)

### Concursos para la selección de Magistrados en el Poder Judicial y el Ministerio Público de la Nación

-   **Nombre:** concursos-magistrados-poder-judicial-ministerio-publico.csv

-   **Descripción:** Concursos para la selección de Magistrados del Poder Judicial y el Ministerio Público de la Nación

-   **Formato:** CSV delimitado por coma

-   **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

-   **fecha\_publicacion\_concurso (date):** Fecha de publicación del concurso

-   **numero\_expediente\_concurso (int):** Número de expediente con el que se tramitó el concurso para la selección de magistrados

-   **numero\_concurso (int):** Número de concurso al que se postuló el magistrado

-   **ambito\_origen\_concurso\_codigo (string):** Código del ámbito en el cuál se originó el concurso. Valores posibles: CMN, Consejo de la Magistratura de la Nación, MPF Ministerio Público Fiscal y MPD Ministerio Público de la Defensa,

-   **ambito\_origen\_concurso\_descripcion (string):** Descripción del ámbito en el cuál se originó el concurso. Valores posibles: Consejo de la Magistratura de la Nación, Ministerio Público Fiscal y Ministerio Público de la Defensa,

-   **cargo\_concursado (string):** Cargo al que se postuló el magistrado.

-   **cantidad\_cargos\_concursados (int):** Cantidad de cargos vacantes que se tramitan en el expediente

-   **numero\_terna (int):** Número de terna, en caso de existir más de una.

-   **identificacion\_terna (string):** Terna seleccionada para cubrir la vacante

-   **nombre\_postulante (string):** Nombre del magistrado que se postuló

-   **dni\_postulante(int):** Número de documento del magistrado que se postuló

-   **puntaje\_jurado (int):** Puntaje obtenido por el magistrados según el jurado

-   **puntaje\_comision\_seleccion (int):** Puntaje obtenido por el magistrados según la comisión de selección

-   **orden\_merito\_comision\_seleccion (int):** Número de orden en mérito de la comisión de selección

-   **orden\_merito\_plenario (string):** Número de orden en mérito del plenario

-   **observación\_concurso (string):** Anotaciones complementarias (fecha de publicación en el B.O, orden de mérito, N° de resolución en la que se publicó la terna, etc.)

-   **id\_curriculum (string):** Identificación del curriculum del magistrado, permite relacionarlo con el curriculum vitae presentado

