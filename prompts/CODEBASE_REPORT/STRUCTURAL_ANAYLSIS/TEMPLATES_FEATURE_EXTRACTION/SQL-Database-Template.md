<BEGIN SQL_TEMPLATE>
Tables:: 
[
  {TABLE_NAME: customers, COLUMNS: [id, name, email]},
  {TABLE_NAME: orders, COLUMNS: [id, customer_id, order_date]},
  {TABLE_NAME: products, COLUMNS: [id, name, price]}
]
Notable Relationships:: 
[
  {FOREIGN_KEYS: [orders.customer_id -> customers.id], REFERENCED COLUMN: id}
]
Indexes::
[
  {TABLE_NAME: customers, COLUMNS: [id], TYPE: PRIMARY KEY},
  {TABLE_NAME: orders, COLUMNS: [id], TYPE: PRIMARY KEY},
  {TABLE_NAME: products, COLUMNS: [id], TYPE: PRIMARY KEY}
]
</END SQL_TEMPLATE>
---

<BEGIN SQL_TEMPLATE>
Tables:: 
[
  {TABLE_NAME: customers, 
    COLUMNS: [
      {NAME: id, TYPE: int, DESCRIPTION: Unique customer ID},
      {NAME: name, TYPE: string, DESCRIPTION: Customer name},
      {NAME: email, TYPE: string, DESCRIPTION: Customer email}
    ]
  },
  {TABLE_NAME: orders, 
    COLUMNS: [
      {NAME: id, TYPE: int, DESCRIPTION: Unique order ID},
      {NAME: customer_id, TYPE: int, DESCRIPTION: Foreign key referencing the customers table},
      {NAME: order_date, TYPE: date, DESCRIPTION: Date the order was placed}
    ]
  },
  {TABLE_NAME: products, 
    COLUMNS: [
      {NAME: id, TYPE: int, DESCRIPTION: Unique product ID},
      {NAME: name, TYPE: string, DESCRIPTION: Product name},
      {NAME: price, TYPE: float, DESCRIPTION: Product price}
    ]
  }
]
Notable Relationships:: 
[
  {FOREIGN_KEYS: [
    {TABLE_NAME: orders, COLUMN_NAME: customer_id, REFERENCES: customers(id)}
  ]}
]
Indexes::
[
  {TABLE_NAME: customers, COLUMNS: [id], TYPE: PRIMARY KEY},
  {TABLE_NAME: orders, COLUMNS: [id], TYPE: PRIMARY KEY},
  {TABLE_NAME: products, COLUMNS: [id], TYPE: PRIMARY KEY}
]
</END SQL_TEMPLATE>