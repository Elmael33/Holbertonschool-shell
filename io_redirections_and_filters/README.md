Shell Redirection

0 #!/bin/bash
echo Hello, World

1 #!/bin/bash
echo -e '"(Ôo)'\'

 2#!/bin/bash
cat /etc/passwd

3 #!/bin/bash
cat /etc/passwd  /etc/hosts

4 #!/bin/bash
cat /etc/passwd | tail

5 #!/bin/bash
cat /etc/passwd | head

6 #!/bin/bash
cat ./iacta | tail --lines=+3 | head -1

7 #!/bin/bash
echo "Best School" > "\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)"

8 #!/bin/bash
ls -la > ls_cwd_content

9 #!/bin/bash
cat ./iacta | tail --lines=1 >> iacta

10 #!/bin/bash
find -name '*.js' -type f -delete

11 #!/bin/bash
find . -type d|tail -n +2|wc -l

12 #!/bin/bash
ls -t |head -n 10

13 #!/bin/bash
sort |uniq -u

14 #!/bin/bash
cat /etc/passwd | grep "root"

15 #!/bin/bash
cat /etc/passwd | grep "bin" -c

16 #!/bin/bash
grep -iA 3 "root" /etc/passwd

17 #!/bin/bash
grep -v "bin" /etc/passwd

18 #!/bin/bash
grep '^[[:alpha:]]' /etc/ssh/sshd_config

19 #!/bin/bash
tr A Z | tr c e

20 #!/bin/bash
tr -d Cc

21 #!/bin/bash
rev

22 #!/bin/bash
cat /etc/passwd |sort | cut -d: -f1,6
