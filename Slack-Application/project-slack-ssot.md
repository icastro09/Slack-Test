# Project Title
Mention here the name of the company owning the project and the link to their website.

## Summary and Scope

[Add a brief summary of the project and its scope here.]

The summary should consist of a maximum of three paragraphs or a link to a file containing the project description. It is important to clearly state the challenge of the project and how it will be addressed, as well as the expected outcomes for both the client and Akurey.

Deliverables
Regarding the project scope, it is important to clearly define what Akurey will deliver and what parts are the responsibility of someone else. A link to a document or platform is also acceptable. It is also crucial to outline any potential business opportunities, improvements, and new fields of research that may arise from the project, either for Akurey or the client.

## Client Description

### name of the client

![Client Logo](link_to_client_logo)

- what is the business of the client
- stakeholders

## Concept Map

if its important add a concept map diagram of the project or business.

## Project Folder Structure

![Folder Structure](link_to_image_of_folder_structure)

The folder structure can be divided into frontend, backend, and other categories. If the image is not self-explanatory, please provide clarification bullets for each folder to ensure understanding.

## Architecture Diagram

When required add an architecture diagram of the project here.

## Services and Technical Troubleshooting

- list and explanation of services, servers, drivers required for this project
- Add a list of common technical issues and their troubleshooting steps here.

## Team Members

| Name | Position | Contact Buddy |
| --- | --- | --- |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |
| [Add team member name here.] | [Add team member position here.] | [Add team member contact buddy here.] |

## Requirement

log of requirements changes

* Kafay Ng [2023-04-26T20:53:32.225Z]

Message: Soledad Kopper Kafay Ng ya estoy satisfecho con esta plantila <https://github.com/akurey/aktech/blob/master/project-slack-ssot.md>

Notes: Nuñez shared a link


* Kafay Ng [2023-04-26T21:02:34.915Z]

Message: Claro digamos que tendría este formato

```
* Buenos días, una consulta
Con respecto al update md file se había pensado que tuviera este formato [Wed, 05 Apr 2023 09:11:40] 

[Additional Notes]
```

Algo así, pero queremos guardar de quien fue la propuesta? o quien mando el update?
O simplemente que se vaya agregando y ya? :thinking_face:  Lo digo en caso de que se quiera saber quien fue el que hizo la propuesta o hizo push al md file

Notes: New Requirem
#### **Kafay Ng [2023-04-27T20:40:12.121Z]**

Message: Buenas tardes, unas notas sobre la reu que acabamos de tener entre Rodrigo Nunez y yo
• Manejo de token para git: se va a utilizar el método de crear un token con un usuario nuevo (dependiendo del cliente) o que un integrante creé el token. Este token tiene la posibilidad de no experirar entonces quedará a disposición del proyecto/cliente
• Manejo de los repositorios: los repositorios van a tener únicamente los md files del proyecto con la información (scopes, requirements, teams, etc…) por lo que se van a clonar los repositorios a nivel de codigo y se van a mantener en memoria en vez de borrarlos una vez terminado el proceso de edición -&gt; git add -&gt; git commit -&gt; git push -&gt; merge
• Buscar un módulo para la escritura de archivos que maneje la inserción en lugares específicos de un archivo para poder evitar tener un buffer de un antes del string a insertar y un después del string a insertar y hacerles join a un solo string grande
* Kafay Ng [2023-04-27T20:59:08.046Z]

Message: <https://github.com/akurey/AK-Slack-App/blob/main/README.md>

Notes: Update

#### **Kafay Ng [2023-05-11T16:41:34.311Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:


#### **Kafay Ng [2023-05-11T17:03:45.624Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Marcela's Ad

#### **Kafay Ng [2023-05-11T17:25:10.300Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T17:31:04.495Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's announcement regarding fofo

#### **Kafay Ng [2023-05-11T17:35:19.784Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T17:37:32.673Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T18:48:09.629Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's invitation to fofo coming to CR

#### **Kafay Ng [2023-05-11T20:37:53.756Z]** 

