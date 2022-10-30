# 100-days-of-code-latinas-berlin
100 días de programación con Latinas en Tecnología Berlin

## Dia 1: Octubre 11, 2022 
 
**Progreso del dia**: Investigue y comparti recursos en español de como crear una cuenta en Github, crear un repositorio, y editar un README.

## Dia 2: Octubre 12, 2022

**Progreso del dia**: Agregue una revisión ortográfica en un repositorio utilizando [Cspell](https://cspell.org/). Cree un comando para agregar palabras a el diccionario personalizado [Makefile][makefile]. También active la revision ortográfica automáticamente para que se revise todo el repositorio con un gancho pre-commit, utilizando [Husky](https://github.com/typicode/husky).

 ## Dia 3: Octubre 13, 2022

**Progreso del dia**: Agregue un [recurso](https://github.com/telia-oss/github-pr-resource) que agrega un comentario en los Pull Requests del repositorio de ayer desde un pipeline[(CI/CD)][concourse]. El comentario contiene los resultados de la revisión ortográfica, para cuando los PR son creados desde GH directamente, ya que el repositorio es de documentación y no código.

## Dia 4: Octubre 14, 2022

**Progreso del dia**: Recuperé este dia con una hora de lectura de documentación de AWS Lambda, para repasar y resolver unas dudas de como escribir lambdas en Ts/node mas eficientemente con CDK.

## Dia 5: Octubre 15, 2022

**Progreso del dia**: Investigue como lograr un sistema para reservar citas usando un chatbot. De todas las opciones que vi la que mas me gusto fue [esta](https://aws.amazon.com/blogs/machine-learning/build-an-appointment-scheduler-interface-integrated-with-meta-using-amazon-lex-and-amazon-connect/). Intentare seguir el blogpost y hacer este, con unas cuantas modificaciones. Me gustaria hacerlo todo usando Infraestructura en forma de código (IaC) quizas con [serverless][https://www.serverless.com/framework/docs/getting-started] o [terraform][terraform] no se. Defini mas o menos que quiero de la infraestructura y creo que omitire lo de la llamada y el mensaje de texto, optando mejor por confirmacion por email, o a través del chatbot si es posible. Y si puedo quizas integrar alguna forma de pago por la cita, vamos a ver...

## Dia 6: Octubre 16, 2022

**Progreso del dia**:  Complete el diagrama de arquitectura con el que voy a empezar utilizando [Draw.io][draw-io]. Empece a leer la documentación de [Terraform][terraform]. Y office-hours con las chicas de LeT-B.

## Dia 7: Octubre 17, 2022

**Progreso del dia**: Recuperé este dia con una hora de debuggig y refactoring de una lambda en Ts. optimize la memoria.

## Dia 8: Octubre 18, 2022

**Progreso del dia**: Empece a leer sobre dynamoDB streams como trigger para una lambda.

## Dia 9: Octubre 19, 2022

**Progreso del dia**: Recuperé este dia: Agregué un corrector ortográfico en español porque 🙈🙊

<!-- ## Dia 10: Octubre 20, 2022

**Progreso del dia**: -->

<!-- ## Dia 11: Octubre 21, 2022

**Progreso del dia**: -->

<!-- ## Dia 12: Octubre 22, 2022

**Progreso del dia**: -->

## Dia 13: Octubre 23, 2022

**Progreso del dia**: empece con el diagrama de arquitectura del servicio de facturación. instalé y configure AWS cli, CDK. typescript desde cero porque no estaba usando mi computador personal. implemente una lamba dummy en ts con [este tutorial](https://bobbyhadz.com/blog/aws-cdk-typescript-lambda)e implementé la infraestructura de DynamoDB, y S3.

## Dia 14: Octubre 24, 2022

**Progreso del dia**: practique usar [PDFKit][pdfkit] con este tutorial para generar una factura, personalize la factura con un logotipo y añadí el campo del IVA, etc.

## Dia 15: Octubre 25, 2022

**Progreso del dia**: Perdí el dia entero tratando de utilizar PDFKit en una lambda creada con CDK, nada que pude lograr que la lambda tuviera acceso al PDFKit  😭   

## Dia 16: Octubre 26, 2022

**Progreso del dia**: Hoy empece con serverless, lei un poco, definí la base de datos y los permisos de ella, un funcion esqueleto, y un esqueleto de api para llamar a la base de datos.

## Dia 17: Octubre 27, 2022

**Progreso del dia**: Lei sobre permisos personalizados en serverless.

## Dia 18: Octubre 28, 2022

**Progreso del dia**: Practiqué la resolución de dependencias obsoletas para eliminar vulnerabilidades de seguridad. También actualicé node a la versión 16 en mi computador, ya que AWS va a depreciar v12 en las lambdas.

## Dia 19: Octubre 29, 2022

**Progreso del dia**: Hoy hice horas de oficina de LeA. Trabajé en el prototipo del servicio de facturación. Comparé qué plugin usar para Ts con serverless y lo aplique. Conseguí que una función creara un PDF (los paquetes correctos se desplegaron en la lambda) y devuelva el PDF codificado en base64. La segunda lambda graba la información de la factura a dynamo como respuesta a la petición del API. Lei un poco sobre AWS SES.

<!-- ## Dia 20: Octubre 30, 2022

**Progreso del dia**: -->

<!-- ## Dia 21: Octubre 31, 2022

**Progreso del dia**: -->

<!-- ## Dia 22: Noviembre 1, 2022

**Progreso del dia**: -->

<!-- ## Dia 23: Noviembre 2, 2022

**Progreso del dia**: -->

<!-- ## Dia 24: Noviembre 3, 2022

**Progreso del dia**: -->

<!-- ## Dia 25: Noviembre 4, 2022

**Progreso del dia**: -->

<!-- ## Dia 26: Noviembre 5, 2022

**Progreso del dia**: -->

<!-- ## Dia 27: Noviembre 6, 2022

**Progreso del dia**: -->

<!-- ## Dia 28: Noviembre 7, 2022

**Progreso del dia**: -->

<!-- ## Dia 29: Noviembre 8, 2022

**Progreso del dia**: -->

<!-- ## Dia 30: Noviembre 9, 2022

**Progreso del dia**: -->

[concourse]: https://concourse-ci.org/
[draw-io]: https://github.com/jgraph/drawio-desktop/releases
[makefile]: https://www.gnu.org/software/make/manual/make.html
[pdfkit]: https://pdfkit.org/
[terraform]: https://learn.hashicorp.com/tutorials/terraform/infrastructure-as-code?in=terraform/aws-get-started
