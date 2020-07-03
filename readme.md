Using POST access

api/signup.php
{
	"nombre":"usuario",
	"contrasena":"contrasena",
	"rol":"usuario"
}

api/signin.php
{
	"usuario":"usuario",
	"contrasena":"contrasena"
}

api/read.php: header
Content-type application/json
Authorization JWT [KEY]
