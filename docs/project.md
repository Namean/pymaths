# Project.md

I'm working a file that can generate data sets from functions.
Once written I'd like to use scp or git to clone down the file to be ran on my windows machine
to be plotted. Or maybe I can jsut SSH into it once I get the server downloaded.

There are some unique features of this project that I've been wanting to implement for some time now.


Environment variables.

I assumed that you could persist environment variables by writing to /etc/environment.
This however is not the case.




We have a function y.

There's a pattern used to generate the data


### /dataset.py
My goal with this file is to pass arbitrary function to dataset.py
which returns a dataset or makes calls to plot the data on a capable machine.



list(map(lambda x: y(x), arr))


###Adding Environment variables
https://www.serverlab.ca/tutorials/linux/administration-linux/how-to-set-environment-variables-in-linux/

###Assigning output of commands to variables
https://www.cyberciti.biz/faq/unix-linux-bsd-appleosx-bash-assign-variable-command-output/

### creating new python files with Shebang
Where shebang = '#!'$(which python)

echo $shebang > <filename.py[, *]>






