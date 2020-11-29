# VS CODE Bootstrap custom snippets 
![Preview](https://github.com/AvgustPol/vs-code-snippets/blob/master/VS%20CODE%20bootstrap%20snippet.gif?raw=true)

Custom created snippets for work with bootstrap to improve development speed.
Author: Anton Vlasiuk - bootstrap VS CODE
Follow me: https://www.linkedin.com/in/vlasiuk-anton/

Snippets
Below is a list of all available snippets and the triggers of each one. The ⇥ means the TAB key.


| Trigger       | Content           
| ------------- |:-------------:|
| cont  ⇥     | [ Bootstrap ] Create div with **"container"** class" |
| row  ⇥    | [ Bootstrap ] Create div with **"row"** class" |
| col  ⇥ | [ Bootstrap ] Create div with **"col"** class"      |


```javascript
{
  	"[ Bootstrap ] Create div with container class" {
		"prefix": "cont",
		"body": [
			"<div className=\"container\">",
			"\t$0",
			"</div>"
			
		],
		"description": "Create container div "
	},
	"[ Bootstrap ] Create div with row class": {
		"prefix": "row",
		"body": [
			"<div className=\"row\">",
			"\t$0",
			"</div>"
			
		],
		"description": "Create row div "
	},
	"[ Bootstrap ] Create div with col class": {
		"prefix": "col",
		"body": [
			"<div className=\"col\">",
			"\t$0",
			"</div>"
			
		],
		"description": "Create col div "
	}
}
```

