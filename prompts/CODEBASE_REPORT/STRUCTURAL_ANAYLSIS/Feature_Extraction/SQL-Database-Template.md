**Extract the features of the provided SQL database components of the codebase:**
EXAMPLE OUTPUT:: 
```
tables: list
relationships: list
indexes: list

tables:
- name: customers
  columns: id, name, email

- name: orders
  columns: id, customer_id, order_date

- name: products
  columns: id, name, price

relationships:
- table: orders
  column: customer_id
  references: customers(id)

indexes:
- table: customers
  columns: id
  type: PRIMARY KEY

- table: orders
  columns: id
  type: PRIMARY KEY

- table: products
  columns: id
  type: PRIMARY KEY
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
    