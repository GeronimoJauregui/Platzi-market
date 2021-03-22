# Platzi-market
Proyecto del curso de Java Spring

# Producción
java -jar -Dspring.profiles.active=pdn  build/libs/platzi-market-1.0.jar

# Heroku
- Crear una cuenta en heroku.
- Instalar Heroku CLI "brew tap heroku/brew && brew install heroku".
- $>heroku create platzimarketversion1
- $>heroku addons:create heroku-postgresql
- $>heroku config: //usuario:contraseña@localhost:puerto/nombrebasedatos
- $>git push heroku main
- $>heroku open
