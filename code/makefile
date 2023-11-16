file=code.c
include makeconfig

build2: compile
	@$(CC) $(file) -o runprogram
compile:
	@$(CC) $(file) 
display :
	@echo $(PATH)


all: display
	gcc $(file) -o code
build: 
	gcc $(file) -o test.o

.PHONY:clean
#clean:
#rm  -rf *.o runprogram 

define adnan
	@echo "Hello adnan how are you ?"
endef	

function:
	@echo "$(sort too bar lip lose)"


LIST = one two three
for:
	@for i in $(LIST); do \
	echo $$i; \
	done

ifcondition: 
ifeq '$(file)' 'code.c'
	echo "true"
endif

clean:
	@if [ -e $(PATH_TO_OBJECT) ] ; \
	then \
		echo "the file exist" ;\
		rm -rf *.o ; \
		rm runprogram ; \
	fi;
info1:
	@echo "test version 1.1"
info2:
	@echo "using $(CC)"

help: info1 info2
	@echo "this is the $@"
	@echo "first prerequisite $<"
	@echo "all prerequisites $^"
	