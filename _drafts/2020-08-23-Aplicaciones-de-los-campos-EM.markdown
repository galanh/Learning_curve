---
layout: post
title:  "Aplicaciones de los campos EM"
permalink: aplicaciones-de-los-campos-EM
---
{% plantuml %}

@startuml
left to right direction
package "longitud de onda" {
    usecase "ondas EM" as w
    usecase "radio" as w1
    usecase "microonda" as w2
    usecase "infrarojo" as w3
    usecase "Sol" as w4
    usecase "ultravioleta" as w5
    usecase "rayos x" as w6
    usecase "rayos gama" as w7
    usecase "contra los virus" as y1
    usecase "running" as y2
    usecase "calor" as y3
    usecase "comunicacion" as y4
}

w --> w1
w --> w2
w --> w3
w --> w4
w --> w5
w --> w6
w --> w7
w5 --> y1
w4 --> y2
w3 --> y3
w2 --> y4
@enduml

{% endplantuml %}



