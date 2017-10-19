    1  sudo shutdown now
    2  sudo apt-get install virtualbox-guest-additions-iso 
    3  mount /usr/share/virtualbox/VBoxGuestAdditions.iso 
    4  sudo mount -o loop /usr/share/virtualbox/VBoxGuestAdditions.iso /media/cdrom
    5  mkdir /media/cdrom
    6  sudo mkdir /media/cdrom
    7  sudo mount -o loop /usr/share/virtualbox/VBoxGuestAdditions.iso /media/cdrom
    8  git --version
    9  ls
   10  help
   11  ls
   12  ls -l
   13  ls --help
   14  ls
   15  ls --help
   16  ls -l -a
   17  ls -la
   18  history 
   19  pwd
   20  clear
   21  ls -la
   22  cd Desktop/
   23  pwd
   24  cd ..
   25  cd Desktop/
   26  cd ..
   27  pwd
   28  cd ../..
   29  ls
   30  cd home/gborowik/Desktop/
   31  mkdir first_repo
   32  cd first_repo/
   33  history 
   34  mkdir 1 2 3 4
   35  rm -rd 1 2 3 4
   36  ls
   37  cd ..
   38  mkdir 1 2 3 4 
   39  rm -rd 1 2 3 4
   40  mkdir 1 2 3 4 
   41  rm -d 1 2 3 4
   42  cd first_repo/
   43  ls
   44  git
   45  sudo apt-get install git
   46  git --version
   47  git help
   48  git --help
   49  git help
   50  grep       Print lines matching a pattern
   51  touch test.txt
   52  nano test.txt 
   53  ls -la
   54  nano test.txt 
   55  ls -la
   56  git init
   57  ls -la
   58  git status
   59* 
   60  git status
   61  git commit -m "utworzenie nowego pliku"
   62  git config --global user.email "grzesiu.borowik@gmail"
   63  git config --global user.name "gborowikwspol"
   64  git commit -m "utworzenie nowego pliku"
   65  git status
   66  history
   67  git log
   68  nano test.txt 
   69  git status
   70  git add .
   71  git commit -m "pierwsza zmiana"
   72  git log
   73  nano test.txt 
   74  git status
   75  git add .
   76  git commit -m "druga zmiana"
   77  git log
   78  git remote add origin https://github.com/gborowikwspol/first_repo.git
   79  git push -u origin master
   80  git remote ls
   81  git remote
   82  git remote add origin https://github.com/gborowikwspol/firtst_repo.git
   83  git push -u origin master
   84  git log
   85  git status
   86  git push
   87  nano ~/.gitconfig 
   88  nano test.txt 
   89  git status
   90  git add .
   91  git commit -m "trzecia zmiana"
   92  git push
   93  git config --global push.default simple
   94  git push
   95  history > readme.md
