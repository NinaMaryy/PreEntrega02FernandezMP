function Producto(nombre, precio, envío, vendido) {
this.nombre = nombre;
this.precio = precio;
this.envio = envio;
this.vendido = false;
}
const producto1 = new Producto(“Café de especialidad Italiano”, “5400$”, “Envío gratis”)
Const producto2 = new Producto(“Mesa color blanco”, “3400$”, “Envío 950$”)
Vender(){
this.vendido = true;
}
console.log(producto1);
console.log(producto2);
producto2.vender();
console.log(producto2);

const nombreProducto = prompt(“Ingrese el nombre del producto”);
const precioProducto = parseInt(prompt(“Ingrese el valor del objeto que quiere vender”);
const envioProducto = parseInt(prompt(“Ingrese el valor del envío del objeto”);
const producto3 = new Producto (`${nombreProducto}, ${precioProducto}, ${envioProducto}`);
const todosProductos = [`${producto1}, ${producto2}, ${producto3}`];
const.venta = todosProductos.splice(1, 1);
console.log(todosProductos);
