<BEGIN PYTHON_TEMPLATE>
Modules:: 
[
  {MODULE: app, IMPORTS: [flask, sqlalchemy], FUNCTIONS: [create_app, init_db]},
  {MODULE: models, IMPORTS: [sqlalchemy], FUNCTIONS: [Customer, Order, Product]},
  {MODULE: routes, IMPORTS: [flask], FUNCTIONS: [getCustomers, getOrders, getProducts]}
]
Classes:: 
[
  {CLASS: Customer, METHODS: [__init__, __repr__], ATTRIBUTES: [id, name, email]},
  {CLASS: Order, METHODS: [__init__, __repr__], ATTRIBUTES: [id, customer_id, order_date]},
  {CLASS: Product, METHODS: [__init__, __repr__], ATTRIBUTES: [id, name, price]}
]
Dictionaries: 
[
  {DICTIONARY: customer_dict, KEYS: [id, name, email], VALUES: [1, 'John Doe', 'johndoe@example.com']}
]
</END PYTHON_TEMPLATE>
---

<BEGIN PYTHON_TEMPLATE>
Modules:: 
[
  {MODULE: app, 
    IMPORTS: [flask, sqlalchemy, jsonify], 
    FUNCTIONS: [
      {NAME: create_app, PARAMETERS: [], RETURNS: Flask},
      {NAME: init_db, PARAMETERS: [], RETURNS: None}
    ]
  },
  {MODULE: models, 
    IMPORTS: [sqlalchemy], 
    FUNCTIONS: [
      {NAME: Customer, PARAMETERS: [id, name, email], RETURNS: Customer object},
      {NAME: Order, PARAMETERS: [id, customer_id, order_date], RETURNS: Order object},
      {NAME: Product, PARAMETERS: [id, name, price], RETURNS: Product object}
    ]
  },
  {MODULE: routes, 
    IMPORTS: [flask, jsonify], 
    FUNCTIONS: [
      {NAME: getCustomers, PARAMETERS: [], RETURNS: JSON response},
      {NAME: getOrders, PARAMETERS: [], RETURNS: JSON response},
      {NAME: getProducts, PARAMETERS: [], RETURNS: JSON response}
    ]
  }
]
Classes:: 
[
  {CLASS: Customer, 
    METHODS: [
      {NAME: __init__, PARAMETERS: [id, name, email], RETURNS: None},
      {NAME: __repr__, PARAMETERS: [], RETURNS: string}
    ],
    ATTRIBUTES: [
      {NAME: id, TYPE: int, DESCRIPTION: Unique customer ID},
      {NAME: name, TYPE: string, DESCRIPTION: Customer name},
      {NAME: email, TYPE: string, DESCRIPTION: Customer email}
    ]
  },
  {CLASS: Order, 
    METHODS: [
      {NAME: __init__, PARAMETERS: [id, customer_id, order_date], RETURNS: None},
      {NAME: __repr__, PARAMETERS: [], RETURNS: string}
    ],
    ATTRIBUTES: [
      {NAME: id, TYPE: int, DESCRIPTION: Unique order ID},
      {NAME: customer_id, TYPE: int, DESCRIPTION: Foreign key referencing the customers table},
      {NAME: order_date, TYPE: date, DESCRIPTION: Date the order was placed}
    ]
  },
  {CLASS: Product, 
    METHODS: [
      {NAME: __init__, PARAMETERS: [id, name, price], RETURNS: None},
      {NAME: __repr__, PARAMETERS: [], RETURNS: string}
    ],
    ATTRIBUTES: [
      {NAME: id, TYPE: int, DESCRIPTION: Unique product ID},
      {NAME: name, TYPE: string, DESCRIPTION: Product name},
      {NAME: price, TYPE: float, DESCRIPTION: Product price}
    ]
  }
]
Dictionaries: 
[
  {DICTIONARY: customer_dict, 
    KEYS: [id, name, email], 
    VALUES: [
      {id: 1, name: 'John Doe', email: 'johndoe@example.com'},
      {id: 2, name: 'Jane Doe', email: 'janedoe@example.com'}
    ]
  }
]
</END PYTHON_TEMPLATE>