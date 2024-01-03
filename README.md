Entities: Subscriber, Trainer, Equipment.
  
Mapping Routes for the subscriber:
  Retrieving the list of subscribers:
    GET https://localhost:7152/api/prod
  Retrieving a subscriber by ID:
    GET https://localhost:7152/api/prod/{id}
  Adding a subscriber:
    POST https://localhost:7152/api/prod
  Subscriber update:
    PUT https://localhost:7152/api/prod/${id}
  Subscriber status update:
    PUT https://localhost:7152/api/prod/${id}/status


Mapping Routes for the trainer:
  Retrieving the list of trainers:
    GET https://localhost:7152/api/prod
  Retrieving a trainer by ID:
    GET https://localhost:7152/api/prod/{id}
  Adding a trainer:
    POST https://localhost:7152/api/prod
  Trainer update:
    PUT https://localhost:7152/api/prod/${id}
  Trainer status update:
    PUT https://localhost:7152/api/prod/${id}/status


Mapping Routes for the equipment:
  Retrieving the list of equipment:
    GET https://localhost:7152/api/prod
  Retrieving a device by ID:
    GET https://localhost:7152/api/prod/{id}
  Adding a device:
    POST https://localhost:7152/api/prod
  device update:
    PUT https://localhost:7152/api/prod/${id}
  Device deletion:
    DELET https://localhost:7152/api/prod/${id}
