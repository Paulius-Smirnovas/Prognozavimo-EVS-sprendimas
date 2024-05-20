
# Duomenų rinkimas ir parengimas:

Importuotos bibliotekos: Kodas pradedamas importuojant reikalingas bibliotekas, tokias kaip pandas, numpy, matplotlib, seaborn, plotly, statsmodels, scikit-learn ir mlxtend.
Kaggle sąranka: Nustatomi „Kaggle“ API įgaliojimai, kad būtų galima atsisiųsti duomenų rinkinius.
Atsisiųsti duomenų rinkinį: Kodas iš „Kaggle“ parsisiunčia duomenų rinkinį pavadinimu „ecommerce-data“.
Duomenų išgavimas: Atsisiųstas duomenų rinkinys ištraukiamas iš zip failo.
Duomenų įkėlimas: Duomenys įkeliami į pandas DataFrame pavadinimu „data“.
Duomenų valymas: Atliekamos įvairios duomenų valymo operacijos, pavyzdžiui, trūkstamų reikšmių tvarkymas, duomenų tipų konvertavimas, dublikatų šalinimas ir įrašų su neįprastais atsargų kodais filtravimas.


# Tiriamoji duomenų analizė (EDA):
Apibendrinamoji statistika: Apskaičiuojama skaitmeninių ir kategorinių kintamųjų apibendrinamoji statistika, kad būtų galima suprasti duomenų pasiskirstymą ir centrines tendencijas.
Vizualizavimas: Siekiant vizualizuoti duomenų pasiskirstymą, tendencijas ir dėsningumus, kuriami įvairūs grafikai, pavyzdžiui, dėžutės grafikai, sklaidos grafikai, laiko eilučių grafikai ir išskaidymo grafikai.
Funkcijų inžinerija: Remiantis esamais duomenimis sukuriamos naujos funkcijos, pavyzdžiui, „is_Cancelled“ ir „len_StockCode“, skirtos tolesnei analizei.

# Modelio kūrimas:
Pirminis duomenų apdorojimas: Duomenys iš anksto apdorojami standartizuojant skaitinius požymius ir vienkartiniu būdu koduojant kategorinius požymius.
Modelio atranka: Mokymui pasirenkami trys skirtingi modeliai: Pasirenkami šie modeliai: logistinė regresija, atsitiktinis miškas ir neuroninis tinklas.
Modelio mokymas: Kiekvienas pasirinktas modelis mokomas naudojant iš anksto apdorotus duomenis.
Modelio vertinimas: Tikslumas, F1 rezultatas ir ROC AUC apskaičiuojami naudojant kryžminį tikrinimą, kad būtų galima įvertinti modelio našumą.

# Modelio vertinimas ir optimizavimas:
Hiperparametrų derinimas: Siekiant rasti geriausius Random Forest modelio hiperparametrus, atliekama tinklelio paieška.
Geriausio modelio vertinimas: Naudojant optimizuotus hiperparametrus įvertinamas geriausiai veikiantis modelis (Random Forest).
Ateities prognozavimas: Nustatoma funkcija „predict_future“, skirta ateities atšaukimų prognozėms atlikti naudojant geriausią modelį.

# Rezultatai ir papildomos užduotys:
Išvesties rezultatai: Spausdinami modelio vertinimo ir ateities prognozių rezultatai.
Apskritai šis kodas demonstruoja išsamų požiūrį į realios e. prekybos srities problemos sprendimą, pradedant duomenų rinkimu ir parengimu, baigiant modelio kūrimu, vertinimu ir ateities prognozavimu. Jame demonstruojama geriausia duomenų mokslo praktika, įskaitant duomenų valymą, žvalgomąją duomenų analizę, požymių inžineriją, modelio parinkimą, vertinimą ir optimizavimą.
