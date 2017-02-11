#JSON GENERATOR
the json generator library helps to create customized json files using a predefined template.

#Template format:
```json
{
  "key": <% value_variable %>
}
```
So all you need is to give the json generator function a dictionay that contains the key 
value_variable and the generator'll replace it.