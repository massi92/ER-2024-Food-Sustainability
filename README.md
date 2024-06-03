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

The schema of the cunsumer module is the following:
![NextCart Food Ontology Schema](https://link-to-schema-image)

### Nutrition Module

The Nutrition module provides a structured way to represent and manage the relationships between consumers, their dietary plans, and various health and personal factors influencing their nutritional requirements.

Key classes in this module include:
- `HealthConditions`: Captures health-related aspects of the consumer, such as food allergies and pathologies.
- `RestrictedDiet`: Models dietary restrictions and preferences, like diabetic, gluten-free, vegetarian, and vegan diets.
- `FoodItem`: Represents specific food items, including properties like `suitableFor` and `includeFood`.
- `NutritionalInformation`: Details nutritional aspects such as carbohydrates, fats, and proteins.

The schema of the nutrition module is as follows:
![NextCart Food Ontology Schema](https://link-to-schema-image)

### Sustainability Module

The Sustainability module captures a comprehensive view of sustainability in the food supply chain, emphasizing environmental, social, and economic dimensions and their impact on various stakeholders.

Key classes in this module include:
- `Sustainability`: Integrates aspects of sustainable practices, with subclasses `EnvironmentalSustainability`, `SocialSustainability`, `EconomicSustainability`, and `WasteSustainability`.
- `EnvironmentalSustainability`: Measures environmental impacts like carbon footprint, energy consumption, and water usage.
- `SocialSustainability`: Addresses social impacts such as food security, labor conditions, and community impact.
- `EconomicSustainability`: Reflects economic viability and fairness, including cost efficiency and fair trade practices.
- `WasteManagement`: Addresses food waste and recycling processes, with subclasses `FoodWaste`, `Composition`, and `Recycling`.

The schema of the sustainability module is as follows:
![NextCart Food Ontology Schema](https://link-to-schema-image)
