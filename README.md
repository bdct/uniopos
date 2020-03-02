## [uniOPOS](http://www.maravento.com)

**uniOPOS** it is a preconfigured installation package of uniCenta OPOS and Wampserver for Points of Sales (POS/ERP Open Source)

**uniOPOS** es un paquete de instalación preconfigurado de uniCenta OPOS y Wampserver para Puntos de Ventas (POS/ERP Open Source)

[![Image](https://4.bp.blogspot.com/-I60lcdWHZfk/WXHzBV95bSI/AAAAAAAADVA/H4_pxdFjRBMLZtGCdYhDrqRXK4NHFOCEwCLcBGAs/s320/uniOPOS.png)](http://www.maravento.com/)

### DATA SHEET
---

|File|Version|OS|Update|Size|
| :---: | :---: | :---: | :---: | :---: |
|[uniOPOS.exe (.zip)](http://pc.cd/0wditalK)|1.0|Windows 7/8/10 x86 x64|Mar 02/2020|713,9 MB|

### HOW TO USE
---

Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Download uniOPOS.exe (.zip), unzip it to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen

Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique la fecha y hora de su PC sea la correcta. Descargue uniOPOS.exe (.zip), descomprimirlo en el escritorio, ejecutarlo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla

### CONTENT
---

- [uniCenta OPOS 4.6](ftp://197.155.77.8/sourceforge/u/un/unicentaopos/releases/windows/)
- [Wampserver 3.1.9](http://wampserver.aviatechno.net/?lang=en)
- [MySQL Workbench Community 8.0.19](https://dev.mysql.com/downloads/workbench/)

### DEPENDENCIES
---

- [WinExternal](https://github.com/maravento/winexternal)
- [trekDB](https://github.com/maravento/trekdb)

### IMPORTANT BEFORE USE
---

- uniOPOS can eliminate previous versions of its components, so it is recommended to backup before using it / uniOPOS puede eliminar versiones previas de sus componentes, por tanto se recomienda hacer Backup antes de usarlo
- According to the developers, [uniCenta oPOS v4 only uses MySQL. MySQL version 5.7 is recommended](https://unicenta.com/pages/configure-unicenta-opos/). Wamserver installs MySQL and MariaDB. So, if you are going to work with MariaDB, check the Unicenta Configuration Panel and select the correct port / Según los desarrolladores, [uniCenta oPOS v4 solamente utiliza MySQL. MySQL version 5.7 es la recomendada](https://unicenta.com/pages/configure-unicenta-opos/) Wamserver instala MySQL y MariaDB. Entonces, si va a trabajar con MariaDB, verifique el Panel de configuración de Unicenta y seleccione el puerto correcto
```
jdbc:mysql://localhost:3306/
```
And edit **.sql** file and replace the line / Y edite el archivo **.sql** y reemplace la línea

```
ROW_FORMAT=COMPACT;
```
by / por
```
ROW_FORMAT=DYNAMIC;
```

### CONTRIBUTIONS
---

We thank all those who contributed to this project / Agradecemos a todos los que han contribuido con este proyecto

### LICENCES
---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)

[![CreativeCommons](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)
[maravento.com](http://www.maravento.com) is licensed under a [Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional License](http://creativecommons.org/licenses/by-sa/4.0/).

[WinZenity](https://github.com/maravento/winzenity), [Jpsoft](https://jpsoft.com/), [SteelWerX](https://fstaal01.home.xs4all.nl/swreg-us.html), [Microsoft](https://www.microsoft.com/), [74cz](http://74.cz/es/make-sfx/index.php), [Resource Hacker](http://www.angusj.com/resourcehacker/), [7zSFX Builder](https://sourceforge.net/projects/s-zipsfxbuilder/)

© 2020 [Maravento Studio](http://www.maravento.com)

### DISCLAIMER
---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
