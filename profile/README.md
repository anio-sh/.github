# Welcome

This repository contains all code and tools for bootstrapping and managing the [@anio-software](https://github.com/anio-software) project.

## 🛠️ Currently available tools

### pmtree - permission tree

> Command line tool that helps you manage file permission and ownership.

`sudo curl https://anio.sh/pmtree -o /usr/local/bin/anio_pmtree && chmod +x /usr/local/bin/anio_pmtree`

### tardp - tar default permissions

> Command line tool to create a script that sets the default owner and permissions for a given tar archive.

`sudo curl https://anio.sh/tardp -o /usr/local/bin/anio_tardp && chmod +x /usr/local/bin/anio_tardp`

### packager - create .anio packages

> Command line tool to create .anio packages.

`sudo curl https://anio.sh/packager -o /usr/local/bin/anio_packager && chmod +x /usr/local/bin/anio_packager`

### tplinkcfggen - tp link configuration tool

> Command line tool to generate TP-Link Configuration files based on JavaScript config files.

`sudo curl https://anio.sh/tplinkcfggen -o /usr/local/bin/anio_tplinkcfggen && chmod +x /usr/local/bin/anio_tplinkcfggen`

---

## ⓘ About repository names

- Repositories starting with `jsdev-` are tools to be used for javascript module development.
- Repositories starting with `nodejs-` are libraries or command line tools targeting [nodejs](https://nodejs.org/en).
- If repository ends with `-cli` this means the repository code is for a [command line tool](https://en.wikipedia.org/wiki/Command-line_interface).

---

### Project Hierarchy

#### 1. anio-software

> Tools/Libraries/Modules intended to be used by third parties. This is considered public API.
   
#### 2. anio-sh (you are here)

> Tools for bootstraping the actual anio.software project. This is still considered an internal API.

#### 3. anio-core-sh

> Core functionality for anio-sh projects / tools. This is still considered an internal API. 

#### 4. anio-js-foundation

> Same as js-core-foundation but is allowed to have dependencies to js-core-foundation.

#### 5. anio-js-core-foundation

> Absolute lowest level of project scope, only things that should be written only once for the entire chain will be put here.

---

All information provided here is subject to change.
