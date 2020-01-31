0. My name is Betty--->su betty
1. Who am I--->Whoami
2. Groups--->groups
3. New owner---> sudo betty hello
4. Empty--> touch hello
5. Executed---> chmod u+x hello
6. multiple permissions--->chmod ug+x,a+r hello
7. Everybody!--->chmod ugo+x hello
8. James Bond--->chmod 007 hello
9. John Doe--->chmod 753 hello
10. Look in the mirror--->chmod --reference=hello olleh
11. Direcrories--->chmod -R ugo+X .
12. More directories--->mkdir -m 751 dir_holberton
13. Change group--->chgrp holberton hello
14. Owner and group--->chown -hR betty:holberton
15. Symbolic links--->chown -h betty:holberton _hello
16. If only--->chown --from=guillaume betty hello 