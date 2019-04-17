---?image=template/img/graph.jpg
@title[List Content Templates]

## @color[white](Balena.io ecosystem)

@fa[arrow-down text-white]

@snap[south-west text-white]
*formerly Resin.io*
@snapend

note:
balena es en espanol
less then a year ago Balena was Resin, info about why can be read in their blog. Short story, it was trademark dispute. 
+++

@snap[midpoint]
Mostly* open source.
OpenBalena (beta)
Contributer to Moby
@snapend
note:
Balena is an upstream 
+++?image=template/img/balena_workflow.png&position=center right&size=90% auto
@title[Title + Concise List]

@snap[south-west template-note text-gray]
Balena Workflow
@snapend

+++?color=linear-gradient(to right, #022c8c, #f2e235)
@snap[west list-content-verbose span-100]
<br>
@ul[](false)
- Balena is built with the goal of 100% updateability
- Device provisioning key pulls image when its pushed to registry
- Dockerfile(s) and docker-compose.yml files build containers
- Once containers are built they are stored in Balenas Container registry
- devices can be managed from Balenas' Dashboard
@ulend
@snapend
