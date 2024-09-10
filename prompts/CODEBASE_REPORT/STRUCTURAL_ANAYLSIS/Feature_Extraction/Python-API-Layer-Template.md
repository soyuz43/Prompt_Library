**Extract the features of the Python API layer of the provided codebase:**
EXAMPLE OUTPUT::
```
modules: list
classes: list
functions: list
dictionaries: list

modules:
- name: app
  imports: flask, sqlalchemy, jsonify
  functions: create_app, init_db

- name: models
  imports: sqlalchemy
  functions: Customer, Order, Product

- name: routes
  imports: flask, jsonify
  functions: getCustomers, getOrders, getProducts

classes:
- name: Customer
  methods: __init__, __repr__
  attributes: id, name, email

- name: Order
  methods: __init__, __repr__
  attributes: id, customer_id, order_date

- name: Product
  methods: __init__, __repr__
  attributes: id, name, price

dictionaries:
- name: customer_dict
  keys: id, name, email
  values:
  - id: 1
    name: John Doe
    email: johndoe@example.com
  - id: 2
    name: Jane Doe
    email: janedoe@example.com
```

**Output Parameters:**

Ensure the output is generated in RAW_MARKDOWN format, with:

- Headers
    
- Numbered lists
    
- Bullet points
    
- Bold emphasis
    
- No empty sections
    
- No introductory text
    
- Verbose output
    
- Full and detailed length
    
- Included code snippets
    
- Consistent formatting
    