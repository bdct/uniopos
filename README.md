## [uniOPOS](http://www.maravento.com)

**uniOPOS** it is a preconfigured installation package of uniCenta OPOS for Points of Sales (POS/ERP Open Source)

**uniOPOS** es un paquete de instalación preconfigurado de uniCenta OPOS para Puntos de Ventas (POS/ERP Open Source)

[![Image](https://4.bp.blogspot.com/-I60lcdWHZfk/WXHzBV95bSI/AAAAAAAADVA/H4_pxdFjRBMLZtGCdYhDrqRXK4NHFOCEwCLcBGAs/s320/uniOPOS.png)](http://www.maravento.com/)

### DATA SHEET
---

|File|Version|OS|Update|Size|language|
| :---: | :---: | :---: | :---: | :---: | :---: |
|[uniOPOS.exe (.zip)](http://pc.cd/0wditalK)|1.0|Windows 7/8/10 x86 x64|Mar 05/2020|1,6 GB|Eng/Spa|

### HOW TO USE
---

Disable your Antivirus, Antimalware, SmartScreen or any other security solution in your Operating System, close all windows and check the date and time of your PC is correct. Download uniOPOS.exe (.zip), unzip it to your desktop, execute it with double click (accept privileged execution) and follow the instructions on the screen

Desactive su Antivirus, Antimalware, SmartScreen o cualquier otra solución de seguridad en su Sistema Operativo, cierre todas las ventanas y verifique la fecha y hora de su PC sea la correcta. Descargue uniOPOS.exe (.zip), descomprimirlo en el escritorio, ejecutarlo con doble clic (acepte la ejecución con privilegios) y siga las instrucciones en pantalla

### IMPORTANT BEFORE USE
---

- uniOPOS can eliminate previous versions of its components, so it is recommended to backup before using it / uniOPOS puede eliminar versiones previas de sus componentes, por tanto se recomienda hacer Backup antes de usarlo
- According to the developers, [uniCenta oPOS v4 only uses MySQL. MySQL version 5.7 is recommended](https://unicenta.com/pages/configure-unicenta-opos/) / Según los desarrolladores, [uniCenta oPOS v4 solamente utiliza MySQL. MySQL version 5.7 es la recomendada](https://unicenta.com/pages/configure-unicenta-opos/)

[![Image](https://1.bp.blogspot.com/-DpcvfI_5Eic/XmbIW9mnBBI/AAAAAAAALPo/jDlqzjbLqJodaECoIiHgx5P6n1V1Q7PsgCLcBGAsYHQ/s1600/unicenta.png)](http://www.maravento.com/)

- If you are going to work with MariaDB instead of MySQL, it is recommended to verify Unicenta Configuration Panel and select the correct port `jdbc:mysql://localhost:3306/` and edit your `.sql` file and replace the line `ROW_FORMAT=COMPACT;` by `ROW_FORMAT=DYNAMIC;` / Si va a trabajar con MariaDB en lugar de MySQL, se recomienda verificar el Panel de configuración de Unicenta y seleccionar el puerto correcto `jdbc:mysql://localhost:3306/`, y edite su archivo `.sql` y reemplace la línea `ROW_FORMAT=COMPACT;` por `ROW_FORMAT=DYNAMIC;`

### SELECTOR AND END
---

UniOPOS contains three (3) installation packages. Select the one you will work with / UniOPOS contiene tres (3) paquetes de instalación. Seleccione con el que va a trabajar

[![Image](https://1.bp.blogspot.com/-xWfn0ZWgdBw/XmFlZVuX0CI/AAAAAAAALJo/BiqUBs7Sw9ID8phaMk0wkKHkcNRonaA-QCLcBGAsYHQ/s1600/uniopos-selector.png)](https://www.maravento.com)

At the end of the installation of each package the following message will appear / Al finalizar la instalación de cada paquete saldrá el siguiente mensaje

[![Image](https://1.bp.blogspot.com/-zXgEY8YK9NY/XmFlYI6dziI/AAAAAAAALJY/NEogpYmRevMSc8tfb6SJyyyiPW71zmo4gCLcBGAsYHQ/s1600/uniopos-end.png)](https://www.maravento.com)

### Unicenta OPOS + MySQL + Workbench
---

[![Image](https://1.bp.blogspot.com/-oQwYjqnGuTg/XmFlZEokWwI/AAAAAAAALJk/324KSU9_03YfFBMijOQbZC1o3IZjbaxxACLcBGAsYHQ/s1600/uniopos-mysql.png)](https://www.maravento.com)

##### Content

- [uniCenta OPOS 4.6 (.exe)](https://unicenta.com/download-files/installers/)
- [MySQL 5.7.29 x86 x64 (.zip)](https://dev.mysql.com/downloads/mysql/5.7.html#downloads/)
- [MySQL Workbench Community 8.0.19 (.msi)](https://dev.mysql.com/downloads/workbench/)

##### Important Before Use Unicenta OPOS + MySQL + WorkBench

- If you select the Unicenta OPOS package with MySQL + WorkBench, the path of MySQL is `%HOMEDRIVE%\mysql\mysql-%version%\data` folder / Si selecciona el paquete Unicenta OPOS con MySQL + WorkBench, el path de MySQL es `%HOMEDRIVE%\mysql\mysql-%version%\data`
- Installation is done in **insecure mode**, so access to `root` account is **without a password** (you must create one) / La instalacion se realiza en **modo inseguro**, por tanto el acceso a la cuenta `root` es **sin contraseña** (deberá crear una)

### Unicenta OPOS + MariaDB + DBeaver
---

[![Image](https://1.bp.blogspot.com/-hH1e_SqkB3M/XmFlYMz_wWI/AAAAAAAALJU/4QKwbj6NgNkFULi5GyduJxjoYWs13KrDACLcBGAsYHQ/s1600/uniopos-mariadb.png)](https://www.maravento.com)

##### Content

- [uniCenta OPOS 4.6 (.exe)](https://unicenta.com/download-files/installers/)
- [MariaDB 10.4.12 Stable x86 x64 (.zip)](https://downloads.mariadb.org/mariadb/10.4.12/)
- [DBeaver ce 7.0.0 x86 64 (.exe)](https://github.com/dbeaver/dbeaver/releases)

##### Important Before Use Unicenta OPOS + MariaDB + DBeaver

- If you select the Unicenta OPOS package with MariaDB + DBeaver, the path of MariaDB is `%HOMEDRIVE%\mariadb\mariadb-%version%\data` folder / Si selecciona el paquete Unicenta OPOS con MariaDB + dbeaver, el path de MariaDB es `%HOMEDRIVE%\mariadb\mariadb-%version%\data`
- According to developers, [MariaDB disables anonymous user by default](https://mariadb.com/kb/en/installing-mariadb-windows-zip-packages/), therefore installation is done in **safe mode** and access to the `root` account is with the password `secret` / Según los desarrolladores, [MariaDB desactiva el usuario anónimo de forma predeterminada](https://mariadb.com/kb/en/installing-mariadb-windows-zip-packages/), por tanto la instalacion se realiza en **modo seguro** y el acceso a la cuenta `root` es con la contraseña `secret`

### Unicenta OPOS + WampServer
---

[![Image](https://1.bp.blogspot.com/-flUtEE_bBVQ/XmFlZ66vFkI/AAAAAAAALJw/9F_WmXE0llc8lnb4alq69NJ-HkrAb1HoACLcBGAsYHQ/s1600/uniopos-wamp.png)](https://www.maravento.com)

##### Content

- [uniCenta OPOS 4.6 (.exe)](https://unicenta.com/download-files/installers/)
- [Wampserver 3.1.9 x86 x64 (.exe with content: Apache 2.4.39 - PHP 5.6.40/7.0.33/7.1.28/7.2.18/7.3.5 - MySQL 5.7.26 - MariaDB 10.3.14)](http://wampserver.aviatechno.net/?lang=en)

##### Important Before Use Unicenta OPOS + WampServer

- If you select the Unicenta OPOS package + WampServer, keep in mind that installs MySQL (By default service start automatically) and MariaDB (By default service does not start automatically) / Si selecciona el paquete Unicenta OPOS + WampServer, tenga en cuenta que instala MySQL (Por defecto inicia automáticamente) y MariaDB (por defecto el servicio no inicia automáticamente)
- Installation is done in **insecure mode**, so access to `root` account is **without a password** (you must create one) / La instalacion se realiza en **modo inseguro**, por tanto el acceso a la cuenta `root` es **sin contraseña** (deberá crear una)

### DEPENDENCIES
---

- [WinExternal](https://github.com/maravento/winexternal)
- [trekDB](https://github.com/maravento/trekdb)

### CONTRIBUTIONS
---

We thank all those who contributed to this project / Agradecemos a todos los que han contribuido con este proyecto

### LICENCES
---

[![GPL-3.0](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl.txt)

[![CreativeCommons](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/)
[maravento.com](http://www.maravento.com) is licensed under a [Creative Commons Reconocimiento-CompartirIgual 4.0 Internacional License](http://creativecommons.org/licenses/by-sa/4.0/).

[WinZenity](https://github.com/maravento/winzenity), [Jpsoft](https://jpsoft.com/), [SteelWerX](https://fstaal01.home.xs4all.nl/swreg-us.html), [Microsoft](https://www.microsoft.com/), [74cz](http://74.cz/es/make-sfx/index.php), [Resource Hacker](http://www.angusj.com/resourcehacker/), [7zSFX Builder](https://sourceforge.net/projects/s-zipsfxbuilder/)

Unicenta OPOS ([Community Version](https://ftp://197.155.77.8/sourceforge/u/un/unicentaopos/releases/windows/) and [Official version](https://unicenta.com/download-files/installers/)), [Wampserver](http://wampserver.aviatechno.net/?lang=en), [MySQL](https://dev.mysql.com/downloads/mysql/5.7.html#downloads/), [MariaDB](https://downloads.mariadb.org/mariadb/10.4.12/), [dbeaver](https://github.com/dbeaver/dbeaver/releases), [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)

© 2020 [Maravento Studio](http://www.maravento.com)

### DISCLAIMER
---

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
