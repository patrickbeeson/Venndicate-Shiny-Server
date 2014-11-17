
### Setup instructions

1. Download and install Oracle Virtual Box [here](http://download.virtualbox.org/virtualbox/4.2.0/)
2. Download and install Vagrant [here](https://www.vagrantup.com/downloads)
3. Install Virtual Box Guest Additions: `$ vagrant plugin install vagrant-vbguest`
4. Checkout this repository: `$ git clone git@github.com:patrickbeeson/Venndicate-Shiny-Server.git`
5. Navigate to the repository folder locally: `cd venndicate-shiny-server`
6. Run: `vagrant up`
7. Shiny server is now visible at `localhost:3838` on your machine.

### Workflow

Put your apps in `venndicate-shiny-server/apps` and they will be visible at `localhost:3838/apps/` on your machine.
