# gildedrose-maven-docker
Práctica ejecutando un proyecto Maven con Docker

---

### Clonar un proyecto Maven (o tener uno previamente hecho)
En este caso utilizaré el repositorio de [@dfleta](https://github.com/dfleta/) (https://github.com/dfleta/docker-multistage-maven-java.git)

### Crear la imagen
![image](https://user-images.githubusercontent.com/91556467/154122767-46c447cc-395a-43d7-a6a4-78ece2efd0a1.png)

```bash
$ docker build -t gildedrose .
```
### Crear el contenedor y ejecutarlo
<img width="802" alt="image" src="https://user-images.githubusercontent.com/91556467/154122838-207b6acb-771e-42cf-a25a-fc9801eb13d1.png">

```bash
$ docker run -it --name katagildedrose gildedrose:latest
```
