# BDD requirements

En ocasiones utilizar una plantilla BDD sirve para integrar los escenarios
con las historias de usuario de forma que se pueden evaluar con pruebas de
comportamiento (_behavior driven design_ (BDD)).

> **Story**:
>
> **As a**
> **In order to**
> **I want to**
>
> **Scenario 1**:
> **Given**
> **And**
> **When**
> **Then**
> **And**
>
> **Scenario 2**:
> **Given**
> **And**
> **When**
> **Then**
> **And**

Example:

> **Story**: Returns go to stock
>
> **In order to** keep track of stock
> **As a** store owner
> **I want to** add items back to stock when they're returned.
>
> **Scenario 1**: Refunded items should be returned to stock
> **Given** that a customer previously bought a black sweater from me
> **And** I have three black sweaters in stock.
> **When** he returns the black sweater for a refund
> **Then** I should have four black sweaters in stock.
>
> **Scenario 2**: Replaced items should be returned to stock
> **Given** that a customer previously bought a blue garment from me
> **And** I have two blue garments in stock
> **And** three black garments in stock.
> **When** he returns the blue garment for a replacement in black
> **Then** I should have three blue garments in stock
> **And** two black garments in stock.
