use escuela_urn;
db.createCollection("alumnos");
db.createCollection("docentes");
db.createCollection("carreras");
db.alumnos.insertOne({numero_control:26001, nombre:"Alan Martinez Rivera", carrera:"Derecho", edad:20, curp:"MARA060312HCHRVL09", tipo_sangre:"AB+"});
db.alumnos.insertOne({numero_control:26002, nombre:"Jose Luis Galvan Rodriguez", carrera:"Administración de Empresas", edad:18, curp:"GARJ071202HCHLDS09", tipo_sangre:"O+"});
db.alumnos.insertOne({numero_control:26003, nombre:"Santiago Coronado Valles", carrera:"Negocios Internacionales", edad:22, curp:"COVS030823HCHRLN09", tipo_sangre:"B-"});
db.alumnos.insertOne({numero_control:26004, nombre:"Mohamed Salah Halbum", carrera:"Dirección y Administración de Aeropuertos y Negocios Aereos", edad:19, curp:"SAHM060911HCHLLH09", tipo_sangre:"O-"});
db.alumnos.insertOne({numero_control:26005, nombre:"Lara Flores Mendoza", carrera:"Contaduría Pública", edad:21, curp:"FOML050403MCHLNR09", tipo_sangre:"A+"});
db.alumnos.insertOne({numero_control:26006, nombre:"Jesus Eduardo Gonzalez Montes", carrera:"Ciencias de la Comunicación", edad:23, curp:"GOCJ030227HCHNR509", tipo_sangre:"B+"});
db.alumnos.insertOne({numero_control:26007, nombre:"Fernanda Rivas Castañeda", carrera:"Mercadotecnia", edad:18, curp:"RICF071018MCHVSN09", tipo_sangre:"AB+"});
db.alumnos.insertOne({numero_control:26008, nombre:"Raul Daniel Armendariz Solis", carrera:"Sistemas Computacionales", edad:18, curp:"AESR070707HCHBLL09", tipo_sangre:"A+"});
db.alumnos.insertOne({numero_control:26009, nombre:"Casandra Montes Jimenez", carrera:"Turismo", edad:22, curp:"MOJC040522MCHNMS09", tipo_sangre:"O+"});
db.alumnos.insertOne({numero_control:26010, nombre:"Monserrat Garcia Lopez", carrera:"Psicología", edad:18, curp:"GALM080115MCHRPN09", tipo_sangre:"O+"});

db.docentes.insertOne({_id:"D-01", nombre:"Jorge Alvarez Romulo", carrera_estudiada:"Lic. En Derecho", materia:"Derecho Procesal Penal", edad:32, curp:"ALRJ940312HDFRMN05", cedula:"10293847"});
db.docentes.insertOne({_id:"D-02", nombre:"Daniela Soto Hernandez", carrera_estudiada:"Lic en Mercadotecnia", materia:"Mercadotecnia Digital", edad:28, curp:"SOHD980722MCATRNO1", cedula:"11405928"});
db.docentes.insertOne({_id:"D-03", nombre:"Alvaro Sanchez Aguilar", carrera_estudiada:"Lic. En Comercio Internacional", materia:"Comercio Exterior y Aduana", edad:30, curp:"SAAA960111HCHNGV03", cedula:"10948573"});
db.docentes.insertOne({_id:"D-04", nombre:"Floriela Carrillo Ortega", carrera_estudiada:"Contador Público", materia:"Contabilidad Financiera", edad:42, curp:"CAOF841102CORRLO9", cedula:"08374625"});
db.docentes.insertOne({_id:"D-05", nombre:"Saul Mejia Moreno", carrera_estudiada:"Ingeniería Aeronáutica", materia:"Meteorología y Navegación Aérea", edad:35, curp:"MEMS910518DFZLL02", cedula:"09483726"});
db.docentes.insertOne({_id:"D-06", nombre:"Valeria Mendoza Hoyos", carrera_estudiada:"Lic. En Ciencias de la Comunicación", materia:"Comunicación y Relaciones Públicas", edad:39, curp:"MEHV870824CHNNR04", cedula:"09182736"});
db.docentes.insertOne({_id:"D-07", nombre:"Hector Charria Gallegos", carrera_estudiada:"Lic. En Derecho", materia:"Derecho Constitucional", edad:45, curp:"CAGH810210DFGGR08", cedula:"07463524"});
db.docentes.insertOne({_id:"D-08", nombre:"Enrique Gomez Gomez", carrera_estudiada:"Lic. En Logística Internacional", materia:"Logística Internacional", edad:41, curp:"GOGE851203CHMMN02", cedula:"089217461"});
db.docentes.insertOne({_id:"D-09", nombre:"Gabriela Velazquez Pozo", carrera_estudiada:"Lic. En Ciencias de la Comunicación", materia:"Producción de Medios y Video", edad:33, curp:"VEPG930430DGZSS09", cedula:"11384950"});
db.docentes.insertOne({_id:"D-10", nombre:"Clara Lozano Rosas", carrera_estudiada:"Lic. En Administración de Empresas", materia:"Recursos Humanos", edad:29, curp:"LOEC971014CHZZNO1", cedula:"11384950"});

