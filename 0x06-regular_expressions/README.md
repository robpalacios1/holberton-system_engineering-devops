# :gear:0x06. Regular expression :gear:
 
## Background Context
For this project, you have to build your regular expression using Oniguruma, a regular expression library that which is used by Ruby by default. Note that other regular expression libraries sometimes have different properties.

Because the focus of this exercise is to play with regular expressions (regex), here is the Ruby code that you should use, just replace the regexp part, meaning the code in between the //:

~~~
Roberto@ubuntu$ cat example.rb
#!/usr/bin/env ruby
puts ARGV[0].scan(/127.0.0.[0-9]/).join
Roberto@ubuntu$
Roberto@ubuntu$ ./example.rb 127.0.0.2
127.0.0.2
Roberto@ubuntu$ ./example.rb 127.0.0.1
127.0.0.1
Roberto@ubuntu$ ./example.rb 127.0.0.a
~~~

## Resources
**Read or watch:**

- Regular expressions - basics
- Regular expressions - advanced
- Rubular is your best friend
- Use a regular expression against a problem: now you have 2 problems
- Learn Regular Expressions with simple, interactive exercises

## Requirements :triangular_ruler:

### General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 14.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- The first line of all your Bash scripts should be exactly #!/usr/bin/env ruby
- All your regex must be built for the Oniguruma library

## Author :book:
Roberto Palacios [Twitter](https://twitter.com/robpalacios11) | [GitHub](https://github.com/robpalacios1)
