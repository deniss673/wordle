# wordle


	

	Echipa este alcatuita din:
	
		-Mitu Iustin Aurelian, 151
		-Mohonea Iulian Marius, 151
		-Bogos Andrei, 151
		-Raducan Denis Iulian, 151

	
	Descrierea proiectului:

		Pentru rularea algoritmului scris, va rugam sa rulati fisierul main.py .
		Algoritmul are un delay de 5 secunde pentru fiecare cuvant introdus automat.
		Aceste 5 secunde au fost alese pentru a ne asigura ca nu exista bugg-uri in ceea ce consta timpul de executie a functiei calcul_entropie.
		Initial, fisierul "fisier.txt" contine cuvantul "CARTI", cuvantul pe care l-am obtinut noi ca fiind cel mai bun cuvant de inceput.
		Conectarea celor 2 fisiere de tip .py a fost facuta prin intermediul unui fisier text , folosind multithreading.
		
		Despre interfata grafica:
			
			-Aceasta a fost realizata de Iustin si Denis
			-Am folosit tkinter 
			-In afara de functia move() , cam tot din fisierul main.py tine de GUI
			-Functia move() este practic functia care simuleaza jocul 

		Despre algoritmul de calculare a entropiei:
	
			-Aceasta a fost realizat de Iulian si Andrei
			-Resursele principale au fost link-urile gasite pe slide-urile proiectului
			-Functia citeste din "fisier.txt" cuvantul incercat dar si un string format din 5 cifre.
			numarul 1 <=> gri
			numarul 2 <=> galben
			numarul 3 <=> verde
			-Apoi, elimina toate cuvintele care nu se potrivesc, si afiseaza in acelasi fisier cel mai bun cuvant.


	Numarul mediu de incercari : 4,43

		-Acest numar a fost obtinut in urma rularii de aproximativ 100 de ori a algoritmului alegandu-se cuvinte random.
		-Numarul de incercari pentru fiecare rulare a fost salvat intr-un fisier text
		-Iar apoi a fost scris un cod scurt care a calculat media incercarilor
	
	
	Referinte:
	
		-https://tkdocs.com/tutorial/widgets.html#entry
		-https://www.youtube.com/watch?v=v68zYyaEmEA&ab_channel=3Blue1Brown
		-https://towardsdatascience.com/multithreading-multiprocessing-python-180d0975ab29
		-https://www.youtube.com/watch?v=jnrCpA1xJPQ&ab_channel=Codemy.com
		-https://www.tutorialspoint.com/python/tk_entry.htm
		-https://stackoverflow.com/questions/45237883/tkinter-check-which-entry-last-had-focus
		-https://www.youtube.com/watch?v=YXPyB4XeYLA&t=3571s&ab_channel=freeCodeCamp.org
		-https://www.youtube.com/watch?v=KV3SPTt1WWs&ab_channel=plus2net
		-https://anzeljg.github.io/rin2/book2/2405/docs/tkinter/entry.html
		
