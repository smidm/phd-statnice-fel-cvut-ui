# 1. Množiny. Teorie matic. Soustavy lineárních rovnic.

## Teorie množin

- Demlová M., Diskrétní matematika a grafy, http://math.feld.cvut.cz/demlova/teaching/dmg/dohromady1516.pdf

## Algebra

- determinant
- Invertibilni matice, singularni matice
- Linearni zobrazeni, eigenvalues
- hodnost

    

## Soustavy lineárních rovnic

- Gaussova eliminace


# 2. Základy matematické analýzy. Metody aproximace funkcí. Metoda nejmenších čtverců. Aplikace pro hledání modelů z naměřených reálných dat.

- metrický prostor
- limity, posloupnosti, řady
- kalkulus
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

# 3. Statická optimalizace. Lineární programování. Gradientní metody. Problém uváznutí v lokálním extrému.

Werner T., Optimalizace, <https://cw.fel.cvut.cz/wiki/_media/courses/a4b33opt/opt.pdf>

- Lagrangeho multiplikatory
- LP basics
- ILP
- Gradient descent
- Newton
- Gauss-Newton
- Levenberg-Marquart

	Powell
	Boltzmann?

# 4. Základní pojmy statistiky, zásady provádění pokusů a ověřování hypotéz, metoda maximální věrohodnosti.

- literatura
    - Navara, Mirko, Pravděpodobnost a matematická statistika.
    - definice pravděpodobnosti http://www.colorado.edu/economics/morey/6818/3defprob.pdf
    - Blitzstein Joe, Chen William. Probability Cheatsheet. http://www.wzchen.com/probability-cheatsheet
    - Prince, Simon. Computer Vision - Models, Learning, Inference.

- kombinatorika
- Lagrangeova (klasická) definice https://en.wikipedia.org/wiki/Classical_definition_of_probability
- Kolmogorova definice https://en.wikipedia.org/wiki/Probability_axioms
- nezávislost a podmíněná pravděpodobnost
    - bayesův vzorec
- náhodné veličiny
    - charakteristiky
    - základní typy
        - Bernoulli, binomial distribution
        - Normal distribution, quantiles      
    - zákon vekých čísel
    - centrální limitní věta
- metoda maximální věrohodnosti
- metoda maximální aposteriorní pravděpodobnosti
- testování hypotéz
    - Null hypothesis
    - chi² distribution

# 5. Grafy. Kombinatorické algoritmy a jejich složitost. Asymptotické míry výpočetní složitosti, třídy P a NP.

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

# 6. Lineární integrální transformace, zejména Fourierova. FFT. Nelineární filtrace.

- fourierova transformace https://en.wikipedia.org/wiki/Fourier_transform https://math.stackexchange.com/a/72479
- FFT http://jakevdp.github.io/blog/2013/08/28/understanding-the-fft/
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

# 7. Teorie informace, míry informace, entropie, střední vzájemná informace, princip maxima entropie.

## Sources

- Gray, Robert M., Entropy and Information Theory.
- https://en.wikipedia.org/wiki/Information_theory
- https://en.wikipedia.org/wiki/Coding_theory


- Entropie
- Diferencialni entropie
- Joint entropy
- conditional entropy
- mutual information (set analogy, Bayes analogy)
- Kullback-leibler divergence (gain) https://en.wikipedia.org/wiki/Kullback%E2%80%93Leibler_divergence
- https://en.wikipedia.org/wiki/Principle_of_maximum_entropy
- Coding theory, noisy channel coding (Shannon theorem)

# 8. Matematický model zavedený na objektu. Problém identifikace struktury a parametrů modelu.

	? ? ? (pry nekde v Maricich)
- dynamický model, statistický model, differenciální rovnice, modely teorie her
- experimenty na objektu: přechodová, impulsní, frekvenční charakteristika
- white box, grey box, black box 
- identifikace: Horáček, Petr. Systémy a modely.

