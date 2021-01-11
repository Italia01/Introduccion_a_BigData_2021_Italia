# Introduccion_a_BigData_2021_Italia
  1  mkdir ejemplo
    2  echo "hola mundo" > ejemplo/hola.txt
    3  cat ejemplo/hola.txt
    4  ls
    5  cd ejemplo/
    6  ls
    7  git init
    8  clear
    9  git remote add origin https://github.com/uracilo/Introduccion_a_BigData_2021_Benjamin.git
   10  clear
   11  git status
   12  git add hola.txt
   13  git status
   14  clear
   15  git commit -m "mi primer commit"
   16  git config --global user.name "Benjamin"
   17  git config --global user.email "benjamin.casazza@gmail.com"
   18  clear
   19  history
   20  git commit -m "mi primer commit"
   21  clear
   22  git status
   23  git commit -m "mi primer commit"
   24  git push origin master
   25  git status
   26  ls
   27  rm -rf ejemplo/
   28  clear
   29  git clone https://github.com/uracilo/Introduccion_a_BigData_2021_Benjamin.git
   30  ls
   31  cd Introduccion_a_BigData_2021_Benjamin/
   32  ls
   33  clear
   34  mkdir hola_mundo
   35  ls
   36  echo "hola" > hola_mundo/hola.txt
   37  ls hola_mundo/
   38  git status
   39  clear
   40  git add .
   41  git status
   42  git push origin master
   43  git status
   44  clear
   45  git push origin/master
   46  git push origin master
   47  cd ..
   48  ls
   49  rm -rf Introduccion_a_BigData_2021_Italia/
   50  ssh-keygen -o -f ~/.ssh/id_rsa
   51  clear
   52  cat  ~/.ssh/id_rsa
   53  cat  ~/.ssh/id_rsa.pub
   54  clear
   55  git clone git@github.com:uracilo/Introduccion_a_BigData_2021_Italia.git
   56  cd Introduccion_a_BigData_2021_Benjamin/
   57  ls
   58  clear
   59  ls
   60  echo "adios" > adios.txt
   61  ls
   62  cat adios.txt
   63  git status
   64  git add adios.txt
   65  git commit -m "adios txt"
   66  git push origin master
   67  clear
   68  history
   docker exec -it <id-container> cat /utm/texto.txt
