# Data Types

- **String** (any character or text that wrap in *single* `'` or *double* `"` quotes)
    - Examples
        - `"Pizza"`  
        - `'Burger'`
- Number (any numberical character)
    - Examples
        - `100`
        - `78.89`
- Boolean ( Similar to Yes or No, 0 or 1 )
    - Examples (not quotes required)
        - `true`
        - `false`


## JSON (JavaScript Object Notation)

Object which has it properties (value holder) and it methods (functioning / process)

User
Properties hold the values (attributes)
- Name          : Syed Zakeer 
- Location      : Hyderabad
- Designation   : UI Dev
- Salary        : 10000
- Student       : true

Methods    process something   (functions)
- sleep()
- doWork()
- listenMusic()


Menu
- Name: Pizza
- Price: 100
- Available: true

- makeNotAvaialble()
    - availabele: false

- makeAvaialble()
    - availabele: true


```csv
name,age
zakeer,32
shoyab,27
```

JSON Support four data types
- "string"
- number
- boolean
- null

### JSON Syntax for Object (`{}`)
*Note: JSON string always need to be in double quotes `""`
```json
{
    "property": value
}
```

Example
```json
{
    "name": "Syed Zakeer Hussain",
    "isStudent": false,
    "pay": 15000,
    "bonus": null,
    "skills": ["HTML", "CSS", "JavaScript"],
    "extra": ["Zakeer", 5000, null, false],
    "address":  [
        {"type": "home", "location": "Mehdipatnam, Hyderabad", "pincode": 500028},
        {"type": "office", "location": "Madhura Nagar, Hyderabad", "pincode": 500018}
    ]
}
```
