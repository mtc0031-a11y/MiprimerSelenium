¿Qué hace @BeforeEach?
Ejecuta el código marcado antes de cada uno de los tests de la clase para asegurar un estado limpio.
¿Para qué sirve assertTrue?
Es una validación que hace que el test pase solo si la condición dentro de los paréntesis es verdadera. Si es falsa, el test falla.
¿Diferencia entre findElement y findElements?
findElement devuelve el primer elemento que coincida; si no hay ninguno, lanza una excepción. findElements devuelve una lista de todos los que coincidan.
¿Por qué usar LoginPage?
Se llama patrón Page Object Model. Sirve para separar la lógica de la página de la lógica de la prueba. Si la web cambia un ID, solo lo corriges en la clase LoginPage y no en todos tus tests.
