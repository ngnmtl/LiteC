# LiteC
LiteC Conkyrc

![SS](../master/Screenshot/ss.png)

# Requirements
- Conky installed
- Python 3 to execute the weather

# Install
Download and extract the project in your system.
Copy the content of the folder **fonts/** to the directory **~/.fonts/**
```shell
cp fonts/* ~/.fonts/
```
Copy the folder **LiteC** for the directory **~/.conky/**
```shell
cp LiteC/ ~/.conky
```
# Execute
To run the widgets enter the commands:
```shell
conky -q -c ~/.conky/LiteC/litecrc
```
Give write permission to the **start.sh** file (inside the LiteC directory)
```shell
chmod +x start.sh
```
Execute the file
```shell
sh start.sh

## Recomendations
Use your graphical environment to run the file **~/.conky/LiteC/start.sh** at startup.
