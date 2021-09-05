# Rest (Representational State Transfer)

- REST stands for representational state transfer and was created by computer scientist Roy Fielding.

![img](https://images.slideplayer.com/20/6053440/slides/slide_3.jpg)

# RESTful API

- A RESTful API is an architectural style for an application program interface (API) that uses HTTP requests to access and use data. That data can be used to GET, PUT, POST and DELETE data types, which refers to the reading, updating, creating and deleting of operations concerning resources.

# identifier of a resource

- A Uniform Resource Identifier (URI) is a unique sequence of characters that identifies a logical or physical resource used by web technologies. ... A URL provides the location of the resource. A URI identifies the resource by name at the specified location or URL.

# HTTP verbs

- The primary or most-commonly-used HTTP verbs (or methods, as they are properly called) are POST, GET, PUT, PATCH, and DELETE. These correspond to create, read, update, and delete (or CRUD) operations, respectively. There are a number of other verbs, too, but are utilized less frequently.

![img](https://miro.medium.com/max/1200/1*J9fy4Ue8Sclxs6axVztAGw.png)

# URI

- A Uniform Resource Identifier (URI) is a unique sequence of characters that identifies a logical or physical resource used by web technologies. URIs may be used to identify anything, including real-world objects, such as people and places, concepts, or information resources such as web pages and books.

![img](https://slidetodoc.com/presentation_image/03a0efd605c4e8f01bb2c3adde003fd2/image-2.jpg)

# Chatty API

- Chatty API is one that requires consumer to make tremendous (subjective matter) amount of distinct API calls to get needed information about a resource. George Reese has defined chatty API as any API that requires consumer to do more than a single call to perform a single, common operation.

![img](https://s3-us-west-2.amazonaws.com/assertible/blog/swagger-petstore-store-endpoints.png)

### What status code does an unsuccessful GET request return?

- If not valid, 400 Bad Request is returned. Order is processed. If the order is successful, a 201 Created is returned for the order. If an unexpected error is encountered, a 500 Server Error is returned.

### What status code does a successful POST request return?

- This means the request was successful and the server created a new resource.

### What status code does a successful DELETE request return?

- A successful response of DELETE requests SHOULD be HTTP response code 200 (OK) if the response includes an entity describing the status, 202 (Accepted) if the action has been queued, or 204 (No Content) if the action has been performed but the response does not include an entity.

![img](https://i0.wp.com/makeseleniumeasy.com/wp-content/uploads/2019/03/image-2.png?fit=944%2C373)
