# IOT-Univalle-2025
Proyectos hechos en iot 2025 univalle tercer semestre
❌ Recepcion de video desde una camara Ip en Node-red grupo B
    Vence el 2 de abril de 2025 22:1 Se cierra el 2 de abril de 2025 22:15
    Instrucciones
    Configurar nodos en la infraestructura Iot para recibir video desde una camara Ip
    Enviar las imagenes a telegram
    Capturas de pantalla que evidencien el funcionamiento
✅ INFRAESTRUCTURA IOT - FIREBASE - WEB
✅ ESP32-MQTT-NODE-RED-TELEGRAM
✅ TELEGRAM - CAMARA GRUPO B
✅ Envio de datos via un sms desde la infraestructura Iot grupo B
Instrucciones
Configurar nodos para simular datos de sensores de temperatura y humedad, solo se genera el dato cuando se injecta la solicitud, se muestra el dato en el dasboard.
Configurar twilio desde su pagina oficial.
Enviar el dato de temperatura y humedad al ddispositivo movil configurado en twilio
capturas de pantalla de la interfaz grafica en node-red, de la configuracion de twilio que evidencie el numero de celular del estudiante y una captura del mensaje en el dispositivo movil
❌ Laboratorio 1 grupo B

-- CODIGO COMPLETO HASTA AHORA

