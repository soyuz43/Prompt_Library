<BEGIN JSX_TEMPLATE>
Component:: 
{
  NAME: <filename>
  PROPS: [],
  STATE: [],
  METHODS: [
    {NAME: handleButtonClick, PARAMETERS: [], RETURNS: void}
  ],
  RENDER: (
    <div>
      <h1>Welcome to my app!</h1>
      <button onClick={handleButtonClick}>Click me!</button>
    </div>
  )
}
</END JSX_TEMPLATE>

--

<BEGIN JSX_TEMPLATE>
Component:: 
{
  NAME: <filename>
  PROPS: [
    {NAME: title, TYPE: string, DESCRIPTION: Title of the app}
  ],
  STATE: [
    {NAME: count, TYPE: int, DESCRIPTION: Current count}
  ],
  METHODS: [
    {NAME: handleButtonClick, PARAMETERS: [], RETURNS: void},
    {NAME: handleInputChange, PARAMETERS: [event], RETURNS: void}
  ],
  RENDER: (
    <div>
      <h1>{title}</h1>
      <p>Count: {count}</p>
      <button onClick={handleButtonClick}>Increment</button>
      <input type="text" onChange={handleInputChange} />
    </div>
  )
}
</END JSX_TEMPLATE>