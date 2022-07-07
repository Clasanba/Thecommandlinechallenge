1.	Get inside the thecmdchallenge/ directory.

    cd thecmdchallenge/ 

    ls 


2.	Print current directory path.

    pwd

3.	List all the files from the current directory including the hidden ones.

    ls  -a


4.	Now list all the files inside the project, recursively (all files in the hierarchy).

    ls -r


5.	Clear all the clutter from the command line.

    clear


6.	Go to the last level below the small-name folder and show on the console the content of the trophy.txt file.

    cd small-name

    ls

    cd bigger-name-than-before

    ls

    cd omg-this-folder-has-a-huuuuuuge-name-and-i-tired-to-type

    ls

    cd this-is-probably-the-longest-folder-name-you-have-ever-seen-but-believe--im-sure-there-are-other-folder-bigger-than-this-one-because-people-sometimes-like-to-assign-huge-names-to-their-personal-stuff-supercalifragilisticexpialidocious

    less trophy.text


7.	Move one level up and get to the funcode directory and list all files with the javascript typical extension.

    cd funcode

    find *.js


8.	Create a new directory inside funcode/the-most-funny/ called “not-that-funny“.

    pwd

    cd the-most-funny/

    mkdir not-that-funny

    pwd


9.	Create a copy of the-mostboring-text.txt (you can find it within /boringfolder/‘s children) and name it lol.txt.

    cd boringfolder

    ls

    cp the-mostboring-text.txt lol.txt


10.	Move funcode/kids.jpg inside funcode/images/hello/.

    cd funcode

    mv kids.jpg images/hello/


11.	Remove the “small-name“ directory.

    rm -Rf small-name


12.	Print in the command line the content of the-ultimate-joke.txt.

    cd funcode

    cd the-most-funny

    cd lol

    less the-ultimate-joke.txt


13.	Remove all the contents from the boringfolder, they are extremely boring…

    rm -Rf boringfolder/


14.	Open the file kamehameha/dragon-ball-jokes.md using the VI command line text editor

    vi kamehameha/dragon-ball-jokes.md


15.	Update the file kamehameha/dragon-ball-jokes.md by removing the first joke you read on the file, finally save and close the text editor.

    Seleccionar lo que se quiere borrar y escribir  el comando dd
    
    Para guardar y cerrar :wq.

