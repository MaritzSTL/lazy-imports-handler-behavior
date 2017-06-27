# lazy-imports-handler-behavior
Pulls in the Polymer.LazyImportsBehavior and listens for an event to tell an instance of this behavior to attempt to import a lazy-group within the provided domain, if it is found then it will stop the event propagation.  Listens for events on the use-capture event cycle. 
