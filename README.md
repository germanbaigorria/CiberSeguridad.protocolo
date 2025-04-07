# CiberSeguridad.protocolo
prototipo de contratos en CiberSeguridad

En este contrato veremos:
 - direccion del propietario del contrato; eventos para registrar cambios y acciones;
 - Constructor; modificador para restringir funciones solo al propietario
 - modificadores para evitar que las funciones se ejecuten cuando el contrato esta pausado
 -  Funciones --> transferir la propiedad a otra direccion;
          |-----> pausar el contrato en caso de emergencia;
          |-----> para reanudar las operaciones del contrato;
          |-----> funcion publica de ejemplo que incorpora validaciones;
          |-----> funcion de retiros de fondo del contrato protegida y solo ejecutable por el propietario.
   Ejemplos de funcion sensible protegida por controles de seguridad.
   
