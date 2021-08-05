
#  Vtiger webform + Sweetalert2

Ejemplo de formulario para enviar datos a Vtiger sin necesidad de redireccionar a otra página.

## Uso

Cambiar el valor de publicid por la del formulario de vtiger:

Línea 18

    <input name="publicid" type="hidden" value="123456abcdef" />

Cambiar la url:

Línea 78

    url: 'http://localhost/vtigercrm/modules/Webforms/capture.php',

