## Reporte registro

### Crear cuenta

###### 1. Responsive no se ajuste y permanecen ocultos ciertos botones
###### 2. No esta casteando el error al crear cuenta, ingresando simbolos y nombres cortos estilo "JUAN"
###### 3. En algunas ocasiones se suelen cargar datos de otros empleadores

### Creacion de contrato

###### 1. Al crear el contrato, seleecionar salario diario e indicar el uso de salario minino asigna el salario minimo mensual, 
###### pero al ser salario diario solo deberia indicar el salario diario basado en el minimo

#### Usuario usado: Mantis+11@symplifica.com | Andres21*
###### 2. No esta consultando el workplace
###### 3. Al recargar la pagina esta indicando que "vacation_days_given" no puede estar en blanco 

### Onboarding

#### Usuario usado: Andrea+8@symplifica.com | Andres21*
#### Usuario usado: Sergio+7@symplifica.com | Andres21*
###### 1. Al iniciar sesion con un empleador en el proceso de carga de datos genera el siguiente error:
```javascript
error_code: "500"
error_message: "{"error":"camundajar.com.google.gson.stream.MalformedJsonException: Use JsonReader.setLenient(true) to accept malformed JSON at line 1 column 10 path $", "url":"https://service-sycorecolombiadomestics/colombia/contract_detail//", "params":"null", "method":"GET"}"
error_name: "UNKNOWN_ERROR"
error_trace: "camundajar.com.google.gson.stream.MalformedJsonException: Use JsonReader.setLenient(true) to accept malformed JSON at line 1 column 10 path $"
success: false
```
###### El error se resuelve al tratar de volver atras, en ese momento si se carga el contrato
###### 1. Añadir boton volver en todas las pantallas de onboarding, en este punto ya se garantizo el pago
###### 2. 

### Creacion de empleado
#### Usuario usado: Mantis+11@symplifica.com | Andres21*
###### 1. Esta listando tan solo la ciudad para lugar de expedicion y solo me lista las mismas ciudades del departamento de naciemiento
###### 2. No me esta indicando error pero tampoco me permite avanzar al añadir numeros en segundo nombre y segundo apellido

### Documentos de empleado
#### Usuario usado: Mantis+11@symplifica.com | Andres21*
###### 1. Se muestran los iconos en color verde, indicando que ya se han cargado archivos y se validaron, pero no se ha cargado nada
###### 2. Establecer formatos especificos para cargar archivos, permite cargar 
###### 3. Se genera error al intentar cargar un archivo
###### 4. Al volver e intentar ingresar de nuevo a documentos de empleado, se genera el siguiente error
```javascript
{error: 500, detail: {type: "RestException",…}}
detail: {type: "RestException",…}
message: "Cannot instantiate process definition ea00a78c-84e5-11ea-b21c-120dfe734381: couldn't execute event listener : The request has [response_code ,health_subscription_type ,contract_id ,contract ,contracts ,employee_documents ,client_id ,token ,contract_type ,response ,employee_id ,vendor_id ,retirement_subscription_type ,client ,id_type ,beneficiaries], but expected [ contract ,beneficiary_documents ,employee_documents ,beneficiaries]"
type: "RestException"
error: 500
```

### Documentos de empleador
###### 1. Se muestran los iconos en color verde, indicando que ya se han cargado archivos y se validaron, pero no se ha cargado nada
###### 2. Establecer formatos especificos para cargar archivos, permite cargar

### Seguridad social onboarding
###### 1. No esta permitiendo la seleccion de entidades de seguridad social
```javascript
{employee_id: ["This field may not be blank."], employer_id: ["This field may not be blank."]}
employee_id: ["This field may not be blank."]
0: "This field may not be blank."
employer_id: ["This field may not be blank."]
0: "This field may not be blank."
```
###### 2. Boton Guardar

###### 3. No me permite añadir beneficiario
```javascript
error_message: "No error was send", error_name: "ANONYMOUS", success: false, error_code: "500",…}
error_code: "500"
error_message: "No error was send"
error_name: "ANONYMOUS"
error_trace: "Clean Error Delegate"
success: false
```

#### Edicion de Contrato y salario
###### 1. Responsive no funciona de manera correcta
###### 2. Edicion contrato no funciona

#### Checkout
###### Tarjetas de credito duplicadas deberi listarme solo una
###### Ajuste de imagen de carga en checkout


#### Finalizar registro
#### Usuario usado: Catalina+10@symplifica.com | Andres21*
###### 1. Al darle click en finalizar registro esta generando error en frontend y backend


