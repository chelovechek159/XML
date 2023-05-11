# XML
___
### 1. Create an external repository called XML
    click create New Repository
    entered Repository name - XML
    choose Public repo, add a Readmy file, create repo.

### 2. Clone XML repository to local machine
    git clone https://......

### 3. Inside local XML create file `new.xml`
    cd XML
    touch new.xml
or    

    cat > new.xml
    "control + c"
### 4. Add file uder git
    git add new.xml
### 5. Commit a file
    git commit -m "newXML"

### 6. Push file to external GitHub repository
    git push
### 7. Edit the contents of the `new.xml` file - write information about yourself (name, age, number of pets, future desired salary). Everything is written in XML format
    cat >> new.xml
or

    add information in XML format

### 8. Push changes to an external repository
    git add new.xml
    git commit -m "text"
    git push
>[result](https://github.com/chelovechek159/XML/blob/main/new.xml)
### 9. Create file `preferences.xml`
    cat > prefernces.xml

### 10. Add information about your preferences (Favorite movie, favorite series, favorite food, favorite season, country you would like to visit) to the `preferences.xml` file in XML format.
    vim preferences.xml
    add information in XML format
>[result](https://github.com/chelovechek159/XML/blob/main/preferences.xml)

### 11. Create a file `skills.xml` add information about the skills that will be studied in the course in XML format
    cat > skills.xml
    add information in XML format
>[result](https://github.com/chelovechek159/XML/blob/main/skills.xml)
### 12. Make commit in one line
    git commit -am "text"
or

    git add . && git commit -m "allNewChanges"

### 13. Send 2 files at once to an external repository
    git push
or u can join 12 and 13 
    git commit -am "text" && git push
    git add . && git commit -m "text" && git push

### 14. On the web interface, create a file `bug_report.xml`
    add file 
    create new file

### 15. Make Commit changes (save) changes on the web interface
    add changes
    click on the button [Commit changes]

### 16. Modify the `bug_report.xml` file on the web interface to add a bug report in XML format
    edit file
    write bug report in XML format
### 17. Make Commit changes (save) changes on the web interface
    click on the button [Commit changes]
>[result](https://github.com/chelovechek159/XML/blob/main/bug_report.xml)
### 18. Synchronize external and local XML repository
    git pull
