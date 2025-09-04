# Mis Apuntes de _P.L.I_

## Comandos básicos de terminal

## Sintaxis de _Markdown_

### Configuración inicial 

Estos comandos los vas a ejecutar una sola vez, después de que hayas instalado **git** en tu computadora

```bash
git --version
git config --global user.name "Jonathan MirCha"
git config --global user.email jonmircha@gmail.com
git config --global user.ui true
git config --global init.defaultBranch main
git config --list
# asignando visual studio code como editor de configuración de git
git config --global core.editor "code --wait"
git config --global -e
# para estandarizar los saltos de línea en windows
git config --global core.autocrlf true
# para estandarizar los saltos de línea en linux/mac
git config --global core.autocrlf input
# ver todas las opciones de la configuración en la terminal
git config -h
# ver todas las opciones de la configuración en el navegador
git help config
```



### Instalando Git
Cuando queremos iniciar _git_ en alguna carpeta local de nuestra computadora, debemos ejecutar ese comando:

``` bash
git intit
```

###
El siguiente comando nos ayuda a visualizar el estado de seguimiento de lo archivos de nuestra carpeta: 

``` bash
git status
```
El siguiente comando nos ayuda a ver el log del historial de cambios del repositorio:

``` bash
git log
```


### Flujo Básico de Git & GitHub

![Flujo Básico entre Git & Hub](https://jonmircha.com/img/blog/git-flow.png)

``` bash
 git add <nombre-archivo>
```

# Encabezado Nivel 1
## Encabezado Nivel 2
### Encabezado Nivel 3
#### Encabezado Nivel 4
#### Encabezado Nivel 5
##### Encabezado Nivel 6

Esto es un párrafo, el párrado en markdown se termina cuando damos enter

Esto es otro párrafo

Para poner **negrita** debes encerrar la palabra entre dobles asterizco

Para poner _cursiva_ debes de encerrar la palabra con guíon bajo

Para poner _**negrita y cursiva**_ debes de encerrar la palabra entre doble asterizco y con guión bajo

- Primavera
- Verano
- Otoño
- Invierno

1. Primavera
2. Verano
3. Otoño
4. Invierno


| País | Ciudad | Continente |
|-|-|-
| México | CDMX | América |
| Francia | Paris | Europa|
| Japón | Tokyo | Asia |

---
>- Yo solo se que no se nada- Sócrates

![CATALYST](https://th.bing.com/th/id/R.eadc3138bfcc7e88f56fd33d214fe035?rik=wgUMmw5KRR4rrg&pid=ImgRaw&r=0)

[Visita la web de AMERIKE](https://fortnite.gg/img/items/458/lego.png?6)

---

```js
function sumar(a, b) {
  if (typeof a !== "number" || typeof b !== "number") {
    console.error(`Los valores ingresados NO son números.`);
    return false;
  }

  let c = a + b;
  return c;
}
```

<form>
  <label for="q">Buscar:</label>
  <input type="search" name="q" id="q" required />
  <input type="submit" value="🔍" />
</form>

<!-- Holi OwO -->