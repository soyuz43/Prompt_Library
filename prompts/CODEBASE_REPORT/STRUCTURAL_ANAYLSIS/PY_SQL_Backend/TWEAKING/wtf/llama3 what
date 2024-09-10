 To increase the number of code blocks used by the LLM, you can try the following:

1. **Specify the number of code blocks**: You can add a hint to your prompt like `"> Include code snippets: 3"` to request a specific number of code blocks.
    
2. **Use a larger model**: Larger models like `llm-2-4096` or `llm-3-8192` have a higher capacity to generate more code blocks.
    
3. **Provide context**: Give more context about the code you want to generate, like the programming language, task, or functionality. This can help the LLM understand what you need and generate more relevant code blocks.
    
4. **Try different prompts**: Rephrase your prompt or try different phrasing to see if the LLM responds with more code blocks.
    

Here's an example prompt that includes some of these suggestions:

```
"> Include code snippets: 3
Generate Python code for a simple calculator that takes in math expressions as input and evaluates them. Use functions for addition, subtraction, multiplication, and division. Also, include a main function to handle user input.
> Model: llm-2-4096"
```

Feel free to experiment and see what works best for your use case!



-------------------------


* **SQL Analysis**
	+ **Table Analysis**
		- **Template:** SQL Table Analysis
		- **Tasks:** Analyze table structure, identify relationships, document findings
	+ **View Analysis**
		- **Template:** SQL View Analysis
		- **Tasks:** Analyze view definition, identify dependencies, document findings
	+ **Relationship Analysis**
		- **Template:** SQL Relationship Analysis
		- **Tasks:** Identify table relationships, document foreign keys, analyze data flow
* **Python API Layer Analysis**
	+ **Module Analysis**
		- **Template:** Python Module Analysis
		- **Tasks:** Analyze module structure, identify functions and classes, document findings
	+ **Function Analysis**
		- **Template:** Python Function Analysis
		- **Tasks:** Analyze function definition, identify parameters and returns, document findings
	+ **Class Analysis**
		- **Template:** Python Class Analysis
		- **Tasks:** Analyze class structure, identify methods and attributes, document findings

## SQL Template:
Scope
{LANGUAGE: SQL}
{SCOPE: TABLES|COLUMNS|VIEWS| }

<BEGIN SQL TEMPLATE>
```markdown
## SQL Database Analysis and Documentation

### SQL Database Categorization and Deconstruction:
- **Tables**:
    {TABLES: [
    {name: "", columns: []},
    {name: "", columns: []},
    ]}
    
- **Views**:
    {VIEWS: [
    {name: "", definition: ""},
    {name: "", definition: ""}
    ]}
### SQL Observations and Recommendations
Categories: {CATEGORIES: [, , ]}
Priorities: {PRIORITIES: [, , ]}
```
```
</END SQL TEMPLATE>

## Python Template:
Scope:
{LANGUAGE: PYTHON}
{SCOPE: MODULE|FUNCTION|CLASS|DICTIONARY}  

<BEGIN PYTHON TEMPLATE>
```markdown
## Python API Layer Analysis and Documentation

### Scope

### Python API Layer Categorization and Deconstruction:
- **Modules/Scripts**:
    {MODULES: [
    {name: "", functions: [], imports: []},
    {name: "", functions: [], imports: []},
    ]}

- **Functions**:
    {FUNCTIONS: [
    {name: "", parameters: [], returns: []},
    {name: "", parameters: [], returns: []},
    ]}

- **Classes**:
    {CLASSES: [
    {name: "", methods: [], attributes: []},
    {name: "", methods: [], attributes: []},
    ]}

- **Hierarchy of Functions**
    {HIERARCHY}