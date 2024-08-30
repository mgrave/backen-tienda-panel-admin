# Docker Commands

docker build -t tienda_backend .
docker run -p 5000:5000 tienda_backend

# Admin
https://bcrypt-generator.com

Collection: admins
{
    _id: ObjectId('66cea6f8830ab71a2d9bb399'),
    nombres: 'admin',
	apellidos:'admin',
	email:'admin@gmail.com',
    password: '$2a$04$bfPKfUwkBA.qxMaJnQZO9uLIHdvrg3w6VHV8bPL3LNFesD8FazUxa',    
	rol: 'admin'
}


Collection: configs
{
    _id: ObjectId('61abe55d2dce63583086f108'),
    envio_activacion: 'Todo el mundo',
	monto_min_soles:'1000',
	monto_min_dolares:'2000',
    createdAt: ''
}