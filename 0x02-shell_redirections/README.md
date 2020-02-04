<<<<<<< HEAD
0. Hello World---> echo -e Hello, World
1. Confused smiley---> echo -e "\"(0o)'"
2. Lets display a file---> cat /etc/passwd
3. What about 2?---> cat /etc/passwd /etc/hosts
4. Last lines of a file---> tail -n 10 /etc/passwd
5. Id prefer the first ones actually---> head -n 10 /etc/passwd
6. Line #2---> head -n  iacta | tail n-1
7. Its a good file that cuts iron without making a noise--->echo "Holberton School" > '\*\\'\''"Holberton School"\'\''\\*$\?\*\*\*\*\*:)'
8. Save current state of directory---> ls -la ls_cwd_content
9. Duplicate last line---> tail -n 1 iacta >> iacta
10. find . -type f -name '*.js' -delete
11. Dont just count tour directories, make your directories count---> find . type d -mindepth 1 | wc -1
12. Whats new---> ls -Ut head -n 10
13. Being unique is better than being perfect--->sort | uniq -u
14. It must be in that file---> grep "root" /etc/passwd
15. Count that word---> grep -c "bin" /etc/passwd
16. Whats next---> grep -A 3 "root" /etc/passwd
17. I hate bin---> grep -v "bin" /etc/passwd
18. Letters only please---> grep ^[[:alpha:]] /etc/ssh/sshd_config
19. A to Z---> tr 'Ac' 'Ze'
20. Without C, you would live in hiago--->tr -d cC
21. esreveR---> rev
22. DJ Cut Killer---> cut -f 1,6 -d ':' /etc/passwd | sort
23. Empty casks make the moise noise---> find . -empty | rev | cut --delimiter='/' -f1 | rev
24. A gif is worth ten thousand words---> find . -name "*.gif" -type f | rev | cut -d "." --complement  -f 1 | cut -d "/" -f 1 | rev | LC_ALL=C  sort -f
25. Acrostic---> cut -c1 | tr -d '\n' | sort 
16. The biggest fan---> tail -n+2 | cut -f1 | sort | uniq -c | sort -nr | rev | cut --delimiter=' ' -f1 | rev | head --lines=11
=======
0-hello_world: a script that prints Hello, World
1-confused_smiley: a script that displays a confused smiley "(Ôo)'
2-hellofile: a script that displays the content of the file /etc/passwd
3-twofiles: a script that displays the contents of the files /etc/passwd and /etc/hosts
4-lastlines: a script that displays the last 10 lines of the file /etc/passwd
5-firstlines: a script that displays the first 10 lines of the file /etc/passwd
6-third_line: a script that displays the third line of the file iacta in the working directory
7-file: a script that generates the file *\'"Holberton School"'\*$?*****:) containing the text 'Holberton School' followed by a new line
8-cwd_state: a script that writes the result of the cmd ls-la to the file ls_cwd_content
9-duplicate_last_line: a script that duplicates the last line of the file iacta in the file iacta
10-no_more_js: a script that deletes all non-directory files ending in .js in the current directory and its subdirectories
11-a script that displays the number of directories and subdirectories in the current directory
12-newest_files: a script that displays the 10 newest files in the current directory, from newest to oldest
13-unique: a script that takes a list of words as input and prints only words that appear exactly once
14-findthatword: a script that displays lines containing the pattern root from the file /etc/passwd
15-countthatword: a script that displays the number of lines that contain the pattern "bin" in the file /etc/passwd
16-whatsnext: a script that displays lines containing the pattern "root" and 3 lines after them in the file /etc/passwd
17-hidethisword: a script that displays all the lines in the file /etc/passwd that do not contain the pattern "bin"
18-letteronly: a script that displays all lines of the file /etc/ssh/sshd_config starting with a letter
19-AZ: a script that replaces all characters A and c from input to Z and e respectively
20-hiago: a script that removes all letters c and C from input
21-reverse: a script that reverses its input
22-users_and_homes: a script that displays all users and their home directories, sorted by users.
>>>>>>> 31fc191cbafa7bd899eaa7921276dfa38f15953a
