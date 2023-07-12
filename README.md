## Deploy JSON Server to Vercel

A template to deploy [JSON Server](https://github.com/typicode/json-server) to [Vercel](https://vercel.com), allow you to run fake REST API online!

Demo from this repository: 

1. https://json-server-in.vercel.app
2. https://json-server-in.vercel.app/api/posts

### How to use

1. Click "**Use this template**" or clone this repository.
2. Update or use the default [`db.json`](./db.json) in the repository.
3. Sign Up or login into [Vercel](https://vercel.com).
4. From the Vercel dashboard, click "**+ New Project**" then "**Import**" your repository.
5. In the "**Configure Project**" screen, leave everything default and click "**Deploy**".
6. Wait until deployment is done, and your own JSON server is ready to serve!

## Default `db.json`

```json
{
  "posts": [
    { "id": 1, "title": "json-server", "author": "typicode" }
  ],
  "comments": [
    { "id": 1, "body": "some comment", "postId": 1 }
  ],
  "profile": { "name": "typicode" }
}
```

## Modificada `db.json`

```json
{
"cell_phones":[
		{
			"id": 1,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55058201/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Câmera Tripla Traseira, Tela Infinita de 6.6 90Hz",
					"model": "Galaxy A14 5G",
					"back_camera": "3 Câmeras",
					"front_camera": "Selfie de 13MP",
					"color": "Preto",
					"ram": "128GB, 4GB",
					"processor": "Octa-Core",
					"price": "R$ 1.159,00"
				}
			]
		},
		{
			"id": 2,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55058955/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Câmera Tripla Traseira, Tela Infinita de 6.4 120Hz",
					"model": "Galaxy A54 5G",
					"back_camera": "3 Câmeras",
					"front_camera": "Selfie de 32MP",
					"color": "Preto",
					"ram": "128GB, 8GB",
					"processor": "Octa-Core",
					"price": "R$ 1.799,00"
				}
			]
		},
		{
			"id": 3,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55058956/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Câmera Tripla Traseira, Tela Infinita de 6.4 90Hz",
					"model": "Galaxy A14 5G",
					"back_camera": "3 Câmeras",
					"front_camera": "Selfie de 32MP",
					"color": "Branco",
					"ram": "128GB, 4GB",
					"processor": "Octa-Core",
					"price": "R$ 1.799,00 "
				}
			]
		},
		{
			"id": 4,
			"name": "Smartphone Motorola",
			"image": "https://imgs.pontofrio.com.br/55052020/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Câmera Traseira Tripla, Android 12 Tela de 6.4",
					"model": "Moto G42",
					"back_camera": "3 Câmeras",
					"front_camera": "Selfie de 13MP",
					"color": "Azul",
					"ram": "128GB, 4GB",
					"processor": "Octa Core Snapdragon 680",
					"price": "R$ 999,00"
				}
			]
		},
		{
			"id": 5,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55049132/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Tela Infinita de 6.5”, Câmera Traseira Tripla, Android 12",
					"model": "Galaxy S20 FE 5G",
					"back_camera": "3 Câmeras",
					"front_camera": "Selfie 32MP",
					"color": "Azul",
					"ram": "128GB, 6GB",
					"processor": "Snapdragon 865",
					"price": "R$ 2.116,58"
				}
			]
		},
		{
			"id": 6,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55052133/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Tela Infinita de 6.5",
					"model": "Galaxy A03",
					"back_camera": "Câmera Traseira de 8MP",
					"front_camera": "Selfie de 5MP",
					"color": "Preto",
					"ram": "32GB, 2GB",
					"processor": "Octa Core",
					"price": "R$ 599,00"
				}
			]
		},
		{
			"id": 7,
			"name": "Smartphone Motorola",
			"image": "https://imgs.pontofrio.com.br/55038795/1xg.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Tela de 6.4”, Câmera Traseira Tripla, Android 11",
					"model": "Moto G31",
					"back_camera": "3 Câmeras",
					"front_camera": "Selfie de 50MP",
					"color": "Grafite",
					"ram": "128GB, 4GB",
					"processor": "Helio G85 Octa-Core",
					"price": "R$ 999,00"
				}
			]
		},
		{
			"id": 8,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55058962/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Câmera Tripla Traseira, Tela Infinita de 6.6 120Hz",
					"model": "Galaxy A34 5G",
					"back_camera": "3 Câmeras",
					"front_camera": "Selfie de 13MP",
					"color": "Violeta",
					"ram": "128GB, 6GB",
					"processor": "Octa-Core",
					"price": "R$ 1.599,00"
				}
			]
		},
		{
			"id": 9,
			"name": "Smartphone Motorola",
			"image": "https://imgs.pontofrio.com.br/55053243/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Câmera Traseira Dupla, Android 12",
					"model": "Moto E22",
					"back_camera": "2 Câmeras",
					"front_camera": "selfie 16 MP",
					"color": "Branco",
					"ram": "32GB, 2GB",
					"processor": "Octa Core",
					"price": "R$ 650,07"
				}
			]
		},
		{
			"id": 10,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55056943/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Câmera Traseira Dupla, Bateria de 5000mAh, Tela de 6.5, Dual Chip",
					"model": "Galaxy A04e",
					"back_camera": "2 Câmeras",
					"front_camera": "",
					"color": "Cobre",
					"ram": "64GB, 3GB",
					"processor": "Octa-Core",
					"price": "R$ 699,00"
				}
			]
		},
		{
			"id": 11,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55052385/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "ela Infinita de 6.7",
					"model": "Galaxy M53 5G",
					"back_camera": "Câmera Quádrupla",
					"front_camera": "Selfie de 32MP",
					"color": "Marrom",
					"ram": "128GB, 8GB",
					"processor": "Octa-Core",
					"price": "R$ 1.799,10"
				}
			]
		},
		{
			"id": 12,
			"name": "Smartphone Motorola",
			"image": "https://imgs.pontofrio.com.br/55053233/1g.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Tela de 6.3 Android 12",
					"model": "Edge 30 Neo 5G",
					"back_camera": "Câmera Dupla",
					"front_camera": "",
					"color": "Very Peri",
					"ram": "256GB 8GB",
					"processor": "Snapdragon 695",
					"price": "R$ 1.899,00"
				}
			]
		},
		{
			"id": 13,
			"name": "Smartphone Samsung",
			"image": "https://imgs.pontofrio.com.br/55041369/1xg.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Tela Infinita de 6.8, Android 12",
					"model": "Galaxy S22 Ultra 5G",
					"back_camera": "Câmera Quádrupla",
					"front_camera": "Selfie 40MP",
					"color": "Preto",
					"ram": "128GB, 4GB",
					"processor": "Snapdragon 8 Gen 1",
					"price": "R$ 4.769,10"
				}
			]
		},
		{
			"id": 14,
			"name": "",
			"image": "https://imgs.pontofrio.com.br/55038797/1xg.jpg?imwidth=292",
			"datasheet":[
				{
					"id": 1,
					"description": "Tela de 6.8 Android 11",
					"model": "Moto G200 5G",
					"back_camera": "Câmera Tripla",
					"front_camera": "Selfie 16MP",
					"color": "Azul",
					"ram": "128GB, 4GB",
					"processor": "Snapdragon 888 Octa-Core",
					"price": "R$ 2.899,00"
				}
			]
		}
	]
}
```

## Reference

#### GitHub JSON-SERVER
1. https://github.com/typicode/json-server

#### SITE PARA DEPLOY
2. https://vercel.com


