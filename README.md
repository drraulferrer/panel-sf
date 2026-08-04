# panel-sf

Página estática cuyo contenido está **cifrado con AES-256-GCM**. La clave se deriva con
PBKDF2-SHA256 (600.000 iteraciones) y el descifrado ocurre íntegramente en el navegador.
Sin la contraseña no se muestra nada: el autenticador GCM rechaza cualquier otra clave.

Este repositorio es público únicamente para poder servir la página; el contenido no lo es.
