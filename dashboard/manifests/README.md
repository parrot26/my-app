#
# _Dashboard para k8s_

### Comenzando 🚀
_Este es el dashboard estándar de **Kubernetes**._

#### _Descripción:_
_La documentación oficial del dashboard de **kubernetes** se la puede consultar [Aquí](https://kubernetes.io/docs/tasks/access-application-cluster/web-ui-dashboard/)._
_Desde ahí se puede seguir el paso a paso para su instalación._


# 
### Hora de meter mano 🛠️
_Si tenemos instalado y configurado el complemento [metallb](https://microk8s-io.translate.goog/docs/addon-metallb?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc) de Microk8s podemos hacer uso del archivo dashboard-service.yml del repo_

_Solo hay que habilitar el complemento de **dasboard** en Microk8s:_

```
microk8s enable dashboard
```
_Luego clonar el archivo dashboard-service.yml del repositorio y ejecutarlo:_


```
kubectl apply -f dashboard-service.yml
```
_Se puede ver la IP del **service/dashboard-service** ejecutando:_

```
kubectl get all --all-namespaces | grep LoadBalancer
```
_De esa forma se puede ver la IP externa asignada por el **metallb**._

_Solo queda acceder desde el navegador a través de la IP externa asiganada._

_Para loguearse al **dashboard** revisar la domumentación [Aquí](https://microk8s-io.translate.goog/docs/addon-dashboard?_x_tr_sl=en&_x_tr_tl=es&_x_tr_hl=es-419&_x_tr_pto=sc)_


#
### Setup utilizado 💻

_**Ubuntu 20.04.5 LTS (Focal Fossa)**: Servidor_.

_**Microk8s**: Kubernetes_. 
