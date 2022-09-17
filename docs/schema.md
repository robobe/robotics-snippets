schema validation depend on `XML Language Support by Red Hat` extension
set the systemid to schema path under extension folder `schames/sdf`

```
"xml.fileAssociations": [
        {
            "pattern": "**/*.sdf",
            "systemId": "/home/user/robotics-snippets/schemas/sdf/root.xsd"
        },
        {
            "pattern": "**/*.sdf.xacro",
            "systemId": "${workspaceFolder}/vscode/sdf/schema/root.xsd"
        },
        {
            "pattern": "**/*.world",
            "systemId": "${workspaceFolder}/vscode/sdf/schema/root.xsd"
        }
    ],
```