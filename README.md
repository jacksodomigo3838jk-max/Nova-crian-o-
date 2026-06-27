{
    "version": "2.0.0",
    "tasks": [
        {
            "label": "Executar Meu Script",
            "type": "shell",
            "command": "python", // Substitua pelo comando da sua linguagem (ex: node, java, g++)
            "args": [
                "${file}"
            ],
            "group": {
                "kind": "build",
                "isDefault": true
            },
            "presentation": {
                "reveal": "always",
                "panel": "shared"
            }
        }
    ]
}
