## Comando de Ayuda

!!! info "Comandos de ayuda en Linux"
    Estos comandos te permiten obtener información, documentación y uso correcto de herramientas en Linux:

    ### Ayuda general
    - **`man <comando>`** — Muestra el manual completo del comando.
    - **`apropos <palabra>`** — Busca comandos relacionados con una palabra clave.

    ### Ayuda integrada
    - **`<comando> --help`** — Muestra una descripción rápida, opciones y ejemplos.
    - **`<comando> -h`** — Variante abreviada de ayuda (cuando está disponible).

    ### Documentación adicional
    - **`info <comando>`** — Muestra documentación más detallada para algunos programas.
    - **`whatis <comando>`** — Muestra una breve descripción del comando.
    - **`help <builtin>`** — Muestra ayuda para comandos internos de bash (como `cd`, `echo`, `exit`).

     *Cuando no sabes qué comando usar, `apropos` y `whatis` son tus mejores aliados.*

---

## Redirección y Tuberías

En Linux, la salida de un comando puede ser la entrada de otro, lo que permite encadenar operaciones.

* **Tubería (`|`)**: Envía la **salida** de un comando como **entrada** a otro.
    * *Ejemplo*: `ls -l | less` (lista el contenido y lo pasa al programa `less` para paginar).
* **Redirección de Salida (`>`)**: Envía la **salida** a un archivo, **sobrescribiendo** su contenido.
    * *Ejemplo*: `echo "Hola" > saludo.txt`
* **Redirección de Adición (`>>`)**: Envía la **salida** a un archivo, **añadiendo** al final.
    * *Ejemplo*: `echo "Adiós" >> saludo.txt`

---

## Consejos Rápidos

* **`Ctrl + C`**: Detiene el comando o proceso en ejecución.
* **`Tab`**: Se usa para el **autocompletado** de comandos, nombres de archivos y rutas.
* **`!!`**: Repite el último comando ejecutado.
* Puedes encontrar más comandos [aqui](https://kinsta.com/es/blog/linux-comandos/)
