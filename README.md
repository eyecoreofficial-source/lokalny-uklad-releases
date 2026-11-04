# Lokalny Układ – pobieranie

Symulator układów cyfrowych w stylu Multisima: bramki, przerzutniki, układy 74xx, generator słów, analizator stanów logicznych i konwerter logiczny. Działa lokalnie na macOS i Windows, bez internetu.

## Pobierz

**[➜ Najnowsza wersja](https://github.com/eyecoreofficial-source/lokalny-uklad-releases/releases/latest)** – na dole strony, w sekcji *Assets*, wybierz plik dla swojego komputera:

| Komputer | Plik |
|---|---|
| Mac z procesorem Apple (M1, M2, M3, M4…) | `Lokalny-Uklad-…-mac-arm64.dmg` |
| Mac z procesorem Intel | `Lokalny-Uklad-…-mac-x64.dmg` |
| Windows 10 / 11 | `Lokalny-Uklad-…-windows-instalator.exe` |

Pliki `.zip`, `.yml` i `.blockmap` są dla automatycznych aktualizacji – nie trzeba ich pobierać.

## Instalacja

**macOS:** otwórz plik `.dmg` i przeciągnij *Lokalny Układ* do folderu *Aplikacje*. Program nie jest podpisany płatnym certyfikatem Apple, więc przy pierwszym uruchomieniu kliknij go prawym przyciskiem → *Otwórz* → *Otwórz*. Jeśli system mówi, że plik jest „uszkodzony”, wpisz w Terminalu:

```bash
xattr -cr "/Applications/Lokalny Układ.app"
```

**Windows:** uruchom instalator. W oknie SmartScreen kliknij *Więcej informacji* → *Uruchom mimo to*.

## Aktualizacje

Od wersji 1.3.0 program sam sprawdza, czy jest nowa wersja, pobiera ją w tle i instaluje po ponownym uruchomieniu. Na Macu trzymaj program w folderze *Aplikacje* – tylko stamtąd może się zaktualizować sam. Starsze wersje (1.2.0 i wcześniejsze) trzeba raz zaktualizować ręcznie, pobierając instalator z tej strony.
