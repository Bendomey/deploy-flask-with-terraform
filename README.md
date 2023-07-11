# Deploy Flask App With Terraform
Provision infrastructure using terraform to deploy simple flask app

# Setup Locally
To run app locally, you can either install deps or create a virtual env:

## Installing Deps without Env
> pip install -r requirements.txt

### Using Virtual Env:
If you're using pyenv, you can follow this:

`pyenv virtualenv your-virtual-env-name` 
> To create your virtual env

`pyenv activate your-virtual-env-name`
> To activate it

`pip install -r requirements.txt`
> Install requirements

## Run App
> python app.py


## Access App
You can access the app in your browser. Visit `http://localhost:5001`


# Deploy using terraform
This setup is using google cloud for deployment. So you'll need to create an account on gcp.
