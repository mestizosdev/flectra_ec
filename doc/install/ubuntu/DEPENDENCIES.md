* Git
```
sudo apt install git
```
* Python
```
sudo apt-get install gcc python3-venv build-essential python3-pillow python3-wheel python3-lxml python3-dev python3-pip python3-setuptools gdebi libldap2-dev libsasl2-dev libxml2-dev libxslt1-dev libjpeg-dev libpq-dev
```
```
sudo apt install python3-virtualenv libxslt-dev libzip-dev libssl-dev
```
* CSS processor
```
sudo apt install npm
```
```
sudo npm install -g less less-plugin-clean-css
```
* wkhtmltopdf HTML to PDF

Go to wkhtmltopdf.org and download your compatible version
```
wget https://github.com/wkhtmltopdf/packaging/releases/download/0.12.6-1/wkhtmltox_0.12.6-1.focal_amd64.deb
```
```
sudo apt install ./wkhtmltox_0.12.6-1.focal_amd64.deb 
```
* Get odoo source code
```
git clone https://gitlab.com/flectra-hq/flectra.git
```
* Create python virtual environment
```
cd flectra
```
```
virtualenv venv
```
* Activate python virtual environment
```
source ./venv/bin/activate
```
* Update pip
```
pip install -U pip
```
* Install requirements
```
pip install -r requirements.txt
```
* Install source code files
```
pip install -e ./
```