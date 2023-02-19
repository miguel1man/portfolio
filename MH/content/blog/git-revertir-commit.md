---
title: "Git - Revertir commit"
date: 2023-01-10
description: "Comandos de Git para revertir cambios a un commit previo."
---

## Post 1

Descripción del post 1.

1. Revisar lista de commits anteriores. 
```git
git log --oneline
```

2. Revertir los cambios hasta un commit específico.
```git
git checkout código-del-commit .
``` 

3. Guarda los cambios.
```git
git add .  
git commit -m "Regresar a un commit anterior"  
git push
```

[git](blog/git)

---

[lista de tags]({{< ref "tags" >}})