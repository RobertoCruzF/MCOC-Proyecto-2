# MCOC-Proyecto-2

# README REPOSITORIO ROBERTO CRUZ

Proyecto 2 Métodos Computacionales para Obras Civiles

Integrantes:

- Fernanda Arcos Hernández
- Fabian Cortes Figueroa (https://github.com/fabianszne)
- Roberto Cruz Fernández (https://github.com/RobertoCruzF)
- Anibal Tapia Triviño   (https://github.com/tapiolaa)

# Introducción
En este proyecto se implementará y validará un modelo de simulación de transporte de sedimentos en base a un método lagrangiano, en específico el método de Euler. 
La validación se hará a nivel del comportamiento de una partícula individual y luego con el comportamiento estadístico de cantidades
crecientes de partículas.

# Objetivos
Implementar un modelo de simulacion numerico para transporte de sedimentos de fondo. Comprender aspectos de desempeño de aplicaciones de computación científica tales como IO y complejidad algorítmica.

- [Meta 3] : Implementación y validación del código para una partícula considerando un perfil de velocidades sencillo.
- [Entrega 3] : (script saltation_one_particle.py) Como resultado del código se obtienen dos gráficos en los cuales se observa el movimiento de la partícula, tanto en las direcciones x e y.

- [Meta 4] : Implementacion del código para múltiples partículas considerando un perfil de velocidad sencillo; además de uno complejo.
- [Entrega 4] : (script saltation_many_particles_validation.py) Para el código se comienza por abordar el movimiento de más de una partícula, específicamente 2 con un perfil de velocidad sencillo; luego se pretende poder entregar los resultados para un número de partículas deseadas por el usuario, creando un input y con esto un ciclo que permita guardar las posiciones de cada una de estas partículas.

# ESPECIFICACIONES DEL COMPUTADOR

- Marca: Asus
- Procesador: Intel Core i5-7300HQ CPU @ 2.5GHz 
- Memoria RAM: 8 GB
- Nucleos: 4
- Sistema Operativo: Windows 10 Home, x64 bites

# COMPORTAMIENTO DEL COMPUTADOR FRENTE A DIFERNTES CASOS

- Se ejecutó el codigo para un numero de 1 a 20 particulas, realizando 3 ejecuciones por particula y guardando la media del tiempo de ejecución para poder realizar un grafico de tiempo de ejecucion del codigo versus cantidad de particulas.
# Caso 1:

- N° de Particulas: 1
- Tiempos de compilacion (segundos):
	* Media:0.352
![1_Particula](https://user-images.githubusercontent.com/30905557/66690983-eb01dd80-ec69-11e9-8292-08cf6f5423d6.png)

- N° de Particulas: 2
- Tiempos de compilacion (segundos):
	* Media:0.637
![2_Particula](https://user-images.githubusercontent.com/30905557/66690982-eb01dd80-ec69-11e9-87e9-436c6d7a6077.png)
- N° de Particulas: 3
- Tiempos de compilacion (segundos):
	* Media:1.272
![3_Particulas](https://user-images.githubusercontent.com/30905557/66690981-ea694700-ec69-11e9-82ae-8ce50232dae0.png)

- N° de Particulas: 4
- Tiempos de compilacion (segundos):
	* Media:2.106
![4_Particulas](https://user-images.githubusercontent.com/30905557/66690980-e9d0b080-ec69-11e9-92d6-1403c98a6f52.png)

- N° de Particulas: 5
- Tiempos de compilacion (segundos):
	* Media:3.627
![5_Particulas](https://user-images.githubusercontent.com/30905557/66690978-e9381a00-ec69-11e9-8ec7-2427d3c937d7.png)

- N° de Particulas: 6
- Tiempos de compilacion (segundos):
	* Media:4.04
![6_Particulas](https://user-images.githubusercontent.com/30905557/66690977-e9381a00-ec69-11e9-832d-53aa7ea389e4.png)

- N° de Particulas: 7
- Tiempos de compilacion (segundos):
	* Media:7.737
![7_Particulas](https://user-images.githubusercontent.com/30905557/66690976-e9381a00-ec69-11e9-803a-5c3b7c675242.png)

- N° de Particulas: 8
- Tiempos de compilacion (segundos):
	* Media:11.32
![8_Particulas](https://user-images.githubusercontent.com/30905557/66690975-e89f8380-ec69-11e9-9ff1-39df4d0d1a7b.png)

- N° de Particulas: 9
- Tiempos de compilacion (segundos):
	* Media:18.958
	
![9_particulas](https://user-images.githubusercontent.com/30905557/66690974-e89f8380-ec69-11e9-9208-5bda435bce37.png)

- N° de Particulas: 10
- Tiempos de compilacion (segundos):
	* Media:50.446
	
![10_Particulas](https://user-images.githubusercontent.com/30905557/66690973-e89f8380-ec69-11e9-8c6f-ce461ed9a2fa.png)

- N° de Particulas: 11
- Tiempos de compilacion (segundos):
	* Media:69.247
	
![11_Particulas](https://user-images.githubusercontent.com/30905557/66690972-e89f8380-ec69-11e9-9458-b2a6fef1c676.png)

- N° de Particulas: 12
- Tiempos de compilacion (segundos):
	* Media:103.517
	
![12_Particulas](https://user-images.githubusercontent.com/30905557/66690971-e806ed00-ec69-11e9-9fe4-5fa1d514d8f5.png)

- N° de Particulas: 13
- Tiempos de compilacion (segundos):
	* Media:88.773
	
![13_Particulas](https://user-images.githubusercontent.com/30905557/66690970-e806ed00-ec69-11e9-986f-dc204824c10d.png)

- N° de Particulas: 14
- Tiempos de compilacion (segundos):
	* Media:107.043
	
![14_Particulas](https://user-images.githubusercontent.com/30905557/66690969-e76e5680-ec69-11e9-84b6-6c072cab7cbb.png)

- N° de Particulas: 15
- Tiempos de compilacion (segundos):
	* Media:123.201
	
![15_Particulas](https://user-images.githubusercontent.com/30905557/66690968-e76e5680-ec69-11e9-8a39-09753e506794.png)
- N° de Particulas: 16
- Tiempos de compilacion (segundos):
	* Media:251.739
![16_Particulas](https://user-images.githubusercontent.com/30905557/66691550-aed07c00-ec6d-11e9-9452-3869a11ec07c.png)

- N° de Particulas: 17
- Tiempos de compilacion (segundos):
	* Media:142.768
![17_Particulas](https://user-images.githubusercontent.com/30905557/66691585-efc89080-ec6d-11e9-8ce5-71997f7ee14b.png)

- N° de Particulas: 18
- Tiempos de compilacion (segundos):
	* Media:179.37
![18_Particulas](https://user-images.githubusercontent.com/30905557/66691684-75e4d700-ec6e-11e9-886f-e2aac1df0dbd.png)

- N° de Particulas: 19
- Tiempos de compilacion (segundos):
	* Media:271.12
![19_Particulas](https://user-images.githubusercontent.com/30905557/66691787-39fe4180-ec6f-11e9-8ec8-dc4d7df38846.png)

- N° de Particulas: 20
- Tiempos de compilacion (segundos): 375.03
![20_ Particulas](https://user-images.githubusercontent.com/30905557/66691370-3ddc9480-ec6c-11e9-84d1-b186a0e17d4a.png)


# GRAFICO RESUMEN TIEMPO DE EJECUCION DEL CODIGO SEGUN CANTIDAD DE PARTICULAS

![Grafico_Resumen](https://user-images.githubusercontent.com/30905557/66691868-d9233900-ec6f-11e9-8d16-12cd7a4e2d64.PNG)
