Here.com access information
_______

App ID: pRx2iZs3UW7YAjlvsdCJ

Key: l6QfiFZpUmxv8qthYmXYlw

Sample Response:

https://route.api.here.com/routing/7.2/calculateroute.json?app_id=pRx2iZs3UW7YAjlvsdCJ&app_code=l6QfiFZpUmxv8qthYmXYlw&waypoint0=geo!52.5,13.4&waypoint1=geo!52.5,13.45&mode=fastest;car;traffic:disabled

`
{
    "response": {
        "metaInfo": {
            "timestamp": "2019-11-17T22:39:47Z",
            "mapVersion": "8.30.102.151",
            "moduleVersion": "7.2.201945-5735",
            "interfaceVersion": "2.6.74",
            "availableMapVersion": [
                "8.30.102.151"
            ]
        },
        "route": [
            {
                "waypoint": [
                    {
                        "linkId": "-53623477",
                        "mappedPosition": {
                            "latitude": 52.4999825,
                            "longitude": 13.3999652
                        },
                        "originalPosition": {
                            "latitude": 52.5,
                            "longitude": 13.4
                        },
                        "type": "stopOver",
                        "spot": 0.3538462,
                        "sideOfStreet": "left",
                        "mappedRoadName": "Neuenburger Straße",
                        "label": "Neuenburger Straße",
                        "shapeIndex": 0,
                        "source": "user"
                    },
                    {
                        "linkId": "+1215312511",
                        "mappedPosition": {
                            "latitude": 52.4992955,
                            "longitude": 13.4491968
                        },
                        "originalPosition": {
                            "latitude": 52.5,
                            "longitude": 13.45
                        },
                        "type": "stopOver",
                        "spot": 1.0,
                        "sideOfStreet": "left",
                        "mappedRoadName": "Schlesische Straße",
                        "label": "Schlesische Straße",
                        "shapeIndex": 55,
                        "source": "user"
                    }
                ],
                "mode": {
                    "type": "fastest",
                    "transportModes": [
                        "car"
                    ],
                    "trafficMode": "disabled",
                    "feature": []
                },
                "leg": [
                    {
                        "start": {
                            "linkId": "-53623477",
                            "mappedPosition": {
                                "latitude": 52.4999825,
                                "longitude": 13.3999652
                            },
                            "originalPosition": {
                                "latitude": 52.5,
                                "longitude": 13.4
                            },
                            "type": "stopOver",
                            "spot": 0.3538462,
                            "sideOfStreet": "left",
                            "mappedRoadName": "Neuenburger Straße",
                            "label": "Neuenburger Straße",
                            "shapeIndex": 0,
                            "source": "user"
                        },
                        "end": {
                            "linkId": "+1215312511",
                            "mappedPosition": {
                                "latitude": 52.4992955,
                                "longitude": 13.4491968
                            },
                            "originalPosition": {
                                "latitude": 52.5,
                                "longitude": 13.45
                            },
                            "type": "stopOver",
                            "spot": 1.0,
                            "sideOfStreet": "left",
                            "mappedRoadName": "Schlesische Straße",
                            "label": "Schlesische Straße",
                            "shapeIndex": 55,
                            "source": "user"
                        },
                        "length": 3847,
                        "travelTime": 667,
                        "maneuver": [
                            {
                                "position": {
                                    "latitude": 52.4999825,
                                    "longitude": 13.3999652
                                },
                                "instruction": "Head <span class=\"heading\">southeast</span> on <span class=\"street\">Neuenburger Straße</span>. <span class=\"distance-description\">Go for <span class=\"length\">46 m</span>.</span>",
                                "travelTime": 17,
                                "length": 46,
                                "id": "M1",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.4995744,
                                    "longitude": 13.4000158
                                },
                                "instruction": "Turn <span class=\"direction\">left</span> onto <span class=\"next-street\">Neuenburger Straße</span>. <span class=\"distance-description\">Go for <span class=\"length\">29 m</span>.</span>",
                                "travelTime": 10,
                                "length": 29,
                                "id": "M2",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.4994671,
                                    "longitude": 13.4004235
                                },
                                "instruction": "Turn <span class=\"direction\">right</span> onto <span class=\"next-street\">Alexandrinenstraße</span>. <span class=\"distance-description\">Go for <span class=\"length\">130 m</span>.</span>",
                                "travelTime": 37,
                                "length": 130,
                                "id": "M3",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.498405,
                                    "longitude": 13.3996081
                                },
                                "instruction": "Turn <span class=\"direction\">left</span> onto <span class=\"next-street\">Gitschiner Straße</span>. <span class=\"distance-description\">Go for <span class=\"length\">876 m</span>.</span>",
                                "travelTime": 106,
                                "length": 876,
                                "id": "M4",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.4985445,
                                    "longitude": 13.4121823
                                },
                                "instruction": "Continue on <span class=\"next-street\">Wassertorplatz</span>. <span class=\"distance-description\">Go for <span class=\"length\">129 m</span>.</span>",
                                "travelTime": 12,
                                "length": 129,
                                "id": "M5",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.4984264,
                                    "longitude": 13.4140706
                                },
                                "instruction": "Continue on <span class=\"next-street\">Skalitzer Straße</span>. <span class=\"distance-description\">Go for <span class=\"length\">269 m</span>.</span>",
                                "travelTime": 41,
                                "length": 269,
                                "id": "M6",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.4988449,
                                    "longitude": 13.4179652
                                },
                                "instruction": "Take the <span class=\"exit\">2nd exit</span> from Kottbusser Tor roundabout onto <span class=\"next-street\">Skalitzer Straße</span>. <span class=\"distance-description\">Go for <span class=\"length\">1.7 km</span>.</span>",
                                "travelTime": 248,
                                "length": 1686,
                                "id": "M7",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.5009799,
                                    "longitude": 13.4421694
                                },
                                "instruction": "Turn <span class=\"direction\">right</span> onto <span class=\"next-street\">Schlesische Straße</span> toward <span class=\"sign\"><span lang=\"de\">A117</span>/<span lang=\"de\">Dresden</span>/<span lang=\"de\">Treptow</span>/<span lang=\"de\">Flughafen Schönefeld</span></span>. <span class=\"distance-description\">Go for <span class=\"length\">500 m</span>.</span>",
                                "travelTime": 65,
                                "length": 500,
                                "id": "M8",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.4979866,
                                    "longitude": 13.4476519
                                },
                                "instruction": "Turn <span class=\"direction\">left</span> onto <span class=\"next-street\">Schlesische Straße</span>. <span class=\"distance-description\">Go for <span class=\"length\">182 m</span>.</span>",
                                "travelTime": 131,
                                "length": 182,
                                "id": "M9",
                                "_type": "PrivateTransportManeuverType"
                            },
                            {
                                "position": {
                                    "latitude": 52.4992955,
                                    "longitude": 13.4491968
                                },
                                "instruction": "Arrive at <span class=\"street\">Schlesische Straße</span>. Your destination is on the left.",
                                "travelTime": 0,
                                "length": 0,
                                "id": "M10",
                                "_type": "PrivateTransportManeuverType"
                            }
                        ]
                    }
                ],
                "summary": {
                    "distance": 3847,
                    "trafficTime": 744,
                    "baseTime": 667,
                    "flags": [
                        "noThroughRoad",
                        "builtUpArea",
                        "park",
                        "privateRoad"
                    ],
                    "text": "The trip takes <span class=\"length\">3.8 km</span> and <span class=\"time\">11 mins</span>.",
                    "travelTime": 667,
                    "_type": "RouteSummaryType"
                }
            }
        ],
        "language": "en-us"
    }
}
`
