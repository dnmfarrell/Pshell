# Pshell

An experimental shell that forks, execs, pipes and redirects.

    $ ./pshell
    🐫 ls -lh / | grep Feb
    drwxr-xr-x.  14 root root 4.0K Feb 17 23:17 usr

Original code from Mark Dominus' wonderful [slides](http://perl.plover.com/classes/commands-perl/).

## To Do

I might add these features if I get around to them:

* Init phase to bootstrap env
* Readline & command history
* Support sequential commands with `;`
* Quoting/string support

## License

See LICENSE

## Author

&copy; 2016 David Farrell

## See also

* [psh](https://github.com/gnp/psh) is another Perl shell
* [Creating a pipe](https://www.gnu.org/software/libc/manual//html_node/Creating-a-Pipe.html) from the GNU C documentation
