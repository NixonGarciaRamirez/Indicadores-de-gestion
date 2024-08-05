# Management indicators / Indicadores de gestion :computer: :keyboard: :green_heart:
## Project explanation

This is a project focused on data analytics for a logistics inventory model for a motorcycle assembly plant. Within it, a fictitious database is created using numpy random selection models and numpy random number generation models. Within the fictitiously created columns are the following:

• Model: Specifies the type or model of motorcycle in the inventory. Each entry in this column represents a specific model, such as "Sport", "Cruiser", "Adventure", etc.
• Suppliers: Lists the suppliers of parts or components needed to assemble the motorcycles. Includes information such as the supplier's name and contact details.
• Inventory issues: Records any inventory-related issues, such as shortages, surpluses, damages or discrepancies. Helps in managing and resolving incidents.
• Inventory movement: Details the inventory flow, recording inputs and outputs of parts. Includes information on dates, quantities, and reasons for movement (e.g., receipt of new parts, use in production, returns).
• Parts_inventory: Maintains an up-to-date record of the number of parts available in inventory. Includes the name of the part, the quantity in stock, and possibly its location in the warehouse.
• Purchase_orders: Contains information on purchase orders placed with suppliers, including details such as order date, supplier, parts requested, quantities, and order status.
• Inventory_costs: Records the costs associated with maintaining inventory, including the cost of acquiring parts, storage, handling, and other related expenses.
• Inventory_turnover: Indicates how often inventory is renewed or used in the production process. Helps identify efficiency in inventory management.
• Customer_demands: Records customer requests and demands, providing information on which models and parts are in greatest demand. Helps in production and inventory planning.
• Operational_efficiency: Measures the efficiency of operations related to inventory management, including metrics such as processing time, order fulfillment, and inventory accuracy.

Something to highlight is that this project randomly introduces null data to the columns: 'Parts_inventory', 'Purchase_orders', 'Inventory_costs', 'Inventory_turnover', 'Customer_demands', 'Operational_efficiency', this in order to put into practice 2 methods of imputing null data: the one focused on imputing using the data mean and the KNN method, within the project to show the difference between the 2 methods a smoke mask was used so that when the data is graphed the imputed data can be seen graphically.

In addition, a statistical analysis is also performed by answering questions of both descriptive statistics and inferential statistics on the data present in the database.

Note: Since the project is carried out in an .ipynb file, it already has a preview.


## Version en español
## Explicación del proyecto

Este es un proyecto enfocado al manejo analítico de datos  para un modelo logístico de inventario de una ensambladora de motos. Dentro de este se crea una base de datos ficticia empleando modelos de selección aleatoria de numpy y modelos de generación de números aleatorios de numpy, dentro de las columnas creadas de forma ficticia se encuentran las siguientes:

    • Modelo: Especifica el tipo o modelo de moto en el inventario. Cada entrada en esta columna representa un modelo específico, como "Sport", "Cruiser", "Adventure", etc. 
    • Proveedores: Lista los proveedores de piezas o componentes necesarios para ensamblar las motos. Incluye información como el nombre del proveedor y detalles de contacto. 
    • Problemas de inventario:Registra cualquier problema relacionado con el inventario, como faltantes, excedentes, daños o discrepancias. Ayuda en la gestión y resolución de incidencias. 
    • Movimiento de inventario: Detalla el flujo de inventario, registrando entradas y salidas de piezas. Incluye información sobre fechas, cantidades y motivos del movimiento (por ejemplo, recepción de nuevas piezas, uso en producción, devoluciones). 
    • Inventario_de_piezas:Mantiene un registro actualizado del número de piezas disponibles en el inventario. Incluye el nombre de la pieza, la cantidad en stock y posiblemente su ubicación en el almacén. 
    • Órdenes_de_compra: Contiene información sobre las órdenes de compra realizadas a los proveedores, incluyendo detalles como fecha de la orden, proveedor, piezas solicitadas, cantidades y estado de la orden. 
    • Costos_de_inventario: Registra los costos asociados con el mantenimiento del inventario, incluyendo el costo de adquisición de las piezas, almacenamiento, manejo y otros gastos relacionados. 
    • Rotación_de_inventario: Indica la frecuencia con la que el inventario se renueva o se utiliza en el proceso de producción. Ayuda a identificar la eficiencia en la gestión del inventario. 
    • Demandas_de_cliente: Registra las solicitudes y demandas de los clientes, proporcionando información sobre qué modelos y piezas tienen mayor demanda. Ayuda en la planificación de la producción y el inventario. 
    • Eficiencia_operativa: Mide la eficiencia de las operaciones relacionadas con la gestión del inventario, incluyendo métricas como tiempo de procesamiento, cumplimiento de órdenes y precisión del inventario. 

Algo a resaltar es que este proyecto introduce de forma aleatoria datos nulos a las columnas: 'Inventario_de_piezas', 'Órdenes_de_compra', 'Costos_de_inventario', 'Rotación_de_inventario', 'Demandas_de_cliente', 'Eficiencia_operativa', esto con el fin de poner en practica 2 métodos de imputación de datos nulos: el enfocado en imputar empleando la media de los datos y el método KNN, dentro de el proyecto para evidenciar la diferencia entre los 2 métodos se empleo una mascara de humo de forma que cuando se grafiquen los datos se pueda ver de forma grafica los datos imputados.


Ademas de eso también se realiza un análisis estadístico respondiendo preguntas tanto de estadística descriptiva, como de estadística inferencial sobre los datos presentes dentro de la base de datos.

Nota: El proyecto al ser realizado en un archivo .ipynb este ya cuenta con vista previa.