Message: Buenos días, bastante bien
Veo que podemos hacer el bypass del validation que le comente ayer con el token ya generado, hoy me estoy dedicando a ya mover toda la implementación de nodegit a octokit que es lo que se usa el github api

Notes: Kafa'ys update about slack app
Push sent  at: 2:37pm

#### **Kafay Ng [2023-05-11T20:45:47.738Z]** 

Message: Lo que pasa es que la versión con la que se está haciendo build localmente está diseñado para esa arquitectura pero cuando se sube a serverless, tiene otra arquitectura, entonces  lo que me dijo Fer es que se tendría que instalar el cli al serverless para que funcione porque se está usando el modulo nodegit para la escritura, igual estoy esperando a ver que me dice Bryan  porque puede que él tenga otro approach

Notes: Sol's update about slack app issue
Push sent  at: 2:45pm

#### **Kafay Ng [2023-05-11T20:54:21.923Z]** 

Message: Pero por alguna razón pareciera que mi token de git expira, entonces ahorita en unos 5mn les hago otro spam

Notes: Update at 2:54pm

#### **Jose Andrés Barboza González [2023-05-12T20:34:03.624Z]** 

Message: cat

Notes: Holi

#### **Ixel Castro Richard [2023-05-12T20:41:42.226Z]** 

Message: Slack procesa por eventos de clicks a diferentes componentes y no por form
Entonces lo que esta pasando es que ahí hubo un post de evento tipo dropdown y select que en realidad no nos sirve pero slack siempre lo envia como evento, el error es que no se esta haciendo nada con ese evento

Notes: Update

#### **Ixel Castro Richard [2023-05-12T21:28:46.650Z]** 

Message: <https://github.com/akurey/AK-Slack-App#add-akurey-source-application-to-the-channels-on-slack>

Notes: Update

## Technical

log of technical decisions

#### **Kafay Ng [2023-05-11T18:39:14.484Z]** 

Message: Estoy viendo que no llega, hace el update al git pero no manda el mensaje
Pero estoy viendo que podría ser un issue con lambda <https://github.com/slackapi/bolt-js/issues/1299>
Pero que hay alternativas como lazyloading

Notes: Kafay's issue

#### **Kafay Ng [2023-05-11T18:42:27.747Z]** 

Message: Cree estos dos tickets <https://ak-slack-app.atlassian.net/browse/ASA-51> y <https://ak-slack-app.atlassian.net/browse/ASA-50> (este ya tiene MR)

Notes: Kafay's MRs

#### **Kafay Ng [2023-05-11T18:58:25.367Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T19:00:46.304Z]** 

Message: I would like to make a reading club mainly with books for business leaders and others.
Would anyone be interested? :book::books:
<#C012A54JPBQ|books>

Notes: Montse's Ad

#### **Kafay Ng [2023-05-11T19:03:31.476Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's invitation

#### **Kafay Ng [2023-05-11T19:11:42.413Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Marcela's Update

#### **Kafay Ng [2023-05-11T19:22:20.105Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T19:23:17.308Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T19:28:34.875Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T19:38:50.110Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T20:07:08.770Z]** 

Message: Hello hello. Are you ready to have fun tomorrow? :partyparrot: We have free breakfast, ice cream, tacos, and two amazing workshops :fire: Remember to sign up: <http://go.akurey.com/attendance|go.akurey.com/attendance> :blue_heart:

Notes: Update

#### **Kafay Ng [2023-05-11T20:23:27.830Z]** 

Message: Buenos días, bastante bien
Veo que podemos hacer el bypass del validation que le comente ayer con el token ya generado, hoy me estoy dedicando a ya mover toda la implementación de nodegit a octokit que es lo que se usa el github api

Notes: update

#### **Kafay Ng [2023-05-12T16:17:48.674Z]** 

Message: GM!
 :hourglass:️ Y: reviewing FWD program
 :hourglass_flowing_sand: T: Reviewing FWD program, 1:1 and I'll be off the afternoon
 :no_entry_sign: B: None


#### **Kafay Ng [2023-05-12T16:39:49.441Z]** 

Message: Hola, Kafay, todo bien?
Sol me mandó a hablar con usted para que me ayudara con cómo voy a testear la app de Slack en la que estaban trabajando

