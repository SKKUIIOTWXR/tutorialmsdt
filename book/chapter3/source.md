>{

    "@id": "dtmi:com:contoso:room;1",

    "@type": "Interface",

    "displayName": "Room",

    "contents": [

        {

            "@type": "Telemetry",

            "name": "temperature",

            "schema": "double"

        },       

        {

            "@type": "Telemetry",

            "name": "lights",

            "schema": "boolean"

        },       {

            "@type": "Telemetry",

            "name": "hasmovement",

            "schema": "boolean"

        },

        {

            "@type": "Property",

            "name": "setlight",

            "writable": true,

            "schema": "boolean"

        }

    ],

    "@context": "dtmi:dtdl:context;2"

}   

> {
    "@id": "dtmi:com:contoso:door;1",
    "@type": "Interface",
    "displayName": "Door",
    "@context": "dtmi:dtdl:context;2"
}

> 