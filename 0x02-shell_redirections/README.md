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
