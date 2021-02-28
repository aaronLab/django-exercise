# Profiles Rest API

## Vagrant

- Init

```commandline
vagrant init ubuntu/bionic64
```

- Up

```commandline
vagrant Up
```

- SSH

```commandline
vagrant ssh
cd /vagrant
```

## Python env

- Setup Env

```commandline
python -m venv ~/env
```

- Activate Env

```commandline
source ~/env/bin/activate
```

- Deactivate Env

```commandline
deactivate
```

- Add dependency file

```text
requirements.txt

django==2.2
djangorestframework==3.9.2
```

- Install Dependency

```commandline
pip install -r requirements.txt
```