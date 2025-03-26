# Inteligencia Artificial Generación de Prompts

### Alumno: Thallys Gomes Leandro
### Curso: Inteligencia Artificial Generación de Prompts
### Comision: 84165
### Año: 2025

## Entrega 2

### Consigna: 
#### Desarrollarás  una POC (proof of concept) que permita, a través de una jupyter notebook, mostrar una implementación utilizando las técnicas de Fast prompting para solucionar el problema seleccionado.

> Usando Chat GPT probanos 2 prompts para conseguir una Fast prompting
En la primera, unicamente solitamos que se pusiera en el roll especifico y al consultar el Chat pasa la información solicitada y una brebe explicación sobre la consulta. 
#### Prompt: 
> Usted está en el roll de un biólogo experto, pasaré el nombre de algún ser vivo y me informarás a que reino pertenece.

#### [Resultado](https://github.com/Thallys8/Curso_IA_Coder_House/blob/main/Captura%20de%20Fast%20prompting%20-%20Teste%201.PNG)

> Al establecer que queríamos únicamente la respuesta, sin la descripción, el Chat nos responde concisamente, aun en los casos que hay divergencia, y solo nos da explicaciones caso la consulta no esté en el escopo de la respuesta. 

#### Prompt: 
> Usted está en el roll de un biólogo experto, pasaré el nombre de algún ser vivo y me informarás únicamente a que reino pertenece, sin descripciones.

#### [Resultado](https://github.com/Thallys8/Curso_IA_Coder_House/blob/main/Captura%20de%20Fast%20prompting%20-%20Teste%202.PNG)


#### Conclusión: 
> Identificamos que para conseguir respuestas concisas es necesario que esto esté muy claro en el prompt, no solo el hecho designar un roll especifico, ya que por default el Chat está configurado para el rol de asistente, mas también definir los parámetros de la respuesta, si deseamos que nos explique y justifique su respuesta o so solamente deseamos que sea una respuesta objetiva. 
