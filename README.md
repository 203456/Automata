## Validador de citas de libro en formato APA
La función principal de este automata es recorrer un archivo 
.pdf y validar que haya una cita de libros en formato APA 
cuando es valida, se guarda en un archivo .txt llamado Aceptadas,
si no lo es se guarda en otro archivo llamado Rechazadas.

El automata sigue esta estructura de citas para libros:

Apellido del autor, Inicial del(os) nombre(s). (Año de publicación). Titulo. Fuente.

Ej:
Rosenthal, R., Rosnow, R. L., & Rubin, D. B. (2000). Contrasts and effect sizes in behavioral research: A correlational approach. Cambridge University Press.
(Valido).

Rosenthal, R., Rosnow, R. L., & Rubin, D. B. Contrasts and effect sizes in behavioral research: A correlational approach. Cambridge University Press.
(No valido).

## Como usarlo
1. Clona este repositorio.
2. Instala PyPDF2 y Automata-lib 'pip install PyPDF2' y 'pip install automata-lib'.
3. Correr el archivo 'python validador.py'.
4. Adjuntar el archivo .pdf a probar.
5. Tendras una lista de citas rechazadas y aceptadas.
