# POST
    https://sockets.asisteclick.com/bot/extensions/aaaaa

# Headers

# Autorización

# Request

    Request for body:
        {
        "data": {
            "timezone": "{{time_zone}}",
            "business_hours": "08:00-12:00,13:00-19:00 08:00-12:00,13:00-19:00 08:00-12:00,13:00-19:00 08:00-12:00,13:00-19:00 08:00-12:00,13:00-19:00 closed closed"
        },
        "pipelines": [
            {
            "pattern": "IS-BUSINESS-HOURS"
            }
        ]
        }

# Mapeo de la respuesta

    {{hours_value}}=in_business_hour