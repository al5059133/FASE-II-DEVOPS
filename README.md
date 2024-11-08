# FASE-II-DEVOPS

yaml 

name: Crear Cliente 
on: [push] 
jobs: 
  build: 
    runs-on: ubuntu-latest 
    steps: 
    - name: Checkout repository 
      uses: actions/checkout@v2 
    - name: Mensaje de creación de cliente 
      run: echo "Un nuevo cliente ha sido creado." 
