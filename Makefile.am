	AUTOMAKE_OPTIONS = subdir-objects
	ACLOCAL_AMFLAGS = ${ACLOCAL_FLAGS}

	bin_PROGRAMS = mike
	mike_SOURCES = virtualhuman

all:install
	
install:
	mkdir /math
	mkdir /bash-human
	cp virtualhuman /usr/local/bin
	ln /usr/local/bin/virtualhuman /usr/local/bin/mike
	cp ./init /math/init
	cp ./name /bash-human/name
	cp ./age /bash-human/age	
	cp ./happ /bash-human/happ
	cp ./afend /bash-human/afend
clean:
	rm -rv /math
	rm -rv /bash-human
	rm -rv /usr/local/bin/mike
	rm -rv /usr/local/bin/virtualhuman
doc:
	mkdir /bash-human/doc
	cp changelog /bash-human/doc
cleandoc:
	rm -rv /bash-human/doc
WIPF:
	cp -rv WIP /WIP
WIPFCLEAN:
	rm -rv /WIP
cleanfull:
	rm -rv /math
	rm -rv /bash-human
	rm -rv /WIP
	rm -rv /usr/local/bin/mike
	rm -rv /usr/local/bin/virtualhuman
test:
	
run:
	./mike
