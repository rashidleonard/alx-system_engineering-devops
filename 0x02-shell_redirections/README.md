# echo 'Hello, World' - This script prints Hello, World to the standard output

# echo "\"(Ô0)'" - This script displays the confused smiley

# cat /etc/passwd - Displaying the contect of the file

# cat /etc/passwd /etc/hosts - Displaying the contents of two files

# tail -n 10 /etc/passwd - Displays the last 10 lines of the file /etc/passwd

# head -n 10 /etc/passwd - Dispalys the first 10 lines of the file /etc/passwd

# head -n 3 iacta | tail -n 1 - Displays the 3rd line of the file iacta
 

#"Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\) - script contains the text Best School

# ls -la > ls_cwd_content - overwrites the content of the file

# tail -n 1 iacta >> iacta - makes a duplicate of the last line of the file iacta

# find . -type f -name "*.js" -delete - deletes regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders

# find . -type d -not -name '.' | wc -l - counts the number of directories adn subdirectories

# ls -t1 | head -n 10 - displays the 10 newest files

# sort | uniq -u | list the words as input and prints only words that appear exactly once.
 
# grep -i "root" /etc/passwd - Display lines containing the pattern “root” from the file /etc/passwd

# grep -i "root" -A 3 /etc/passwd - Display lines containing the pattern “root” and 3 lines after them in the file /etc/passwd  

# grep -i -v "bin" /etc/passwd - Displays all the lines of the file

grep -i "^[a-z]" /etc/ssh/sshd_config - Display all lines of the file /etc/ssh/sshd_config starting with a letter.


# tr "A" "Z" | tr "c" "e" - Replaces all characters A and c from input to Z and e respectively.  

# tr -d "cC" - Create a script that removes all letters c and C from input.

# rev - reverses an input

# cut -d ':' -f 1,6 /etc/passwd | sort - displays all users and their home directories, sorted by users.
