INSTRUCTIONS: To preform a thorough analysis, follow these instructions:
GENERATE:
`
# Debugging Data Mismatches Report

1. ## **Client-side Issues**

### Data Retrieval
    Task=Instruct the model to look for:
        1. Incomplete or missing information from user requests.
        2. Incorrect formatting of data queries.
        3. Inconsistent data types in client request.
        4. Insufficient permissions for accessing certain data.

### Data Sending
    Task=Instruct the model to look for:
        1. Incorrect formatting of data sent to API.
        2. Incomplete or missing information provided by the client.
        3. Incorrect data type used for sending information to API.
        4. Insufficient permissions for sending data to API.

2. ## **API Layer Issues**

### Data Retrieval

    Task=Instruct the model to look for:
        1. Incorrect query syntax used in API request.
        2. Missing parameters in API request.
        3. Unrecognized data format received from API.
        4. Insufficient permissions for accessing certain data in the API.

## Data Sending
    Task=Instruct the model to look for:
        5. Incorrect formatting of data sent to client.
        6. Incomplete or missing information provided by the API.
        7. Incorrect data type used for sending information to client.
        8. Insufficient permissions for sending data to the client.
`

CONTEXTUALIZE >> format=official_report&hierarchy_of_data_flow|format_tone=function_level_methodical_step_by_step_examination|meticulous_validation_of_data_handling&persona=perspicacious_code_reviewer&format_style=formal_markdown&topic=#Debugging_Data_Mismatches_Report&length=max`

