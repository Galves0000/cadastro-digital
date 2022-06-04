Programas necessarios para Rodar o programa:
  Python


-----windows-------------------------------------------------------------------------------------------------


1- ao clonar o programa acesse o mesmo atraves do terminal de comando
  C:\Users\gabri\Documents\projeto\cadastro-digital

2- ao acessar a pasta pelo terminal de comando ative o ambiente virtual "auth" com o comando:
  auth\Scripts\activate

resultado:
  (auth) C:\Users\gabri\Documents\projeto\cadastro-digital
  
 3- apos ativar o ambiente é necessario instruir o app para inicial, então digitamos o codigo:
      set FLASK_APP=project
      set FLASK_DEBUG=1
      flask run
      
4- se tudo ocorrer bem o terminal deve gerar esta msg ou semelhante:

 * Serving Flask app 'project' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
C:\Users\gabri\Documents\projeto\flask_auth_app\auth\lib\site-packages\flask_sqlalchemy\__init__.py:872: FSADeprecationWarning: SQLALCHEMY_TRACK_MODIFICATIONS adds significant overhead and will be disabled by default in the future.  Set it to True or False to suppress this warning.
  warnings.warn(FSADeprecationWarning(
 * Running on http://127.0.0.1:5000 (Press CTRL+C to quit)
 
 
 
4.1- copie o link http://127.0.0.1:5000 e cole no seu navegador.
 
 
 se vc desejar recriar a pasta auth (ambiente virtual):
 
 5- acesse a pasta cadastro-digital pelo terminal de comando e crie um ambiente virtual usando os comando abaixo:
  C:\Users\gabri\Documents\projeto\cadastro-digital
  
  comandos:
    py -3 -m venv auth
    
   5.1 ative:
      auth\Scripts\activate
      
    5.2 instale os apps:

    pip install flask
    pip install sqlalchemy
    pip install flask-sqlalchemy
    pip install flask-login
    
    e volte para o passo 3
    
    
    
    -------LINUX---------------------------------------------
  
 
 1- ao clonar o programa acesse o mesmo atraves do terminal de comando
  C:\Users\gabri\Documents\projeto\cadastro-digital

2- ao acessar a pasta pelo terminal de comando ative o ambiente virtual "auth" com o comando:
  auth/bin/activate

resultado:
  (auth) C:\Users\gabri\Documents\projeto\cadastro-digital
  
 3- apos ativar o ambiente é necessario instruir o app para inicial então digitamos o codigo:
      export FLASK_APP=project
      export FLASK_DEBUG=1
      flask run
      
4- se tudo ocorrer bem o terminal deve gerar esta msg ou semelhante:

 * Serving Flask app 'project' (lazy loading)
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
C:\Users\gabri\Documents\projeto\flask_auth_app\auth\lib\site-packages\flask_sqlalchemy\__init__.py:872: FSADeprecationWarning: SQLALCHEMY_TRACK_MODIFICATIONS adds significant overhead and will be disabled by default in the future.  Set it to True or False to suppress this warning.
  warnings.warn(FSADeprecationWarning(
 * Running on http://127.0.0.1:5000 (Press CTRL+C to quit)
 
 
 
4.1- copie o link http://127.0.0.1:5000 e cole no seu navegador.
 
 
  se vc desejar recriar a pasta auth (ambiente virtual):
 
  5- acesse a pasta cadastro-digital pelo terminal de comando e crie um ambiente virtual usando os comando abaixo:
  C:\Users\gabri\Documents\projeto\cadastro-digital
  
  comandos:
    python3 -m venv auth
    
   5.1 ative:
      auth/bin/activate
      
    5.2 instale os apps:

    pip install flask
    pip install sqlalchemy
    pip install flask-sqlalchemy
    pip install flask-login
    
    e volte para o passo 3
    
 
 
