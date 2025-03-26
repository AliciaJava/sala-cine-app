# Proyecto SalaCine

Este proyecto simula el funcionamiento de una sala de cine. La clase `SalaCine` maneja la cantidad de asientos, las entradas vendidas, la película que se está proyectando, y los ingresos generados, entre otras funcionalidades.

## Características

- **Aforo**: Establece el número total de asientos en la sala de cine.
- **Ocupadas**: Realiza el seguimiento de los asientos ocupados en la sala.
- **Pelicula**: Define el nombre de la película que se está proyectando.
- **Entrada**: Define el precio de la entrada para ver la película.
- **Cálculos**: 
  - Porcentaje de ocupación de la sala.
  - Ingresos generados por las entradas vendidas.
- **Métodos de Gestión**:
  - **Vaciar**: Restablece la sala (vacía la sala y borra el nombre de la película).
  - **EntraUno**: Incrementa la ocupación de la sala en uno (simula que una persona entra).
  
## Requisitos

- JDK 8 o superior.

## Instalación

1. Clona este repositorio a tu máquina local:

    ```bash
    git clone https://github.com/tu_usuario/SalaCine.git
    ```

2. Abre el proyecto en tu IDE favorito.

3. Asegúrate de tener el JDK 8 o superior instalado.

## Uso

La clase `SalaCine` te permite gestionar los parámetros de una sala de cine. Aquí se describe cómo usar los métodos principales:

### Crear una instancia de SalaCine

```java

SalaCine sala = new SalaCine();
## Métodos

### `setAforo(int afo)`
Establece el número total de asientos en la sala de cine.

### `setOcupadas(int ocu)`
Establece el número de asientos ocupados.

### `setPelicula(String peli)`
Establece el nombre de la película que se está proyectando.

### `setEntrada(double entra)`
Establece el precio de la entrada.

### `setLibres(int lib)`
Establece el número de asientos libres, actualizando el número de asientos ocupados.

### `getAforo()`
Devuelve el número total de asientos en la sala.

### `getOcupadas()`
Devuelve el número de asientos ocupados.

### `getPelicula()`
Devuelve el nombre de la película que se está proyectando.

### `getEntrada()`
Devuelve el precio de la entrada.

### `getLibres()`
Devuelve el número de asientos libres en la sala.

### `setPorcentaje()`
Devuelve el porcentaje de ocupación de la sala.

### `setIngresos()`
Devuelve los ingresos generados por las entradas vendidas.

### `Vaciar()`
Restablece la sala (vacía los asientos ocupados y borra el nombre de la película).

### `EntraUno()`
Incrementa la ocupación de la sala en 1, simulando la entrada de una persona.
