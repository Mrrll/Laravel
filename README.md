# Laravel 8
Aprendiendo Laravel
<a name="top"></a>

## Índice de contenidos

- [Instalación de Laravel con Composer](#item1)
- [Inicializando Git](#item2)
- [Preparar el contenido preparado para la próxima confirmación](#item3)
- [Archivos de Configuracion](#item4)
- [Primer Commit](#item5)
- [Configuración de usuario para git y github](#item6)
- [Subimos repositorio de git a github](#item7)

## Instalación de Laravel con Composer ...
<a name="item1"></a>
>`Typee:` En Consola ...
```console
composer create-project laravel/laravel:^8.0 NombreProyecto
```
<a name="top"></a>

## Inicializando Git ...
<a name="item2"></a>
>`Typee:` En Consola ...
```console
git init
```
<a name="top"></a>

### Archivos de Configuracion ...
<a name="item3"></a>
**`Nota:`
Modificaremos el archivo `.gitignore` para incluir los archivos de configuracion al repositorio.**

>`Abrimos:` el archivo `.gitignore` y borramos la linea siguiente ...
```git
.env
```
<a name="top"></a>

### Preparar el contenido preparado para la próxima confirmación ...
<a name="item4"></a>
>`Typee:` En Consola ...
```console
git add .
```
<a name="top"></a>

### Primer Commit
<a name="item5"></a>

**`Nota:` Creamos una nueva confirmación que contenga el contenido actual del índice y el mensaje de registro dado que describa los cambios.**

>`Typee:` En Consola ...
```console
    git commit -m "Instalacion de Laravel"
```
<a name="top"></a>

### Configuración de usuario para git y github
<a name="item6"></a>

>`Typee:` En Consola ...
```console
    git config --global user.email "..."
```
>`Typee:` En Consola ...
```console
    git config --global user.name "..."
```
<a name="top"></a>

### Subimos repositorio de git a github
<a name="item7"></a>

>`Typee:` En Consola ...
```console
    git remote add origin "URL del Repositorio en GitHub"
```
<a name="top"></a>
