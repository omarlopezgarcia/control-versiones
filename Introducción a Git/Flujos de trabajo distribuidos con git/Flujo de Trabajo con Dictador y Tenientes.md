# Flujo de Trabajo con Dictador y Tenientes

Es una variante del flujo de trabajo con multiples repositorios. Se utiliza generalmente en proyectos muy grandes, con cientos de colaboradores. Un ejemplo muy conocido es el del kernel de Linux. Unos gestores de integración se encargan de partes concretas del repositorio; y se denominan tenientes. Todos los tenientes rinden cuentas a un gestor de integración; conocido como el dictador benevolente. El repositorio del dictador benevolente es el repositorio de referencia, del que recuperan (pull) todos los colaboradores.

![flujo de trabajo con dictador y tenientes](https://github.com/omarlopezgarcia/control-versiones/blob/main/src/flujo%20de%20trabajo%20con%20dictador%20y%20tenientes.PNG)
