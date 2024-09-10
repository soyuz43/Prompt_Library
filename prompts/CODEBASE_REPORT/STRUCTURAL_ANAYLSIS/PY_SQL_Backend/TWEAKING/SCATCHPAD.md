------
{TRANSITION=TRUE}
------

# SQL and Python Analysis

## TASK:
Model::Analyze the provided SQL and Python API layer codebase thoroughly, breaking down each script or function in natural language to elucidate its role and contribution to the application's overall functionality. This analysis should separate the python and SQL operations then manually document and then report your findings following all standards required for thorough and professional documentation. The overarching goal for the final report is to manually document both the grand picture and minute details to the user. The analysis and resulting final report should use the following templates below::

**Expertise Level:** Intermediate (with potential for advanced skills)

**Summary:**
Provide a brief overview of the analysis and findings, including:

* SQL database structure and relationships
* Python API layer architecture and functionality
* Key findings and recommendations

**Breakdown:**

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
* **Documentation**
	+ **SQL Database Documentation**
		- **Template:** SQL Database Documentation
		- **Tasks:** Document database structure, tables, views, relationships
	+ **Python API Layer Documentation**
		- **Template:** Python API Layer Documentation
		- **Tasks:** Document module structure, functions, classes, and relationships

**Examples for Ambiguous Sections:**

* **Hierarchy of Functions**
	+ Example 1: Simple Calculator Application
		- Input: `add(2, 3)`
		- Processing: `add` function calls `calculate` function
		- Output: `5`
	+ Example 2: Complex Software Application
		- Input: `login(username, password)`
		- Processing: `login` function calls `authenticate` function, which calls `database` function
		- Output: `success` or `failure`

{**FOR THE SQL FILE(S) USE THE FOLLOWING TEMPLATE::**}
---

    ## SQL Database Analysis and Documentation
    ### Scope
    {Language: SQL}
    {SCOPE: FUNCTION/MODULE}

    ###  SQL Database Explanation
    #### Tables
    - **Table Name**: {name}
        - **Columns**: [{column_name: data_type}]
        - **Relationships**: {relationships}

    #### Views
    - **View Name**: {name}
        - **Query**: {query}

    ### SQL Conventions and Best Practices
    {CONVENTIONS}

    ###  SQL Database Observations and Recommendations
    Categories: {CATEGORIES: [, , ]}
    Priorities: {PRIORITIES: [, , ]}

<|END SQL TEMPLATE|>

{**FOR THE PYTHON FILE(S) USE THE FOLLOWING TEMPLATE::**}
---
    ## Python API Layer Analysis and Documentation

    ### Scope
    {LANGUAGE: PYTHON}
    {SCOPE: FUNCTION/MODULE}

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

    ### Python Conventions and Best Practices
    {CONVENTIONS}

    ### Hierarchy of Functions
    {HIERARCHY}

    ### Natural Language Breakdown
    {NATURAL LANGUAGE BREAKDOWN}


    ## **Python Observations and Recommendations**
    Categories: {CATEGORIES: [, , ]}
    Priorities: {PRIORITIES: [, , ]}
---
<|END PYTHON TEMPLATE|>

Your final

------

Here is the revised template from the line "<|END PYTHON TEMPLATE|>" down, with the added summary section improvement:

<|END PYTHON TEMPLATE|>

**Summary:**  
Provide a brief overview of the analysis and findings, including:

- SQL database structure and relationships
    
- Python API layer architecture and functionality
    
- Key findings and recommendations
    

**Final Report:**

Using the analysis and documentation templates provided, generate a comprehensive report that covers all aspects of the SQL database and Python API layer. Ensure that the report includes:

- A clear summary of the analysis and findings
    
- Detailed documentation of the SQL database structure, tables, views, and relationships
    
- Detailed documentation of the Python API layer architecture, modules, functions, classes, and relationships
    
- Observations and recommendations for improvement
    
- Adherence to standards and best practices
    

**OUTPUT PARAMETERS**::  
> **Headers**:: true  
> **Introductory text**:: NO_INTRO=true  
> **Numbered lists**:: true  
> **Bullet points**:: false  
> **Emphasis**:: bold  
> **Hide empty**::true  
> **Output format**:: RAW_MARKDOWN  
> **Verbose**:: true  
> **Length**:: long

I hope this revised template meets your needs! Let me know if you have any further questions or need any additional assistance.

----
<|END PYTHON TEMPLATE|>

Your final report will provide a Pedagogical analysis of the SQL database and Python API layer, including module level explanations, a hierarchy of functions, and overall adherence to standards & conventions system architecture. The documentation is written in clear and technically specific terms, with a focus on educating and informing the reader.

