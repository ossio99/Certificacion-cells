## Como obtener  un elemento de un map
## Obtener propiedad css desde el atributo style del elemento HTML
```js
const propiedad = element.style.proiedad
```
## Como asociar un input y un dataset
```html
<!-- usando propiedad list en input y id en datalist -->
<input type="text" id="fruit" list="fruits" placeholder="Select a fruit">

<datalist id="fruits">
  <option value="Apple">
  <option value="Banana">
  <option value="Cherry">
  <option value="Orange">
  <option value="Strawberry">
</datalist>
```
## Uso de mixing
```js
class MyComponent extends MyMixin(LitElement) {}
```
## Map y set, que es cada uno y como agregar y obtener datos de cada uno
## Que pasa con la sintaxis de map que venía en un problema donde se agregaba como clase un map
> no se agregaba ninguna clase
```js
const array = [['key1', 'value1'], ['key2', 'value2']];
const map1 = new Map(array);
this.class = false;

return html`
  <p class=${this.class ? map1 : ""}>parrafo</p>
  <button @click=${() => this.toggle()}>buton</button>
`

toggle(){
  this.class = !this.class
}

```
## Cómo saber si un elemento tiene una clase con js
```js
const elemento = document.querySelector('.mi-elemento');

if (elemento && elemento.classList.contains('clase-deseada')) {
  console.log('El elemento tiene la clase.');
}
```
## Como añadir un Event listener en boton con lit
```js
render() {
  return html`<button @click="${this._handleClick}">`;
}
```
## Slots
## Qué escenario describia al concepto de agregación
## ?operator enfrente de una propiedad de lit
## obtener tamaño de un map
## obtener tamaño de un set que se le intento agregar valores repetidos
## que es body en peticiones http  
> informacion adicional que se puede mandar en peticiones como post o put
## que afirmacion de fetch es verdadera?
> devuelve una promesa que al resolverse devuelve un response