# 9. Výroková logika. Predikátová logika prvního řádu. Formální systém, teorie a jejich korektnost a úplnost. Metody dokazování vět. Rezoluční princip. Meze dokazatelnosti.

	Definice: term, literal, vyrok, řád, teorie, model, korektnost/uplnost
	Odvozovaci schemata
	Dokazovani:
		Forward/backward chaining
		Rezolucni metoda (https://en.wikipedia.org/wiki/Resolution_(logic))
		Unifikace
		(grounding, lifting, rete)
	Godelovy vety

# 10. Řešení úloh. Stavový prostor úlohy a metody jeho prohledávání.
   
- stavový prostor
- prohledávání do hloubky https://en.wikipedia.org/wiki/Depth-first_search
- prohledávání do šířky https://en.wikipedia.org/wiki/Breadth-first_search
- A* https://en.wikipedia.org/wiki/A*_search_algorithm
- metoda větví a mezí https://en.wikipedia.org/wiki/Branch_and_bound
- Alfa-beta ořezávání https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning

# 11. Formulace úlohy statistického rozhodování, rozpoznávání. Bayesovské rozhodování jako minimalizace střední ztráty. Nebayesovské úlohy.

- RPZ přednášky https://cw.fel.cvut.cz/wiki/courses/a4b33rpz/lectures
- bayesovské rozhování
- neyman pearson
- minimax

# 12. Definice problému učení. Indukce, dedukce a abdukce. Učení (trénování) a odhady parametrů. Odlišnosti učení s učitelem a bez učitele. Základní metody. Trénovací a testovací množina a jejich rozsah.

	Slajdy z Hlavace
	??? odhady parametru?
	Indukce, dedukce, abdukce
	Precision, recall, ROC
	Cross-validation

# 13. Znalosti, jejich reprezentace a použití v úlohách umělé inteligence.

- literatura:
    - Mařík V. et al., Umělá inteligence 1
        - kap. Řešení úloh a využívání znalostí
        - kap. Reprezentace znalostí
        - kap. Plánování
    - https://en.wikipedia.org/wiki/Knowledge_representation_and_reasoning

- sémantika predikátové logiky
- sémantické sítě https://en.wikipedia.org/wiki/Semantic_network
- ontologie https://en.wikipedia.org/wiki/Ontology_(information_science)
- rámce https://en.wikipedia.org/wiki/Frame_(artificial_intelligence)
- semantic web https://en.wikipedia.org/wiki/Semantic_Web

- ?? Vyrokova logika
- ?? plánování
    - Block world
    - SHRDLU
	- Planovaci operatory
	- STRIPS

# 14. Znalostní systémy a jejich praktické aplikace.

- Mařík V. et al., Umělá inteligence 2
- https://en.wikipedia.org/wiki/Expert_system

- ?? ontologie, data a inferencni pravidla

# 15. Základní cíle umělé inteligence a přístupy k jejich dosažení: manipulace se symboly, konekcionismus, distribuované systémy.

- https://en.wikipedia.org/wiki/Artificial_intelligence
- Mařík V. et al., Umělá inteligence 3, kap. Přirozené a umělé myšlení jako filozofický problém
- Mařík V. et al., Umělá inteligence 2, kap. Distribuované systémy

---

# 16. Teorie statistického učení podle Vapnika a Červoněnkise.

- literatura:
    - Hlaváč V. Vapnik-Chervonenkis learning theory. http://people.ciirc.cvut.cz/~hlavac/TeachPresEn/31PattRecog/27VapnikChervonenkis.pdf
    - https://en.wikipedia.org/wiki/Vapnik%E2%80%93Chervonenkis_theory
    - Schlesinger M., Hlaváč V., Deset přednášek z teorie statistického a strukturního rozpoznávání, kap. 4.3.

- VC dimenze

# 17. Statistické učení bez učitele. EM algoritmus.

- Matas J., Rozpoznávání. https://cw.fel.cvut.cz/wiki/courses/a4b33rpz/lectures
- Flach B., Statistical Machine Learning. https://cw.fel.cvut.cz/wiki/courses/be4m33ssu/lectures

# 18. Lineární diskriminační funkce. Perceptron. SVM (Support Vector Machine). Mnohovrstvý perceptron a jeho učení metodou zpětného šíření.

- Matas J., Rozpoznávání.
- Flach B., Statistical Machine Learning.
- hluboké sítě 
    - https://cw.fel.cvut.cz/wiki/_media/courses/ae4m33mpv/deep_learning_mpv.pdf
    - https://cw.fel.cvut.cz/wiki/_media/courses/be4m33ssu/anns_l07.pdf

# 19. Syntaktické rozpoznávání. Úlohy hledající přesnou a nepřesnou shodu. Rozpoznávání markovských řetězců.

- Flach B., Graphical Markov Models. https://cw.fel.cvut.cz/wiki/courses/xep33gmm/materials/lectures

# 20. Obecné úlohy počítačového vidění. Měření tvaru, navigace, sledování, stíhání, rozpoznávání.

- cíle
- úlohy
- Marrova teorie vidění
- ...

# 21. Formování obrazu. Struktura obrazu. Vztah mezi vlastnostmi povrchu a jasovou funkcí.

- Szeliski R., Computer Vision: Algorithms and Applications. http://szeliski.org/Book/
- geometrie kamery
- digitální gamera
- radiometrie, fotometrie
    - zář, radiance https://en.wikipedia.org/wiki/Radiance
    - 

# 22. Projektivní a afinní geometrie.

- Pajdla T., Elements of Geometry for Computer Vision. http://cmp.felk.cvut.cz/~pajdla/gvg/GVG-2017-Lecture.pdf
- Šára R., Matoušek M., 3D computer Vision, kap. Perspective camera, Computing with single camera http://cmp.felk.cvut.cz/cmp/courses/TDV/2016W/lectures/tdv-2016-all-annotated.pdf
- afinní prostor
    - vs euklidovský prostor
    - vs vektorový prostor
    - vs lineární prostor
- projektivní rovina
- homogenní reprezentace
- incidence
- vektorový součin https://en.wikipedia.org/wiki/Cross_product
- homografie
- dvojpoměr

# 23. Geometrie více kamer.

- Šára R., Matoušek M., 3D computer Vision.

# 24. Analýza pohybu. Problém korespondence.

- literatura:
    - Matas J., Metody počítačového vidění. https://cw.fel.cvut.cz/wiki/courses/ae4m33mpv/start
- korelace
- lokální příznaky
    - Harris
    - Harris - Laplace
    - měřítko
        - DoG https://en.wikipedia.org/wiki/Difference_of_Gaussians
        - LoG http://homepages.inf.ed.ac.uk/rbf/HIPR2/log.htm
    - SIFT
    - MSER
- deskriptory
    - SIFT
    - SURF
    - HOG
    - LBP
- RANSAC
- sledování objektů
    - KLT
    - mean shift
- filtrování
    - Kalman
    - particle filter
- optický tok https://en.wikipedia.org/wiki/Optical_flow
    - LK https://en.wikipedia.org/wiki/Lucas%E2%80%93Kanade_method
    - Horn-Schunck https://en.wikipedia.org/wiki/Horn%E2%80%93Schunck_method


# 25. Tvar z X. Stereovidění. Fotometrické stereo. Tvar ze stínování.

- Šára R., Matoušek M., 3D computer Vision.
- tvar ze stínování (jeden snímek, jeden zdroj světla)
- fotometrické stereo (více zdrojů světla), Šára
- stereovidění, Šára
- structure from motion
- brdf - obousměrná distribuční funkce odrazu světla
- lambertovský povrch
- na okraj: shape from texture, shape from focus, active rangefinding
    
tématické okruhy: http://www.fel.cvut.cz/cz/education/phd/tem_okruhy/TO13133.html

založeno na: https://gist.github.com/pasky/4d2a4467cc5435dc1cf4
