https://www.manning.com/books/redux-in-action

https://github.com/wfro/parsnip

https://blog.isquaredsoftware.com/2016/10/practical-redux-part-0-introduction/

### Flux architecture:
![Flux architecture](https://www.safaribooksonline.com/library/view/redux-in-action/9781617294976/01fig01.jpg "Flux architecture")
### Redux architecture:
![Redux architecture](https://www.safaribooksonline.com/library/view/redux-in-action/9781617294976/01fig08_alt.jpg "Redux architecture")
### connect():
![connect()](https://www.safaribooksonline.com/library/view/redux-in-action/9781617294976/02fig05_alt.jpg "connect()")

### Immutability:
* https://github.com/facebook/immutable-js/
* https://github.com/substantial/updeep
* https://github.com/rtfeldman/seamless-immutable

### Presentational components:
* don’t have dependencies on Redux.
* they introduce determinism into your view renders.
* are easily tested.

### Container components:
* get data from the Redux store via connect.
* use mapStateToProps to pass only relevant data to the component being connected.
* render presentational components.

https://github.com/redux-utilities/flux-standard-action

### Action creators:
![Action creators](https://www.safaribooksonline.com/library/view/redux-in-action/9781617294976/02fig09_alt.jpg "action creators")

### Actions and action creators are closely related and work together to dispatch actions to the store, but they fulfill different roles:
* **Actions —** Objects that describe an event
* **Action creators —** Functions that return actions



