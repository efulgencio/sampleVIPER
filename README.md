# sampleVIPER
Simple VIPER sample one use case

Castellano 
---------------------------------------------------------------

Ejemplo básico de un caso de uso utilizando VIPER (Clean Architecture).

PRESENTER
INTERACTOR
VIEW

VIPER es una aplicación de Clean Architecture para iOs.

VIPER es un acrónimo:

VIEW: Muestra lo que se le dice que por el Presentator.
INTERACTOR: Contiene la lógica de negocio según lo especificado por un caso de uso.
PRESENTADOR: Contiene vista lógica para la preparación de contenidos para la pantalla (como se recibió del INTERACTOR).
ENTIDAD: Contiene objetos modelo básico utilizado por el INTERACTOR.
RUTA: Contiene la lógica de navegación para describir qué pantalla se muestran y en qué orden.

Esta separación también se ajusta al principio de responsabilidad individual.
El INTERACTOR es responsable ante el analista de negocios, el PRESENTER representa el diseñador de interacción, y la VIEW es responsable del diseñador visual.




Inglés
---------------------------------------------------------------
Basic example of a use case using VIPER (Clean Architecture).

PRESENTER
INTERACTOR
VIEW

VIPER is an application of Clean Architeture to iOs.

VIPER is a backronym for:

View
Interactor
Presenter
Entity
Routing 

VIEW: Display what it is told to by the Presenter.
INTERACTOR: Contains the business logic as specified by a use case.
PRESENTER: Contains view logic for preparing content for display  (as received from the Interactor).
ENTITY: Contains basic model object used by the interactor.
ROUTING: Contains navigation logic for describing which screen are shown in which order.


This separation also conforms to the SINGLE RESPONSIBILITY PRINCIPLE. 
The ITERACTOR is responsible to the business analyst, the PRESENTER represents the interaction designer, and the VIEW is reponsible to the visual designer.


