# Downloader Studio

Aplikacja Windows do pobierania filmów i muzyki z YouTube.

## Pobierz

**[⬇ Pobierz najnowszy instalator](https://github.com/Aropatx/DownloaderStudio-Installer/releases/latest/download/DownloaderStudio-Setup.exe)**

Windows 10 (1809+) lub Windows 11, 64-bit. Instalacja dla bieżącego użytkownika, bez uprawnień administratora. Instalator zawiera środowisko .NET i WPF. Licencje i informacje o wersjach znajdziesz w **Ustawienia → Aplikacja → Licencje i komponenty zewnętrzne**, w menu Start oraz w folderze `licenses` w katalogu instalacji.

## Narzędzia i sesja YouTube

Przy starcie aplikacja sprawdza zainstalowane narzędzia. Po kliknięciu **Pobierz brakujące narzędzia** pobiera yt-dlp z GitHuba oraz FFmpeg i ffprobe z Gyan.dev, zależnie od tego, czego brakuje. yt-dlp może aktualizować się przy uruchomieniu po upływie 20 godzin od ostatniej próby. [Wydania yt-dlp](https://github.com/yt-dlp/yt-dlp/releases/latest) · [FFmpeg Release Essentials](https://www.gyan.dev/ffmpeg/builds/)

Możesz też zainstalować FFmpeg samodzielnie poleceniem `winget install --id yt-dlp.FFmpeg --exact --source winget`. Jeżeli WinGet wyświetli warunki, przeczytaj je i zdecyduj, czy chcesz kontynuować. [Pomoc WinGet](https://learn.microsoft.com/pl-pl/windows/package-manager/winget/install)

Sesja przeglądarki lub plik cookies jest używany przez yt-dlp przy wyszukiwaniu, podglądzie, odczycie playlisty i pobieraniu. Opcja **Bez logowania** wyłącza dostęp do sesji. Pobieraj materiały, gdy zezwala na to YouTube, masz wymaganą zgodę lub pozwala na to prawo. [Warunki korzystania z YouTube](https://www.youtube.com/t/terms?hl=pl)

## Aktualizacje

Aplikacja sprawdza dostępność nowych wersji i pokazuje przycisk **Zaktualizuj**. Po kliknięciu pobiera instalator, sprawdza jego sumę i ponownie uruchamia aplikację po instalacji. Jeśli zmienią się warunki licencji dołączonych składników Microsoftu, instalator poprosi o decyzję. Biblioteka, ustawienia i pobrane pliki są zachowywane. Od wersji 6.1.5 zapisywane są też niezakończone zadania. Przed aktualizacją z wcześniejszej wersji dokończ kolejkę.

## Co potrafi

- Wideo (MP4, MKV, WebM, do 4K) i dźwięk (MP3, M4A, Opus, FLAC, WAV)
- Kolejka pobrań: wiele linków naraz, kilka pobrań jednocześnie
- Playlisty: wybierasz, które filmy pobrać
- Wycinanie fragmentu, okładka i tagi, napisy
- Powiadomienia Windows po zakończeniu pobierania
- Minimalistyczny wygląd z własnymi ikonami i efektem Mica; motyw jasny, ciemny, granatowy lub OLED
- Autostart z Windows – aplikacja czeka w tle obok zegara (można wyłączyć w Ustawieniach)
- Polski i angielski

---

# Downloader Studio (English)

A Windows app for downloading YouTube videos and music.

**[⬇ Download the latest installer](https://github.com/Aropatx/DownloaderStudio-Installer/releases/latest/download/DownloaderStudio-Setup.exe)**. Requires 64-bit Windows 10 (1809+) or Windows 11. No admin rights needed.

The installer includes .NET and WPF. License texts and component versions are available in **Settings → App → Third-party licenses and notices**, in the Start menu and in the installation folder under `licenses`.

The app checks for installed tools at startup. Select **Download missing tools** to get yt-dlp from its official GitHub Releases and FFmpeg and ffprobe from Gyan.dev as needed. yt-dlp can update at startup once 20 hours have passed since the last attempt. To choose WinGet yourself, run `winget install --id yt-dlp.FFmpeg --exact --source winget` and review any terms before accepting or declining. [yt-dlp releases](https://github.com/yt-dlp/yt-dlp/releases/latest) · [FFmpeg Release Essentials](https://www.gyan.dev/ffmpeg/builds/) · [WinGet license agreements](https://learn.microsoft.com/en-us/windows/package-manager/winget/install#license-agreements)

yt-dlp uses a selected browser session or cookies file for search, previews, playlist loading and downloads. Select **No sign-in** to turn off session access. Download when YouTube permits it, you have the required permission, or applicable law permits it. [YouTube Terms of Service](https://www.youtube.com/t/terms?hl=en)

When a new version is available, select **Update**. The app downloads and verifies the installer before restarting. Setup asks you to review new Microsoft component terms. The library, settings and downloaded files are kept. Version 6.1.5 and later also keep queued work. Finish your queue before updating from an earlier version.
