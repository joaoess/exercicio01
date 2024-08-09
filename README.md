<h4 align="center">
⬇️ * # Exercicio01 # * ⬇️
</h4>
<h4 align="center">
  * Exercicio01_CICD_Impacta: *
</h4>

<h4>
  ! CONFIGS INICIAIS !
<h4> 
   R: 
<h4>
</h4>
</h4>
</h4>
<h4>


 ![Ex_1](https://github.com/user-attachments/assets/3c959589-910e-48dc-9f16-312a1ffe24f7)



A) No working dir, executar o comando:
   echo 01 > arquivo.txt
<h4> 
   R: 
<h4>   
</h4>
</h4>
</h4>
<h4>

![Ex_2](https://github.com/user-attachments/assets/6a7c75f3-e9c8-4b7e-8bb7-2d166e9a5374)



B) Adicionar o arquivo no staging e conferir o status:
<h4> 
 R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4> 
<h4>
</h4>
</h4>
</h4>
<h4>

![Ex_3](https://github.com/user-attachments/assets/f02d82ab-7a09-4d8d-9261-4f52f5c44517)



C) Commitar o arquivo do staging com a descrição "git add example - arquivo.txt":
<h4> 
R:
<h4>
@joaoess ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git commit -m "git add example - arquivo.txt" .
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![Ex_4](https://github.com/user-attachments/assets/25c8f20e-f266-4d83-8832-fad4201aa133)



D) Sobrescrever o conteúdo do arquivo.txt:
   echo 02 > arquivo.txt
<h4> 
R:
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 02 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![Ex_5](https://github.com/user-attachments/assets/b423afec-ac81-4614-a2f5-be09f2e9e76b)



E) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![Ex_6](https://github.com/user-attachments/assets/b00399b3-1293-4b8c-a7fd-9675fff49cae)




F) Adicionar novamente o arquivo no staging e conferir o status:
<h4>
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git add .
</h4>
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![Ex_7](https://github.com/user-attachments/assets/760f86c1-c931-4a3d-82ee-2bd743cb96e7)



G) Verificar o diffing no arquivo:
<h4> 
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>




H) Sobrescrever o conteúdo do arquivo.txt:
 echo 03 > arquivo.txt
<h4>
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo 03 > arquivo.txt
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![Ex_8](https://github.com/user-attachments/assets/00f1dcab-02e7-4a65-9e16-ee1414e6fae7)



I) Verificar o diffing no arquivo:
<h4>
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/exercicio01 (main) $ git diff
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>



![image](https://github.com/user-attachments/assets/834d4bd9-cc1b-4a48-bc84-60b70edd8f15)


J) Fazer o restore do arquivo da área de staging e verificar o status:
<h4>
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git restore arquivo.txt 
</h4>
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>


![Ex_9](https://github.com/user-attachments/assets/5eaa6ced-81fc-459d-a120-dc82a5175aaa)



K) Realizar o commit do arquivo e verificar o log:
<h4>
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git commit -m "Primeiro Commit - Arquivo.txt"
</h4>
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ git log
<h4>
</h4>
</h4>
</h4>
<h4>

![Ex_11](https://github.com/user-attachments/assets/7eef56ad-ab21-4c25-a5cf-72077587ca7e)


![Ex_12](https://github.com/user-attachments/assets/fdf2c0fa-5fcb-421c-be45-399e12549cf0)



L) Adicionar um arquivo gitignore com o seguinte conteúdo:
 *.txt
<h4> 
R: 
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ vi .gitignore
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![Ex_13](https://github.com/user-attachments/assets/0664d758-9bc2-47fe-bb76-019387e65635)


![Ex_14](https://github.com/user-attachments/assets/de2a120c-ca5f-4d5d-a2a8-de0d244d3dc2)



M) Criar um arquivo novo.txt e verificar o status:
<h4> 
R:
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > novo.txt
</h4>
<h4>
@joaoess ➜ /workspaces/codespaces-blank/Exercicio01 (main) $ echo > git status
</h4>
<h4>
</h4>
</h4>
</h4>
<h4>

![Ex_15](https://github.com/user-attachments/assets/c898f7e9-1b3b-4cd9-80f4-858bdd9b5482)


