# Description

This is a project made for a Restaurant Menu Website.

# Requirements

1. Virtual machine - [Vagrant](https://www.vagrantup.com/)
2. [VirtualBox](https://www.virtualbox.org/)
3. [SQLAlchemy](https://www.sqlalchemy.org/) module
4. Flask module
5. Python3

# <span id="data">Data</span>

1. `python database_setup.py` to build the database.
2. `python lotsofmenus.py` to write in the data samples.

# Setup

1. Fork the [fullstack-nanodegree-vm](https://github.com/udacity/fullstack-nanodegree-vm) .
2.  `git clone http://github.com/<username>/fullstack-nanodegree-vm fullstack`
3. `vagrant up`  to start up the virtual machine.
4. `vagrant ssh` to log into the virtual machine.
5. `cd /vagrant`, copy the project into the directory.
6. Prepare the data according to [Data](#data).
7. `python project.py` to start the server.

# <span id="view">Browse Instruction</span>

See the home page of certain restaurant:

```url
http://0.0.0.0:5000/restaurants/<restaurant-id>/menu/
eg. http://0.0.0.0:5000/restaurants/2/menu/
```

See the JSON of certain restaurant:

```url
http://0.0.0.0:5000/restaurants/<restaurant-id>/menu/JSOn
eg. http://0.0.0.0:5000/restaurants/2/menu/JSON
```

See the JSON of certain menu of certain restaurant:

```url
http://0.0.0.0:5000/restaurants/<restaurant-id>/menu/<menu-id>/JSOn
eg. http://0.0.0.0:5000/restaurants/2/menu/3/JSON
```

