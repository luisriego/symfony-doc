## Visual Studio Code Utils

launch.json

    {
      "version": "0.2.0",
      "configurations": [
          {
              "name": "cmicro-app",
              "type": "php",
              "request": "launch",
              "port": 9003,
              "pathMappings": {
                  "/appdata/www": "${workspaceFolder}/"
              }
          }
      ]
    }
    
This prepar VSC for XDebug 
