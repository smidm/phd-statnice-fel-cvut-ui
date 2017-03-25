# Množiny. Teorie matic. Soustavy lineárních rovnic.

## Teorie množin

- Demlová M., Diskrétní matematika a grafy, http://math.feld.cvut.cz/demlova/teaching/dmg/dohromady1516.pdf

	Gaussova eliminace
	determinant
	Invertibilni matice, singularni matice
	Linearni zobrazeni, eigenvalues

# Základy matematické analýzy. Metody aproximace funkcí. Metoda nejmenších čtverců. Aplikace pro hledání modelů z naměřených reálných dat.

- metrický prostor
- limity, posloupnosti, řady
- kalkulus
- Lagrangeho multiplikatory
- taylorův teorém
- Newtonova metoda
- Linearni regrese

## Metody aproximace funkcí.

- https://en.wikipedia.org/wiki/Taylor%27s_theorem
- https://en.wikipedia.org/wiki/Fourier_series
- https://en.wikipedia.org/wiki/Interpolation
- https://en.wikipedia.org/wiki/Spline_(mathematics)      
- Navara M., Aproximace funkcí a numerická derivace, <http://cmp.felk.cvut.cz/~navara/nm/aprox_print.pdf>
    
## Metoda nejmenších čtverců.

- https://en.wikipedia.org/wiki/Least_squares
- Navara M., Aproximace funkcí a numerická derivace, <http://cmp.felk.cvut.cz/~navara/nm/aprox_print.pdf>
    
- Least-squares; MSE
- Lasso, elastic net, L1/L2-priors

# Statická optimalizace. Lineární programování. Gradientní metody. Problém uváznutí v lokálním extrému.

Werner T., Optimalizace, <https://cw.fel.cvut.cz/wiki/_media/courses/a4b33opt/opt.pdf>

- LP basics
- ILP
- Gradient descent
- Newton
- Gauss-Newton
- Levenberg-Marquart

	Powell
	Boltzmann?

# Základní pojmy statistiky, zásady provádění pokusů a ověřování hypotéz, metoda maximální věrohodnosti.

- Navara, Mirko, Pravděpodobnost a matematická statistika.
- Lagrangeova (klasická) definice https://en.wikipedia.org/wiki/Classical_definition_of_probability
- Kolmogorova definice https://en.wikipedia.org/wiki/Probability_axioms
- definice pravděpodobnosti http://www.colorado.edu/economics/morey/6818/3defprob.pdf


	Probability space
	Bayes rule
	Bernoulli, binomial distribution
	Normal distribution, central limit theorem, quantiles
	Poisson distribution, chi² distribution
	Null hypothesis
	ML, MAP

# Grafy. Kombinatorické algoritmy a jejich složitost. Asymptotické míry výpočetní složitosti, třídy P a NP.

- Dasgupta, Sanjoy, Christos H. Papadimitriou, and Umesh Vazirani. Algorithms. McGraw-Hill, Inc., 2006. https://people.eecs.berkeley.edu/~vazirani/algorithms/toc.pdf
- Černý, Jakub, Základní grafové algoritmy. http://kam.mff.cuni.cz/~kuba/ka/
- Kolář, Josef, Teoretická informatika. http://www.exfort.org/2005l/4/x36tin/pdf/ti.pdf

## Základní pojmy

## Reprezentace

- matice souslednosti
- matice vzdáleností
- laplaceouva matice
- seznam sousedů
- seznam hran
- vis Kolář et al.

## Grafové algoritmy

- Kombinatorická optimalizace, https://cw.fel.cvut.cz/wiki/courses/a4m35ko/start

- Dijkstra
- Bellman-Ford
- minimální kostra (Kruskalův algoritmus, MST)
- A*
- Maximum flow, maximum pairing
- TSP, 3SAT, knapsack
- barvení grafu

## Třídění?

## Složitost

- Formalne P, NP, PSPACE, EXPTIME
- viz Dasgupta et al.
- http://kam.mff.cuni.cz/~kuba/ka/cas_sloz.pdf

# Lineární integrální transformace, zejména Fourierova. FFT. Nelineární filtrace.

