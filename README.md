# saman Fifa

Documentación de la API de Saman Fifa:

{
    "teams":[
    {
        "name": String,
        "stadium": {
            "name": String,
            "map": {
                "general": [int,int] # Representa fila y columna,
                "vip": [int,int]
            }
        },
        "lineup": [
            {
                "name": String,
                "number": int,
                "position": String
            },
        ],
     "referees": [String],
     "restaurant":[
            {
              "name": String,
              "price": Float,
              "quantity": int # inventario,
              "type": "c" or "b" # c=comida or b=bebida ,
              "packing": Bool # True es de empaque, False es de preparacion,
            }
       ]
   }
   
}
