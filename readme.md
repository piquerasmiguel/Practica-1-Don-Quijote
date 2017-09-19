
# Práctica GIT

### Apellidos: Piqueras Garrigós, Nombre: Miguel

# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque de esta forma deshago el último commit perdiendo los cambios (sin "--hard" los conservaría).

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué??**

`git reflog y git reset --hard <identificador>` 

Para conseguir desplazarme de nuevo al commit que había deshecho.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No, porque la rama style sale de master y está en linea directa con esta.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Causa un conflicto de contenido, debemos elegir con cual nos quedamos.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No. Porque están en linea y porque el orden de mergeado es de master a style, y no al revés (style es posterior a master, ya tiene la info de este).

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph` 

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**


No, no están en línea.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 

Para conseguir desplazarme de nuevo al commit que había deshecho.

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git reflog, git reset --hard <identificador> y git reset --hard HEAD~1` 

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D <nombre rama>` 

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog y git reset --hard <identificador>` 

--

**12. ¿Qué comando o comandos utilizaste en el paso 32?**

`git reflog y git reset --hard <identificador>` 

--

**13. ¿Qué comando o comandos utilizaste en el paso 33?**

`git reflog y git reset --hard <identificador>` 

--