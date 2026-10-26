# events

register and query for events about changes in the landscape.

### POST `/events/push`

Push a new event to a registered consumer. Used by an upstream server to notify subscribers of model changes.

**Request body**

Required.

- `application/json`: [Event](../schemas/Event.md)

**Responses**

- `200` — OK

### GET `/events/query/{sequenceId}`

Retrieve changes since the given sequence ID.

**Parameters**

- `sequenceId` (path, required, string)

**Responses**

- `200` — OK
- `308` — Found. This sequence ID does not exist and the url returned with this status code is the next existing one 
in the sequence.
- `404` — Not Found'
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

### POST `/events/register`

Register a new event consumer.

**Request body**

Required.

- `application/json`: object

**Responses**

- `201` — Created

### GET `/events/subscribers`

Retrieve the list of registered event consumers.

**Responses**

- `200` — OK
  - `application/json`: array of string (uri)

### POST `/events/unregister`

Unregister an existing event consumer.

**Request body**

Required.

- `application/json`: object

**Responses**

- `200` — OK
- `404` — URL of callback not found
  - `application/json`: [ErrorString](../schemas/ErrorString.md)

