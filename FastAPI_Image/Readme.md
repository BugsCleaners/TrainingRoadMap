
# *_Build your first image._*

### Step one:

First step is to write your python code and decide what it would be:

*Example:*



### Step two:

Create your docker file, this file should contain the libraries that your code depend on, and the python image imported from docker hub.

*Example:*



### Step three:

create requirements.txt file, which contains the modules and their versions and also this file is referenced in the dockerfile.

*Example:*



### Step four:

Build the image using the following command:

"docker build -t ahmad:latest ."

This command will create your image with the name ahmad.

### Step five:

Then use the docker command to run your image:

Ensure that the target port and the container port match.



Finally access your image:



Press on the link and you will be redirected to a new tab with your API code.

### _SIMPLE AND STUIPD!_
