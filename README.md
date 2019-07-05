## Modo de execução serial: <br>
`g++ apriori_sequencial.cpp -o apriori_sequencial.o` <br>
`./apriori_serial.o 2 input.txt output_serial.txt` <br> <br>

## Modo de execução paralelo: <br>
`g++ -fopenmp apriori_paralelo.cpp -o apriori_paralelo.o` <br>
`./apriori_paralelo.o 2 input.txt output_paralelo.txt`
