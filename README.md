# CopyClipSharepoint

```json
{
  "$schema": "https://developer.microsoft.com/json-schemas/sp/v2/column-formatting.schema.json",
  "elmType": "a",
  "attributes": {
    "iconName": "Copy",
    "target": "_blank",
    "class": "ms-borderColor-white ms-borderColor-themePrimary--hover",
    "href": "='https://almirjuniorlanlink.github.io/copy-to-clipboard/index.html?copy=' + @currentField"
  },
  "style": {
    "color": "#272727",
    "text-decoration": "none",
    "font-size": "14px",
    "border-bottom-width": "1px",
    "border-bottom-style": "solid",
    "min-width": "400px"
  },
  "children": [
    {
      "elmType": "span",
      "txtContent": "@currentField",
      "style": {
        "padding-left": "5px"
      }
    }
  ]
}
```
