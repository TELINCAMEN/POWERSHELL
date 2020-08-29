## POWERSHELL

```markdown
Syntax highlighted code block

# OBTENER OBJETOS DE EQUIPOS REMOTOS MEDIANTE METODOS MICROSOFT.NET
## Los siguientes metodos "no usan infraestructura Remota"
### Objects Its a noun, that has properties and methods

- Bulleted
- LisT

1. GET-SERVICE
2. GET-PROCESS
3. GET-WMI-OBJECT
4. GET-EVENTLOG
5. GET-WINEVENT
**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

### Jekyll Themes

#To add the IP addresses of particular computers to the list of trusted hosts,
#use the following command format:

set-item wsman:\localhost\Client\TrustedHosts -value <IP Address>

#For example:
set-item wsman:\localhost\Client\TrustedHosts -value 172.16.0.0

# La comunicación remota de Windows PowerShell usa el puerto 80 para el transporte HTTP de forma predeterminada. el
# puerto predeterminado se utiliza siempre que el usuario no especifique el ConnectionURI
# o parámetros de puerto en un comando remoto.

#For example, the following command changes the default port to 8080.

set-item wsman:\localhost\listener\listener*\port -value 8080


### Support or Contact

http://luiszarate.com.mx/contact.html


