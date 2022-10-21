# PFSwChO_lab3
JAN MAZUREK 91001


Użyte polecenia


Do budowy obrazu:

$docker build --secret id=id_rsa,src=C:/Users/Jan.Mazurek/.ssh/id_rsa -f Lab3/Dockerfile_s1 -t lab2.v1

Do wysłania go na docker hub

$ docker login

$ docker tag lab2.v1 janeeczek/lab2.v1

$ docker push janeeczek/lab2.v1
