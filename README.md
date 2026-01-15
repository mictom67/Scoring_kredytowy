# analizadanych

Projekt z przedmiotu: Analiza danych w R

Uczelnia: Politechnika Gdańska

Kierunek: Analityka gospodarcza - 2 stopnia, 1 semestr

Autorzy: Agata Downar, Michał Tomaszewicz, Paweł Tomaszewski, Kacper Żmudowski

Dane: Zestaw danych do klasyfikacji zatwierdzania pożyczek

Syntetyczne dane do klasyfikacji binarnej zatwierdzenia pożyczki

Zbiór danych zawiera 45 000 rekordów i 14 zmiennych, z których każda została opisana poniżej:

Column, Description, Type

person_age, Age of the person, Float

person_gender, Gender of the person, Categorical

person_education, Highest education level, Categorical

person_income, Annual income, Float

person_emp_exp, Years of employment experience, Integer

person_home_ownership, Home ownership status (e.g., rent, own, mortgage), Categorical

loan_amnt, Loan amount requested, Float

loan_intent, Purpose of the loan, Categorical

loan_int_rate, Loan interest rate, Float

loan_percent_income, Loan amount as a percentage of annual income, Float

cb_person_cred_hist_length, Length of credit history in years, Float

credit_score, Credit score of the person, Integer

previous_loan_defaults_on_file, Indicator of previous loan defaults, Categorical

loan_status, (target variable) Loan approval status: 1 = approved; 0 = rejected, Integer

Zbiór danych może być wykorzystywany do wielu celów:

Eksploracyjna analiza danych (EDA): Analiza kluczowych cech, wzorców dystrybucji i relacji w celu zrozumienia czynników ryzyka kredytowego.

Klasyfikacja: Tworzenie modeli predykcyjnych w celu sklasyfikowania zmiennej loan_status (zatwierdzony/niezatwierdzony) dla potencjalnych wnioskodawców.

Regresja: Opracowanie modeli regresji w celu przewidywania zmiennej credit_score w oparciu o atrybuty indywidualne i związane z pożyczką.

Należy pamiętać o kwestii danych z oryginalnych danych, takich jak instancja > 100 lat jako wiek.

Ten zestaw danych stanowi bogatą podstawę do zrozumienia czynników ryzyka finansowego i symulacji procesów modelowania predykcyjnego w celu zatwierdzenia pożyczki i oceny zdolności kredytowej

