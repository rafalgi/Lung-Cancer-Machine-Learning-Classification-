Cel projektu
Celem projektu jest zbadanie możliwego związku między poziomem zaawansowania raka u pacjentów a poziomem zanieczyszczenia powietrza, na podstawie danych medycznych i środowiskowych. Analiza obejmuje wykorzystanie różnych technik uczenia maszynowego do przewidywania poziomu zaawansowania raka.

Kroki projektu
Importowanie bibliotek
Na początku projektu importowane są niezbędne biblioteki Python, takie jak Pandas, NumPy, Matplotlib, Seaborn oraz kilka z bibliotek Scikit-learn do przetwarzania danych, wizualizacji i budowy modeli uczenia maszynowego.

Wczytywanie i wstępna analiza danych
Dane są wczytywane z pliku CSV. Przeprowadzana jest wstępna analiza, która obejmuje wyświetlanie pierwszych kilku wierszy danych, generowanie statystyk opisowych oraz sprawdzanie informacji o kolumnach i typach danych.

Czyszczenie danych
Dane są czyszczone poprzez usuwanie duplikatów i sprawdzanie brakujących wartości. Dzięki temu można uniknąć błędów w dalszej analizie.

Kodowanie zmiennej docelowej
Zmienna docelowa, czyli poziom zaawansowania raka (Level), jest kodowana na wartości numeryczne, aby można było ją użyć w modelach uczenia maszynowego. Usuwane są również niepotrzebne kolumny, takie jak index i Patient Id.

Wizualizacja danych
Dane są wizualizowane w celu lepszego zrozumienia rozkładu zmiennych oraz korelacji między nimi. Używane są wykresy kołowe do przedstawienia rozkładu poziomów raka oraz mapy cieplne do pokazania korelacji między zmiennymi.

Budowa modeli uczenia maszynowego
W projekcie używane są różne modele uczenia maszynowego, takie jak:

K-Nearest Neighbors (KNN)
Random Forest
Naive Bayes
Decision Tree
Modele te są trenowane i testowane na danych, a ich wyniki są porównywane w celu wybrania najlepszego modelu do przewidywania poziomu zaawansowania raka.

Ewaluacja modeli
Modele są oceniane za pomocą różnych metryk, takich jak macierz pomyłek, raport klasyfikacji i dokładność. Metryki te pomagają ocenić skuteczność każdego modelu i wybrać ten, który daje najlepsze wyniki.

Wnioski
Na podstawie wyników analizy można wyciągnąć wnioski dotyczące potencjalnego związku między zanieczyszczeniem powietrza a poziomem zaawansowania raka. Wyniki mogą również wskazać, które modele uczenia maszynowego są najbardziej efektywne w przewidywaniu poziomu zaawansowania raka.

Potencjalne zastosowania
Wyniki tego projektu mogą być wykorzystane do:

Zwiększenia świadomości na temat wpływu zanieczyszczenia powietrza na zdrowie.
Wspierania decydentów w tworzeniu polityk mających na celu redukcję zanieczyszczenia powietrza.
Wsparcia pracowników służby zdrowia w identyfikacji pacjentów o podwyższonym ryzyku zachorowania na zaawansowane stadia raka.
Projekt ten stanowi cenny wkład w badania nad wpływem środowiska na zdrowie i może przyczynić się do poprawy jakości życia pacjentów oraz ochrony środowiska.
