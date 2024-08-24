Script utilizado:

```SQL
CREATE TABLE tbUsuario(
    UUID_Usuario VARCHAR2(100),
    Nombre VARCHAR2(50),
    Correo VARCHAR2(50),
    Contraseña VARCHAR2(50)
);
select * from tbUsuario
```
</br></br>

El proyecto tiene la estructura MVC </br>
![image](https://github.com/user-attachments/assets/29cae166-50ea-40d9-bd2c-7c314d09109f)

En la vista, se crearon dos JFrame Form </br>
![image](https://github.com/user-attachments/assets/3ccc80cf-cd6a-4e6f-9032-972811c21e7b)

Pantalla de Login y registro:</br>
![image](https://github.com/user-attachments/assets/fe1877bb-ad55-4410-b32c-0982b8667708)
![image](https://github.com/user-attachments/assets/e5c9dd71-7470-4a7b-821e-95db84bbdb63)
</br></br>
Luego, en el modelo, la clase de conexión y una clase para la tabla usuarios por que es la unica tabla que se usa para el login y registro
![image](https://github.com/user-attachments/assets/459b2f1d-7c1a-47bc-9f8b-f0826be901fc)

Dentro de esta clase, seguimos los tres pasos:
![image](https://github.com/user-attachments/assets/f35c3fb8-d5ac-4067-9d2d-072fc4c83452)
![image](https://github.com/user-attachments/assets/7536d892-3dfc-47e5-8f4f-2cd692b062a4)
Y 3- Los metodos, los cuales pondremos el metodo de Guardarusuario
![image](https://github.com/user-attachments/assets/2aefdaa8-b032-4a58-addd-e08bb6ad6b6c)
y el método de iniciarSesion
![image](https://github.com/user-attachments/assets/14facfad-d19d-4094-ac44-2f76510d10ec)






