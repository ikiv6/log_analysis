# Logs Analysis

> ibrahem kamal

## About

This is the third project for the Udacity Full Stack Nanodegree.The project mimics building an internal reporting tool for a newpaper site to discover what kind of articles the site's readers like. The database contains newspaper articles, as well as the web server log for the site.

## To Run

### You will need:
- Python3
- Vagrant
- VirtualBox

### Setup
1. Install Vagrant And VirtualBox
2. Clone this repository

### To Run

Launch Vagrant VM by running `vagrant up`, you can the log in with `vagrant ssh`

To load the data, use the command `psql -d news -f newsdata.sql` to connect a database and run the necessary SQL statements.

The database includes three tables:
- Authors table
- Articles table
- Log table

To execute the program, run `python3 log_analysis.py` from the command line.
