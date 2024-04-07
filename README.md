<p align="center">
  <img src="http://www.ideiadofuturo.com.br/img/logo_ideia.png" width="120" title="" alt="">  
</p>



---

# projeto_organa_react_nodejs
projeto de estudo com react e nodejs


## instalando node no Linux

 - Para instalar o Node, abra o terminal e digite:
   - ```bash 
      sudo apt install nodejs 
      ```

 - Para conferir se o download ocorreu corretamente, digite
   - ```bash 
      node -v 
      node --version  
      ```

- modelo do figma: https://www.figma.com/file/T6BLI1HfB81eYOiVgpqQz7/Projeto-Intro-ao-React?type=design&node-id=190-1050&mode=design&t=kNGHgmJrdEYFcPap-0
- imagens para utilizar: [modelos](modelos)



---

# comandos úteis

## GIT
 - lembre se trocar o nome do **branch** de acordo com a necessidade



### iniciar o repo
    git init
    git remote add origin https://github.com/eniodefarias/projeto_organa_react_nodejs.git



### puxar "git pull" da branch "ajuste_01"
    git pull -f origin ajuste_01


#### ou da main, se necessário:
    git pull -f origin main




### trocar branch main
    git branch main ; git checkout main 


### enviar "git push" da branch
    git add . ; git add * ; git commit -m "fix: ajuste de log debug com prints" ; git push -f origin ajuste_01


#### ou trocar branch para uma de teste, se for fazer algum ajuste
    git branch ajuste_01 ; git checkout ajuste_01