> **OUTPUT PARAMETERS**::  
> > **Headers**:: true  
> > **Introductory text**:: NO_INTRO=true  
> > **Numbered lists**:: true  
> > **Bullet points**:: false  
> > **Emphasis**:: bold  
> > **Hide empty**::true  
> > **Output format**:: RAW_MARKDOWN  
> > **Verbose**:: true  
> > **Length**:: long
>

---
	OUTPUT PARAMETERS::
	
> 	Headers:: true  
> 	Introductory text:: NO_INTRO=true  
> 	Numbered lists:: true  
> 	Bullet points:: false  
> 	Emphasis:: bold  
> 	Hide empty::true  
> 	Output format:: RAW_MARKDOWN  
> 	Verbose:: true  
> 	Length:: long  
> 	Include code snippets:: true  
> 	Include visual diagrams:: true  
> 	Organize with headings:: true

---
There are many other ways to format output parameters using Markdown. Here are a few more examples:

**Using a table with alignment:**


**OUTPUT PARAMETERS**
=======================

| Parameter              | Value                         |
|------------------------|-------------------------------|
| Headers                | `true`                        |
| Introductory text      | `NO_INTRO=true`               |
| Numbered lists         | `true`                        |
| Bullet points          | `false`                       |
| Emphasis               | **bold**                      |
| Hide empty             | `true`                        |
| Output format          | `RAW_MARKDOWN`                |
| Verbose                | `true`                        |
| Length                 | `long`                        |
| Include code snippets  | `true`                        |
| Include visual diagrams| `true`                        |
| Organize with headings | `true`                        |

---


**Using a code block:**

```
OUTPUT PARAMETERS:
```

YAML

```
Headers: true
Introductory text: NO_INTRO=true
Numbered lists: true
Bullet points: false
Emphasis: bold
Hide empty: true
Output format: RAW_MARKDOWN
Verbose: true
Length: long
Include code snippets: true
Include visual diagrams: true
Organize with headings: true
```

**Using a definition list:**

```
OUTPUT PARAMETERS:
=======================

Headers
: true

Introductory text
: NO_INTRO=true

Numbered lists
: true

Bullet points
: false

Emphasis
: **bold**

Hide empty
: true

Output format
: RAW_MARKDOWN

Verbose
: true

Length
: long

Include code snippets
: true

Include visual diagrams
: true

Organize with headings
: true
```




Here are some additional refined output formats for LLaMA:

**Pretty JSON**

JSON

```
{
  "output_parameters": {
    "headers": true,
    "introductory_text": "NO_INTRO=true",
    "numbered_lists": true,
    "bullet_points": false,
    "emphasis": "bold",
    "hide_empty": true,
    "output_format": "RAW_MARKDOWN",
    "verbose": true,
    "length": "long",
    "include_code_snippets": true,
    "include_visual_diagrams": true,
    "organize_with_headings": true
  }
}
```

**YAML with anchors**

YAML
```
output_parameters:
  headers: true
  introductory_text: NO_INTRO=true
  numbered_lists: true
  bullet_points: false
  emphasis: bold
  hide_empty: true
  output_format: RAW_MARKDOWN
  verbose: true
  length: long
  include_code_snippets: true
  include_visual_diagrams: true
  organize_with_headings: true
```
YAML with anchors:
```
output_parameters:
  headers: true
  introductory_text: NO_INTRO=true
  numbered_lists: true
  bullet_points: false
  emphasis: bold
  hide_empty: true
  output_format: RAW_MARKDOWN
  verbose: true
  length: long
  include_code_snippets: true
  include_visual_diagrams: true
  organize_with_headings: true

anchors:
  - headers
  - introductory_text
  - numbered_lists
  - ...
```



**CSV**

CSV

```
Parameter,Value
headers,true
introductory_text,NO_INTRO=true
numbered_lists,true
bullet_points,false
emphasis,bold
hide_empty,true
output_format,RAW_MARKDOWN
verbose,true
length,long
include_code_snippets,true
include_visual_diagrams,true
organize_with_headings,true
```

Let me know if you need even more options!
Based on the context, the `Length` parameter likely controls the level of detail or verbosity of the output. Here are some valid options for the `Length` parameter:

- `short`: Brief output, likely showing only essential information.
    
- `medium`: Medium-length output, providing a balanced level of detail.
    
- `long`: Detailed output, showing all available information.
    
- `full`: Complete output, including all possible details and ancillary information.
    
- `brief`: Similar to `short`, but might exclude some secondary information.
    
- `extended`: Similar to `long`, but might include additional ancillary information.
    

Please note that these options are hypothetical, and the actual valid values for the `Length` parameter depend on the specific tool or system using this format.