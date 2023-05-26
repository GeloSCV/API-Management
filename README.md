# API-Management
Azure API management
En un contexto previo se administraban las APIS desde el portal de AZURE, pero ahora contamos con una extensión en VSCode que nos permite hacer ello desde el editor. 



![1](https://github.com/GeloSCV/API-Management/assets/12092016/42e26ef3-a269-4aa3-8dc1-c6d6480e6075)


Para empezar hacer uso de la misma tenemos que instalar la extensión, así mismo en el portal de AZURE tenemos que contar con una cuenta de usuario, ya sea paga o gratis. 

![0](https://github.com/GeloSCV/API-Management/assets/12092016/b5786cbc-55ba-4ee5-934c-9f1fe988916a)

Luego hay que crear una instancia para la API. 
Nos tenemos que dirigir a configuración y seleccionar en el cuadro Azure API Management


![3](https://github.com/GeloSCV/API-Management/assets/12092016/72a3641f-c7ca-41c4-8916-6dee8bd0c499)

Luego damos click derecho a nuestra subscripción, elegimos Consumption, elegimos una fuente grupal y la localidad del uso de la misma. 

![4](https://github.com/GeloSCV/API-Management/assets/12092016/4aef5b77-5c52-40f1-badf-b2764ce5ab32)
![5](https://github.com/GeloSCV/API-Management/assets/12092016/7194b80f-c6ee-4539-8791-73669b057f79)

Para que la instancia se cree sin problemas tenemos que tener activo en nuestro portal de Azure, seleccionando nuestra subscripción > Proveedores de recursos > "api" en el buscador y registrando la opción "Microsoft.ApiManagement"

![10](https://github.com/GeloSCV/API-Management/assets/12092016/59840936-6666-48f5-b846-c4936c7f0f97)

A este momento contamos con la instancia creada la misma que tenemos que probar que haga conexión una API que podemos estar trabajando, una de prueba.

![7](https://github.com/GeloSCV/API-Management/assets/12092016/1c1bbc27-ed74-46d8-8660-cf2ff1ef8ebf)

Para este escenario usamos una API de prueba de AZURE a través de un vínculo.  https://conferenceapi.azurewebsites.net/?format=json 

![8](https://github.com/GeloSCV/API-Management/assets/12092016/496884b5-b326-4d75-bd4e-9c88aa70a433)

Para comprobar que esté funcionando la configuración realizada lo que necesitamos hacer es copiar la "Subscription Key" haciendo click derecho en el nombre de nuestra subscripción y haciendo un request. Al lado derecho podemos observar que hay una comunicación de tipo HTTP exitosa que muestra una respuesta de OK.

![9](https://github.com/GeloSCV/API-Management/assets/12092016/ccbb2afc-b4bc-476d-8262-f9020051e305)

