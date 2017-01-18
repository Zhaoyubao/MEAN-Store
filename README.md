## mini MEAN Store - NodeJS / Express / Angular / MongoDB

### Routing

  Client Route         |    Server Route    | Server Method
  :------------------- |:-------------------|:-------------:
  `/`                  |`/`                 | GET
  `/products`          |`/products`         | GET
                       |`/products`         | POST
                       |`/products/:id`     | PUT
                       |`/products/:id`     | DELETE
  `/orders`            |`/orders`           | GET
                       |`/orders`           | POST
                       |`/orders/:id`       | DELETE
  `/customers`         |`/customers`        | GET
                       |`/customers`        | POST
                       |`/customers/:id`    | DELETE

### Partials

 The base HTML is `/client/index.html`

 Tab      | Description                                 | File Location
 :-------:|---------------------------------------------|--------------
 Dashboard| Store Dashboard                             | `/client/partials/_dashboard.html`
 Products | Show all products and add/delete product    | `/client/partials/_products.html`
 Orders   | Show all orders and add/cancel order        | `/client/partials/_orders.html`
 Customers| Show all customers and add/delete customer  | `/client/partials/_customers.html`

### Dependencies

  On     | Name             | Version | Description
  :-----:|:----------------:|:-------:|----------------------------
  Server | express          | 4.14.0  | web-server
  Server | body-parser      | 1.15.2  | package for parsing requests
  Server | mongoose         | 4.6.8   | mongoDB driver API
  Client | angular          | 1.5.8   | front-end framework
  Client | angular-route    | 1.5.8   | angular plug-in for routing