db.carreras.insertOne({_id:"C-01", nombre:"Derecho", campus:["Chihuahua", "Cd. Juárez", "Parral", "Cuauhtémoc", "NCG"], creditos:340, duracion_cuatrimestres:9, modalidad:["Escolarizado", "DYES", "Sabatino"]});
db.carreras.insertOne({_id:"C-02", nombre:"Administración de Empresas", campus:["Chihuahua", "Cd. Juárez", "Parral", "Cuauhtémoc", "NCG", "Virtual"], creditos:325, duracion_cuatrimestres:9, modalidad:["Escolarizada", "Sabatino", "Virtual"]});
db.carreras.insertOne({_id:"C-03", nombre:"Negocios Internacionales", campus:["Chihuahua", "Cd. Juárez", "Virtual"], creditos:330, duracion_cuatrimestres:9, modalidad:["Escolarizada", "Virtual"]});
db.carreras.insertOne({_id:"C-04", nombre:"Dirección y Administración de Aeropuertos y Negocios Aéreos", campus:["Chihuahua"], creditos:360, duracion_cuatrimestres:9, modalidad:["Escolarizada"]});
db.carreras.insertOne({_id:"C-05", nombre:"Contaduría Pública", campus:["Chihuahua", "Cd. Juárez", "Parral", "Virtual"], creditos:330, duracion_cuatrimestres:9, modalidad:["Escolarizada", "Sabatino", "Virtual"]});
db.carreras.insertOne({_id:"C-06", nombre:"Ciencias de la Comunicación", campus:["Chihuahua"], creditos:320, duracion_cuatrimestres:9, modalidad:["Escolarizada"]});
db.carreras.insertOne({_id:"C-07", nombre:"Mercadotecnia", campus:["Chihuahua", "Cd. Juárez", "Virtual"], creditos:325, duracion_cuatrimestres:9, modalidad:["Escolarizada", "Virtual"]});
db.carreras.insertOne({_id:"C-08", nombre:"Sistemas Computacionales", campus:["Chihuahua", "Cd. Juárez"], creditos:350, duracion_cuatrimestres:9, modalidad:["Escolarizada", "Sabatino"]});
db.carreras.insertOne({_id:"C-09", nombre:"Turismo", campus:["Chihuahua", "Cd. Juárez"], creditos:315, duracion_cuatrimestres:9, modalidad:["Escolarizada"]});
db.carreras.insertOne({_id:"C-10", nombre:"Psicología", campus:["Chihuahua", "Cd. Juárez", "Virtual"], creditos:330, duracion_cuatrimestres:9, modalidad:["Escolarizada", "Virtual"]});

db.alumnos.find({tipo_sangre:"O+"});
db.docentes.findOne({_id:"D-05"});

db.alumnos.updateOne({numero_control:26002}, {$set:{edad:19}});
db.docentes.updateOne({_id:"D-01"}, {$set:{materia:"Derecho Penal Avanzado"}});

db.alumnos.deleteOne({numero_control:26003});
db.docentes.deleteOne({_id:"D-10"});
