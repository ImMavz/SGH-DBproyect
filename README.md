# SGH-DBproyect
DataBase proyect "Sistema de Gestion de Hoteleria".

UNIVERSIDAD DEL VALLE SEDE TULUA
FACULTAD DE INGENIERÍA
PROGRAMA ACADÉMICO DE INGENIERÍA DE SISTEMAS
Proyecto Curso Bases de Datos (750006C)
DESCRIPCIÓN FUNCIONAL DEL PROYECTO
Período Febrero – Junio de 2024
Resultados de Aprendizaje Evaluados: R.A. 1, R.A 2, R.A 3, R.A. 4
SISTEMA DE GESTION DE HOTELERA (SGH)
Se debe desarrollar un producto de software para la gestión de la información de ocupación y
reservas del Hotel “El Descanso”. El desarrollo de la base de datos debe hacerse conforme a los
temas tratados en la asignatura de Bases de Datos.
Características Funcionales:
El Hotel “El Descanso” posee varios tipos de habitaciones: sencilla, doble, matrimonial, suite
sencilla y suite presidencial. También tiene varios tipos de cliente: habituales y esporádicos, los
habituales pueden ser clientes corporativos o personas naturales.
Una reserva está determinada por los datos del cliente, los datos de la habitación, la fecha de
entrada y el número de días que estará ocupada la habitación.
El recepcionista del hotel debe poder hacer las siguientes operaciones:
• Obtener un listado de las habitaciones disponibles de acuerdo a su tipo
• Preguntar por el precio de una habitación de acuerdo a su tipo
• Preguntar por el descuento ofrecido a los clientes habituales
• Preguntar por el precio total para un cliente dado, especificando su número de
identificación, el tipo de habitación y el número de noches.
• Reservar una habitación especificando el número de habitación y la identificación del
cliente.
• Realizar el registro de cada huésped cuando toma una habitación
Por otro lado, el administrador podrá usar la aplicación desarrollada para:
• Cambiar el precio de una habitación de acuerdo a su tipo
• Cambiar el valor de descuento ofrecido a los clientes habituales
• Calcular las ventas que tendrán en un mes especificado (Considerando todos los meses
de 30 días)
Cuando una persona llegue a tomar una habitación se debe verificar su reserva y la habitación
debe pasar del estado “reservada” u “ocupada”; se debe considerar que alguna persona llegue
a tomar una habitación sin haber hecho la reserva respectiva, en tal caso se verifica que haya
habitaciones disponibles y se le puede asignar, considerando los días de estadía.
Las personas hospedadas en el Hotel, pueden acceder a servicios como: llamadas de larga
distancia, restaurante, bar, lavado, planchado, etc. Que serán cargados a su cuenta con fecha y
hora y se incluirán en la factura cuando el huésped haga su check out.
Cuando un huésped hace el check out, debe generarse una factura por el número de días que
estuvo hospedada y los servicios prestados; se debe tener en cuenta que si el check out se hace
después de las 13 horas, se cobra un día más.
Además de las operaciones anteriores la dirección de la empresa necesita conocer ciertos
informes que son de mucha importancia para la gestión del negocio. La información solicitada
es:
• Un listado que describa todas las características y servicios con los que cuenta cada
habitación.
• Un listado de las reservas realizadas por un determinado cliente. Este listado se genera
seleccionado primero el cliente.
• Un consolidado mensual de ventas por servicio.
• Datos estadísticos como porcentaje de ocupación del Hotel en un período determinado,
servicios más solicitados, porcentaje de cancelación de reservas, etc.
Perfiles de usuario y Privilegios
Por razones de seguridad en el manejo de la información se deben crear diferentes perfiles de
usuario y cada perfil tiene unos privilegios asignados.
Perfil Gerente: Tiene privilegios para generar todos los informes, visualizar la información
registrada por otros usuarios.
Perfil Cajero: Tiene permisos para registrar check out y cerrar cuenta.
Perfil Recepcionista: Tiene permisos para registrar reservas, ingresos, servicios solicitados,
consultar disponibilidad, características y costos de las habitaciones, cancelar reservas.
Perfil Administrador: Tiene privilegios para gestionar usuarios, clientes, habitaciones,
reservas, servicios e ingresos. También tiene acceso a las tareas de los demás perfiles.
