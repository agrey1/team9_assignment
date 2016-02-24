# team9_assignment

## Contributing

Simple rules to stick to really.
- Fork this repository to your github account.
- Follow the Fork-Branch workflow as explained here http://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/
- Once you're done with your work, make a pull request to me.
- Master branch should be ready for deployement at any given time. Therfore, make sure your code is tested before submitting a pull request.


## Notes for running the API tests
Please note that these are only guidelines and that there are different ways of accomplishing the same results.
Also these are steps to follow if you're using a Debian based distribution.

Make sure these are installed in your general environment first:
- Python3 (any version) 
  sudo apt-get install python3
- VirtualEnv 
  sudo apt-get install virtualenv
- A few mysql needed packages sudo 
  apt-get install python-dev python3-dev
  sudo apt-get install libmysqlclient-dev

Setup a virtual environment:
  virtualenv -p /usr/bin/python3 venv
  
Run your virtual environment:
  source venv/bin/activate
  



