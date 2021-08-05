# Pruebas unitarias con Jest y express

## Instalar las siguientes dependendencias en ambiente desarrollo:

npm install --save-dev babel-cli babel-preset-env jest supertest

## Instalar las siguientes dependendencias:

npm install express

## Dónde hubicar los ficheros de test:

Crear la carpeta __test__ o __TEST__ para Jest sepa identificar dónde están los test.

## COMPARADORES / MATCHERS
- toBe
- not.toBe
- toEqual
- not.toEqual

## PRUEBAS UNITARIAS CON NÚMEROS
- .toBeGreaterThan()
- .toBeGreaterThanOrEqual()
- .toBeLessThan()
- .toBeLessThanOrEqual()
- .toBeCloseTo()

## FUNCIONES QUE DEVUELEN Boolean, Udefined o Null
- .toBeNull() solo coincidencias null
- .toBeTruthy() solo coincidencias undefined
- .toBeFalsy() es lo contrario de toBeUndefined
- .toBeUndefined() coincide con cualquier cosa que una if declaración considere verdadera
- .not.toBeTruthy() coincide con cualquier cosa que una if declaración considere falsa

# Fuente de consulta:
https://jestjs.io/es-ES/docs/next/setup-teardown