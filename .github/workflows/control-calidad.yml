name:

on:
    push:
        branches: [main]

    pull_request:
        branches: [main]

jobs:
    revision-de-calida:
        runs-on: ubuntu-latest

        steps:
            - name: Brainiac accede a los planes
              uses: actions/checkout@v4
            
            - name: El consejo revisa los cambios
              run: |
                chmod +x scripts/validar-planes.sh
                ./scripts/validar-planes.sh