- fourierova transformace https://en.wikipedia.org/wiki/Fourier_transform
- FFT https://  en.wikipedia.org/wiki/Fast_Fourier_transform, https://en.wikipedia.org/wiki/Cooley%E2%80%93Tukey_FFT_algorithm
- jen přehled: laplaceova, z transformace
- konvoluce https://en.wikipedia.org/wiki/Convolution
- Impulse response, frequency response https://en.wikipedia.org/wiki/Frequency_response
- Window funkce atd. (DCT, wavelets)

- Kalmanův filter
	
## Nelineární filtrace	

- https://en.wikipedia.org/wiki/Nonlinear_filter
- Phase-locked loop https://en.wikipedia.org/wiki/Phase-locked_loop
- particle filters
- median filter

# Teorie informace, míry informace, entropie, střední vzájemná informace, princip maxima entropie.

	Entropie, diferencialni entropie
	Joint entropy, conditional entropy, and mutual information (set analogy, Bayes analogy)
	Kullback-leibler divergence (gain)
	Coding theory, noisy channel coding (Shannon theorem)
	https://en.wikipedia.org/wiki/Principle_of_maximum_entropy

# Matematický model zavedený na objektu. Problém identifikace struktury a parametrů modelu.

	? ? ? (pry nekde v Maricich)

# Výroková logika. Predikátová logika prvního řádu. Formální systém, teorie a jejich korektnost a úplnost. Metody dokazování vět. Rezoluční princip. Meze dokazatelnosti.

	Definice: term, literal, vyrok, řád, teorie, model, korektnost/uplnost
	Odvozovaci schemata
	Dokazovani:
		Forward/backward chaining
		Rezolucni metoda (https://en.wikipedia.org/wiki/Resolution_(logic))
		Unifikace
		(grounding, lifting, rete)
	Godelovy vety

# Řešení úloh. Stavový prostor úlohy a metody jeho prohledávání.

	BFS, DFS, branch&bound, alpha-beta
	Prohledavani systemu verzi
	???

# Formulace úlohy statistického rozhodování, rozpoznávání. Bayesovské rozhodování jako minimalizace střední ztráty. Nebayesovské úlohy.

	Supervised, unsupervised, semi-supervised
	Slajdy z Hlavace
	Mixture of gaussians https://en.wikipedia.org/wiki/Jensen%27s_inequality

# Definice problému učení. Indukce, dedukce a abdukce. Učení (trénování) a odhady parametrů. Odlišnosti učení s učitelem a bez učitele. Základní metody. Trénovací a testovací množina a jejich rozsah.

	Slajdy z Hlavace
	??? odhady parametru?
	Indukce, dedukce, abdukce
	Precision, recall, ROC
	Cross-validation

# Znalosti, jejich reprezentace a použití v úlohách umělé inteligence.

	???
	Vyrokova logika, ramce
	Block world, SHRDLU
	Planovaci operatory, STRIPS

# Znalostní systémy a jejich praktické aplikace.

	??? (ontologie, data a inferencni pravidla?)

# Základní cíle umělé inteligence a přístupy k jejich dosažení: manipulace se symboly, konekcionismus, distribuované systémy.

---

# Teorie statistického učení podle Vapnika a Červoněnkise.

# Statistické učení bez učitele. EM algoritmus.

# Lineární diskriminační funkce. Perceptron. SVM (Support Vector Machine). Mnohovrstvý perceptron a jeho učení metodou zpětného šíření.

# Syntaktické rozpoznávání. Úlohy hledající přesnou a nepřesnou shodu. Rozpoznávání markovských řetězců.

# Obecné úlohy počítačového vidění. Měření tvaru, navigace, sledování, stíhání, rozpoznávání.

# Formování obrazu. Struktura obrazu. Vztah mezi vlastnostmi povrchu a jasovou funkcí.

# Projektivní a afinní geometrie.

# Geometrie více kamer.

# Analýza pohybu. Problém korespondence.

# Tvar z X. Stereovidění. Fotometrické stereo. Tvar ze stínování.
    
tématické okruhy: http://www.fel.cvut.cz/cz/education/phd/tem_okruhy/TO13133.html

založeno na: https://gist.github.com/pasky/4d2a4467cc5435dc1cf4
