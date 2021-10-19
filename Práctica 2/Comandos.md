alter role miusuario with password '123456'

\l

\s

CREATE DATABASE pract1

;

CREATE TABLE usuarios(

nombre varchar(30),

clave varchar(10)

)

;

INSERT INTO usuarios(nombre, clave) VALUES('Isa','asdf')

;

ISERT INTO usuarios(nombre, clave) VALUES('Pablo','jfx344')

;

INSERT INTO usuarios(nombre, clave) VALUES('Ana','tru3fal')

;

SELECT *

FROM usuarios

;

\s
