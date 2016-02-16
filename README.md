#Parkitect Custom Shops Template

##Sample Json

```json
{
	"cube" : {
		"model":"model1",
		"price": 20.5,
		"products": {
			"A": {
				"model":"model2",
				"price": 20.5,
				"type" : "wearable",
				"bodylocation" : "head",
				"hideonrides" : false,
				"hidehair" : true,
				"ingridents": {
					"ingredient2" :{
					 "price": 1.0,
					 "amount" : 10.0,
					 "tweakable" : false
					},
					"ingredient1" :{
					 "price": 1.0,
					 "amount" : 1.0,
					 "tweakable" : true
					}
				}
			},
			"B": {
				"model":"model3",
				"price": 20.5,
				"type" : "consumable",
				"temprature" : "hot",
				"consumeanimation" : "generic", 
				"portions" : 10,
				"effects": [
					{
						"affectStat" : "hunger",
						"amount" : 0.4
					}
				],
				"ingridents": {
					"ingredient1" :{
					 "price": 1.0,
					 "amount" : 1.0,
					"tweakable" : false
					}
				}
			}
		}
	}
}
```

##Wearable Products

bodylocation: head/face/back

##Consumable Products

consumeanimation : generic/drink_straw/lick/with_hands

temprature: none/cold/hot

affectStat: hunger/thirst /happiness/tiredness/sugerboost


