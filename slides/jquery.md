##  jQuery

Gestión del estado en el DOM

```html
$( '#form' ).on( 'submit', function( e ) {
  e.preventDefault();
  var $el = $( this );
  if ( $el.find( 'checkbox' ).checked ) {
    doSomething(); //…
  }
} );
```
