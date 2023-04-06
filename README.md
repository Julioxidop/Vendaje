# Vendaje
 Resourcepack y datapack listo para implementar un vendaje en minecraft

## Tabla de contenidos
- [Vendaje](#vendaje)
  * [Caracteristicas](#caracteristicas)
  * [Descargar e instalar](#descargar-e-instalar)
  * [Como usar](#como-usar)
    + [Colocar la venda](#colocar-la-venda)
    + [Quitar la venda](#quitar-la-venda)
  * [Personalización](#personalizaci-n)
  * [Notas](#notas)

## Caracteristicas
- Bloquea la visión en F5
- Todos los archivos y funciones listos para su uso directo.
- Posibilidad de modificar la textura de la venda.

## Descargar e instalar
Primero necesitaremos [***descargar***](https://github.com/Julioxidop/Vendaje/releases/tag/1.0 "aquí") este archivo que contiene el resourcepack y datapack, después descomprimimos el archivo y nos quedarán 2 carpetas:
- **VendajeRP** el cual colocaremos dentro de nuestra carpeta de resourcepacks.
- **p22vendaje** el cual colocaremos dentro de la carpeta datapacks de nuestro mundo.

## Como usar
### Colocar la venda
Para colocar la venda a una persona o personas necesitaremos ejecutar el siguiente comando:
```
/execute as <JUGADOR> run function vendaje:_set
```
Donde reemplazaremos `<JUGADOR>` por el nombre del jugador o el selector de los jugadores a los cuales queremos aplicar la venda.
 
### Quitar la venda
Para quitar la venda a una persona o personas necesitaremos ejecutar el siguiente comando:
```
/execute as <JUGADOR> run function vendaje:_unset
```
Donde reemplazaremos `<JUGADOR>` por el nombre del jugador o el selector de los jugadores a los cuales queremos quitar la venda.

## Personalización
Si queremos cambiar la textura de la venda que viene por default en el resourcepack deberemos de modificar la textura `venda.png` ubicada en `VendajeRP\assets\minecraft\textures\vendaje`
 
 **Si vamos a crear una de 0 debe de tener un tamaño de 32x32 pixeles**
 
## Notas
- No bloquea la visión en F1
- Si encuentras algun fallo, tienes alguna duda o quieres contactar conmigo, mi user de discord es: **hugme#8792**
