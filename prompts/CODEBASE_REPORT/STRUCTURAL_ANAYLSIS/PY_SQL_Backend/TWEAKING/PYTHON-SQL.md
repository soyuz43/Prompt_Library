# SQL Database Template: Analysis and Documentation of the Preceding Codebase 

## Scope
{LANGUAGE: SQL}
{SCOPE: Tables and Views}

```markdown
<BEGIN SQL_TEMPLATE>
Tables:: {TABLES: [], COLUMNS: []}
Notable Relationships:: {FOREIGN_KEYS: [] REFERENCED COLUMN : []}
</END SQL_TEMPLATE>
```

## Python API Layer Template:

### Scope
{LANGUAGE: PYTHON}
{SCOPE: Modules, Classes, Functions, Dictionaries}

```markdown
<BEGIN PYTHON_TEMPLATE>
Modules:: {MODULES; IMPORTS: [], FUNCTIONS: []}
Classes:: {CLASSES; METHODS: [], ATTRIBUTES: []}
Dictionaries: {DICTIONARIES; KEYS: [], VALUES: []}
</END PYTHON_TEMPLATE>
```
# TASK:: Complete the templates above. Then, using those, the model's instructions are: **To produce the Final Report as expert-level documentation that exceeds intermediate skills standards with potential for advanced expertise in specific areas. The Final Report is to serve a pedagogical analysis of the SQL database and Python API layer**

## EXAMPLE OUTPUT::
### Final Report Structure:

1. **Forward**
   + (2-3 Sentences Introducing the Final Report)
2. **Table of Contents (Linked)**
3. **Completed Templates**
    1. SQL Database Structure:
          + Completed <SQL_TEMPLATE>[INSERT HERE]</SQL_TEMPLATE>
    2. Python API Layer:
          + Completed <PYTHON_TEMPLATE>[INSERT HERE]</PYTHON_TEMPLATE>
4. **Report and Analysis**
        * Observations and Summary of Existing Logic & Data Flow::
                - SQL Database Structure and Relationships::
                        - Overview & Summary: 
                          + Synopsis of Current SQL Schema
                            + Bulleted list recapping key points not addressed about the existing data schema
                - Python & SQL: Dictionaries and Serialization
                        - Overview & Summary: 
                          - Summary of endpoints, classes, and dictionaries
                            - Endpoints:: 
                              + Bulleted List of Endpoints
                               + Python Code Snippets 
                            - Classes:: 
                              + Numbered List of Classes
                               + Python Code Snippets 
                            - Dictionaries::
                              + Bulleted List of Key Dictionaries
                               + Python Code Snippets 
            - Python API Layer:
                    + Diagram of Python Specific Logic Flow
                        - Flow Between Modules: Considerations and Relevant Observations
                        - Summary of key observations & additional relevant information
               - Numbered Markdown list of key Observations.
    - Final Notes and Connecting Structure to Observations and Recommendations
5. **Thorough Review of Findings & Recommendations**
        * 1. Performance Optimization Suggestions and Best Practices::
          - Summary of key observations & additional best practices information
            + Please explain your reasoning behind choosing those. How did you arrive at that conclusion? 
              + Bulleted Markdown list with categorization of key observations
        * 2. Security Vulnerability Observations and Recommendations::
          - Summary of security vulnerabilities & additional relevant information
            + Please explain your reasoning behind choosing those. How did you arrive at that conclusion? 
              + Bulleted Markdown list of vulnerabilities and concerns
                + Numbered Markdown list with prioritization of vulnerabilities to address
        * 3. Scalability/Integration:Key Findings and Recommendations::
          - Summary of Key Findings and Recommendations for the future relating to scalability
            + Please explain your reasoning behind choosing those. How did you arrive at that conclusion? 
              + Bulleted Markdown list of concerns and considerations relating to scalability
          - Summary of Key Findings and Recommendations for the future relating to integration::
            + Please explain your reasoning behind choosing those. How did you arrive at that conclusion? =
              + Bulleted Markdown list of concerns and considerations relating to integration
6. **Broader and Final Considerations**    
   - Synopsis of Key Considerations & Limitations Moving Forward::
        + Numbered Markdown list of most vital observations and recommendations
          - Considerations and Moving Forward:
            + What additional information or context might be useful for us to consider before making a final decision on this matter?
        - Statement summarizing the decision points involved in implementation of recommendations
            + Paragraph clarifying relationships between all noted recommendations
    - Create a Conceptual Diagram in Markdown::
        *  Conceptual Diagram illustrating a hierarchical breakdown of the assumptions, inferences, and decision points involved in implementing the recommendations
           +  Provide a detailed, step-by-step analytical explanation illustrating the relationships between the recommendations, barriers to implementation, and potential solution paths
           +  Include alternative approaches and their potential consequences.
              +  Explain your reasoning behind choosing that path towards a solution 
7. **Conclusion**
- Synopsis (2 sentences)
        - 
 > Output Parameters for the Final Report:
      > * Headers: true
      > * Introductory text: NO_INTRO=true
      > * Numbered lists: true
      > * Bullet points: false
      > * Emphasis: bold
      > * Hide empty: true
      > * Output format: RAW_MARKDOWN
      > * Verbose: true
      > * Length: full=detailed
      > * Include code snippets: true
      > * Include visual diagrams: true
      > * Organize with headings: true
      > * Use clear and concise language: true
      > * Use proper grammar and spelling: true
      > * Use consistent formatting: true