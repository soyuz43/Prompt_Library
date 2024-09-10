
## SQL Template:
---
Scope:
```sql
{LANGUAGE: SQL}
{SCOPE: TABLES|COLUMNS|VIEWS}

<BEGIN SQL TEMPLATE>
- **Tables**:
    {TABLES: [
        {
            table_name: "table1",
            columns: [
                {name: "column1", type: "datatype", constraints: "constraints"},
                {name: "column2", type: "datatype", constraints: "constraints"}
            ],
            primary_key: ["column1"],
            foreign_keys: [
                {column: "column_name", references: "referenced_table(referenced_column)"}
            ]
        },
        {
            table_name: "table2",
            columns: [
                {name: "column1", type: "datatype", constraints: "constraints"}
            ],
            primary_key: ["column1"]
        }
    ]}
- **Views**:
    {VIEWS: [
        {view_name: "view1", definition: "SELECT * FROM table1 WHERE condition;"},
        {view_name: "view2", definition: "SELECT * FROM table2 WHERE condition;"}
    ]}
> CONDITIONAL::    
- + **Indexes**
- + **Triggers**
- + **Stored Procedures**:

</END SQL TEMPLATE>

```
---

## Python API Layer Template:
---
Scope:
```python
{LANGUAGE: PYTHON}
{SCOPE: MODULE|FUNCTION|CLASS|DICTIONARY}

<BEGIN PYTHON TEMPLATE>

- **Modules/Scripts**:
    {MODULES: [
        {name: "module1", functions: ["function1", "function2"], imports: ["import1", "import2"]},
        {name: "module2", functions: ["function3", "function4"], imports: ["import3", "import4"]}
    ]}

- **Functions**:
    {FUNCTIONS: [
        {name: "function1", parameters: ["param1", "param2"], returns: "return_type"},
        {name: "function2", parameters: ["param1", "param2"], returns: "return_type"}
    ]}

- **Classes**:
    {CLASSES: [
        {name: "Class1", methods: ["method1", "method2"], attributes: ["attribute1", "attribute2"]},
        {name: "Class2", methods: ["method3", "method4"], attributes: ["attribute3", "attribute4"]}
    ]}

- **Dictionaries**:
    {DICTIONARIES: [
        {name: "dict1", keys: ["key1", "key2"], values: ["value1", "value2"]},
        {name: "dict2", keys: ["key3", "key4"], values: ["value3", "value4"]}
    ]}

- **Hierarchy of Functions**:
    {HIERARCHY: [
        {name: "function1", calls: ["sub_function1", "sub_function2"]},
        {name: "function2", calls: ["sub_function3", "sub_function4"]}
    ]}

</END PYTHON TEMPLATE>

```