[
    {
        "id": "33d47bcfb2dc80fe",
        "type": "tab",
        "label": "Telegram",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "e3a5f26415482c1f",
        "type": "tab",
        "label": "Flow 2",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "e753a5a3d4255523",
        "type": "tab",
        "label": "Flow 1",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "8a06ab2c7a2d6c48",
        "type": "tab",
        "label": "TWILIO",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "449b8b755fa52a13",
        "type": "tab",
        "label": "Flow 1",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "da3341ce70c0a11c",
        "type": "tab",
        "label": "Flow 4",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "122ba55f1f40dd1c",
        "type": "tab",
        "label": "Flow 1",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "fa070e5a50702e44",
        "type": "tab",
        "label": "Flow 1",
        "disabled": true,
        "info": ""
    },
    {
        "id": "d44832a3560ad5ce",
        "type": "tab",
        "label": "Telegram T/M",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "900f939f0d0d9da2",
        "type": "tab",
        "label": "Flow 3",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "c89345ecddbf181e",
        "type": "tab",
        "label": "MQTT",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "38bf26e98cb97eac",
        "type": "tab",
        "label": "FIREBASE",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "0e08f5c08fd80381",
        "type": "tab",
        "label": "Flow 5",
        "disabled": true,
        "info": "",
        "env": []
    },
    {
        "id": "2415bc24a6e52d63",
        "type": "tab",
        "label": "Flow 6",
        "disabled": false,
        "info": "",
        "env": []
    },
    {
        "id": "a32b84d65eaae1ae",
        "type": "group",
        "z": "c89345ecddbf181e",
        "style": {
            "stroke": "#999999",
            "stroke-opacity": "1",
            "fill": "none",
            "fill-opacity": "1",
            "label": true,
            "label-position": "nw",
            "color": "#a4a4a4"
        },
        "nodes": [
            "2777ba40ad2619da",
            "e345924d3ee8f328"
        ],
        "x": 34,
        "y": 439,
        "w": 192,
        "h": 122
    },
    {
        "id": "b9afc84572988ecb",
        "type": "ui_base",
        "theme": {
            "name": "theme-light",
            "lightTheme": {
                "default": "#0094CE",
                "baseColor": "#0094CE",
                "baseFont": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif",
                "edited": true,
                "reset": false
            },
            "darkTheme": {
                "default": "#097479",
                "baseColor": "#097479",
                "baseFont": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif",
                "edited": false
            },
            "customTheme": {
                "name": "Untitled Theme 1",
                "default": "#4B7930",
                "baseColor": "#4B7930",
                "baseFont": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif"
            },
            "themeState": {
                "base-color": {
                    "default": "#0094CE",
                    "value": "#0094CE",
                    "edited": false
                },
                "page-titlebar-backgroundColor": {
                    "value": "#0094CE",
                    "edited": false
                },
                "page-backgroundColor": {
                    "value": "#fafafa",
                    "edited": false
                },
                "page-sidebar-backgroundColor": {
                    "value": "#ffffff",
                    "edited": false
                },
                "group-textColor": {
                    "value": "#1bbfff",
                    "edited": false
                },
                "group-borderColor": {
                    "value": "#ffffff",
                    "edited": false
                },
                "group-backgroundColor": {
                    "value": "#ffffff",
                    "edited": false
                },
                "widget-textColor": {
                    "value": "#111111",
                    "edited": false
                },
                "widget-backgroundColor": {
                    "value": "#0094ce",
                    "edited": false
                },
                "widget-borderColor": {
                    "value": "#ffffff",
                    "edited": false
                },
                "base-font": {
                    "value": "-apple-system,BlinkMacSystemFont,Segoe UI,Roboto,Oxygen-Sans,Ubuntu,Cantarell,Helvetica Neue,sans-serif"
                }
            },
            "angularTheme": {
                "primary": "indigo",
                "accents": "blue",
                "warn": "red",
                "background": "grey",
                "palette": "light"
            }
        },
        "site": {
            "name": "Node-RED Dashboard",
            "hideToolbar": "false",
            "allowSwipe": "false",
            "lockMenu": "false",
            "allowTempTheme": "true",
            "dateFormat": "DD/MM/YYYY",
            "sizes": {
                "sx": 48,
                "sy": 48,
                "gx": 6,
                "gy": 6,
                "cx": 6,
                "cy": 6,
                "px": 0,
                "py": 0
            }
        }
    },
    {
        "id": "863c6dd9fcc773b4",
        "type": "ui_tab",
        "name": "Home",
        "icon": "dashboard",
        "order": 3,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "2c9b8accf5012abf",
        "type": "ui_group",
        "d": true,
        "name": "Group 1",
        "tab": "",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "d8647e528ed5a178",
        "type": "ui_group",
        "name": "IOTTemperatura",
        "tab": "863c6dd9fcc773b4",
        "order": 2,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "135e084d9a11625c",
        "type": "ui_group",
        "name": "Group 3",
        "tab": "",
        "order": 3,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "ab4f39419f88c164",
        "type": "ui_group",
        "name": "Group 4",
        "tab": "",
        "order": 4,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "4a1984f00c1a7dac",
        "type": "ui_group",
        "name": "Group 5",
        "tab": "",
        "order": 5,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "43ee07eff43ebb02",
        "type": "ui_group",
        "name": "Group 6",
        "tab": "",
        "order": 6,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "de3c0d807cab7fad",
        "type": "ui_group",
        "name": "Group 7",
        "tab": "",
        "order": 7,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "137d8ad1153bf0c6",
        "type": "ui_group",
        "name": "Group 8",
        "tab": "",
        "order": 8,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "77377857764c8927",
        "type": "ui_group",
        "name": "Group 9",
        "tab": "",
        "order": 9,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "d9a5ed1ed81ab2e6",
        "type": "ui_group",
        "name": "OITTemperatura",
        "tab": "",
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "b9a36a6128ee7248",
        "type": "ui_group",
        "name": "Group 10",
        "tab": "",
        "order": 10,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "b5cad99d37820136",
        "type": "ttsultimate-config",
        "name": "TTS Service",
        "noderedipaddress": "AUTODISCOVER",
        "noderedport": "1980",
        "purgediratrestart": "purge",
        "ttsservice": "googletranslate",
        "TTSRootFolderPath": ""
    },
    {
        "id": "20409a816ae0314a",
        "type": "ttsultimate-config",
        "name": "TTS Service",
        "noderedipaddress": "AUTODISCOVER",
        "noderedport": "1980",
        "purgediratrestart": "purge",
        "ttsservice": "googletranslate",
        "TTSRootFolderPath": ""
    },
    {
        "id": "0a5fa677b12b2b75",
        "type": "ui_tab",
        "name": "Home",
        "icon": "dashboard",
        "order": 4,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "6d71d57574986794",
        "type": "ui_group",
        "d": true,
        "name": "Group 1",
        "tab": "",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "9b68537c8eccded8",
        "type": "ui_group",
        "name": "IOTTemperatura",
        "tab": "0a5fa677b12b2b75",
        "order": 2,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "a269c37ba02f4aa5",
        "type": "ui_group",
        "name": "Group 3",
        "tab": "",
        "order": 3,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "16a51de7e14ccc16",
        "type": "ui_group",
        "name": "Group 4",
        "tab": "",
        "order": 4,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "e4e2607ef93175d5",
        "type": "ui_group",
        "name": "Group 5",
        "tab": "",
        "order": 5,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "d311758af537c8a8",
        "type": "ui_group",
        "name": "Group 6",
        "tab": "",
        "order": 6,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "b2854f13bde57b26",
        "type": "ui_group",
        "name": "Group 7",
        "tab": "",
        "order": 7,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "0d8e71a4ba8d2810",
        "type": "ui_group",
        "name": "Group 8",
        "tab": "",
        "order": 8,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "627d115a7e0f3d3f",
        "type": "ui_group",
        "name": "Group 9",
        "tab": "",
        "order": 9,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "c93eaf83b711e67b",
        "type": "ui_group",
        "name": "OITTemperatura",
        "tab": "",
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "6eaab6fbb62c73df",
        "type": "ui_group",
        "name": "Group 10",
        "tab": "",
        "order": 10,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "fd84f50a7453aa0d",
        "type": "ttsultimate-config",
        "name": "TTS Service",
        "noderedipaddress": "AUTODISCOVER",
        "noderedport": "1980",
        "purgediratrestart": "purge",
        "ttsservice": "googletranslate",
        "TTSRootFolderPath": ""
    },
    {
        "id": "6c7d0c0355c32ded",
        "type": "ttsultimate-config",
        "name": "TTS Service",
        "noderedipaddress": "AUTODISCOVER",
        "noderedport": "1980",
        "purgediratrestart": "purge",
        "ttsservice": "googletranslate",
        "TTSRootFolderPath": ""
    },
    {
        "id": "64b71ebc8fe73466",
        "type": "ui_group",
        "name": "Default",
        "tab": "",
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "bb1d77cbccfed328",
        "type": "ui_tab",
        "name": "Home",
        "icon": "dashboard",
        "order": 5,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "58cfe9fca0315246",
        "type": "ui_group",
        "name": "IOTVALTemperatura24",
        "tab": "bb1d77cbccfed328",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "5cda015f9b85189e",
        "type": "twilio-api",
        "name": "Rafanum",
        "sid": "AC3bf6771f652bb695eb451812435e4fd2",
        "from": "+13023032693"
    },
    {
        "id": "c0bead7296cd5eb1",
        "type": "ui_group",
        "name": "Default",
        "tab": "",
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "5bf15c3466e58fc9",
        "type": "serial-port",
        "name": "",
        "serialport": "COM3",
        "serialbaud": "9600",
        "databits": 8,
        "parity": "none",
        "stopbits": 1,
        "waitfor": "",
        "dtr": "none",
        "rts": "none",
        "cts": "none",
        "dsr": "none",
        "newline": "\\n",
        "bin": "false",
        "out": "char",
        "addchar": "\\n",
        "responsetimeout": 10000
    },
    {
        "id": "41108b2e8460d007",
        "type": "ui_tab",
        "name": "Home",
        "icon": "dashboard",
        "order": 6,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "3bc713571948a486",
        "type": "ui_group",
        "name": "IOTVALTemperatura24",
        "tab": "41108b2e8460d007",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "2966ee4b0bca1171",
        "type": "ui_group",
        "name": "Default",
        "tab": "",
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "8c8a16623754ee27",
        "type": "serial-port",
        "name": "",
        "serialport": "COM3",
        "serialbaud": "9600",
        "databits": 8,
        "parity": "none",
        "stopbits": 1,
        "waitfor": "",
        "dtr": "none",
        "rts": "none",
        "cts": "none",
        "dsr": "none",
        "newline": "\\n",
        "bin": "false",
        "out": "char",
        "addchar": "\\n",
        "responsetimeout": 10000
    },
    {
        "id": "6c88e220e32215bd",
        "type": "ui_tab",
        "name": "Home",
        "icon": "dashboard",
        "order": 7,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "9be1e963857e6c23",
        "type": "ui_group",
        "name": "IOTVALTemperatura24",
        "tab": "6c88e220e32215bd",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "3ef6d052beb962b9",
        "type": "telegram bot",
        "botname": "Rafa_iot_bot",
        "usernames": "",
        "chatids": "",
        "baseapiurl": "",
        "testenvironment": false,
        "updatemode": "polling",
        "pollinterval": 300,
        "usesocks": false,
        "sockshost": "",
        "socksprotocol": "socks5",
        "socksport": 6667,
        "socksusername": "anonymous",
        "sockspassword": "",
        "bothost": "",
        "botpath": "",
        "localbothost": "0.0.0.0",
        "localbotport": 8443,
        "publicbotport": 8443,
        "privatekey": "",
        "certificate": "",
        "useselfsignedcertificate": false,
        "sslterminated": false,
        "verboselogging": false
    },
    {
        "id": "7157127c01ad1549",
        "type": "ui_tab",
        "name": "TM",
        "icon": "dashboard",
        "order": 8,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "bed9a22cd1d142b8",
        "type": "ui_group",
        "name": "Hum/Temperatura",
        "tab": "7157127c01ad1549",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "1f28c87104a8cd3f",
        "type": "mqtt-broker",
        "name": "IOTRafa",
        "broker": "broker.emqx.io",
        "port": 1883,
        "clientid": "",
        "autoConnect": true,
        "usetls": false,
        "protocolVersion": 4,
        "keepalive": 60,
        "cleansession": true,
        "autoUnsubscribe": true,
        "birthTopic": "",
        "birthQos": "0",
        "birthRetain": "false",
        "birthPayload": "",
        "birthMsg": {},
        "closeTopic": "",
        "closeQos": "0",
        "closeRetain": "false",
        "closePayload": "",
        "closeMsg": {},
        "willTopic": "",
        "willQos": "0",
        "willRetain": "false",
        "willPayload": "",
        "willMsg": {},
        "userProps": "",
        "sessionExpiry": ""
    },
    {
        "id": "2e46ae8146ef13f9",
        "type": "ui_tab",
        "name": "MQTT",
        "icon": "dashboard",
        "order": 2,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "3ce8278568b35a57",
        "type": "ui_group",
        "name": "MQTT",
        "tab": "2e46ae8146ef13f9",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "ec05f7e6242e7de5",
        "type": "firebase config",
        "firebaseurl": "proyectoiot-df109-default-rtdb",
        "loginType": "none"
    },
    {
        "id": "eea6c2cb51089223",
        "type": "ui_tab",
        "name": "Firebase",
        "icon": "dashboard",
        "order": 9,
        "disabled": true,
        "hidden": true
    },
    {
        "id": "2e4fde67c6424d50",
        "type": "ui_group",
        "name": "Firebase",
        "tab": "eea6c2cb51089223",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "2996560e0e73505f",
        "type": "firebase config",
        "firebaseurl": "proyectoiot-df109-default-rtdb",
        "loginType": "none"
    },
    {
        "id": "2c125d4d326da34f",
        "type": "firebase config",
        "firebaseurl": "proyectoiot-df109-default-rtdb",
        "loginType": "none"
    },
    {
        "id": "b5d48302b30b82cf",
        "type": "firebase config",
        "firebaseurl": "proyectoiot-df109-default-rtdb",
        "loginType": "none"
    },
    {
        "id": "bdebdcffd901a4e5",
        "type": "ui_tab",
        "name": "ApiTemp",
        "icon": "dashboard",
        "order": 1,
        "disabled": false,
        "hidden": false
    },
    {
        "id": "2674e269c51c343f",
        "type": "ui_group",
        "name": "TemperaturaApi",
        "tab": "bdebdcffd901a4e5",
        "order": 1,
        "disp": true,
        "width": 6,
        "collapse": false,
        "className": ""
    },
    {
        "id": "a5bd99d91b026c58",
        "type": "ui_group",
        "name": "Group 2",
        "tab": "bb1d77cbccfed328",
        "order": 2,
        "disp": true,
        "width": 6
    },
    {
        "id": "2149f5f6e2cbae87",
        "type": "telegram receiver",
        "z": "33d47bcfb2dc80fe",
        "name": "Recepcion mensajes",
        "bot": "",
        "saveDataDir": "",
        "filterCommands": false,
        "x": 130,
        "y": 120,
        "wires": [
            [
                "736a64baaf5526ec"
            ],
            []
        ]
    },
    {
        "id": "736a64baaf5526ec",
        "type": "debug",
        "z": "33d47bcfb2dc80fe",
        "name": "debug 2",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 200,
        "y": 220,
        "wires": []
    },
    {
        "id": "Switch",
        "type": "switch",
        "z": "33d47bcfb2dc80fe",
        "name": "Filtro de comandos",
        "property": "payload.content",
        "rules": [
            {
                "t": "eq",
                "v": "temp"
            },
            {
                "t": "eq",
                "v": "hum"
            }
        ],
        "outputs": 2,
        "x": 150,
        "y": 340,
        "wires": [
            [
                "GenerarTemp"
            ],
            [
                "GenerarHum"
            ]
        ]
    },
    {
        "id": "GenerarTemp",
        "type": "function",
        "z": "33d47bcfb2dc80fe",
        "name": "Generar Temperatura",
        "func": "msg.temperatura = Math.floor(Math.random() * 60);\nmsg.payload = `La temperatura actual es ${msg.temperatura}°C`;\nreturn msg;",
        "outputs": 1,
        "x": 380,
        "y": 280,
        "wires": [
            [
                "TelegramSender",
                "EvaluarAlerta"
            ]
        ]
    },
    {
        "id": "GenerarHum",
        "type": "function",
        "z": "33d47bcfb2dc80fe",
        "name": "Generar Humedad",
        "func": "msg.humedad = Math.floor(Math.random() * 100);\nmsg.payload = `La humedad actual es ${msg.humedad}%`;\nreturn msg;",
        "outputs": 1,
        "x": 370,
        "y": 420,
        "wires": [
            [
                "TelegramSender"
            ]
        ]
    },
    {
        "id": "EvaluarAlerta",
        "type": "function",
        "z": "33d47bcfb2dc80fe",
        "name": "Alerta de Voz",
        "func": "if (msg.temperatura > 40 && msg.humedad > 50) {\n    msg.payload = \"¡Alerta! Hace mucho calor y la humedad es alta.\";\n    return msg;\n}\nreturn null;",
        "outputs": 1,
        "x": 570,
        "y": 220,
        "wires": [
            [
                "TTSUltimate"
            ]
        ]
    },
    {
        "id": "TTSUltimate",
        "type": "ttsultimate",
        "z": "33d47bcfb2dc80fe",
        "name": "Conversión a voz",
        "voice": "es-ES-Standard-A",
        "x": 790,
        "y": 220,
        "wires": [
            [
                "TelegramSender"
            ],
            []
        ]
    },
    {
        "id": "TelegramSender",
        "type": "telegram sender",
        "z": "33d47bcfb2dc80fe",
        "name": "Enviar mensaje",
        "bot": "",
        "haserroroutput": false,
        "outputs": 1,
        "x": 680,
        "y": 320,
        "wires": [
            []
        ]
    },
    {
        "id": "38c7b1e9ba78e4e1",
        "type": "inject",
        "z": "e3a5f26415482c1f",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 100,
        "y": 180,
        "wires": [
            [
                "c47178f6e94ae4aa",
                "17f05076f706e60c"
            ]
        ]
    },
    {
        "id": "c47178f6e94ae4aa",
        "type": "random",
        "z": "e3a5f26415482c1f",
        "name": "",
        "low": 1,
        "high": 10,
        "inte": "true",
        "property": "payload",
        "x": 260,
        "y": 120,
        "wires": [
            []
        ]
    },
    {
        "id": "17f05076f706e60c",
        "type": "random",
        "z": "e3a5f26415482c1f",
        "name": "",
        "low": 1,
        "high": 10,
        "inte": "true",
        "property": "payload",
        "x": 260,
        "y": 220,
        "wires": [
            []
        ]
    },
    {
        "id": "344609a280702409",
        "type": "trigger",
        "z": "e3a5f26415482c1f",
        "name": "",
        "op1": "1",
        "op2": "0",
        "op1type": "val",
        "op2type": "val",
        "duration": "250",
        "extend": "false",
        "overrideDelay": "false",
        "units": "ms",
        "reset": "",
        "bytopic": "all",
        "topic": "topic",
        "outputs": 1,
        "x": 80,
        "y": 340,
        "wires": [
            [
                "80ec43fbe5591506"
            ]
        ]
    },
    {
        "id": "80ec43fbe5591506",
        "type": "json",
        "z": "e3a5f26415482c1f",
        "name": "",
        "property": "payload",
        "action": "",
        "pretty": false,
        "x": 290,
        "y": 340,
        "wires": [
            [
                "21e1fc34cf1e9cad",
                "1e11feca5ca73213",
                "50eebb28dfd9541f"
            ]
        ]
    },
    {
        "id": "1e11feca5ca73213",
        "type": "function",
        "z": "e3a5f26415482c1f",
        "name": "function 1",
        "func": "\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 480,
        "y": 280,
        "wires": [
            [
                "e740db2331401962",
                "d3970cea090f4190",
                "f94f3b7c4df09a93"
            ]
        ]
    },
    {
        "id": "50eebb28dfd9541f",
        "type": "function",
        "z": "e3a5f26415482c1f",
        "name": "function 2",
        "func": "\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 480,
        "y": 360,
        "wires": [
            []
        ]
    },
    {
        "id": "f94f3b7c4df09a93",
        "type": "function",
        "z": "e3a5f26415482c1f",
        "name": "function 5",
        "func": "\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 640,
        "y": 320,
        "wires": [
            [
                "b00549ddb8e7907f",
                "db8d228844169e90"
            ]
        ]
    },
    {
        "id": "21e1fc34cf1e9cad",
        "type": "debug",
        "z": "e3a5f26415482c1f",
        "name": "debug 1",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 480,
        "y": 200,
        "wires": []
    },
    {
        "id": "e740db2331401962",
        "type": "ui_gauge",
        "z": "e3a5f26415482c1f",
        "name": "",
        "group": "d8647e528ed5a178",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "donut",
        "title": "TEMPERATURA",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "50",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 810,
        "y": 180,
        "wires": []
    },
    {
        "id": "d3970cea090f4190",
        "type": "ui_text",
        "z": "e3a5f26415482c1f",
        "group": "d8647e528ed5a178",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Temperatura",
        "format": "{{msg.payload}} grados centrigados",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 790,
        "y": 240,
        "wires": []
    },
    {
        "id": "b00549ddb8e7907f",
        "type": "ui_text",
        "z": "e3a5f26415482c1f",
        "group": "d8647e528ed5a178",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "clima",
        "format": "{{msg.payload}} grados centrigados",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 790,
        "y": 300,
        "wires": []
    },
    {
        "id": "db8d228844169e90",
        "type": "ui_audio",
        "z": "e3a5f26415482c1f",
        "name": "",
        "voice": "",
        "always": "",
        "x": 820,
        "y": 360,
        "wires": []
    },
    {
        "id": "12300d9debed158e",
        "type": "inject",
        "z": "e753a5a3d4255523",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "1",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 130,
        "y": 160,
        "wires": [
            [
                "04dd3d4fcd20855b",
                "a2e6d3a36a54b135"
            ]
        ]
    },
    {
        "id": "04dd3d4fcd20855b",
        "type": "random",
        "z": "e753a5a3d4255523",
        "name": "TEMPERATURA",
        "low": "0",
        "high": "50",
        "inte": "true",
        "property": "payload",
        "x": 390,
        "y": 80,
        "wires": [
            []
        ]
    },
    {
        "id": "a2e6d3a36a54b135",
        "type": "random",
        "z": "e753a5a3d4255523",
        "name": "HUMEDAD",
        "low": 1,
        "high": "100",
        "inte": "true",
        "property": "payload",
        "x": 350,
        "y": 240,
        "wires": [
            []
        ]
    },
    {
        "id": "11729e8ef06110d1",
        "type": "ui_gauge",
        "z": "e753a5a3d4255523",
        "name": "Temp",
        "group": "58cfe9fca0315246",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "donut",
        "title": "HUMEDAD",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 910,
        "y": 520,
        "wires": []
    },
    {
        "id": "7340384115304846",
        "type": "ui_gauge",
        "z": "e753a5a3d4255523",
        "name": "",
        "group": "58cfe9fca0315246",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "HUMEDAD",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 870,
        "y": 320,
        "wires": []
    },
    {
        "id": "d78330884b7cbbd2",
        "type": "ui_text",
        "z": "e753a5a3d4255523",
        "group": "64b71ebc8fe73466",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Temperatura",
        "format": "{{msg.payload}} Grados centrigrados",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 890,
        "y": 140,
        "wires": []
    },
    {
        "id": "d8093daebfca3855",
        "type": "ui_text",
        "z": "e753a5a3d4255523",
        "group": "58cfe9fca0315246",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Humedad",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 860,
        "y": 360,
        "wires": []
    },
    {
        "id": "36b1e7a192df9c85",
        "type": "function",
        "z": "e753a5a3d4255523",
        "name": "temperatura",
        "func": "let temp = msg.payload\n\n\nif(temp>33){\n\n    msg.payload=\"TEMPERATURA ALTA\"\nreturn msg;\n\n} else{\n    msg.payload=\"\";\n    return msg\n}\n\n\n\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 630,
        "y": 200,
        "wires": [
            [
                "08432b95391f93f0",
                "ff206b96b5aef36c",
                "c2b5d055e68cd4d6"
            ]
        ]
    },
    {
        "id": "08432b95391f93f0",
        "type": "ui_text",
        "z": "e753a5a3d4255523",
        "group": "58cfe9fca0315246",
        "order": 4,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 910,
        "y": 200,
        "wires": []
    },
    {
        "id": "79fdac770f13ff99",
        "type": "function",
        "z": "e753a5a3d4255523",
        "name": "humedad",
        "func": "let temp = msg.payload\n\n\nif(temp>70){\n\n    msg.payload=\"Niveles de humedad altos\"\n    return msg;\n\n} else{\n    msg.payload=\"\"\n    return msg;\n}\n\n\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 600,
        "y": 420,
        "wires": [
            [
                "5d4c7638dc975f6f",
                "11729e8ef06110d1"
            ]
        ]
    },
    {
        "id": "5d4c7638dc975f6f",
        "type": "ui_text",
        "z": "e753a5a3d4255523",
        "group": "58cfe9fca0315246",
        "order": 5,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 850,
        "y": 460,
        "wires": []
    },
    {
        "id": "ff206b96b5aef36c",
        "type": "ui_audio",
        "z": "e753a5a3d4255523",
        "name": "",
        "group": "58cfe9fca0315246",
        "voice": "",
        "always": "",
        "x": 860,
        "y": 260,
        "wires": []
    },
    {
        "id": "be3685f496aa5767",
        "type": "ui_audio",
        "z": "e753a5a3d4255523",
        "name": "",
        "group": "58cfe9fca0315246",
        "voice": "",
        "always": "",
        "x": 720,
        "y": 520,
        "wires": []
    },
    {
        "id": "fd0fbbc0566967c9",
        "type": "telegram receiver",
        "z": "e753a5a3d4255523",
        "name": "",
        "bot": "",
        "saveDataDir": "",
        "filterCommands": false,
        "x": 230,
        "y": 540,
        "wires": [
            [
                "c01dbbfc5a412b64"
            ],
            []
        ]
    },
    {
        "id": "c01dbbfc5a412b64",
        "type": "debug",
        "z": "e753a5a3d4255523",
        "name": "debug 3",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 460,
        "y": 560,
        "wires": []
    },
    {
        "id": "973c5a66a628811a",
        "type": "inject",
        "z": "e753a5a3d4255523",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 100,
        "y": 680,
        "wires": [
            [
                "98b9b18fd3fff380"
            ]
        ]
    },
    {
        "id": "98b9b18fd3fff380",
        "type": "function",
        "z": "e753a5a3d4255523",
        "name": "function 6",
        "func": "\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 300,
        "y": 680,
        "wires": [
            [
                "a9b2affd88e4592e"
            ]
        ]
    },
    {
        "id": "a9b2affd88e4592e",
        "type": "telegram sender",
        "z": "e753a5a3d4255523",
        "name": "",
        "bot": "",
        "haserroroutput": false,
        "outputs": 1,
        "x": 490,
        "y": 680,
        "wires": [
            []
        ]
    },
    {
        "id": "6e28b156f5ae465b",
        "type": "serial in",
        "z": "e753a5a3d4255523",
        "name": "COM3",
        "serial": "",
        "x": 110,
        "y": 360,
        "wires": [
            [
                "77b7560ff8afc1aa"
            ]
        ]
    },
    {
        "id": "77b7560ff8afc1aa",
        "type": "debug",
        "z": "e753a5a3d4255523",
        "name": "debug 4",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 260,
        "y": 360,
        "wires": []
    },
    {
        "id": "0989c2dc6113705b",
        "type": "json",
        "z": "e753a5a3d4255523",
        "name": "",
        "property": "payload",
        "action": "",
        "pretty": false,
        "x": 470,
        "y": 320,
        "wires": [
            [
                "36b1e7a192df9c85",
                "79fdac770f13ff99"
            ]
        ]
    },
    {
        "id": "c2b5d055e68cd4d6",
        "type": "function",
        "z": "e753a5a3d4255523",
        "name": "function 7",
        "func": "\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 740,
        "y": 140,
        "wires": [
            []
        ]
    },
    {
        "id": "799e78201c3f21b7",
        "type": "inject",
        "z": "8a06ab2c7a2d6c48",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "num",
        "x": 70,
        "y": 280,
        "wires": [
            [
                "5ef5229bd9d3db7c",
                "3ef4d3bd662677df"
            ]
        ]
    },
    {
        "id": "5ef5229bd9d3db7c",
        "type": "random",
        "z": "8a06ab2c7a2d6c48",
        "name": "TEMPERATURA",
        "low": "0",
        "high": "50",
        "inte": "true",
        "property": "payload",
        "x": 230,
        "y": 180,
        "wires": [
            [
                "a41de05f1778751a"
            ]
        ]
    },
    {
        "id": "3ef4d3bd662677df",
        "type": "random",
        "z": "8a06ab2c7a2d6c48",
        "name": "HUMEDAD",
        "low": "0",
        "high": "100",
        "inte": "true",
        "property": "payload",
        "x": 210,
        "y": 360,
        "wires": [
            [
                "e56ceae6c58abc48"
            ]
        ]
    },
    {
        "id": "a41de05f1778751a",
        "type": "function",
        "z": "8a06ab2c7a2d6c48",
        "name": "MensajeTemperatura",
        "func": "let horaActual = new Date().toLocaleString();\n\nmsg.payload = \"La Temperatura es: \" + msg.payload + \"% Hora Actual es: \" + horaActual + \" JHH\";\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 460,
        "y": 180,
        "wires": [
            [
                "96a45d6c5ad595b0",
                "15d7947b27ef1263"
            ]
        ]
    },
    {
        "id": "e56ceae6c58abc48",
        "type": "function",
        "z": "8a06ab2c7a2d6c48",
        "name": "MensajeHumedad",
        "func": "let horaActual = new Date().toLocaleString();\n\nmsg.payload = \"La Humedad es: \" + msg.payload + \"% Hora Actual es: \" + horaActual + \" JHH\";\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 430,
        "y": 360,
        "wires": [
            [
                "4216094a0b2e61a1",
                "4b6bafbf09dc5e6b"
            ]
        ]
    },
    {
        "id": "96a45d6c5ad595b0",
        "type": "debug",
        "z": "8a06ab2c7a2d6c48",
        "name": "debug 1",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 700,
        "y": 180,
        "wires": []
    },
    {
        "id": "15d7947b27ef1263",
        "type": "twilio out",
        "z": "8a06ab2c7a2d6c48",
        "twilio": "5cda015f9b85189e",
        "twilioType": "sms",
        "url": "",
        "number": "+591 73785986",
        "name": "RafaNumero",
        "x": 730,
        "y": 100,
        "wires": []
    },
    {
        "id": "4216094a0b2e61a1",
        "type": "debug",
        "z": "8a06ab2c7a2d6c48",
        "name": "debug 2",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 640,
        "y": 440,
        "wires": []
    },
    {
        "id": "4b6bafbf09dc5e6b",
        "type": "twilio out",
        "z": "8a06ab2c7a2d6c48",
        "twilio": "5cda015f9b85189e",
        "twilioType": "sms",
        "url": "",
        "number": "+591 73785986",
        "name": "RafaNumero",
        "x": 650,
        "y": 320,
        "wires": []
    },
    {
        "id": "d8d8c64733580786",
        "type": "inject",
        "z": "449b8b755fa52a13",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "1",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 140,
        "y": 180,
        "wires": [
            [
                "fd6aaa76c515749e",
                "a4120d1468a05a8b"
            ]
        ]
    },
    {
        "id": "fd6aaa76c515749e",
        "type": "random",
        "z": "449b8b755fa52a13",
        "name": "HUMEDAD",
        "low": 1,
        "high": "100",
        "inte": "true",
        "property": "payload",
        "x": 330,
        "y": 180,
        "wires": [
            []
        ]
    },
    {
        "id": "1807f31c088d0e5f",
        "type": "ui_gauge",
        "z": "449b8b755fa52a13",
        "name": "Temp",
        "group": "3bc713571948a486",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "donut",
        "title": "TEMPERATURA",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 630,
        "y": 40,
        "wires": []
    },
    {
        "id": "6f70dc9ba07aed17",
        "type": "ui_gauge",
        "z": "449b8b755fa52a13",
        "name": "",
        "group": "3bc713571948a486",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "HUMEDAD",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 590,
        "y": 400,
        "wires": []
    },
    {
        "id": "053984357f68892d",
        "type": "ui_text",
        "z": "449b8b755fa52a13",
        "group": "c93eaf83b711e67b",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Temperatura",
        "format": "{{msg.payload}} Grados centrigrados",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 670,
        "y": 140,
        "wires": []
    },
    {
        "id": "c687e8e548a43533",
        "type": "ui_text",
        "z": "449b8b755fa52a13",
        "group": "3bc713571948a486",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Humedad",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 580,
        "y": 440,
        "wires": []
    },
    {
        "id": "6c1e6c03818f8cf0",
        "type": "function",
        "z": "449b8b755fa52a13",
        "name": "function 1",
        "func": "// Suponiendo que la cadena que recibimos es algo como:\n// \"Temperatura: 25 Humedad: 60\"\n\nlet datos = msg.payload;  // Los datos llegan en msg.payload como una cadena\n\n// Extraer la temperatura usando una expresión regular\nlet temperatura = datos.match(/Temperatura:\\s*(\\d+)/);  // Busca el número después de \"Temperatura:\"\n\nif (temperatura && temperatura[1]) {\n    // Almacena la temperatura en msg.payload\n    msg.payload = parseInt(temperatura[1]);\n    return msg;\n} else {\n    // Si no se encuentra la temperatura, se devuelve un mensaje de error\n    msg.payload = \"Error al extraer temperatura\";\n    return msg;\n}\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 400,
        "y": 320,
        "wires": [
            [
                "053984357f68892d",
                "1807f31c088d0e5f",
                "7af8cafdbf70908b"
            ]
        ]
    },
    {
        "id": "bec0c48469e45039",
        "type": "ui_text",
        "z": "449b8b755fa52a13",
        "group": "3bc713571948a486",
        "order": 4,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 830,
        "y": 240,
        "wires": []
    },
    {
        "id": "37514d913c632484",
        "type": "function",
        "z": "449b8b755fa52a13",
        "name": "function 2",
        "func": "// Suponiendo que la cadena que recibimos es algo como:\n// \"Temperatura: 25 Humedad: 60\"\n\nlet datos = msg.payload;  // Los datos llegan en msg.payload como una cadena\n\n// Extraer la humedad usando una expresión regular\nlet humedad = datos.match(/Humedad:\\s*(\\d+)/);  // Busca el número después de \"Humedad:\"\n\nif (humedad && humedad[1]) {\n    // Almacena la humedad en msg.payload\n    msg.payload = parseInt(humedad[1]);\n    return msg;\n} else {\n    // Si no se encuentra la humedad, se devuelve un mensaje de error\n    msg.payload = \"Error al extraer humedad\";\n    return msg;\n}\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 380,
        "y": 420,
        "wires": [
            [
                "6f70dc9ba07aed17",
                "c687e8e548a43533"
            ]
        ]
    },
    {
        "id": "1cdd4e4f417c871d",
        "type": "ui_text",
        "z": "449b8b755fa52a13",
        "group": "3bc713571948a486",
        "order": 5,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 590,
        "y": 560,
        "wires": []
    },
    {
        "id": "ebc0da330307d684",
        "type": "ui_audio",
        "z": "449b8b755fa52a13",
        "name": "",
        "group": "3bc713571948a486",
        "voice": "",
        "always": "",
        "x": 840,
        "y": 320,
        "wires": []
    },
    {
        "id": "30aa66721a4e3262",
        "type": "ui_audio",
        "z": "449b8b755fa52a13",
        "name": "",
        "group": "3bc713571948a486",
        "voice": "",
        "always": "",
        "x": 400,
        "y": 520,
        "wires": []
    },
    {
        "id": "40b930b5c304edfc",
        "type": "serial in",
        "z": "449b8b755fa52a13",
        "name": "COM3",
        "serial": "5bf15c3466e58fc9",
        "x": 70,
        "y": 360,
        "wires": [
            [
                "8f1fd196334b9d5a"
            ]
        ]
    },
    {
        "id": "f290c0cdea37d590",
        "type": "debug",
        "z": "449b8b755fa52a13",
        "name": "debug 1",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 380,
        "y": 240,
        "wires": []
    },
    {
        "id": "8f1fd196334b9d5a",
        "type": "json",
        "z": "449b8b755fa52a13",
        "name": "",
        "property": "payload",
        "action": "",
        "pretty": false,
        "x": 210,
        "y": 360,
        "wires": [
            [
                "6c1e6c03818f8cf0",
                "37514d913c632484"
            ]
        ]
    },
    {
        "id": "7af8cafdbf70908b",
        "type": "function",
        "z": "449b8b755fa52a13",
        "name": "function 3",
        "func": "let temp = msg.payload\n\n\nif (temp > 20) {\n\n    msg.payload = \"TEMPERATURA CALIDA\"\n    return msg;\n\n} else {\n    msg.payload = \"\";\n    return msg\n}\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 580,
        "y": 320,
        "wires": [
            [
                "bec0c48469e45039",
                "ebc0da330307d684"
            ]
        ]
    },
    {
        "id": "b338a1e2d502c1ee",
        "type": "function",
        "z": "449b8b755fa52a13",
        "name": "function 4",
        "func": "\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 120,
        "y": 80,
        "wires": [
            []
        ]
    },
    {
        "id": "a4120d1468a05a8b",
        "type": "random",
        "z": "449b8b755fa52a13",
        "name": "TEMPERATURA",
        "low": "0",
        "high": "50",
        "inte": "true",
        "property": "payload",
        "x": 390,
        "y": 80,
        "wires": [
            []
        ]
    },
    {
        "id": "7beeb98724a88dc9",
        "type": "telegram sender",
        "z": "da3341ce70c0a11c",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "haserroroutput": false,
        "outputs": 1,
        "x": 1090,
        "y": 240,
        "wires": [
            []
        ]
    },
    {
        "id": "b294b58ec9693d4c",
        "type": "function",
        "z": "da3341ce70c0a11c",
        "name": "function 8",
        "func": "var temperatura = global.get(\"temperatura\") || \"No disponible\";\nvar horaActual = global.get(\"tiempo\"); // Formato de hora local\n\n// Construir el mensaje para Telegram\nmsg.payload = {\n    chatId: 1561121830,  // Reemplaza con tu ID de chat\n    type: \"message\",\n    content: \"⏰ Hora: \" + horaActual + \"\\n🌡️ Temperatura actual: \" + temperatura + \"°C\"\n};\n\nreturn msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 540,
        "y": 20,
        "wires": [
            [
                "7beeb98724a88dc9",
                "06f3f594e367b705"
            ]
        ]
    },
    {
        "id": "42312e25aa8d6c8f",
        "type": "function",
        "z": "da3341ce70c0a11c",
        "name": "function 9",
        "func": "var humedad = global.get(\"humedad\") || \"No disponible\";\nvar horaActual = global.get(\"tiempo\"); // Formato de hora local\n\n// Construir el mensaje para Telegram\nmsg.payload = {\n    chatId: 1561121830,  // Reemplaza con tu ID de chat\n    type: \"message\",\n    content: \"⏰ Hora: \" + horaActual + \"\\n💧 Humedad actual: \" + humedad\n};\n\nreturn msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 540,
        "y": 460,
        "wires": [
            [
                "047477c4bb153233",
                "7beeb98724a88dc9"
            ]
        ]
    },
    {
        "id": "435e74156f3bc370",
        "type": "telegram command",
        "z": "da3341ce70c0a11c",
        "name": "",
        "command": "/temperatura",
        "description": "",
        "registercommand": false,
        "language": "",
        "scope": "default",
        "bot": "3ef6d052beb962b9",
        "strict": false,
        "hasresponse": true,
        "useregex": false,
        "removeregexcommand": false,
        "outputs": 2,
        "x": 230,
        "y": 160,
        "wires": [
            [
                "a3aaacd3658627c0",
                "b294b58ec9693d4c"
            ],
            []
        ]
    },
    {
        "id": "06f3f594e367b705",
        "type": "function",
        "z": "da3341ce70c0a11c",
        "name": "function 11",
        "func": "var temperatura = global.get(\"temperatura\")\n\nmsg.payload = temperatura;\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 570,
        "y": 140,
        "wires": [
            [
                "18ddfd936f10a9a9"
            ]
        ]
    },
    {
        "id": "e20f742ff43163bb",
        "type": "telegram command",
        "z": "da3341ce70c0a11c",
        "name": "",
        "command": "/humedad",
        "description": "",
        "registercommand": false,
        "language": "",
        "scope": "default",
        "bot": "3ef6d052beb962b9",
        "strict": false,
        "hasresponse": true,
        "useregex": false,
        "removeregexcommand": false,
        "outputs": 2,
        "x": 220,
        "y": 300,
        "wires": [
            [
                "a3aaacd3658627c0",
                "42312e25aa8d6c8f"
            ],
            []
        ]
    },
    {
        "id": "047477c4bb153233",
        "type": "function",
        "z": "da3341ce70c0a11c",
        "name": "function 12",
        "func": "var humedad = global.get(\"humedad\")\n\nmsg.payload = humedad;\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 590,
        "y": 320,
        "wires": [
            [
                "3d04e990085cf5be"
            ]
        ]
    },
    {
        "id": "a3aaacd3658627c0",
        "type": "function",
        "z": "da3341ce70c0a11c",
        "name": "function 10",
        "func": "// Generar valores aleatorios\nvar temperatura = (Math.random() * (35 - 15) + 15).toFixed(2); // Temperatura entre 15°C y 35°C\nvar humedad = (Math.random() * (100 - 30) + 30).toFixed(2); // Humedad entre 30% y 100%\nvar tiempo = new Date().toLocaleTimeString(\"es-ES\"); // Formato de hora local\n\n// Guardar en variables globales\nglobal.set(\"temperatura\", temperatura);\nglobal.set(\"humedad\", humedad);\nglobal.set(\"tiempo\", tiempo);\n\n// Devolver los valores\nmsg.payload = {\n    temperatura: temperatura,\n    humedad: humedad,\n    tiempo: tiempo\n};\n\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 410,
        "y": 220,
        "wires": [
            [
                "06f3f594e367b705",
                "047477c4bb153233"
            ]
        ]
    },
    {
        "id": "18ddfd936f10a9a9",
        "type": "ui_gauge",
        "z": "da3341ce70c0a11c",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Temperatura",
        "label": "units",
        "format": "{{value}}",
        "min": "1",
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 770,
        "y": 180,
        "wires": []
    },
    {
        "id": "3d04e990085cf5be",
        "type": "ui_gauge",
        "z": "da3341ce70c0a11c",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "order": 1,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Humedad",
        "label": "units",
        "format": "{{value}}",
        "min": "1",
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 780,
        "y": 280,
        "wires": []
    },
    {
        "id": "d1ca5573c42ae4d0",
        "type": "inject",
        "z": "122ba55f1f40dd1c",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "1",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 140,
        "y": 180,
        "wires": [
            [
                "8a4285989cd24165",
                "f627d97a57e0ae9f"
            ]
        ]
    },
    {
        "id": "8a4285989cd24165",
        "type": "random",
        "z": "122ba55f1f40dd1c",
        "name": "TEMPERATURA",
        "low": "0",
        "high": "50",
        "inte": "true",
        "property": "payload",
        "x": 390,
        "y": 80,
        "wires": [
            []
        ]
    },
    {
        "id": "f627d97a57e0ae9f",
        "type": "random",
        "z": "122ba55f1f40dd1c",
        "name": "HUMEDAD",
        "low": 1,
        "high": "100",
        "inte": "true",
        "property": "payload",
        "x": 330,
        "y": 180,
        "wires": [
            []
        ]
    },
    {
        "id": "5d3b79f4ca50ac42",
        "type": "ui_gauge",
        "z": "122ba55f1f40dd1c",
        "name": "Temp",
        "group": "9be1e963857e6c23",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "donut",
        "title": "TEMPERATURA",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 610,
        "y": 100,
        "wires": []
    },
    {
        "id": "12d3e8c0ab275d3c",
        "type": "ui_gauge",
        "z": "122ba55f1f40dd1c",
        "name": "",
        "group": "9be1e963857e6c23",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "HUMEDAD",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 590,
        "y": 400,
        "wires": []
    },
    {
        "id": "b0a5e8b60c2b6c5a",
        "type": "ui_text",
        "z": "122ba55f1f40dd1c",
        "group": "2966ee4b0bca1171",
        "order": 1,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Temperatura",
        "format": "{{msg.payload}} Grados centrigrados",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 650,
        "y": 160,
        "wires": []
    },
    {
        "id": "198e1b3f24fa5250",
        "type": "ui_text",
        "z": "122ba55f1f40dd1c",
        "group": "9be1e963857e6c23",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "Humedad",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 580,
        "y": 440,
        "wires": []
    },
    {
        "id": "4b88e0ebcae2d8e1",
        "type": "function",
        "z": "122ba55f1f40dd1c",
        "name": "function 1",
        "func": "// Suponiendo que la cadena que recibimos es algo como:\n// \"Temperatura: 25 Humedad: 60\"\n\nlet datos = msg.payload;  // Los datos llegan en msg.payload como una cadena\n\n// Extraer la temperatura usando una expresión regular\nlet temperatura = datos.match(/Temperatura:\\s*(\\d+)/);  // Busca el número después de \"Temperatura:\"\n\nif (temperatura && temperatura[1]) {\n    // Almacena la temperatura en msg.payload\n    msg.payload = parseInt(temperatura[1]);\n    return msg;\n} else {\n    // Si no se encuentra la temperatura, se devuelve un mensaje de error\n    msg.payload = \"Error al extraer temperatura\";\n    return msg;\n}\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 400,
        "y": 320,
        "wires": [
            [
                "b0a5e8b60c2b6c5a",
                "5d3b79f4ca50ac42",
                "95f1625d43611812"
            ]
        ]
    },
    {
        "id": "6d7c9c0ee33256ae",
        "type": "ui_text",
        "z": "122ba55f1f40dd1c",
        "group": "9be1e963857e6c23",
        "order": 4,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 810,
        "y": 220,
        "wires": []
    },
    {
        "id": "4ea9084aa2d16fb9",
        "type": "function",
        "z": "122ba55f1f40dd1c",
        "name": "function 2",
        "func": "// Suponiendo que la cadena que recibimos es algo como:\n// \"Temperatura: 25 Humedad: 60\"\n\nlet datos = msg.payload;  // Los datos llegan en msg.payload como una cadena\n\n// Extraer la humedad usando una expresión regular\nlet humedad = datos.match(/Humedad:\\s*(\\d+)/);  // Busca el número después de \"Humedad:\"\n\nif (humedad && humedad[1]) {\n    // Almacena la humedad en msg.payload\n    msg.payload = parseInt(humedad[1]);\n    return msg;\n} else {\n    // Si no se encuentra la humedad, se devuelve un mensaje de error\n    msg.payload = \"Error al extraer humedad\";\n    return msg;\n}\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 380,
        "y": 420,
        "wires": [
            [
                "12d3e8c0ab275d3c",
                "198e1b3f24fa5250"
            ]
        ]
    },
    {
        "id": "f2f8603cc76ba9d7",
        "type": "ui_text",
        "z": "122ba55f1f40dd1c",
        "group": "9be1e963857e6c23",
        "order": 5,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "",
        "format": "{{msg.payload}}",
        "layout": "row-spread",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 590,
        "y": 560,
        "wires": []
    },
    {
        "id": "685add628fc903ad",
        "type": "ui_audio",
        "z": "122ba55f1f40dd1c",
        "name": "",
        "group": "9be1e963857e6c23",
        "voice": "",
        "always": "",
        "x": 840,
        "y": 280,
        "wires": []
    },
    {
        "id": "58ce04cbe44dd91e",
        "type": "ui_audio",
        "z": "122ba55f1f40dd1c",
        "name": "",
        "group": "9be1e963857e6c23",
        "voice": "",
        "always": "",
        "x": 400,
        "y": 520,
        "wires": []
    },
    {
        "id": "adeac25e284e69ce",
        "type": "serial in",
        "z": "122ba55f1f40dd1c",
        "name": "COM3",
        "serial": "8c8a16623754ee27",
        "x": 90,
        "y": 240,
        "wires": [
            [
                "aaed7265a44b2a78"
            ]
        ]
    },
    {
        "id": "b7968c36b52fbb3b",
        "type": "debug",
        "z": "122ba55f1f40dd1c",
        "name": "debug 1",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 380,
        "y": 240,
        "wires": []
    },
    {
        "id": "aaed7265a44b2a78",
        "type": "json",
        "z": "122ba55f1f40dd1c",
        "name": "",
        "property": "payload",
        "action": "",
        "pretty": false,
        "x": 210,
        "y": 360,
        "wires": [
            [
                "4b88e0ebcae2d8e1",
                "4ea9084aa2d16fb9"
            ]
        ]
    },
    {
        "id": "95f1625d43611812",
        "type": "function",
        "z": "122ba55f1f40dd1c",
        "name": "function 3",
        "func": "let temp = msg.payload\n\n\nif (temp > 20) {\n\n    msg.payload = \"TEMPERATURA CALIDA\"\n    return msg;\n\n} else {\n    msg.payload = \"\";\n    return msg\n}\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 580,
        "y": 320,
        "wires": [
            [
                "6d7c9c0ee33256ae",
                "685add628fc903ad"
            ]
        ]
    },
    {
        "id": "58490739941a0eb3",
        "type": "function",
        "z": "122ba55f1f40dd1c",
        "name": "function 4",
        "func": "\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 120,
        "y": 80,
        "wires": [
            []
        ]
    },
    {
        "id": "c5751b16ab291de7",
        "type": "inject",
        "z": "fa070e5a50702e44",
        "name": "Cada 30s",
        "props": [
            {
                "p": "payload"
            }
        ],
        "repeat": "30",
        "once": true,
        "x": 130,
        "y": 100,
        "wires": [
            [
                "16e0a55f59137c05",
                "495aa77cba27649d"
            ]
        ]
    },
    {
        "id": "16e0a55f59137c05",
        "type": "random",
        "z": "fa070e5a50702e44",
        "name": "TEMPERATURA",
        "low": "10",
        "high": "40",
        "inte": "true",
        "property": "payload.temp",
        "x": 350,
        "y": 80,
        "wires": [
            [
                "3dfd2c88bcf88b34"
            ]
        ]
    },
    {
        "id": "495aa77cba27649d",
        "type": "random",
        "z": "fa070e5a50702e44",
        "name": "HUMEDAD",
        "low": "20",
        "high": "90",
        "inte": "true",
        "property": "payload.hum",
        "x": 330,
        "y": 160,
        "wires": [
            [
                "3dfd2c88bcf88b34"
            ]
        ]
    },
    {
        "id": "3dfd2c88bcf88b34",
        "type": "change",
        "z": "fa070e5a50702e44",
        "name": "Guardar valores",
        "rules": [
            {
                "t": "set",
                "p": "temp",
                "to": "payload.temp"
            },
            {
                "t": "set",
                "p": "hum",
                "to": "payload.hum"
            },
            {
                "t": "set",
                "p": "time",
                "to": "$moment().format('HH:mm:ss')"
            }
        ],
        "x": 580,
        "y": 100,
        "wires": [
            [
                "cee9705c1914bdc8"
            ]
        ]
    },
    {
        "id": "cee9705c1914bdc8",
        "type": "telegram sender",
        "z": "fa070e5a50702e44",
        "name": "Enviar a Telegram",
        "bot": "",
        "haserroroutput": false,
        "outputs": 1,
        "x": 1010,
        "y": 140,
        "wires": [
            []
        ]
    },
    {
        "id": "f770bbc35de17d0b",
        "type": "telegram receiver",
        "z": "fa070e5a50702e44",
        "name": "Recibir comandos",
        "bot": "",
        "saveDataDir": "",
        "filterCommands": false,
        "x": 110,
        "y": 320,
        "wires": [
            [
                "8f3c5fd5d320974d"
            ],
            []
        ]
    },
    {
        "id": "8f3c5fd5d320974d",
        "type": "switch",
        "z": "fa070e5a50702e44",
        "name": "Procesar comando",
        "property": "payload.content",
        "rules": [
            {
                "t": "eq",
                "v": "/temperatura"
            },
            {
                "t": "eq",
                "v": "/humedad"
            }
        ],
        "outputs": 1,
        "x": 390,
        "y": 320,
        "wires": [
            [
                "e8aa564982313ce2"
            ]
        ]
    },
    {
        "id": "e8aa564982313ce2",
        "type": "template",
        "z": "fa070e5a50702e44",
        "name": "Mensaje temperatura",
        "template": "🌡️ Temperatura: {{temp}}°C\n🕒 Hora: {{time}}",
        "x": 660,
        "y": 220,
        "wires": [
            [
                "cee9705c1914bdc8"
            ]
        ]
    },
    {
        "id": "3a938eebb89cf6b5",
        "type": "template",
        "z": "fa070e5a50702e44",
        "name": "Mensaje humedad",
        "template": "💧 Humedad: {{hum}}%\n🕒 Hora: {{time}}",
        "x": 650,
        "y": 340,
        "wires": [
            [
                "cee9705c1914bdc8"
            ]
        ]
    },
    {
        "id": "6fc0f225d983f78e",
        "type": "inject",
        "z": "d44832a3560ad5ce",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "30",
        "crontab": "",
        "once": false,
        "onceDelay": "30",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 250,
        "y": 1060,
        "wires": [
            [
                "566754fc7b061c49",
                "f794225887b404fe"
            ]
        ]
    },
    {
        "id": "566754fc7b061c49",
        "type": "random",
        "z": "d44832a3560ad5ce",
        "name": "Temperatura",
        "low": "20",
        "high": "50",
        "inte": "true",
        "property": "payload",
        "x": 430,
        "y": 980,
        "wires": [
            [
                "f2b92f73ca445d54",
                "3d854d07fe36deb8",
                "0ff12ed3ae48fb6d"
            ]
        ]
    },
    {
        "id": "f794225887b404fe",
        "type": "random",
        "z": "d44832a3560ad5ce",
        "name": "Humedad",
        "low": "30",
        "high": "100",
        "inte": "true",
        "property": "payload",
        "x": 420,
        "y": 1100,
        "wires": [
            [
                "1a358dae43da51d1",
                "ee5d1b6b5e6d2dca",
                "e3133be18c7448b9"
            ]
        ]
    },
    {
        "id": "f2b92f73ca445d54",
        "type": "function",
        "z": "d44832a3560ad5ce",
        "name": "temperatura",
        "func": "let temp = msg.payload; // Recibe el valor del nodo random\nglobal.set(\"temperatura\", temp); // Guarda en variable global\n\nif (temp > 40) {\n    msg.payload = `Clima muy cálido (${temp}°C)`;\n} else {\n    msg.payload = `Temperatura normal (${temp}°C)`;\n}\nreturn msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 630,
        "y": 980,
        "wires": [
            [
                "ba75aec30926f9fa"
            ]
        ]
    },
    {
        "id": "1a358dae43da51d1",
        "type": "function",
        "z": "d44832a3560ad5ce",
        "name": "humedad",
        "func": "let hum = msg.payload; // Recibe el valor del nodo random\nglobal.set(\"humedad\", hum); // Guarda en variable global\n\nif (hum > 40) {\n    msg.payload = `Clima muy humedo (${hum}°C)`;\n} else {\n    msg.payload = `Temperatura normal (${hum}°C)`;\n}\nreturn msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 580,
        "y": 1160,
        "wires": [
            [
                "a9ee4e772003238e"
            ]
        ]
    },
    {
        "id": "8cc9ab4a35a98070",
        "type": "telegram sender",
        "z": "d44832a3560ad5ce",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "haserroroutput": false,
        "outputs": 1,
        "x": 870,
        "y": 1260,
        "wires": [
            []
        ]
    },
    {
        "id": "0ff12ed3ae48fb6d",
        "type": "ui_text",
        "z": "d44832a3560ad5ce",
        "group": "bed9a22cd1d142b8",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "temperatura",
        "format": "{{msg.payload}}",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 590,
        "y": 840,
        "wires": []
    },
    {
        "id": "3d854d07fe36deb8",
        "type": "ui_gauge",
        "z": "d44832a3560ad5ce",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Temperatura",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 590,
        "y": 900,
        "wires": []
    },
    {
        "id": "ba75aec30926f9fa",
        "type": "ui_audio",
        "z": "d44832a3560ad5ce",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "voice": "",
        "always": "",
        "x": 820,
        "y": 980,
        "wires": []
    },
    {
        "id": "bef82217cca4b027",
        "type": "function",
        "z": "d44832a3560ad5ce",
        "name": "Mostrar",
        "func": "let temp = global.get(\"temperatura\") || \"No disponible\";\nlet now = new Date();\nlet hora = now.toLocaleTimeString(\"es-ES\");\n\nnode.warn(`Temperatura: ${temp}°C, Hora: ${hora}`); // Muestra en la consola\n\n msg.payload = {\n     chatId: msg.payload.chatId, // Mantiene el Chat ID para la respuesta\n     type: \"message\",\n     content: `La temperatura es: ${temp}°C, y la hora es: ${hora}.`\n };\n return msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 520,
        "y": 1240,
        "wires": [
            [
                "8cc9ab4a35a98070"
            ]
        ]
    },
    {
        "id": "ee5d1b6b5e6d2dca",
        "type": "ui_text",
        "z": "d44832a3560ad5ce",
        "group": "bed9a22cd1d142b8",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "humedad",
        "format": "{{msg.payload}}",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 600,
        "y": 1060,
        "wires": []
    },
    {
        "id": "e3133be18c7448b9",
        "type": "ui_gauge",
        "z": "d44832a3560ad5ce",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Humedad",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 600,
        "y": 1100,
        "wires": []
    },
    {
        "id": "a9ee4e772003238e",
        "type": "ui_audio",
        "z": "d44832a3560ad5ce",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "voice": "",
        "always": "",
        "x": 780,
        "y": 1160,
        "wires": []
    },
    {
        "id": "f4cd15e5d24c0aa8",
        "type": "telegram command",
        "z": "d44832a3560ad5ce",
        "name": "",
        "command": "/temperatura",
        "description": "",
        "registercommand": false,
        "language": "",
        "scope": "default",
        "bot": "3ef6d052beb962b9",
        "strict": false,
        "hasresponse": true,
        "useregex": false,
        "removeregexcommand": false,
        "outputs": 2,
        "x": 230,
        "y": 1260,
        "wires": [
            [
                "bef82217cca4b027"
            ],
            []
        ]
    },
    {
        "id": "8e253f1825b5b1bc",
        "type": "telegram command",
        "z": "d44832a3560ad5ce",
        "name": "",
        "command": "/humedad",
        "description": "",
        "registercommand": false,
        "language": "",
        "scope": "default",
        "bot": "3ef6d052beb962b9",
        "strict": false,
        "hasresponse": true,
        "useregex": false,
        "removeregexcommand": false,
        "outputs": 2,
        "x": 240,
        "y": 1340,
        "wires": [
            [
                "da35460812653489"
            ],
            []
        ]
    },
    {
        "id": "da35460812653489",
        "type": "function",
        "z": "d44832a3560ad5ce",
        "name": "Mostrar",
        "func": "let hum = global.get(\"humedad\") || \"No disposible\";\nlet now = new Date();\nlet hora = now.toLocaleTimeString(\"es-ES\");\n\nnode.warn(`Humedad: ${hum}°C, Hora: ${hora}`); // Muestra en la consola\n\n msg.payload = {\n     chatId: msg.payload.chatId, // Mantiene el Chat ID para la respuesta\n     type: \"message\",\n     content: `La humedad es: ${hum}, y la hora es: ${hora}`\n };\n return msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 520,
        "y": 1320,
        "wires": [
            [
                "50790072d98843a3"
            ]
        ]
    },
    {
        "id": "50790072d98843a3",
        "type": "telegram sender",
        "z": "d44832a3560ad5ce",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "haserroroutput": false,
        "outputs": 1,
        "x": 850,
        "y": 1340,
        "wires": [
            []
        ]
    },
    {
        "id": "62922b3efdfc6223",
        "type": "inject",
        "z": "900f939f0d0d9da2",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "30",
        "crontab": "",
        "once": false,
        "onceDelay": "30",
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 230,
        "y": 640,
        "wires": [
            [
                "49c25d0b21b1073f",
                "bbc630816340023c"
            ]
        ]
    },
    {
        "id": "49c25d0b21b1073f",
        "type": "random",
        "z": "900f939f0d0d9da2",
        "name": "Temperatura",
        "low": "20",
        "high": "50",
        "inte": "true",
        "property": "payload",
        "x": 410,
        "y": 560,
        "wires": [
            [
                "1b85b49b981b9688",
                "a3c8a549ca1e2b41",
                "1a22bff9733d46c8"
            ]
        ]
    },
    {
        "id": "bbc630816340023c",
        "type": "random",
        "z": "900f939f0d0d9da2",
        "name": "Humedad",
        "low": "30",
        "high": "100",
        "inte": "true",
        "property": "payload",
        "x": 400,
        "y": 680,
        "wires": [
            [
                "c6c627493db9a30a",
                "4dbf21267b669b58",
                "0edf0458d67e87c1"
            ]
        ]
    },
    {
        "id": "1b85b49b981b9688",
        "type": "function",
        "z": "900f939f0d0d9da2",
        "name": "temperatura",
        "func": "let temp = msg.payload; // Recibe el valor del nodo random\nglobal.set(\"temperatura\", temp); // Guarda en variable global\n\nif (temp > 40) {\n    msg.payload = `Clima muy cálido (${temp}°C)`;\n} else {\n    msg.payload = `Temperatura normal (${temp}°C)`;\n}\nreturn msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 610,
        "y": 560,
        "wires": [
            [
                "c389706bb51cc8b5"
            ]
        ]
    },
    {
        "id": "c6c627493db9a30a",
        "type": "function",
        "z": "900f939f0d0d9da2",
        "name": "humedad",
        "func": "let hum = msg.payload; // Recibe el valor del nodo random\nglobal.set(\"humedad\", hum); // Guarda en variable global\n\nif (hum > 40) {\n    msg.payload = `Clima muy humedo (${hum}°C)`;\n} else {\n    msg.payload = `Temperatura normal (${hum}°C)`;\n}\nreturn msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 560,
        "y": 740,
        "wires": [
            [
                "f4d5805ff7e6b581"
            ]
        ]
    },
    {
        "id": "5b176cdea3b3c96e",
        "type": "telegram sender",
        "z": "900f939f0d0d9da2",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "haserroroutput": false,
        "outputs": 1,
        "x": 850,
        "y": 840,
        "wires": [
            []
        ]
    },
    {
        "id": "1a22bff9733d46c8",
        "type": "ui_text",
        "z": "900f939f0d0d9da2",
        "group": "bed9a22cd1d142b8",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "temperatura",
        "format": "{{msg.payload}}",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 570,
        "y": 420,
        "wires": []
    },
    {
        "id": "a3c8a549ca1e2b41",
        "type": "ui_gauge",
        "z": "900f939f0d0d9da2",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Temperatura",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 570,
        "y": 480,
        "wires": []
    },
    {
        "id": "c389706bb51cc8b5",
        "type": "ui_audio",
        "z": "900f939f0d0d9da2",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "voice": "",
        "always": "",
        "x": 800,
        "y": 560,
        "wires": []
    },
    {
        "id": "1337146ab8e7953f",
        "type": "function",
        "z": "900f939f0d0d9da2",
        "name": "Mostrar",
        "func": "let temp = global.get(\"temperatura\") || \"No disponible\";\nlet now = new Date();\nlet hora = now.toLocaleTimeString(\"es-ES\");\n\nnode.warn(`Temperatura: ${temp}°C, Hora: ${hora}`); // Muestra en la consola\n\n msg.payload = {\n     chatId: msg.payload.chatId, // Mantiene el Chat ID para la respuesta\n     type: \"message\",\n     content: `La temperatura es: ${temp}°C, y la hora es: ${hora}.`\n };\n return msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 500,
        "y": 820,
        "wires": [
            [
                "5b176cdea3b3c96e"
            ]
        ]
    },
    {
        "id": "4dbf21267b669b58",
        "type": "ui_text",
        "z": "900f939f0d0d9da2",
        "group": "bed9a22cd1d142b8",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "humedad",
        "format": "{{msg.payload}}",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 580,
        "y": 640,
        "wires": []
    },
    {
        "id": "0edf0458d67e87c1",
        "type": "ui_gauge",
        "z": "900f939f0d0d9da2",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "order": 2,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Humedad",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 580,
        "y": 680,
        "wires": []
    },
    {
        "id": "f4d5805ff7e6b581",
        "type": "ui_audio",
        "z": "900f939f0d0d9da2",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "voice": "",
        "always": "",
        "x": 760,
        "y": 740,
        "wires": []
    },
    {
        "id": "ff11436d870b1e1d",
        "type": "telegram command",
        "z": "900f939f0d0d9da2",
        "name": "",
        "command": "/temperatura",
        "description": "",
        "registercommand": false,
        "language": "",
        "scope": "default",
        "bot": "3ef6d052beb962b9",
        "strict": false,
        "hasresponse": true,
        "useregex": false,
        "removeregexcommand": false,
        "outputs": 2,
        "x": 210,
        "y": 840,
        "wires": [
            [
                "1337146ab8e7953f"
            ],
            []
        ]
    },
    {
        "id": "baedc38d377a490b",
        "type": "telegram command",
        "z": "900f939f0d0d9da2",
        "name": "",
        "command": "/humedad",
        "description": "",
        "registercommand": false,
        "language": "",
        "scope": "default",
        "bot": "3ef6d052beb962b9",
        "strict": false,
        "hasresponse": true,
        "useregex": false,
        "removeregexcommand": false,
        "outputs": 2,
        "x": 220,
        "y": 920,
        "wires": [
            [
                "f1ebba54929660d6"
            ],
            []
        ]
    },
    {
        "id": "f1ebba54929660d6",
        "type": "function",
        "z": "900f939f0d0d9da2",
        "name": "Mostrar",
        "func": "let hum = global.get(\"humedad\") || \"No disposible\";\nlet now = new Date();\nlet hora = now.toLocaleTimeString(\"es-ES\");\n\nnode.warn(`Humedad: ${hum}°C, Hora: ${hora}`); // Muestra en la consola\n\n msg.payload = {\n     chatId: msg.payload.chatId, // Mantiene el Chat ID para la respuesta\n     type: \"message\",\n     content: `La humedad es: ${hum}, y la hora es: ${hora}`\n };\n return msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 500,
        "y": 900,
        "wires": [
            [
                "d11cc060cb469b81"
            ]
        ]
    },
    {
        "id": "d11cc060cb469b81",
        "type": "telegram sender",
        "z": "900f939f0d0d9da2",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "haserroroutput": false,
        "outputs": 1,
        "x": 830,
        "y": 920,
        "wires": [
            []
        ]
    },
    {
        "id": "214063fa84d3c52a",
        "type": "inject",
        "z": "900f939f0d0d9da2",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 220,
        "y": 1120,
        "wires": [
            [
                "d4445b648d65a3f1"
            ]
        ]
    },
    {
        "id": "360e20ca77ba03c1",
        "type": "telegram command",
        "z": "900f939f0d0d9da2",
        "name": "",
        "command": "/camara",
        "description": "",
        "registercommand": false,
        "language": "",
        "scope": "default",
        "bot": "3ef6d052beb962b9",
        "strict": false,
        "hasresponse": true,
        "useregex": false,
        "removeregexcommand": false,
        "outputs": 2,
        "x": 340,
        "y": 1200,
        "wires": [
            [
                "d4445b648d65a3f1"
            ],
            []
        ]
    },
    {
        "id": "d4445b648d65a3f1",
        "type": "function",
        "z": "900f939f0d0d9da2",
        "name": "function 13",
        "func": "if (msg.payload && msg.payload.type === \"message\") {\n    // Si el mensaje tiene contenido, lo usa; si no, usa un valor por defecto\n    var comando = msg.payload.content || \"vacio\";\n    node.warn(\"Mensaje recibido: \" + comando); // Muestra en el debug\n    \n    if (comando === \"/camara\") {\n        return { payload: \"capturar\", chatId: msg.payload.chatId };\n    }\n}\n\nreturn null;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 460,
        "y": 1100,
        "wires": [
            [
                "5e283320bb678241",
                "577f0c83ea48a91d"
            ]
        ]
    },
    {
        "id": "5e283320bb678241",
        "type": "ui_webcam",
        "z": "900f939f0d0d9da2",
        "name": "",
        "group": "bed9a22cd1d142b8",
        "order": 14,
        "width": 0,
        "height": "0",
        "countdown": false,
        "autoStart": true,
        "hideCaptureButton": false,
        "showImage": "2",
        "mirror": true,
        "format": "jpeg",
        "x": 600,
        "y": 1200,
        "wires": [
            [
                "052886d3309498c6",
                "99b8c06b1169771b"
            ]
        ]
    },
    {
        "id": "99b8c06b1169771b",
        "type": "debug",
        "z": "900f939f0d0d9da2",
        "name": "msg.playload",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "payload",
        "targetType": "msg",
        "statusVal": "",
        "statusType": "auto",
        "x": 870,
        "y": 1180,
        "wires": []
    },
    {
        "id": "052886d3309498c6",
        "type": "function",
        "z": "900f939f0d0d9da2",
        "name": "function 14",
        "func": "msg.payload = {\n    chatId: msg.chatId,\n    type: \"photo\",\n    content: msg.payload // Imagen en buffer\n};\nreturn msg;\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 750,
        "y": 1100,
        "wires": [
            [
                "a15c69c47fbec4d7"
            ]
        ]
    },
    {
        "id": "a15c69c47fbec4d7",
        "type": "telegram sender",
        "z": "900f939f0d0d9da2",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "haserroroutput": false,
        "outputs": 1,
        "x": 1010,
        "y": 1120,
        "wires": [
            []
        ]
    },
    {
        "id": "fd620dc07b85ed7a",
        "type": "inject",
        "z": "900f939f0d0d9da2",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 380,
        "y": 980,
        "wires": [
            [
                "e3155ae9e676e984"
            ]
        ]
    },
    {
        "id": "e3155ae9e676e984",
        "type": "debug",
        "z": "900f939f0d0d9da2",
        "name": "debug 5",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 600,
        "y": 980,
        "wires": []
    },
    {
        "id": "577f0c83ea48a91d",
        "type": "debug",
        "z": "900f939f0d0d9da2",
        "name": "debug 6",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 480,
        "y": 1320,
        "wires": []
    },
    {
        "id": "233afcf58a3b7586",
        "type": "mqtt in",
        "z": "c89345ecddbf181e",
        "name": "",
        "topic": "sensor/datos",
        "qos": "2",
        "datatype": "auto-detect",
        "broker": "1f28c87104a8cd3f",
        "nl": false,
        "rap": true,
        "rh": 0,
        "inputs": 0,
        "x": 110,
        "y": 220,
        "wires": [
            [
                "d75b2a4bd2557f01"
            ]
        ]
    },
    {
        "id": "6bb33d9a1675970a",
        "type": "debug",
        "z": "c89345ecddbf181e",
        "name": "debug 7",
        "active": true,
        "tosidebar": true,
        "console": false,
        "tostatus": false,
        "complete": "false",
        "statusVal": "",
        "statusType": "auto",
        "x": 420,
        "y": 240,
        "wires": []
    },
    {
        "id": "d75b2a4bd2557f01",
        "type": "json",
        "z": "c89345ecddbf181e",
        "name": "",
        "property": "payload",
        "action": "",
        "pretty": true,
        "x": 270,
        "y": 220,
        "wires": [
            [
                "6bb33d9a1675970a",
                "e01f07556e8a6cf0",
                "083bd32c2616055f",
                "3a40770a21167f9a",
                "c1c1d7bf24bb3afe"
            ]
        ]
    },
    {
        "id": "2777ba40ad2619da",
        "type": "mqtt out",
        "z": "c89345ecddbf181e",
        "g": "a32b84d65eaae1ae",
        "name": "",
        "topic": "led/control",
        "qos": "",
        "retain": "",
        "respTopic": "",
        "contentType": "",
        "userProps": "",
        "correl": "",
        "expiry": "",
        "broker": "1f28c87104a8cd3f",
        "x": 130,
        "y": 520,
        "wires": []
    },
    {
        "id": "e345924d3ee8f328",
        "type": "inject",
        "z": "c89345ecddbf181e",
        "g": "a32b84d65eaae1ae",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 140,
        "y": 480,
        "wires": [
            []
        ]
    },
    {
        "id": "e01f07556e8a6cf0",
        "type": "ui_gauge",
        "z": "c89345ecddbf181e",
        "name": "",
        "group": "3ce8278568b35a57",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Temperatura",
        "label": "units",
        "format": "{{msg.payload.temperatura}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 430,
        "y": 160,
        "wires": []
    },
    {
        "id": "083bd32c2616055f",
        "type": "ui_gauge",
        "z": "c89345ecddbf181e",
        "name": "",
        "group": "3ce8278568b35a57",
        "order": 1,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Humedad",
        "label": "units",
        "format": "{{msg.payload.humedad}}",
        "min": 0,
        "max": "100",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 400,
        "y": 320,
        "wires": []
    },
    {
        "id": "3a40770a21167f9a",
        "type": "ui_text",
        "z": "c89345ecddbf181e",
        "group": "bed9a22cd1d142b8",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "temperatura",
        "format": "{{msg.payload}}",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 430,
        "y": 100,
        "wires": []
    },
    {
        "id": "c1c1d7bf24bb3afe",
        "type": "ui_text",
        "z": "c89345ecddbf181e",
        "group": "bed9a22cd1d142b8",
        "order": 3,
        "width": 0,
        "height": 0,
        "name": "",
        "label": "humedad",
        "format": "{{msg.payload}}",
        "layout": "row-left",
        "className": "",
        "style": false,
        "font": "",
        "fontSize": 16,
        "color": "#000000",
        "x": 420,
        "y": 380,
        "wires": []
    },
    {
        "id": "741f5b964fb93ada",
        "type": "inject",
        "z": "38bf26e98cb97eac",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "30",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "num",
        "x": 90,
        "y": 200,
        "wires": [
            [
                "bcfdc7dd0549a34b"
            ]
        ]
    },
    {
        "id": "5739d805efe2b075",
        "type": "firebase modify",
        "z": "38bf26e98cb97eac",
        "name": "",
        "firebaseconfig": "ec05f7e6242e7de5",
        "childpath": "Temperatura",
        "method": "push",
        "value": "msg.payload",
        "priority": "msg.priority",
        "x": 720,
        "y": 200,
        "wires": [
            []
        ]
    },
    {
        "id": "15d803eb5bdf58ce",
        "type": "ui_button",
        "z": "38bf26e98cb97eac",
        "name": "",
        "group": "2e4fde67c6424d50",
        "order": 0,
        "width": 0,
        "height": 0,
        "passthru": false,
        "label": "Borrar",
        "tooltip": "",
        "color": "",
        "bgcolor": "",
        "className": "",
        "icon": "",
        "payload": "0",
        "payloadType": "num",
        "topic": "topic",
        "topicType": "msg",
        "x": 90,
        "y": 280,
        "wires": [
            [
                "660bc6397fd22ede"
            ]
        ]
    },
    {
        "id": "660bc6397fd22ede",
        "type": "firebase modify",
        "z": "38bf26e98cb97eac",
        "name": "",
        "firebaseconfig": "2c125d4d326da34f",
        "childpath": "Temperatura",
        "method": "set",
        "value": "msg.payload",
        "priority": "msg.priority",
        "x": 590,
        "y": 300,
        "wires": [
            []
        ]
    },
    {
        "id": "d83b00cd69c1218b",
        "type": "firebase.on",
        "z": "38bf26e98cb97eac",
        "name": "",
        "firebaseconfig": "b5d48302b30b82cf",
        "childpath": "Temperatura",
        "atStart": true,
        "eventType": "child_added",
        "queries": [],
        "x": 310,
        "y": 440,
        "wires": [
            [
                "f629db7d442d1324"
            ]
        ]
    },
    {
        "id": "f629db7d442d1324",
        "type": "ui_gauge",
        "z": "38bf26e98cb97eac",
        "name": "",
        "group": "2e4fde67c6424d50",
        "order": 1,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "gauge",
        "label": "units",
        "format": "{{value}}",
        "min": 0,
        "max": "20",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 730,
        "y": 400,
        "wires": []
    },
    {
        "id": "bcfdc7dd0549a34b",
        "type": "random",
        "z": "38bf26e98cb97eac",
        "name": "",
        "low": 1,
        "high": "20",
        "inte": "true",
        "property": "payload",
        "x": 300,
        "y": 200,
        "wires": [
            [
                "5739d805efe2b075"
            ]
        ]
    },
    {
        "id": "50402ea190b03308",
        "type": "jimp-image",
        "z": "0e08f5c08fd80381",
        "name": "",
        "data": "payload",
        "dataType": "msg",
        "ret": "img",
        "parameter1": "",
        "parameter1Type": "msg",
        "parameter2": "",
        "parameter2Type": "msg",
        "parameter3": "",
        "parameter3Type": "msg",
        "parameter4": "",
        "parameter4Type": "msg",
        "parameter5": "",
        "parameter5Type": "msg",
        "parameter6": "",
        "parameter6Type": "msg",
        "parameter7": "",
        "parameter7Type": "msg",
        "parameter8": "",
        "parameter8Type": "msg",
        "sendProperty": "payload",
        "sendPropertyType": "msg",
        "parameterCount": 0,
        "jimpFunction": "none",
        "selectedJimpFunction": {},
        "x": 650,
        "y": 560,
        "wires": [
            []
        ]
    },
    {
        "id": "535068e6c16b789b",
        "type": "inject",
        "z": "0e08f5c08fd80381",
        "name": "Iniciar Video",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "30",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "https://cdn.skylinewebcams.com/4608.jpg",
        "payloadType": "str",
        "x": 260,
        "y": 220,
        "wires": [
            []
        ]
    },
    {
        "id": "3ef81e8a75e631bd",
        "type": "http request",
        "z": "0e08f5c08fd80381",
        "name": "",
        "method": "GET",
        "ret": "bin",
        "paytoqs": "ignore",
        "url": "https://cdn.skylinewebcams.com/4608.jpg",
        "tls": "",
        "persist": false,
        "proxy": "",
        "insecureHTTPParser": false,
        "authType": "",
        "senderr": false,
        "headers": [],
        "x": 470,
        "y": 260,
        "wires": [
            [
                "c5463decea5565fa"
            ]
        ]
    },
    {
        "id": "e2dc3da91f22712c",
        "type": "telegram receiver",
        "z": "0e08f5c08fd80381",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "saveDataDir": "",
        "filterCommands": false,
        "x": 326.1999816894531,
        "y": 386.1999816894531,
        "wires": [
            [],
            []
        ]
    },
    {
        "id": "c5463decea5565fa",
        "type": "function",
        "z": "0e08f5c08fd80381",
        "name": "function 15",
        "func": "if (msg.payload && msg.payload.length > 0) {\n    // Si hay datos en el payload (la imagen se descargó correctamente)\n    return msg;  // Pasamos el mensaje al siguiente nodo (telegram sender)\n} else {\n    // Si no hay datos (la imagen no se descargó correctamente)\n    node.warn(\"No se pudo descargar la imagen.\");\n    return null;  // No pasa el mensaje, no se envía nada a Telegram\n}\n",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 666.1999816894531,
        "y": 406.1999816894531,
        "wires": [
            [
                "b59d37be53e836cc"
            ]
        ]
    },
    {
        "id": "b59d37be53e836cc",
        "type": "telegram sender",
        "z": "0e08f5c08fd80381",
        "name": "",
        "bot": "3ef6d052beb962b9",
        "haserroroutput": false,
        "outputs": 1,
        "x": 886.1999816894531,
        "y": 306.1999816894531,
        "wires": [
            []
        ]
    },
    {
        "id": "c8cce61a4a36d07a",
        "type": "http request",
        "z": "2415bc24a6e52d63",
        "name": "",
        "method": "GET",
        "ret": "txt",
        "paytoqs": "ignore",
        "url": "https://api.open-meteo.com/v1/forecast?latitude=-16.2902&longitude=-63.5887&hourly=temperature_2m,relative_humidity_2m,temperature_80m,temperature_120m,temperature_180m",
        "tls": "",
        "persist": false,
        "proxy": "",
        "insecureHTTPParser": false,
        "authType": "",
        "senderr": false,
        "headers": [],
        "x": 290,
        "y": 380,
        "wires": [
            [
                "8e99abba9b4c6ee9"
            ]
        ]
    },
    {
        "id": "8e99abba9b4c6ee9",
        "type": "json",
        "z": "2415bc24a6e52d63",
        "name": "",
        "property": "payload",
        "action": "",
        "pretty": false,
        "x": 490,
        "y": 360,
        "wires": [
            [
                "c6cd3743028716cd"
            ]
        ]
    },
    {
        "id": "65e39927f0c9a065",
        "type": "inject",
        "z": "2415bc24a6e52d63",
        "name": "",
        "props": [
            {
                "p": "payload"
            },
            {
                "p": "topic",
                "vt": "str"
            }
        ],
        "repeat": "",
        "crontab": "",
        "once": false,
        "onceDelay": 0.1,
        "topic": "",
        "payload": "",
        "payloadType": "date",
        "x": 100,
        "y": 340,
        "wires": [
            [
                "c8cce61a4a36d07a"
            ]
        ]
    },
    {
        "id": "c6cd3743028716cd",
        "type": "function",
        "z": "2415bc24a6e52d63",
        "name": "Temp",
        "func": "var data = {\n    \"hourly\": {\n        \"temperature_2m\": [25.4, 24.8, 24.1, 23.4] // Simulación de valores\n    }\n};\n\n// Extraer temperatura actual\nmsg.payload = data.hourly.temperature_2m[0]; // Primera lectura\nreturn msg;",
        "outputs": 1,
        "timeout": 0,
        "noerr": 0,
        "initialize": "",
        "finalize": "",
        "libs": [],
        "x": 650,
        "y": 340,
        "wires": [
            [
                "254540f86f088eea"
            ]
        ]
    },
    {
        "id": "254540f86f088eea",
        "type": "ui_gauge",
        "z": "2415bc24a6e52d63",
        "name": "",
        "group": "2674e269c51c343f",
        "order": 0,
        "width": 0,
        "height": 0,
        "gtype": "gage",
        "title": "Temperatura",
        "label": "C°",
        "format": "{{value}}",
        "min": 0,
        "max": "40",
        "colors": [
            "#00b500",
            "#e6e600",
            "#ca3838"
        ],
        "seg1": "",
        "seg2": "",
        "diff": false,
        "className": "",
        "x": 810,
        "y": 340,
        "wires": []
    }
]
