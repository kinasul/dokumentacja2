# **Dokumentacja Techniczna cz.1**

# **Dokumentacja techniczna GIMP**

**Nazwa aplikacji:** GIMP (GNU Image Manipulation Program)  
**Autorzy:** Społeczność GNU / GIMP Development Team  
**Licencja:** GNU General Public License v3 (GPL-3.0)  
**Strona projektu:** [https://www.gimp.org](https://www.gimp.org/)

## **Spis treści**

1. Strona tytułowa  
2. Spis treści  
3. Opis programu  
4. Opis metod i funkcji  
   * Interfejs użytkownika  
   * Obsługiwane formaty plików  
   * Warstwy i maski  
   * Narzędzia edycji  
   * Filtry i efekty  
   * Skrypty i automatyzacja  
   * Obsługa wtyczek  
   * Funkcjonalności Programu  
   * Opis metod i funkcji  
5. Określenie warunków użytkowania  
   * Możliwości  
   * Ograniczenia  
6. Podsumowanie

## **Opis programu**

GIMP (GNU Image Manipulation Program) to otwartoźródłowy edytor grafiki rastrowej, wykorzystywany do obróbki zdjęć, tworzenia grafik oraz projektowania interfejsów. Dzięki wsparciu dla warstw, masek, pędzli i filtrów, stanowi darmową alternatywę dla komercyjnych programów takich jak Adobe Photoshop. GIMP umożliwia rozszerzanie funkcjonalności za pomocą wtyczek i skryptów napisanych w Pythonie oraz Scheme.

**Opis metod i funkcji**

### **Interfejs użytkownika**

* GIMP oferuje interfejs oparty na dockach, umożliwiający użytkownikowi dostosowanie przestrzeni roboczej.  
* Podstawowe okna: Obraz, Narzędzia, Warstwy, Kanały, Pędzle, Opcje narzędzia.  
* Obsługa skrótów klawiszowych i dostosowywania interfejsu.

### **Obsługiwane formaty plików**

* Import/eksport: XCF (format natywny), PNG, JPEG, BMP, GIF, TIFF, PSD (częściowa kompatybilność).  
* Obsługa formatów wektorowych poprzez import SVG.  
* Możliwość eksportu do formatu PDF.

### **Warstwy i maski**

* Obsługa wielowarstwowych plików.  
* Maski warstwowe umożliwiające edycję przezroczystości.  
* Tryby mieszania warstw (np. Mnożenie, Nakładka, Ekran).  
* Grupy warstw dla organizacji złożonych projektów.

### **Narzędzia edycji**

* Narzędzia selekcji (Prostokąt, Lasso, Różdżka, Ścieżki).  
* Transformacje (Przesuwanie, Skalowanie, Obracanie, Wypaczenie).  
* Malowanie (Pędzel, Ołówek, Aerograf, Klonowanie, Rozmazywanie).  
* Korekta kolorów (Poziomy, Krzywe, Balans kolorów, Nasycenie).

### **Filtry i efekty**

* Filtry rozmycia (Gaussa, Ruchome, Średnie).  
* Efekty artystyczne (Malowanie olejne, Mozaika, Neon).  
* Filtry wyostrzania i redukcji szumów.  
* Obsługa wtyczek do dodatkowych efektów graficznych.

###  **Obsługa wtyczek**

* Możliwość instalacji i zarządzania rozszerzeniami.  
* Wtyczki do obsługi dodatkowych formatów plików.  
* Rozszerzenia dodające nowe filtry i efekty.

**Funkcjonalności programu**

* Edycja obrazów rastrowych – narzędzia do przycinania, zmiany rozmiaru, obracania i korekcji kolorów.  
* Retusz i fotomontaż – funkcje klonowania, usuwania elementów, poprawiania jakości zdjęć.  
* Tworzenie grafik – wsparcie dla rysowania, warstw, masek i ścieżek.  
* Obsługa warstw – nielimitowana liczba warstw z różnymi trybami mieszania.  
* Wsparcie dla formatów plików – obsługa JPEG, PNG, GIF, TIFF, PSD i innych.  
* Automatyzacja – możliwość korzystania z Pythona i Scheme do skryptowania.  
* Integracja z tabletami graficznymi – wsparcie dla nacisku i nachylenia pióra.

**Opis Metod i Funkcji**

* gimp-edit-copy(image) – kopiuje zaznaczony obszar obrazu.  
* gimp-edit-paste(image, floating\_selection\_mode) – wkleja wcześniej skopiowany fragment.  
* gimp-layer-new(image, width, height, type, name, opacity, mode) – tworzy nową warstwę w obrazie.  
* gimp-file-load(filename) – ładuje obraz z pliku.  
* gimp-file-save(image, drawable, filename) – zapisuje obraz do pliku.

## **Określenie warunków użytkowania**

**Możliwości**

* Pobierać, używać i modyfikować kod źródłowy programu.  
* Rozpowszechniać program oraz jego zmodyfikowane wersje pod warunkiem zachowania licencji GPL.  
* Nieodpłatnie korzystać z oprogramowania zarówno do celów prywatnych, jak i komercyjnych.

### **Ograniczenia:**

* Nie wolno zmieniać licencji i rozpowszechniać GIMP-a na warunkach innych niż GPL v3.  
* Wszelkie zmodyfikowane wersje muszą zachować informacje o oryginalnych autorach.  
* Program nie jest objęty żadną gwarancją – użytkownicy korzystają z niego na własną odpowiedzialność.

## **Podsumowanie**

GIMP to potężne narzędzie do edycji grafiki, oferujące szeroki wachlarz funkcji i narzędzi porównywalnych do komercyjnych programów. Jego elastyczność, wsparcie dla skryptów i obsługa wtyczek sprawiają, że jest popularnym wyborem zarówno dla początkujących, jak i zaawansowanych użytkowników.

