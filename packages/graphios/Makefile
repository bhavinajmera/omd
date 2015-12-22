include ../../Makefile.omd

NAME     = graphios
VERSION  = 2.0
DIR = $(NAME)-$(VERSION)

build:
	if [ -d $(DIR) ]; then rm -rf $(DIR); fi
	tar xzf $(DIR).tar.gz

install:
	mkdir -p $(DESTDIR)$(OMD_ROOT)/lib/python
	cd $(DIR) && \
	    export PYTHONPATH=$$PYTHONPATH:$(DESTDIR)$(OMD_ROOT)/lib/python ; \
	        python setup.py install --home=$(DESTDIR)$(OMD_ROOT) \
		    --prefix='' \
                    --install-platlib=$(DESTDIR)$(OMD_ROOT)/lib/python \
                    --install-purelib=$(DESTDIR)$(OMD_ROOT)/lib/python ; \
                cd .. ; \
            done

skel:

clean:
	rm -rf $(DIR)

