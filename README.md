# 250: Autos y confianza

Juego económico por turnos sobre un lote de autos usados en un pueblo de Estados Unidos, en la primavera de 1957. Empiezas con un Chevrolet en consignación, un teléfono de disco y una guía de papel, y en 90 días construyes un concesionario al que la gente llega por recomendación.

Todo el juego cabe en un solo archivo `index.html`: las imágenes, la fuente y el sonido van dentro y no hace falta internet. Está pensado para el teléfono; en la computadora se abre como una columna angosta.

## Cómo publicarlo en GitHub Pages

1. Crea un repositorio público nuevo en GitHub (por ejemplo, `autos-250`).
2. Haz clic en **Add file → Upload files** y arrastra `index.html` y `README.md` de este ZIP. Haz clic en **Commit changes**.
3. Abre **Settings → Pages**. En **Build and deployment** elige **Deploy from a branch**, la rama `main` y la carpeta `/ (root)`. Haz clic en **Save**.
4. En uno o dos minutos el juego estará en `https://TU-USUARIO.github.io/autos-250/`.

En iPhone, abre la dirección en Safari y toca «Compartir» → «Agregar a pantalla de inicio»: aparecerá un ícono con una llave y el juego se abrirá en pantalla completa.

## Cómo se juega

- **El día** tiene 4 unidades de tiempo. Una llamada, preparar un auto, ayudar a un cliente o hacer una compra cuestan 1 cada una; una cita con demostración, 2. No más de dos citas al día.
- **Los objetos del escritorio son el menú.** Teléfono: citas, llamadas entrantes, reclamos. Guía: gente nueva por barrios. Libreta: todo lo que sabes de tus clientes. Calendario: promesas. Periódico: demanda, anuncios, compras. Caja: dinero, nivel, mejoras. Ventana: el lote con los autos. La radio pone jazz.
- **La cita:** presentación → dos preguntas → demostración (el auto y una prueba según la necesidad) → decisión. Para comprar hace falta un auto listo, cubrir la necesidad principal, un precio dentro del presupuesto y los papeles revisados.
- **Las promesas** (citas, llamadas, entregas, respuestas a reclamos) se anotan en el calendario. Cumplir una suma confianza; aplazarla de común acuerdo casi no cuesta nada; incumplirla en silencio quita 12 puntos.
- **Honestidad:** decir «todavía no está revisado» no se castiga. Asegurar «el auto está perfecto» sin revisarlo te hace responsable si aparece un defecto.
- **Opiniones:** entre 2 y 5 días después de entregar las llaves, el comprador valora su propio auto: es la línea «Opinión del comprador» en la tarjeta de la mañana, con el modelo y la fecha de compra. Un auto entregado, una opinión.
- **Recomendaciones:** un cliente satisfecho puede traer a un conocido una vez por semana. Si se lo pides, la probabilidad es mayor.
- **Objetivo de la campaña** (90 días): nivel 9, 12 000 $ de ganancia neta, 50 autos entregados (10 por recomendación), satisfacción media de 80 o más en 15 compradores, reservas para una semana y ninguna promesa vencida. Después del día 90 puedes seguir en modo libre.

Gastar dinero, contratar, entregar un auto y la oferta final de un trato se confirman con un segundo toque: el primero pone el botón amarillo con el texto «¿Confirmar?».

## Partida guardada

El juego se guarda en el navegador después de cada acción. Borrar los datos de Safari o Chrome elimina el progreso, así que de vez en cuando haz una copia: **Menú → Guardar archivo de progreso**. Puedes cargarla desde el menú o desde la pantalla de inicio del juego. Al cargarla, el juego comprueba la versión y que las cuentas cuadren.

## Qué hay dentro

- 9 niveles, 6 familias de autos (3 ejemplares de cada una, en distinto estado), 7 tipos de compradores, 88 vecinos en 6 barrios, 45 caras de compradores y 9 personajes fijos.
- 8 demostraciones, 24 eventos de historia, noticias de demanda en el periódico, un competidor al otro lado de la calle, especialización, equipo (asistente, mecánico, segundo vendedor) y pedidos de empresas.
- Resúmenes en los días 30, 60 y 90 con tres historias: un buen trato, una oportunidad perdida y lo que trajo una promesa.

## Verificación

El juego se probó con bots de cinco estrategias (cuidadosa, con descuentos, arriesgada, por recomendaciones y de novato) y con un jugador «caótico» que pulsa cualquier cosa en cualquier orden: 150 campañas, desde el primer día y también desde la mitad y el final del juego. Después de cada acción se comprueba la lógica: la caja, la ganancia y los anticipos cuadran; cada promesa corresponde a una cita, un trato o un reclamo reales; ningún cliente se pierde sin forma de contactarlo; una venta da exactamente una opinión; los textos concuerdan en género y número (comprador, compradora, pareja). Un juego cuidadoso llega al nivel 7–8; para ganar hace falta uno casi impecable. La interfaz se probó con toques al azar al principio, a la mitad y al final del juego, sin errores.

---

Inspirado en las ideas de Joe Girard sobre la confianza, las recomendaciones y la ayuda después de la venta. Los sucesos de 1957 y todos los vecinos son ficticios; los precios están en dólares de juego. El juego enseña a través de las consecuencias de las decisiones y no promete éxito en ventas reales.
