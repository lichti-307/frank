### Intro

While it’s possible to install this go package using the common way it likely won’t work: The configuration is hard coded as constants, so you most likely simply want to check out the repository, modify and run `go install` to get your binary of choice.

### Installation

```
apt-get install liburi-find-perl
go get github.com/breunigs/frank
echo "Modify away!"
```


### Attribution

The project is ISC-licensed, but all other software used remains under their respective license.

- Go, see http://golang.org/LICENSE
- `goirc` © Alex Bramley; same license as Go
- The `urifind` executable is a modified version from `liburi-find-perl`. It uses `URI::Find::Schemeless` instead of `URI::Find` but has no further changes. © 2003 Darren Chamberlain; same license as Perl