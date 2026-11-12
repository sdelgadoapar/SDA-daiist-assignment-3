# Adding a document: before and after

**Question (q34, unanswerable in the initial corpus):** ¿Puede la comunidad de propietarios prohibir los pisos turísticos en mi edificio?

**Document added:** LPH (Ley 49/1960) — `corpus/BOE-A-1960-10906.xml`
(https://www.boe.es/buscar/act.php?id=BOE-A-1960-10906), through the same pipeline as `add_document`.

- First add: 54 chunks, 54 embedded (71s incl. second call).
- Adding it again: 0 embedded, 0 removed — already indexed and unchanged, so nothing is re-embedded.

## Before

**Sí**, la comunidad de propietarios puede limitar o condicionar el ejercicio de pisos turísticos en el edificio, siempre que se apruebe con el voto favorable de las **tres quintas partes del total de los propietarios** que a su vez representen las **tres quintas partes de las cuotas de participación** [RDL 7/2019, Artículo segundo. Modificación de la Ley 49/1960].

**Condiciones clave:**
* Estos acuerdos **no tendrán efectos retroactivos** sobre viviendas que ya estuvieran ejerciendo la actividad legalmente antes de la adopción del acuerdo [RDL 7/2019, Artículo segundo. Modificación de la Ley 49/1960].
* Con esta misma mayoría de tres quintas partes, la comunidad también puede establecer cuotas especiales de gastos o incrementar hasta un 20% la participación en los gastos comunes para las viviendas que realicen dicha actividad [RDL 7/2019, Artículo segundo. Modificación de la Ley 49/1960].

*Para un caso concreto, conviene confirmar la normativa aplicable con un abogado o con el organismo de vivienda de su comunidad autónoma.*

*Tool calls: 1; citation guard: ok*

## After

Sí, la comunidad de propietarios puede limitar, condicionar o prohibir el ejercicio de pisos turísticos en el edificio mediante un acuerdo adoptado por el voto favorable de las **tres quintas partes del total de los propietarios que, a su vez, representen las tres quintas partes de las cuotas de participación** [LPH (Ley 49/1960), Artículo diecisiete]. 

Condiciones y aspectos clave a tener en cuenta:
* **Efectos:** Estos acuerdos **no tienen efectos retroactivos**, por lo que no afectan a viviendas que ya estuvieran ejerciendo la actividad legalmente antes de la adopción del acuerdo (salvo supuestos específicos regulados en la normativa sectorial o reformas recientes) [LPH (Ley 49/1960), Artículo diecisiete; LPH (Ley 49/1960), Disposición adicional segunda].
* **Nueva normativa:** Además, para iniciar cualquier actividad de alquiler turístico, la normativa exige contar con la **aprobación expresa de la comunidad de propietarios** en los mismos términos de mayoría de tres quintas partes [LPH (Ley 49/1960), Artículo séptimo].

*Nota: Para casos particulares o conflictos sobre la aplicación de estos acuerdos, se recomienda confirmarlo con un abogado especializado o con los servicios de vivienda de su comunidad autónoma.*

*Tool calls: 1; citation guard: ok; valid citations: ['LPH (Ley 49/1960), Artículo diecisiete', 'LPH (Ley 49/1960), Artículo diecisiete; LPH (Ley 49/1960), Disposición adicional segunda', 'LPH (Ley 49/1960), Artículo séptimo']*
