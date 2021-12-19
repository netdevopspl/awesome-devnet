# **AWESOME DEVNET**

- [**AWESOME DEVNET**](#awesome-devnet)
  - [**MODELOWANIE DANYCH**](#modelowanie-danych)
    - [JSON](#json)
    - [XML](#xml)
    - [YAML](#yaml)
    - [YANG](#yang)
    - [SZABLONY I PARSOWANIE](#szablony-i-parsowanie)
  - [**TWORZENIE KODU I DOKUMENTACJI**](#tworzenie-kodu-i-dokumentacji)
    - [EDYTORY](#edytory)
    - [DIAGRAMY](#diagramy)
    - [DOKUMENTACJA](#dokumentacja)
  - [**CICD**](#cicd)
  - [**GIT**](#git)
  - [**TESTOWANIE**](#testowanie)
    - [TESTOWANIE KODU](#testowanie-kodu)
    - [TESTOWANIE API](#testowanie-api)
    - [EMULATORY](#emulatory)
    - [TESTOWANIE SIECI](#testowanie-sieci)
  - [**IAAC**](#iaac)
    - [SSOT / CMDB](#ssot--cmdb)
    - [NARZĘDZIA IAAC](#narzędzia-iaac)
    - [BIBLIOTEKI PYTHON](#biblioteki-python)
    - [ORKIESTRACJA](#orkiestracja)
  - [APLIKACJE](#aplikacje)
  - [**BEZPIECZEŃSTWO**](#bezpieczeństwo)
  - [**INFRASTRUKTURA**](#infrastruktura)
    - [DOCKER](#docker)
    - [SERWERY](#serwery)
    - [MONITOROWANIE](#monitorowanie)
  - [**NARZĘDZIA DESKTOP**](#narzędzia-desktop)
  - [**NARZĘDZIA ONLINE**](#narzędzia-online)
  - [**SPOŁECZNOŚCI**](#społeczności)

## **MODELOWANIE DANYCH**

- [Jinja2](https://jinja.palletsprojects.com/en/2.11.x/)
- [HCL](https://github.com/hashicorp/hcl)

### JSON

- [JSON Homepage](https://www.json.org/json-en.html)
- [json](https://docs.python.org/3/library/json.html) - standardowa biblioteka pythona
- [simplejson](https://pypi.org/project/simplejson/) - inna biblioteka pythona
- [Schema store](https://www.schemastore.org/json/) - różne schema
- [Schema doc](https://json-schema.org/understanding-json-schema/) - opis tworzenia schema
- [JSON Schema Generator](https://jsonschema.net/home) - generator schema

### XML

- [XML Homepage](https://www.w3.org/XML/)
- [Untangle](https://untangle.readthedocs.io/en/latest/) - biblioteka python do serializacji XML

### YAML

- [YAML Homepage](https://yaml.org/)
- [Ansible YAML Doc](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html) - dobra dokumentacja YAML
- [YAML Validator](https://codebeautify.org/yaml-validator) - walidacja poprawności składni
- [pyyaml](https://pyyaml.org/) - biblioteka dla pythona
- [YAML Lint](https://yamllint.readthedocs.io/en/latest/) - linter YAML

### YANG

- [Cisco YANG Introduction](https://developer.cisco.com/learning/lab/intro-yang/step/1)
- [IETF RFC](https://tools.ietf.org/html/rfc6020)
- [YANG for dummies](https://napalm-automation.net/yang-for-dummies/) - NAPALM YANG

### SZABLONY I PARSOWANIE

- [Jinja2](http://jinja.pocoo.org/docs/2.10/templates/)
- [TextFSM](https://github.com/google/textfsm)

## **TWORZENIE KODU I DOKUMENTACJI**

### EDYTORY

- [Atom](https://atom.io/) - Edytor napisany przez zespół GitHuba
- [Notepad++](https://notepad-plus-plus.org/) - Prosty i szybki edytor tekstowy
- [SublimeText3](http://www.sublimetext.com/3) - Prosty i szybki edytor tekstowy
- [VSCode](https://code.visualstudio.com/) - Bardzo rozbudowane narzędzie do kodowania
- [PyCharm](https://www.jetbrains.com/pycharm) - Edytor dedykowany dla języka python
- [Vim](https://www.vim.org) - Najlepszy edytor tekstowy dla systemów Linux
- [Foxit Reader](https://www.foxitsoftware.com/)
- [Nano](nano-editor.org)

### DIAGRAMY

- [AsciiFlow](https://asciiflow.com/#/) - Rysowanie online diagramów ASCII
- [Visio](https://www.microsoft.com/en-ww/microsoft-365/visio/flowchart-software) - Najlepsze komercyjne narzędzie do rysowania diagramów
- [Draw.io](https://app.diagrams.net/) - Alternatywa online dla Visio

### DOKUMENTACJA

- [Markdown](https://daringfireball.net/projects/markdown/syntax) - Prosty język markdown do pisania dokumentacji
- [AsciiDoc](https://asciidoc.org/) - Zaawansowany język markup do pisania dokumentacji
- [reStructuredText](https://docutils.sourceforge.io/rst.html) - Zaawansowany język markup do pisania dokumentacji
- [Sphinx](https://www.sphinx-doc.org/en/master/) - Narzędzie do generowania dokumentacji kodu pythona
- https://github.com/yoloseem/awesome-sphinxdoc
- [Python Docstring](https://www.python.org/dev/peps/pep-0257/) - Zasady dokumentowania pythona
- [Docstring Tutorial](https://realpython.com/documenting-python-code/) - Poradnik jak korzystać z docstring dla pythona
- [Pandoc](https://pandoc.org/getting-started.html) - konwerter dokumentacji
- https://github.com/mkdocs/mkdocs/ - generowanie dokumentacji markdown

## **CICD**

- [GitLab CI](https://docs.gitlab.com/ee/ci/) - Połączenie Repo i CICD
- [Jenkins](https://www.jenkins.io/) - Popularne narzędzie, dedykowane do CICD
- [GNU make](https://www.gnu.org/software/make/)

## **GIT**

- [Git](https://git-scm.com/) - Najlepsze narzędzie do wersjonowania plików tekstowych
- [GitHub](https://github.com/) - Publiczne zasoby Repo
- [Pre-Commit](https://pre-commit.com/) - Wtyczka dla Git do uruchamiania skryptów przed wykonaniem `commit`
- [Flight rules for Git](https://github.com/k88hudson/git-flight-rules) - Masa przydatnych scenariuszy
- [Git Tips](https://github.com/git-tips/tips) - Kolejna porcja przydatnych scenariuszy
- [Understand gitk](https://lostechies.com/joshuaflanagan/2010/09/03/use-gitk-to-understand-git/)
- [Message Style Guide](https://udacity.github.io/git-styleguide/index.html) - Jak pisać message w commit
- [Gitflow](http://nvie.com/posts/a-successful-git-branching-model/) - Jak powinien wyglądać workflow

## **TESTOWANIE**

### TESTOWANIE KODU

https://www.pylint.org/ - linter dla Pythona
https://github.com/pyeve/cerberus - walidatory
https://docs.pytest.org/en/latest/
https://docs.python.org/3/library/unittest.html
https://pypi.org/project/coverage/ - weryfikacja pokrycia kodu testami

### TESTOWANIE API

- [Postman](https://www.getpostman.com/postman) - Rozbudowany klient graficzny do generowania zapytań REST API
- [CURL](https://curl.haxx.se) - Testowe narzędzie do testowania zapytań REST API

### EMULATORY

- [Vagrant](https://www.vagrantup.com/) - Narzędzie do automatycznego uruchamiania testowych środowisk wwirtualnych
- [VirtualBox](https://www.virtualbox.org/) - Darmowy wirtualizator
- [CML](https://www.cisco.com/c/en/us/products/cloud-systems-management/modeling-labs/index.html) - Komercyjne (Cisco) narzędzie do tworzenia wirtualnych topologii sieciowych
- [EVE-NG](https://www.eve-ng.net/) - Darmowe narzędzie do tworzenia wirtualnych topologii sieciowych
- [GNS3](https://www.gns3.com/) - Darmowe narzędzie do tworzenia wirtualnych topologii sieciowych
- [VMware vSphere](https://www.vmware.com/products/vsphere.html)

### TESTOWANIE SIECI

- [ToDD](https://github.com/toddproject/todd)
- [pyATS](https://developer.cisco.com/pyats/)
- [Batfish](https://github.com/batfish/batfish)

## **IAAC**

### SSOT / CMDB

- [NetBox](https://github.com/digitalocean/netbox) - Zarządzanie adresacją IP, baza infrastruktury
- [phpIPAM](https://phpipam.net/) - Zarządzanie adresacją IP
- [Ralph](https://github.com/allegro/ralph)
- [Nautobot](https://github.com/nautobot/nautobot) - SSOT i automatyzacja
- [NSoT](https://github.com/dropbox/nsot)

### NARZĘDZIA IAAC

- [Ansible](https://docs.ansible.com/) - Zarządzanie konfiguracją serwerów i urządzeń sieciowych
- [Terraform](https://www.terraform.io/) - Orkiestrator IaaC

### BIBLIOTEKI PYTHON

- [Napalm](https://napalm.readthedocs.io/en/latest/index.html) - Zarządzanie urządzeniami wielu producentów
- [Paramiko](http://www.paramiko.org/) - Konfiguracja urządzeń za pomocą SSH
- [Netmiko](https://pypi.org/project/netmiko/) - Rozszerzenie sieciowe do Paramiko
- [Nornir](https://nornir.readthedocs.io/en/latest/) - Framework do automatyzacji

### ORKIESTRACJA

- [UCSD](https://www.cisco.com/c/en/us/products/servers-unified-computing/ucs-director/index.html) - Komercyjny (Cisco) orkiestrator IaaC
- [UCSD Index](https://community.cisco.com/t5/ucs-director-documents/ucsd-workflow-index-ucsd-technical-content-index/ta-p/3614412) - Obszerny zestaw Workflow dla UCS Directora
- [Intersight](https://www.cisco.com/c/en/us/products/cloud-systems-management/intersight/index.html) - Komercyjny (Cisco) orkiestrator IaaC, ma zastąpić UCSD
- [Cisco NSO](https://cisco.com/go/nso)
- [vRO](https://www.vmware.com/pl/products/vrealize-orchestrator.html) - Komercyjny (VMware) orkiestrator IaaC
- [Rundeck](https://www.rundeck.com/)

## APLIKACJE

- [Django]
- [Flask]
https://fastapi.tiangolo.com/
http://babel.pocoo.org/en/latest/ - internacjonalizacja kodu


## **BEZPIECZEŃSTWO**

- [Ansible Vault](https://docs.ansible.com/ansible/latest/user_guide/vault.html) - Szyfrowanie zmiennych
- [Hashicorp Vault](https://www.vaultproject.io/) - Centralne zarządzanie hasłami i kluczami

## **INFRASTRUKTURA**

### DOCKER

- [Docker](https://docs.docker.com/)
- [Obrazy docker](https://hub.docker.com/)
- [Kubernetes](https://kubernetes.io/) - Zarządzanie klastrami docker
- [Docker Compose](https://github.com/docker/compose) - Tworzenie złożonych środowisk kontenerów

### SERWERY

- [Gunicorn](https://gunicorn.org/) - Serwer WSGI HTTP
- [Nginx](https://www.nginx.com/) - Serwer www i proxy
- [HaProxy](https://www.haproxy.org/) - Proxy dla połączeń TCP/HTTP
- [ProFTPd](http://www.proftpd.org/) - Serwer FTP
- [VsFTPd](https://security.appspot.com/vsftpd.html) - Serwer FTP
- [Bind](https://www.isc.org/bind/) - Serwer DNS
- [RabbitMQ](https://www.rabbitmq.com/) - Kolejkowanie komunikatów

### MONITOROWANIE

- [Nagios](https://www.nagios.org/) - Kompleksowe monitorowanie środowiska
- [Zabbix](https://www.zabbix.com/) - Kompleksowe monitorowanie środowiska
- [Sensu](https://sensu.io/) - Wydajny i masywnie skalowalny system do monitorowania
- [Cacti](https://www.cacti.net/) - Rysowanie wykresów wysycenia zasobów
- [Simple Event Conrelator](https://simple-evcorr.github.io/) - korelacja zdarzeń z różnych systemów
- [Elastic Search](https://www.elastic.co/)
- [Kibana](https://www.elastic.co/kibana)
- [Logstash](https://www.elastic.co/logstash)
- [Rancid](https://shrubbery.net/rancid/)
- [gNMIc](https://gnmic.kmrd.dev) - kolektor gNMI
- [SEC - Simple Event Correlator](https://simple-evcorr.github.io/)

## **NARZĘDZIA DESKTOP**

- [Putty](http://www.chiark.greenend.org.uk/~sgtatham/putty/download.html) - Najpopularniejszy, darmowy terminal
- [SecureCrt](https://www.vandyke.com/products/securecrt/) - Bardzo dobry, ale niestety komercyjny terminal
- [Windows Terminal](https://github.com/microsoft/terminal) - Bardziej przyjazny zamiennik cmd.exe
- [Dokumentacja Windows Terminal](https://docs.microsoft.com/en-us/windows/terminal/)
- [KeePass](http://www.keepass.info) - Zarządzanie hasłami
- [VeraCrypt](https://www.veracrypt.fr/en/Home.html) - Szyfrowanie plików, katalogów i dysków
- [Open VPN](https://community.openvpn.net/openvpn)
- [Total Commander](https://www.ghisler.com/) - Najlepsze narzędzie do poruszania się po katalogach i plikach
- [WinSCP](https://winscp.net/) - Klient graficzny SCP
- [Wireshark](https://www.wireshark.org/) - Analiza pakietów
- [WinMTR](https://sourceforge.net/projects/winmtr/) - Połączenie `ping` i `traceroute`
- [Greenshot](https://github.com/greenshot/greenshot) - Narzędzie do robienia zrzutów ekranów
- [IrfanView](http://www.irfanview.com/) - Prosta i szybka przeglądarka do zdjęć

## **NARZĘDZIA ONLINE**

- [URL Encode/Decode](https://www.url-encode-decode.com) - Zamiana URL na przyjazdny dla HTTP
- [Regex101](https://regex101.com) - Testowanie wyrażeń regularnych
- [Tools for Developers](https://extendsclass.com) - Narzędzia dla programistów

## **SPOŁECZNOŚCI**

- [NANOG](https://www.youtube.com/c/TeamNANOG/videos)
- [Tech Field Day](https://www.youtube.com/c/Techfieldday/videos)
- [Network to Code](https://www.youtube.com/channel/UCwBh-dDdoqzxXKyvTw3BuTw/videos)
