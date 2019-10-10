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

# Caso 1:

- N° de Particulas: 1
- Tiempos de compilacion:
	* Prueba 1:2.197
	* Prueba 2:1.94
	* Prueba 3:1.718
	* Media:1.952
![1_Particula](https://user-images.githubusercontent.com/30905557/66610618-8e7fbf00-eb92-11e9-93d2-ccc12855de0d.png)


- N° de Particulas: 2
- Tiempos de compilacion:
	* Prueba 1:2.442
	* Prueba 2:2.092
	* Prueba 3:2.276
	* Media:2.263
![2_Particula](https://user-images.githubusercontent.com/30905557/66610140-211f5e80-eb91-11e9-8147-83e9f06b8cc9.png)

- N° de Particulas: 3
- Tiempos de compilacion:
	* Prueba 1:3.661
	* Prueba 2:3.552
	* Prueba 3: 3.596
	* Media:3.603
![3_Particulas](https://user-images.githubusercontent.com/30905557/66610158-2da3b700-eb91-11e9-986d-8dc97e416fe2.png)

- N° de Particulas: 4
- Tiempos de compilacion:
	* Prueba 1:7.6
	* Prueba 2:5.039
	* Prueba 3:5.085
	* Media:5.908
![4_Particulas](https://user-images.githubusercontent.com/30905557/66610167-372d1f00-eb91-11e9-9f34-7a0341f5cdd5.png)

- N° de Particulas: 5
- Tiempos de compilacion:
	* Prueba 1:13.794
	* Prueba 2:7.6
	* Prueba 3:8.952
	* Media:10.115
![5_Particulas](https://user-images.githubusercontent.com/30905557/66610217-55931a80-eb91-11e9-96c0-4bf9b0901345.png)

- N° de Particulas: 6
- Tiempos de compilacion:
	* Prueba 1:17.09
	* Prueba 2:26.009
	* Prueba 3:27.692
	* Media:23.597
![6_Particulas](https://user-images.githubusercontent.com/30905557/66610215-55931a80-eb91-11e9-8496-21c0bbcc7775.png)

- N° de Particulas: 7
- Tiempos de compilacion:
	* Prueba 1:25.165
	* Prueba 2:31.604
	* Prueba 3:23.523
	* Media:26.764
![7_Particulas](https://user-images.githubusercontent.com/30905557/66610214-55931a80-eb91-11e9-89a8-05becf408dfe.png)

- N° de Particulas: 8
- Tiempos de compilacion:
	* Prueba 1:29.566
	* Prueba 2:28.809
	* Prueba 3:50.694
	* Media:36.356
![8_Particulas](https://user-images.githubusercontent.com/30905557/66610213-54fa8400-eb91-11e9-872a-5d35948e1e24.png)

- N° de Particulas: 9
- Tiempos de compilacion:
	* Prueba 1:58.832
	* Prueba 2:74.51
	* Prueba 3:48.6
	* Media:60.647
![9_particulas](https://user-images.githubusercontent.com/30905557/66610212-54fa8400-eb91-11e9-9b81-18838e737ba5.png)

- N° de Particulas: 10
- Tiempos de compilacion:
	* Prueba 1:84.565
	* Prueba 2:123.372
	* Prueba 3:131.434
	* Media:113.124
![10_Particulas](https://user-images.githubusercontent.com/30905557/66610220-562bb100-eb91-11e9-9888-dd06579ce27c.png)

- N° de Particulas: 11
- Tiempos de compilacion:
	* Prueba 1:85.307
	* Prueba 2:149.472
	* Prueba 3:84.307
	* Media:106.477
![11_Particulas](https://user-images.githubusercontent.com/30905557/66610219-562bb100-eb91-11e9-9e14-0a74f135bf23.png)

- N° de Particulas: 12
- Tiempos de compilacion:
	* Prueba 1:216.095
	* Prueba 2:446.621
	* Prueba 3:163.211
	* Media:275.309
![12_Particulas](https://user-images.githubusercontent.com/30905557/66610218-55931a80-eb91-11e9-9dfd-0ecf447cf0d1.png)

- N° de Particulas: 13
- Tiempos de compilacion:
	* Prueba 1:312.009
	* Prueba 2:224.496
	* Prueba 3:308.924
	* Media:281.810
![13_Particulas](https://user-images.githubusercontent.com/30905557/66610315-925f1180-eb91-11e9-8739-d5fb0ddae49a.png)

- N° de Particulas: 14
- Tiempos de compilacion:
	* Prueba 1:412.936
	* Prueba 2:948.824
	* Prueba 3:823.54
	* Media:728.433
![14_Particulas](https://user-images.githubusercontent.com/30905557/66610329-9b4fe300-eb91-11e9-95b6-85fbb8df855e.png)


# GRAFICO RESUMEN TIEMPO DE EJECUCION DEL CODIGO SEGUN CANTIDAD DE PARTICULAS

![Grafico_Resumen](https://user-images.githubusercontent.com/30905557/66610728-e7e7ee00-eb92-11e9-941a-6c29a063338b.PNG)
