 run below things to start and changes made from the original files:
    - git clone https://github.com/josephmachado/adv_data_transformation_in_sql.git
    - cd adv_data_transformation_in_sql
    - python -m venv ./env # create a virtual  env  ## use this in  (Mac/Linux)
        I used: C:\Users\<username>\AppData\Local\Programs\Python\Python312\python.exe --version
        reason: python 3.13 or latest had issues with requirements.txt
        also changed:   
            - Requirements.txt file 
                - cffi==1.16.0 to cffi==1.17.1
    - source env/bin/activate # use virtual environment
        I used:   venv\Scripts\activate     ## use this in (Windows)
    - pip install -r requirements.txt
    - python setup.py
    - jupyter lab
    

