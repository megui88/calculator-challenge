# Developer Challenge

> Desarrollar de manera simple un sistema que permita visualizar por pantalla:
>
> Un encabezado y pié de página
> Un campo de entrada de texto en donde se pueda ingresar una formula matemática utilizando números y caracteres []{}() + - * /
> Un botón que permita resolver la formula ingresada o mostrar una advertencia si existe un error en la misma.
> El resultado se deberá mostrar por pantalla.
> 
> Ej: Caso correcto:
> (2+3)-[5-(3*1)] Resultado 3
> 
> Caso erróneo:
> (2+3)-(5-(3*1)] Resultado Error en formula
> (2+3)-[5-[3*1]] Resultado Error en formula
>
> Se deberá entregar en un .zip o .rar el código fuente y las indicaciones necesarias para poder visualizarlo en un navegador



## Challenge solution by Mariano G. Egui 

* I used Javascript, because I thought this not require processing in server
* I don't use libraries or frameworks, because was not necessary
#### This solution can use with any browser or using docker.

----

## How to check?

Clone the project:

```
git clone --recursive git@github.com:megui88/calculator-challenge.git
```

Go to your browser and open the file index.html

## Or use Docker

#### Please, is necessary to have
* docker:  [Ubuntu](https://docs.docker.com/engine/installation/linux/ubuntu/) or [Mac](https://docs.docker.com/docker-for-mac/install/)
* docker-compose [Ubuntu](https://docs.docker.com/compose/install/) 


Go to folder and run docker-compose

```
cd calculator-challenge
docker-compose up -d
```

Test in [localhost:8080](http://localhost:8080/)