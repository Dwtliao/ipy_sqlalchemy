# ipy_sqlalchemy
###Abstract: 
Use **SQL** inside python notebook and create/load SQL tables with *Obj Oriented* python **sqlalchemy** library

There's a word doc of instructions to install **Binstar** first (preferred library installer for Anaconda Py)
in order to install **psycopg2** for Python to connect to SQL data bases

2nd helpful library installed is for **ipython-sql** Extensions
3rd library sqlalchemy should already be part of base Anaconda Py install- use Anaconda Navigator to confirm

Bring up Anaconda Navigator and you should see the **psycopg2 , ipython-sql** packages was installed successfully and is recognized by Anaconda on your pc.

import **sqlalchemy** to use object oriented py libraries to create a class that represents an SQL table you want to create or already exists in your DB system.  this is a great way to loop thru local data cleaned up in a python notebook session and stay in your py session and load data directly into a SQL table.  

You can also execute typical SQL qrys with the **ipython-sql** extension.

See the python notebook example as HTML file in this repository
