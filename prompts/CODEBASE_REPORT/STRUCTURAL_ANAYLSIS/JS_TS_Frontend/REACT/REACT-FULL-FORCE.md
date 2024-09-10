Here's the refactored template with the added "Action Items" section:
---


TASK:: Analyze the provided React Codebase and Prepare Documentation:

## React Codebase Analysis and Documentation
**Scope:** {SCOPE: FUNCTION/MODULE}

## Script-by-Script Explanation

### Components:
- **Components**:
    {COMPONENTS: [
    {name: "ComponentA", props: ["prop1", "prop2"], imports: ["import1", "import2"]},
    {name: "ComponentB", props: ["propA", "propB"], imports: ["importX", "importY"]},
    ]}
  
### Hooks:
- **Hooks**:
    {HOOKS: [
    {name: "useHookA", parameters: ["param1", "param2"], returns: ["return1", "return2"]},
    {name: "useHookB", parameters: ["paramX", "paramY"], returns: ["returnA", "returnB"]},
    ]}

### Utility Functions:
- **Utility Functions**:
    {UTIL FUNCTIONS: [
    {name: "utilityFunctionA", parameters: ["param1"], returns: "resultA"},
    {name: "utilityFunctionB", parameters: ["paramX"], returns: "resultB"},
    ]}

## Hierarchy of Functions
{HIERARCHY: [
  {name: "ComponentA", children: ["useHookA", "utilityFunctionA"]},
  {name: "ComponentB", children: ["useHookB", "utilityFunctionB"]},
]}

### React Conventions and Best Practices
{CONVENTIONS: [
  "Use functional components instead of class components.",
  "Use hooks for managing state and side effects.",
  "Keep components small and focused on a single responsibility.",
  "Use prop-types or TypeScript for type checking."
]}

#### Component Relationships & Hierarchy
{COMPONENT HIERARCHY: [
  {parent: "App", children: ["ComponentA", "ComponentB"]},
  {parent: "ComponentA", children: ["SubComponentA1", "SubComponentA2"]},
]}

#### Component Interactions
{COMPONENT INTERACTIONS: [
  "ComponentA passes prop1 to SubComponentA1.",
  "ComponentB updates state using useHookB and triggers re-render."
]}

## Documentation Requirements
{REQUIREMENTS: [
  "Detailed comments explaining each component's purpose.",
  "Prop types and default values documentation.",
  "Examples of how to use each component and hook.",
  "Explanation of utility functions and their usage contexts."
]}

### Natural Language Breakdown
{NATURAL LANGUAGE BREAKDOWN:
  "ComponentA is responsible for displaying user data. It receives 'prop1' and 'prop2' which are used to fetch and display the user's details. It imports 'import1' for styling and 'import2' for API calls. Inside ComponentA, the 'useHookA' manages the state of the user data and 'utilityFunctionA' formats the data before display."
}

## **Action Items**:
**High Priority**:
- Address prop type inconsistencies in ComponentA and ComponentB
- Optimize re-renders in ComponentB using React.memo or useCallback

**Medium Priority**:
- Add detailed comments to utilityFunctionA and utilityFunctionB
- Update the natural language breakdown to include SubComponentA1 and SubComponentA2

**Low Priority**:
- Refactor ComponentA to use a more efficient data fetching approach
- Consider adding a loading indicator to ComponentB

## **Observations and Recommendations**:
**Categories:** {CATEGORIES: ["Code Quality", "Performance", "Best Practices"]}

**Priorities:** {PRIORITIES: ["High", "Medium", "Low"]}

### Observations:
1. **Code Quality**: The code is well-structured, but lacks comments in some places which makes it harder to understand the logic quickly.
2. **Performance**: Some components are re-rendering unnecessarily which can be optimized using React.memo or useCallback.
3. **Best Practices**: There are instances where prop types are not defined, which could lead to bugs and inconsistencies.

### Recommendations:
1. **Add Detailed Comments**: Ensure each component and function is documented with comments explaining their purpose and logic.
2. **Optimize Re-renders**: Use React.memo and useCallback to prevent unnecessary re-renders.
3. **Define Prop Types**: Use prop-types or TypeScript to define and check prop types to ensure components receive expected data types.
---
```
---
    > Introductory text: NO_INTRO=true=FORCE
    > Numbered lists:: true
    > Bullet points:: true
    > Emphasis:: bold
    > Hide empty:: true
    > Headers:: H1
    > Output format:: RAW_MARKDOWN
    > Code blocks:: LANGUAGE=jsx, HIGHLIGHT=TRUE
    > Verbose:: true