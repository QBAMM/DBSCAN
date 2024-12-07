Opis Projektu:
Projekt implementuje algorytm DBSCAN (Density-Based Spatial Clustering of Applications with Noise) w celu grupowania obrazów z zestawu danych MNIST. MNIST to popularny zbiór danych zawierający cyfry odręcznie pisane, wykorzystywany w zadaniach klasyfikacji w uczeniu maszynowym. W tym projekcie wykorzystano algorytm grupowania (clustering), aby odkryć wzorce w danych bez użycia etykiet.

Wyniki grupowania są wizualizowane za pomocą PCA (Analizy Składowych Głównych), która redukuje dane do dwóch wymiarów (DBSCAN clustering). Program pokazuje również przykłady obrazów należących do poszczególnych klastrów (obrazy cluster1.png, cluster2.png, cluster3.png, cluster4.png).

Funkcje:
Implementacja  algorytmu DBSCAN, w tym funkcje do wyszukiwania sąsiadów i rozszerzania klastrów.
Standaryzacja danych oraz filtracja kolumn o zerowej wariancji.
Wizualizacja wyników grupowania w 2D za pomocą PCA.
Wyświetlanie liczby klastrów (console view.png) i przykładów obrazów w każdym klastrze.
