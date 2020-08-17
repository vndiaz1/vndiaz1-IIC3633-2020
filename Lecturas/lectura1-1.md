# Crítica de la lectura 1-1: ItemBased Collaborative Filtering Recommendation Algorithms
Este paper presenta el sistema recomendador de filtro colaborativo basado en Items, un sistema muy conocido y utilizado a lo largo de los años. El artículo comienza con una introducción en donde plantea la función de los sistemas recomendadores y los problemas que tienen los algoritmos de la actualidad dado el gran crecimiento de la información y de clientes en la Web. Los principales desafíos que presentan estos filtros colaborativos son la escalabilidad y el desempeño de las recomendaciones. Después, realiza una breve contextualización de los filtros colaborativos y explica el funcionamiento del UKNN y sus problemas, para luego presentar el FC basado en Items como mejora para los sistemas recomendadores. Esto los comprueba mediante experimentos que comparan ambos sistemas y finalmente obtiene conclusiones acerca del tema, señalando que el IBCF contiene mejor escalabilidad y desempeño que el UBCF.


La sección 2, que habla sobre de los filtros colaborativos, me pareció adecuada antes de mostrar el nuevo sistema propuesto, ya que así permite al lector tener una contextualización de cómo funcionan estas recomendaciones y los problemas que están enfrentando con el aumento de información. Esto permite comprender y valorar más el sistema que se propone más adelante en el artículo.

Encuentro que la explicación del sistema propuesto está bien ordenada y simple, lo que facilita el entendimiento de este, aunque me pareció que las imágenes no aportaban demasiado para la comprensión del algoritmo. Es más, la figura 3 es un poco confusa y no la pude entender bien. Sin embargo, dejan claro el por qué este sistema puede llegar a obtener buenos resultados, dado a la correlación estática que hay entro los Items.

En cuanto a los experimentos, al igual que los otras secciones, están bien ordenados y simples de seguir. Me gustó que se hicieran sensibilizaciones en los hiperparámetros de los algoritmos, ya que le proporciona una robustez a la comparación de estos. A pesar de que justificaron la decisión de utilizar como métrica el MAE, siento que es mejor utilizar el RMSE o el MSE para castigar más los peores resultados. Por último, los gráficos eran claros y permitían una fácil comprensión de los resultados.

Las discusión y conclusión me parecieron acertadas a lo que se explicó en el cuerpo del paper.

Como comentario general, me pareció un buen artículo, ya que explican un sistema recomendador completo de forma simple y de fácil comprensión para el lector. Además, comunican bien el mensaje de que el algoritmo de recomendación propuesto obtiene buenos resultados y soluciona de mejor forma los problemas de escalabilidad y de desempeño que los sistemas recomendadores del momento.
