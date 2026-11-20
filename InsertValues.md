# INSERTAR VALUES EN LAS TABLAS #

### INSERTAR EN EMPLEAT ###

```console
INSERT INTO empleat(dni,nom,tlf)
VALUES('1111F','Josep','987654321'),
('2222Z','Vegetta','123456789'),
('3333A','Willy','147258369'),
('4444E','Rubius','369258147'),
('5555W','Wismichu','789654123'),
('6666T','Trebor','321456987');
```
### INSERTAR EN PARENTESC ###

```console
INSERT INTO parentesc(dni1,dni2)
VALUES('1111F','2222Z'),
('3333A','6666T');
```
### INSERTAR EN LLIBRE ###

```console
INSERT INTO llibre(isbn)
VALUES(123),
(321),
(456),
(654),
(789),
(987);
```
### INSERTAR EN EXEMPLAR ###

```console
INSERT INTO exemplar(num,isbn_llibre)
VALUES(1,123),
(2,321),
(3,456),
(4,654),
(5,789),
(6,987);
```
### INSERTAR EN PRESTEC (RELACIÓ) ###

```console
INSERT INTO prestec(num_exemplar,dni_empleat,inici,final,durada)
VALUES(1,'1111F','2026-10-12','2026-10-30','18 dias'),
(2,'2222Z','2025-05-03','2025-06-10','37 dias'),
(3,'3333A','2026-04-03','2026-04-10','7 dias'),
(4,'6666T','2025-11-16','2025-11-20','4 dias'),
(5,'4444E','2026-01-25','2026-01-30','5 dias'),
(6,'5555W','2026-02-25','2026-03-10','15 dias');
```
### INSERTAR EN ###

```console

```
### INSERTAR EN ###

```console

```
### INSERTAR EN ###

```console

```
### INSERTAR EN ###

```console

```
### INSERTAR EN GUARDERÍA ###

```console
INSERT INTO guarderia(codi, nom) VALUES
(10, 'Escuela Karmaland'),
(20, 'Guarderia Wigetta'),
(30, 'Guarderia ClashRoyale');
```
### INSERTAR EN FILL ###

```console
INSERT INTO fill(nom, naixement, dni_empleat) VALUES
('Mini Vegetta', '2023-04-15', '2222Z'),
('Willy Jr', '2021-01-12', '3333A'),
('Rubius Jr', '2024-07-20', '4444E'),
('Josep Jr', '2022-03-10', '1111F');
```
### INSERTAR EN INSCRIPCIÓ ###

```console
INSERT INTO inscripcio(codi, nom, data) VALUES
(10, 'Mini Vegetta', '2025-09-01'),
(20, 'Willy Jr', '2023-09-01'),
(30, 'Rubius Jr', '2026-09-01'),
(10, 'Josep Jr', '2024-09-01');
```
