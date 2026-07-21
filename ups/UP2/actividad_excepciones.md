## :a:ctividad. Uso de nuevas excepciones y método _`.hasNextInt()`_ para controlar formatos numéricos

Crea un programa que se comporte diferente según el modo de ejecución introducido por el usuario.  

- Si el usuario elige el `modo 1`, el programa deberá pedir el `año de nacimiento` de la persona (_String_). Después, el programa debe convertir a entero (_int_) el valor introducido y comprobar si es un valor válido (`año >=1900` y `año <= año_actual`).

- Si el usuario elige el `modo 2`, el programa deberá pedir la `edad` de la persona (_int_). Además, deberemos asegurarnos de que es un valor válido (`edad >= 0`). Para no complicarlo mucho, calcularemos el `año de nacimiento` como `año_actual - edad` (sin tener en cuenta el mes de nacimiento exacto). 

&nbsp;&nbsp;&nbsp;**:pushpin: NOTA**: Para obtener el `año actual`, utiliza la clase _`LocalDateTime`_ de la siguiente manera:

    LocalDateTime hoy = LocalDateTime.now();

    System.out.println("El día es: " + hoy.getDayOfMonth());
    System.out.println("El mes es: " + hoy.getMonthValue());
    System.out.println("El año es: " + hoy.getYear());
    System.out.println("Minutos: " + hoy.getMinute());

Con los datos introducidos, el programa debe mostrar al usuario el nombre de su generación:

- **Sin Generación bautizada** (nacidos entre 1900 y 1927).
- **Generación Silent** (nacidos entre 1928 y 1944).
- **Baby Boomers** (nacidos entre 1945 y 1964).
- **Generación X** (nacidos entre 1965 y 1981).
- **Generación Y** o **Millennials** (nacidos entre 1982 y 1994).
- **Generación Z** o **Centennials** (nacidos entre 1995 y 2009 en adelante).

---

### :outbox_tray: Entrega

Recopila en un documento de texto todos los pasos realizados anteriormente, pásalo a PDF y súbelo a la entrega de AULES disponible.