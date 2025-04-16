# tk
Command line tool for keeping track of time on projects

## Installation
* Copy the `tk` file to your `~/bin` folder
* Run command `chmod +x ~/bin/tk` to make the file executable
* Login or create an account on https://tkonline.io
* Go to https://tkonline.io/account and create an API keyset

## Authentication
There are two ways to authenticate:

### Method 1: Using the login command
* Run `tk login` in your terminal
* When prompted, enter your API Key and API Secret (these will be provided on https://tkonline.io/account)
* The credentials will be automatically saved to `~/.tk`

### Method 2: Manual configuration
* Create a `.tk` file in your home directory (`~/.tk`)
* Add the following content, replacing the values with your actual API credentials:
```
[tkonline.io]
api_key = your_api_key_here
api_secret = your_api_secret_here
```

## Usage
* To track time on a project: `tk project_name`
* To check API status: `tk` (without any arguments)
