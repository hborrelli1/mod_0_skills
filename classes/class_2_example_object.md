## Class that may exist in a Restaurant

### Class: GrilledOctopus

**Attributes**
menuItemName: 'Grilled Octopus'
itemDescription: 'Our Grilled Octopus is marinated in a coconut lime, grilled and mixed with sticky coconut rice and vegetables'
itemPrice: 28
itemIngredients: ['octopus', 'coconut milk', 'sticky rice', 'steamed vegetables', 'lime', 'salt']
happyHourDiscount: false
available: true

**Methods**
changeName('Chef\'s Grilled Octopus') - Changes menuItemName from 'Grilled Octopus' to 'Chef's Grilled Octopus'
updateDescription('Our Chef's Special Grilled Octopus is marinated in a coconut lime, grilled and mixed with sticky coconut rice and vegetables') - updates itemDescription
updatePrice(30) - Updates itemPrice to 30
addIngredient('mango salsa') - adds 'mango salsa' to itemIngredients array
addToHappyHour() - sets happyHourDiscount to true
makeUnavailable() - sets available to false
