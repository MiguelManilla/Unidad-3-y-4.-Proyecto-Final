# Unidad-3-y-4.-Proyecto-Final

===========================================
RESTAURANT MANAGER
Sistema de Gestión de Restaurante
Asignatura: Programación Visual
===========================================

INTEGRANTES DEL EQUIPO:
CAMBRON ESCOBAR GUILLERMO
CASTILLO MANILLA MIGUEL ANGEL
RODRIGUEZ MORENO EROS

===========================================
REQUISITOS DEL SISTEMA
===========================================
- Windows 10/11
- Visual Studio 2022
- MySQL Server 8.x
- MySQL Workbench (opcional)
- .NET Framework 6.0 o superior

===========================================
INSTALACIÓN DE LA BASE DE DATOS
===========================================
1. Abrir MySQL Workbench
2. Conectarse con usuario "root"
3. Ejecutar el archivo database/restaurant_manager.sql
4. Verificar que se crearon las 7 tablas y las vistas

===========================================
CONFIGURACIÓN DE CONEXIÓN
===========================================
- Servidor: localhost
- Puerto: 3306
- Usuario: root
- Contraseña: (la que tenga tu MySQL)
- Base de datos: restaurant_manager

===========================================
CÓMO EJECUTAR LA APLICACIÓN
===========================================
1. Abrir RestaurantManager.sln en Visual Studio
2. Modificar la contraseña en DAL/Conexion.cs
3. Instalar paquetes NuGet (MySql.Data e itext)
4. Presionar F5 para ejecutar
5. Usuario: admin
6. Contraseña: admin123

===========================================
MÓDULOS DEL SISTEMA
===========================================
1. Categorías - CRUD de categorías de platillos
2. Platillos - CRUD con carga de foto (BLOB)
3. Mesas - CRUD y control de estatus
4. Empleados - CRUD con carga de foto (BLOB)
5. Órdenes - Creación, detalle y cierre
6. Usuarios - CRUD (solo visible para admin)
7. Reportes - 9 reportes + exportación a PDF

===========================================
CREDENCIALES DE PRUEBA
===========================================
- Administrador: admin / admin123
- Operador: operador / op123
- Consultor: consultor / con123

===========================================
SOLUCIÓN DE PROBLEMAS
===========================================
PROBLEMA: Error de conexión a MySQL
SOLUCIÓN: Verificar que MySQL esté activo y la contraseña correcta

PROBLEMA: Error "Helpers no existe"
SOLUCIÓN: Recompilar la solución (Ctrl+Shift+B)

PROBLEMA: Error al exportar PDF
SOLUCIÓN: Verificar que los paquetes iText estén instalados

===========================================
VIDEO DE DEMOSTRACIÓN
===========================================
[Enlace al video]

===========================================
ENTREGABLES EN GITHUB
===========================================
- Código fuente completo
- Script SQL en carpeta database/
- Manual de usuario en PDF
- Diagrama ER
- README.md

===========================================
FECHA DE ENTREGA
===========================================
05 de junio de 2026

===========================================
INSTITUTO TECNOLÓGICO DE REYNOSA
Ingeniería en Tecnologías de la Información y Comunicaciones
===========================================
