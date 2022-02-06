# Starter App

The starter app will make a lazy loaded reference to the module default export. And wrap it inside a react suspense component. The resulting component is then bount to the routing entry in the interface file.

The interface file intent is to provide an interface to the rest of the application. This is why the actions and the router is in this file. Since ideally those two are the high level iterface to each component.

## files

interface.tsx
* Actions
* Routing
* Types

module.tsx
* Epic
* Reducer
* Module

form-module
* use`sub-feature`Form,
* `sub-feature`FormActions
* get`sub-feature`FormState
* `sub-feature`FormProvider
    
components directory








