# Product Backlog

## Historias de Usuario para la Calculadora de Triángulos

### HU1: Identificación del Tipo de Triángulo y Cálculos Asociados

#### Descripción:
Implementar la funcionalidad para identificar el tipo de triángulo (equilátero, isósceles, escaleno) y realizar cálculos asociados, como el perímetro y el área, con base en las longitudes de los lados ingresados por el usuario.

#### Criterios de Aceptación:
1. **Identificación del Tipo de Triángulo:**
   - Como usuario, quiero que la aplicación evalúe las longitudes de los lados de un triángulo.
   - Como usuario, quiero que la aplicación determine si el triángulo es equilátero, isósceles o escaleno.
   - Como usuario, quiero que el resultado de la identificación se muestre claramente.

2. **Cálculo del Perímetro:**
   - Como usuario, quiero que la aplicación calcule el perímetro del triángulo.
   - Como usuario, quiero que el resultado del cálculo del perímetro se muestre claramente.

3. **Cálculo del Área:**
   - Como usuario, quiero que la aplicación calcule el área del triángulo utilizando la fórmula de Herón.
   - Como usuario, quiero que el resultado del cálculo del área se muestre claramente.

### HU2: Manejo de Errores y Mensajes Informativos

#### Descripción:
Mejorar la aplicación para manejar casos de entrada inválida y proporcionar mensajes claros y educativos al usuario.

#### Criterios de Aceptación:
1. **Identificación de Entrada Inválida:**
   - Como usuario, quiero que la aplicación identifique si las longitudes ingresadas no forman un triángulo válido.
   - Como usuario, quiero que la aplicación muestre un mensaje de error si se detecta una entrada inválida.

2. **Mensaje de Error Informativo:**
   - Como usuario, quiero que el mensaje de error indique claramente que la entrada no es válida.
   - Como usuario, quiero que el mensaje de error proporcione instrucciones claras sobre cómo ingresar longitudes válidas.

### HU3: Continuidad de la Ejecución

#### Descripción:
Permitir que la aplicación continúe ejecutándose hasta que el usuario decida finalizarla, ofreciendo opciones claras después de cada cálculo.

#### Criterios de Aceptación:
1. **Opción de Traducir Otro Número:**
   - Como usuario, quiero que después de cada cálculo, la aplicación ofrezca la opción de ingresar las longitudes de otro triángulo.
   - Como usuario, quiero que si elijo traducir otro número, la aplicación permita ingresar nuevas longitudes y realice los cálculos correspondientes.

2. **Finalización Ordenada:**
   - Como usuario, quiero que si decido no traducir otro número, la aplicación finalice de manera ordenada.
   - Como usuario, quiero que la aplicación cierre la ejecución de forma clara y sin errores.
