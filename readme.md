**¿Qué comando utilizaste en el paso 11? ¿Por qué?**
```
git reset --hard HEAD~1
```

Porque nos indican que hay que eliminar el Working Copy. Además, como hay que eliminar el último commit, es el método más sencillo.

**¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**
```
git reflog
git reset 6037f88 
```

Uso el método Selección Directa, usando el SHA del commit, que lo obtengo del reflog. 
**El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No. El merge se puede realizar usando el método fast forward

**El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**
 
Sí. Se había realizado ya un merge en la rama htmlfy, y había tocado las mismas lineas de código,  y al no poder crear una lista del grafo, tiene que hacer un merge.	

**El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**
 
No, la rama syled y master, ya habían sido mergeadas con anterioridad. En esta ocasión, sí se puede usar un mergeo fast forward, y por ello no genera conflictos.

**¿Qué comando o comandos utilizaste en el paso 25?**

Tengo un alias creado:
```
git config alias.graph “log --graph --decorate --pretty=oneline”
git graph
```

**El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Si, ya que pueden formar una lista.

**¿Qué comando o comandos utilizaste en el paso 27? **
```
git reset HEAD~1
```

**¿Qué comando o comandos utilizaste en el paso 28?**
```
git reset HEAD GIT-NUESTRO.MD
```

**¿Qué comando o comandos utilizaste en el paso 29?**
```
git branch -D title
```

**¿Qué comando o comandos utilizaste en el paso 30?**
```
git reset --hard 930015b
```
También he hecho.
```
git reflog
```
Para obtener el último acceso donde estaba creada la rama ‘title’
```
git checkout a7934ff 
```
acceso al commit donde estaba la rama title
```
git checkout -b title 
```
creo la rama y accedo

**¿Qué comando o comandos usaste en el paso 32?**
```
git reset --hard 12eddbb
```
También he usado el siguiente método.
```
git log
```
Obtengo el primer comit
```
git reset --hard 4dfa1fad2b27366657a52670c25318359891306f
```

**¿Qué comando o comandos usaste en el punto 33? **
```
git reflog -> obtener el listado de commit realizados
git checkout a7934ff -> donde realizamos el commit dentro de la rama title, del cambio
git checkout -b title -> restauro la rama title, donde estaba, y vuelvo al commit fina.
```