Notes: Update test

#### **Ixel Castro Richard [2023-05-12T20:11:17.877Z]** 
Notes: Correct way of getting notifications

#### **Ixel Castro Richard [2023-05-12T20:32:14.006Z]** 

Message: Slack procesa por eventos de clicks a diferentes componentes y no por form
Entonces lo que esta pasando es que ahí hubo un post de evento tipo dropdown y select que en realidad no nos sirve pero slack siempre lo envia como evento, el error es que no se esta haciendo nada con ese evento

Notes: Technical Issue

#### **Rodrigo Nunez [2023-05-12T21:23:53.810Z]** 

Message: Hola buenos días, para ya probarlos con otros proyectos sería modificar el data.json que esta en el repo y si se quiere que el chatbot mande mensajes a channels se tiene que agregar a los channels. En el readme esta más información de como hacerle setup


#### **Kafay Ng [2023-05-15T17:41:02.147Z]** 

Message: Recordé que tenemos el alias que se creo para aws <mailto:slack-poc-aws@akurey.com|slack-poc-aws@akurey.com>


#### **Kafay Ng [2023-05-15T17:52:08.983Z]** 

Message: GM! Sorry I couldn't, had another meeting
 :hourglass:️ Y: Demo and reviewing the program
 :hourglass_flowing_sand: T: I'll be having a couple of meetings during the morning then I'll continue reviewing the program and creating some figma files for the course
 :no_entry_sign: B: None

Notes: Status Update

#### **Kafay Ng [2023-05-16T14:36:20.188Z]** 

Message: <https://files.slack.com/files-tmb/T2DPLE8AY-F0588PY7N3A-307b69ec49/internal_message_64.png>

Notes: TEST QA

#### **Kafay Ng [2023-05-16T14:41:30.197Z]** 

Message: GM! Sorry I couldn't, had another meeting
 :hourglass:️ Y: Demo and reviewing the program
 :hourglass_flowing_sand: T: I'll be having a couple of meetings during the morning then I'll continue reviewing the program and creating some figma files for the course
 :no_entry_sign: B: None

Notes: TEST Prod

## Scope

log of decisions reducing or adding time to the scope
* Kafay Ng [2023-04-26T20:54:16.174Z]

Message: Buenas tardes, unas notas sobre la reu que acabamos de tener entre Rodrigo Nunez y yo
• Manejo de token para git: se va a utilizar el método de crear un token con un usuario nuevo (dependiendo del cliente) o que un integrante creé el token. Este token tiene la posibilidad de no experirar entonces quedará a disposición del proyecto/cliente
• Manejo de los repositorios: los repositorios van a tener únicamente los md files del proyecto con la información (scopes, requirements, teams, etc…) por lo que se van a clonar los repositorios a nivel de codigo y se van a mantener en memoria en vez de borrarlos una vez terminado el proceso de edición -&gt; git add -&gt; git commit -&gt; git push -&gt; merge
• Buscar un módulo para la escritura de archivos que maneje la inserción en lugares específicos de un archivo para poder evitar tener un buffer de un antes del string a insertar y un después del string a insertar y hacerles join a un solo string grande.

Notes: Kafay explained the new scope after meeting with Nuñez

#### **Ixel Castro Richard [2023-05-12T21:30:18.955Z]** 

Message: <https://github.com/akurey/AK-Slack-App#add-akurey-source-application-to-the-channels-on-slack>

Notes: Update

## Notes

log of project notes 


#### **Kafay Ng [2023-05-12T15:24:25.127Z]** 

Message: <!here> La otra semana viene Fofo(rodolfo cordero) desde Argentina después de varios años. Entonces los invito a ir a la oficina si tienen la oportunidad, para que vacilemos todos y pasemos el día bonito :slightly_smiling_face:
Por ahí les pasé invite para que les quede de reminder. Como siempre es opcional, pero espero verlos!

Notes: Jose's invitation for fofo

#### **Ixel Castro Richard [2023-05-12T17:22:09.523Z]** 

Message: <https://github.com/akurey/AK-Projects-Single-Source>

Notes: Update
