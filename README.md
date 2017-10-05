# Algunos comandos

Observaciones en cada paso que hagan vayan revisando el estado del repositorio con:
```sh
git status
```
## git clone
Clonar el repositorio :)
git clone https://github.com/vanecan/factory.git

## git add
Crear el archivo test.rb
```ruby
puts "Hola Equipo Factory"
```
Agregar al staging area: 
```sh
git add test.rb
```

## git commit 
```sh
git commit test.rb -m "Creación de un test en el equipo factory"
```

## git push
```sh
git push origin master
```

## git branch
```sh
git branch develop
```

## git checkout 
```sh
git checkout develop
```

## git merge
```sh
git merge master
```

## git tag
```sh
git tag -a v1.0 -m "Version 1.0"
```

## git remote 
```sh
git remote -v
git remote add company https://github.com/vanecan/company.git
```

## git pull remote branch
```sh
git pull company master
```

