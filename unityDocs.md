# Opis podstawowych funkcji w silniku Unity
Spis treści:

- [Przechodzenie do tryby gry](#przechodzenie-do-trybu-gry)

## Przechodzenie do trybu gry
Aby przetestować grę możemy użyć tryby gry "Play Mode" który znajduję się na środku ekranu na samej górze 
![](/img/playMode.png)

Tryb gry pozwala na przetestowanie aktualnego stanu gry

## Zarządzanie projektem
Wszystkie obiekty jakie zostały dodane do gry znajdują się wewnątrz drzewa o nazwie `Hierarchy` znajdujące się po lewej stronie edytora

![](/img/drzewoObiektow.png)

Wybranie obiektu pozwoli nam na edytowanie jego zachowania

## Dodawanie nowego pomieszczenia do mapy

Podczas edytowania wygladu strony, można przełączyć się tryb `View tools` pozwalający na swobodne poruszanie się po edytorze

![](/img/view-tools.png)

Zaznaczona łapka w toolbarze pozwala nam na przejście w tryb `View tools`

## Okno projektu

Okno projektu jest miejscem gdzie można znaleźć wszystkie pliki wykorzystywane wewnątrz projektu.

Assety są plikami, którze tworzą projekt takie jak `Prefab GameObjects`, `textures`, `audio`

Okno projektu działa jak eksplorator plików.

## Narzędzie przesuwania

Aby przesunąć dowolny element na mapie, musimy przejść w tryb `Move Tool`

- skrót klawiszowy aby przejść w ten tryb to `W`

![](/img/move-tool.png)

## Przy każdym dodaniu nowej powierzcni terenu
Podczas dodania nowej powierzchni terenu należy zaktualizować `NavMeshSurface` po przejśiu w `drzewie hierarchi` należy kliknąć przycisk `Bake` aby wypalić nowy mesh nawigacji