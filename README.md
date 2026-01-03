# Mezcla_Gaussiana

Agrupamiento inteligente: A diferencia de otros métodos que usan círculos rígidos, el GMM asume que los datos vienen de diferentes "nubes" o distribuciones de probabilidad. El código intenta ajustar estas nubes a los puntos que le dimos (X_train).

Pesos, Medios y Covarianzas: El modelo arroja tres valores clave para describir cada grupo:

Weights (Pesos): Qué tan grande o importante es cada grupo dentro del conjunto total.

Means (Medios): El centro exacto de cada "nube" o grupo.

Covariances (Covarianzas): La forma y orientación de la nube (si es alargada, redonda o inclinada).

Visualización de la "probabilidad": Las gráficas de contorno (los círculos de colores) muestran el log-verosimilitud negativo. Básicamente, entre más cerca del centro de los círculos esté un punto, más probable es que pertenezca a ese grupo.

Probando con 2 y 3 grupos: Se hicieron dos pruebas. En una se le pidió al modelo encontrar 2 componentes y en la otra 3 componentes. Esto sirve para ver cómo se reclasifican los puntos cuando intentamos ser más específicos con los grupos.

<img width="589" height="499" alt="image" src="https://github.com/user-attachments/assets/7d9ac5dc-5f05-4846-8c86-e90849de1234" />
<img width="543" height="553" alt="image" src="https://github.com/user-attachments/assets/dcdc5b85-8851-4fd7-ac9a-22c48134b51e" />
