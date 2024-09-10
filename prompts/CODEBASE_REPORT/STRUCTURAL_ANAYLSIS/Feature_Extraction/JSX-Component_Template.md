**Extract the features of the JSX components in the provided codebase:**
EXAMPLE OUTPUT:: 
```
component: object

component:
  name: MyApp
  props:
  - name: title
    type: string
  state:
  - name: count
    type: int
  methods:
  - name: handleButtonClick
    parameters: []
    returns: void
  - name: handleInputChange
    parameters: [event]
    returns: void
  render:
    type: div
    children:
    - type: h1
      children: ["{title}"]
    - type: p
      children: ["Count: {count}"]
    - type: button
      children: ["Increment"]
      onClick: handleButtonClick
    - type: input
      type: text
      onChange: handleInputChange
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
    