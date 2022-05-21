

build: auditor.o vmcs.o
	g++ auditor.o vmcs.o -o vmcsAuditor

auditor.o: Auditor.cpp
	g++ -c Auditor.cpp -o auditor.o

vmcs.o: VmcsAuditor.cpp
	g++ -c VmcsAuditor.cpp -o vmcs.o

run:
	./vmcsAuditor

clean:
	rm -rf auditor.o vmcs.o vmcsAuditor
