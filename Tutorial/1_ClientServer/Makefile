PMC = coyote test

main:
	pc -proj:./ClientServer.pproj
.PHONY: main

test:
	$(PMC) ./POutput/netcoreapp3.1/ClientServer.dll -m PImplementation.tcSingleClient.Execute -i 1000
	$(PMC) ./POutput/netcoreapp3.1/ClientServer.dll -m PImplementation.tcMultipleClients.Execute -i 1000
	$(PMC) ./POutput/netcoreapp3.1/ClientServer.dll -m PImplementation.tcSingleClientAbstractServer.Execute -i 1000
.PHONY: test
