![Imagen.](/image/k8s.jpg "Imagen.")

#
# _Repo App para k8s_

### Comenzando 🚀
_Aplicaciones para poder desplegar en **Kubernetes**._

#### _Descripción:_
_Este es un repositorio de aplicaciones para desplegar en **kubernetes**._


# 
### Hora de meter mano 🛠️
_Las diferentes Apps se pueden desplegar directamente en **Kubernetes** o utilizando **ArgoCD**_
_Para el despliegue en k8s solo se tiene que clonar los archivos de la App deseada en su clúster y ejecutar:_

```
kubectl apply -f .
```
_Este comando aplicará todos los archivos YAML que se encuentren en el directorio actual._
_Si se quisiera ir realizando el deploy de a uno solo se tiene que utilizar el mismo comando pero reemplazando el punto "." por el nombre del archivo a ejecutar. Por ejemplo:_

```
kubectl apply -f archivo1.yaml
kubectl apply -f archivo2.yaml
kubectl apply -f archivo3.yaml
etc...
```
_Si se quiere hacer los despligues utilizando ArgoCD hay que ir al [argocd-repo](https://github.com/parrot26/argocd-repo)_

#
### Setup utilizado 💻

_**Ubuntu 20.04.5 LTS (Focal Fossa)**: Servidor_.

_**Microk8s**: Kubernetes_. 

#
### Apps ▶️ 

* [netdata](https://github.com/parrot26/my-app/tree/main/netdata/manifests)
* [dashboard](https://github.com/parrot26/my-app/tree/main/dashboard/manifests)
*



# 
### Contribuyendo 🖇️

_Las contribuciones son lo que hacen que la comunidad de código abierto sea un lugar mejor. Cualquier contribución que hagas será muy apreciada._

_Si queres aportar con alguna sugerencia para mejorarlo, simplemente un **fork** en el repo y crear un **pull request**. También podes abrir un issue con la etiqueta **enhancement**. ¡No te olvides de sumar una estrella al repo! **¡Gracias de nuevo!**_

# 
### Autor ✒️

* **Juan Pablo Soto** - [GitHub](https://github.com/parrot26) - [Linkedin](www.linkedin.com/in/juanpablosoto26)



# 
### Expresiones de Gratitud 🎁

* Comenta a otros sobre este repo 📢
* Invita una cerveza 🍺 o un café ☕ a alguien del equipo. 
* Da las gracias públicamente 🤓.

#### _Gracias a:_

* [Microk8s](https://microk8s.io)
* [GitHub](https://github.com/)
* [Git](https://git-scm.com/)
* [Linkedin](https://www.linkedin.com/)
* [ArgoCD](https://argoproj.github.io/cd/)


---
⌨️ con ❤️ por [Juan Pablo Soto](https://github.com/parrot26)
