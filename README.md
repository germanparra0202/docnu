# docnu
Full-stack project for my startup co-founded with Jorge Armenta 

#### Configure Application Environment
 
Install `virtualenv` for Python:
> may need to upgrade pip if prompted.
 
    $ pip3 install virtualenv
 
Create a virtual environment (in the `backend-api` directory):

    $ python3 -m venv venv

To Activate the Virtual Environment, run the following command

    $ source venv/bin/activate

Download `Flask` from Python:
> May need to upgrade pip if prompted. 

    $ pip3 install flask

> To confirm it is working correctly, type in the following command.

    $ python3 -m flask version
    
The next command should handle the previous commands and install other dependencies.

    $ pip3 install -r requirements.txt
