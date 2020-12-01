# Example Python Flask Crud

 Simple example python flask crud app for sqlite.


## Run in CodeReady Workspaces

[![Contribute](https://raw.githubusercontent.com/blues-man/django-realworld-example-app/master/factory-contribute.svg)](https://codeready-openshift-workspaces.apps.cluster-a64e.a64e.example.opentlc.com/factory?url=https://github.com/blues-man/example-flask-crud.git)

## Screenshots


![image](screenshots.png)  
 
 
### Installing (for linux)

open the terminal and follow the white rabbit.


```
git clone https://github.com/gurkanakdeniz/example-flask-crud.git
```
```
cd example-flask-crud/
```
```
python3 -m venv venv
```
```
source venv/bin/activate
```
```
pip install --upgrade pip
```
```
pip install -r requirements.txt
```
```
export FLASK_APP=crudapp.py
```
```
flask db init
```
```
flask db migrate -m "entries table"
```
```
flask db upgrade
```
```
flask run
```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
