# Conceptual Modelling for Improving Consumers Awareness in Food Shopping Experience
The NextCart Food Ontology defines the main concepts and properties used to understand consumer habits, health conditions, food nutrition, and sustainability within the food supply chain. The ontology aims to support the retrieval and management of information relevant to consumers, nutrition, and sustainable practices, enhancing decision-making processes in these domains.

The NextCart Food Ontology is composed of 3 modules, published at:

- Consumer module: [Consumer Ontology](https://anonymous.4open.science/r/ER-2024-Food-Sustainability/consumer.owl)
- Nutrition module: [Nutrition Ontology](https://anonymous.4open.science/r/ER-2024-Food-Sustainability/health-dietary.owl)
- Sustainability module: [Sustainability Ontology](https://anonymous.4open.science/r/ER-2024-Food-Sustainability/sustainability.owl)

### Consumer Module

The Consumer module captures a comprehensive view of a consumer's lifestyle, including their demographic information, activities (like sleep and sports), dietary choices, health conditions, and shopping habits. 
Key classes in this module include:
- `Activity`: Captures lifestyle activities, with subclasses `PhysicalActivity` and `Sleep`.
- `WeightObservation`: Tracks changes in a consumer's weight over time.
- `ShoppingList` and `ShoppingCart`: Represent planned and purchased food items, respectively.
- `ShoppingItem`: Details the quantity and price of items in shopping lists or carts.
- `Diet and Health`: Links consumers to their dietary choices and health conditions.
- `Sustainability`: Reflects consumer preferences for sustainable practices.

The schema of the ontology is the following:
![NextCart Food Ontology Schema](https://link-to-schema-image)
