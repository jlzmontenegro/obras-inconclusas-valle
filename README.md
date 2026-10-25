# Obras inconclusas y sin uso · Valle del Cauca

Tablero interactivo de las obras públicas del Valle del Cauca que las entidades reportaron a la Contraloría General de la República como inconclusas o terminadas pero sin uso: cuánto costaron, cuánto se pagó, por qué se frenaron, quién las contrató y qué garantías las respaldan.

**Ver el tablero:** https://jlzmontenegro.github.io/obras-inconclusas-valle/

## Qué incluye

- Hallazgos principales y alertas sobre los registros: obras que la entidad ya da por terminadas o en uso, posibles duplicados, pagos sin avance físico, pagos por encima del presupuesto, coordenadas fuera del Valle y fechas inválidas.
- Mapa por municipio con la ubicación reportada de cada obra.
- Gráficos que se leen por número de obras, presupuesto o valor pagado: causa, clase de obra, estado, decisión administrativa, avance físico, año de inicio y de registro, entidad, fuente de financiación, procesos, aseguradoras y personas que se repiten.
- Filtros que se combinan y gráficos que filtran al hacer clic.
- Ficha completa de cada obra: contratos y otrosíes, pagos, historia del presupuesto, fuentes, personas vinculadas, pólizas, procesos, actas, licencias y ubicación, con enlace a la ficha en la Contraloría.
- Exportación a CSV.

## Datos

- **Fuente:** [Consulta de Registros de Obras Inconclusas (COI)](https://obrasinconclusas.contraloria.gov.co/search?term=VALLE%20DEL%20CAUCA&type=department) de la Contraloría General de la República. Se descargó la ficha de cada obra (formularios th2000 a th2011) y se verificó contra el export nacional oficial del COI: las filas coinciden tabla por tabla.
- Una obra activa del Valle que el buscador no devuelve (Bolívar) se tomó del export. Once registros con contratos y pagos en el Valle pero sin ficha general se muestran aparte y no se suman.
- Límites municipales: DANE MGN 2018 (para validar coordenadas) y una geometría más detallada para dibujar el mapa.
- Montos en pesos corrientes. Corte de la ficha general: 1 de junio de 2026; formularios de detalle: 25 de octubre de 2026.
