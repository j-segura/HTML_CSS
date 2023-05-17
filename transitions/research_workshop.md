# 1. ¿Qué es una transición en css?

Una transición en CSS es un efecto visual que ocurre cuando se cambia el estado de un elemento, como su posición, tamaño, color o visibilidad. Permite suavizar la transición entre dos estados y agregar animaciones fluidas a los elementos de una página web.

# 2. ¿Cuál es su utilidad?

La utilidad de las transiciones en CSS es mejorar la experiencia del usuario al proporcionar un cambio visual suave y agradable cuando se producen interacciones en la página. Ayudan a crear efectos de transición más atractivos y profesionales, lo que puede aumentar la usabilidad y la interactividad de un sitio web.

# 3. ¿Cuáles son los casos en los que más se usan las transiciones de css?

Las transiciones de CSS se utilizan en una amplia variedad de casos, pero algunos de los más comunes son:

- Cambios de estado de los botones: al pasar el mouse sobre un botón, se puede aplicar una transición para cambiar su color de fondo o su apariencia.

- Mostrar u ocultar elementos: las transiciones se utilizan para suavizar la aparición o desaparición de elementos en una página web.

- Transiciones de navegación: al cambiar de una página a otra, se pueden aplicar transiciones para suavizar la carga de contenido o el cambio de diseño.

# 4. Hay dos características que si o si deben establecerse para lograr un efecto de transición, ¿Cuáles son?

la duración para definir el tiempo en el cual se tiene que completar

# 5. ¿Qué pseudoclase activa el efecto de transición?

La pseudoclase que activa el efecto de transición es :hover. Esta pseudoclase se utiliza para seleccionar un elemento cuando se coloca el puntero del mouse sobre él. Al aplicar estilos y propiedades de transición a la pseudoclase :hover, se activará la transición cuando el usuario interactúe con el elemento.

# 6. Consulta los siguientes conceptos de la propiedad transition y explica mediante un ejemplo en código de cada una:

* **transition-delay:** especifica un retraso antes de que comience la transición. Puede ayudar a sincronizar múltiples transiciones en un elemento. Ejemplo:

    > div {
        transition-property: width;
        transition-duration: 1s;
        transition-delay: 0.5s;
    }

* **transition-duration:** establece la duración de la transición. Define cuánto tiempo tardará la animación en completarse. Ejemplo:

    > div {
        transition-property: width;
        transition-duration: 2s;
    }

* **transition-property:** indica qué propiedades CSS se animarán durante la transición. Pueden ser múltiples propiedades separadas por comas. Ejemplo:

    > div {
        transition-property: width, height;
        transition-duration: 1s;
    }

* **transition-timing-function:** define cómo se calcula la progresión de la transición a lo largo del tiempo. Puede ajustar la aceleración o desaceleración de la animación. Ejemplo:

    > div {
        transition-property: width;
        transition-duration: 1s;
        transition-timing-function: ease-in-out;
    }

# 7. Especifica claramente los efectos que tienen los siguientes valores del atributo transition- timingfunction

* **ease:** proporciona una transición suave con una aceleración y desaceleración gradual. Es el valor por defecto si no se especifica ningún otro. Es similar a una función de tiempo de aceleración-desaceleración suave.

* **linear:**  produce una transición lineal y constante sin aceleración ni desaceleración. La animación avanza a una velocidad constante durante toda la duración.

* **ease-in:** genera una transición con una aceleración gradual al principio y luego se mantiene constante. El efecto es más suave al comienzo y se acelera a medida que avanza la transición.

* **ease-out:** produce una transición con una desaceleración gradual al final. La animación comienza rápidamente y luego se desacelera suavemente hacia el final.

* **ease-in-out:** combina los efectos de **ease-in** y **ease-out**. La transición comienza lentamente, se acelera en el medio y luego se desacelera al final. Es una combinación equilibrada de aceleración y desaceleración.

Estos valores permiten ajustar la apariencia y la sensación de las transiciones en función de las necesidades específicas de diseño y la experiencia de usuario que se desee lograr.