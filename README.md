# ¡Escala tus ‘pipelines’ de procesado de datos mixtos sin salir de scikit-learn!

La mayoría de problemas reales que abordamos con Aprendizaje Automático requieren ingerir datos de diversa naturaleza y fuentes de procedencia: los atributos de nuestras muestras pueden tener carácter numérico, categórico, o textual.

Los modelos de Aprendizaje Automático necesitan que la información entrante esté expresada en un formato adecuado, en la mayoría de ocasiones como vector o tensor numérico. Es imperativo pues definir una cadena de operaciones para transformar nuestros datos originales al formato tolerado por el modelo en cuestión, a la vez que intentamos extraer nuevas variables que faciliten el aprendizaje del modelo y mejoren su poder predictivo. 

Dado que las operaciones a realizar dependerán de la tipología de partida de los atributos, estas cadenas de operaciones o pipelines pueden llegar a ser complejas y difíciles de encapsular, pudiendo dificultar el posterior mantenimiento y provocar potenciales errores metodológicos en la etapa de validación del modelo o de puesta en producción.

Scikit-learn ha incluido una nueva funcionalidad en su recientemente lanzada versión 0.20, que complementa a su poderoso “Pipeline” para construir arquitecturas multimodales como la esbozada: “ColumnTransformer”.

En esta charla presentaremos a través de ejemplos prácticos la problemática que puede plantear el procesamiento de datos mixtos y cómo scikit-learn nos proporciona una potente solución 'off-the-shelf'.
