## Anleitung zum Erstellen von GitHub Pages mit Visual Studio Code

In dieser Anleitung zeige ich Ihnen Schritt für Schritt, wie Sie eine Website mit GitHub Pages erstellen können. Wir verwenden Visual Studio Code als Editor und müssen keine zusätzlichen Tools wie Jekyll installieren. Die Seite wird direkt auf GitHub gehostet, ohne dass eine lokale Vorschau im Browser nötig ist.

### Voraussetzungen

- Installieren Sie Visual Studio Code von https://code.visualstudio.com/download
- Richten Sie ein kostenloses GitHub-Konto ein unter https://github.com

### 1. Repository erstellen

1. Melden Sie sich bei GitHub an und erstellen Sie ein neues Repository mit dem Namen "username.github.io", wobei "username" Ihr GitHub-Benutzername ist.
2. Wählen Sie "Initialize this repository with a README" aus, um eine README.md Datei zu erstellen.

### 2. Visual Studio Code einrichten

1. Öffnen Sie Visual Studio Code.
2. Installieren Sie die offizielle GitHub-Erweiterung, indem Sie in der Seitenleiste auf die Erweiterungen-Symbole klicken und "GitHub Pull Requests and Issues" suchen.
3. Sobald die Erweiterung installiert ist, werden Sie aufgefordert, sich bei GitHub anzumelden. Folgen Sie den Anweisungen.

### 3. Repository klonen

1. Drücken Sie `Ctrl+Shift+P` (Windows) oder `Cmd+Shift+P` (Mac) um die Befehlspalette zu öffnen.
2. Geben Sie "Git: Clone" ein und drücken Sie Enter.
3. Wählen Sie "Clone from GitHub" aus.
4. Suchen Sie Ihr Repository "username.github.io" und klicken Sie auf "Klonen".

### 4. Markdown-Dateien erstellen

1. Erstellen Sie im Explorer-Bereich von VS Code eine neue Datei mit der Endung ".md". Dies ist eine Markdown-Datei.
2. Geben Sie einen Titel und Inhalt in Markdown-Syntax ein, z.B:

```markdown
# Meine GitHub Pages

Dies ist der Inhalt meiner ersten Seite auf GitHub Pages.
```

3. Speichern Sie die Datei mit `Ctrl+S` oder `Cmd+S`.

### 5. Änderungen committen und pushen

1. Wechseln Sie im Seitenbereich zu "Source Control".
2. Geben Sie eine Commit-Nachricht ein, z.B. "Erste Seite erstellt".
3. Klicken Sie auf das ✓ Symbol, um die Änderungen zu committen.
4. Klicken Sie auf die Schaltfläche "Publish Branch", um Ihren Commit auf GitHub zu pushen.

### 6. GitHub Pages aktivieren

1. Gehen Sie zu Ihrem GitHub-Repository "username.github.io".
2. Klicken Sie auf "Settings".
3. Scrollen Sie nach unten zu "GitHub Pages".
4. Unter "Source" wählen Sie "master branch" aus.
5. Klicken Sie auf "Save".

Nach wenigen Minuten sollte Ihre Seite unter "https://username.github.io" erreichbar sein!

### 7. Weitere Änderungen

Um weitere Änderungen vorzunehmen, erstellen oder bearbeiten Sie einfach Markdown-Dateien in Visual Studio Code. Committen und pushen Sie Ihre Änderungen wie in Schritt 5 beschrieben. GitHub Pages wird Ihre Seite automatisch aktualisieren.

Durch die Verwendung von Visual Studio Code mit der GitHub-Erweiterung können Sie komfortabel Markdown-Dateien bearbeiten und direkt auf GitHub veröffentlichen, ohne zusätzliche Tools zu installieren. Viel Spaß beim Erstellen Ihrer GitHub Pages!

Citations:
[1] https://www.reddit.com/r/github/comments/d703bn/can_i_create_a_github_pages_website_without_using/
[2] https://www.markdownguide.org/tools/github-pages/
[3] https://nicolas-van.github.io/easy-markdown-to-github-pages/
[4] https://automationpanda.com/2021/03/24/testing-github-pages-without-local-jekyll-setup/
[5] https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/setting-a-markdown-processor-for-your-github-pages-site-using-jekyll
[6] https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages
[7] https://docs.github.com/en/pages/quickstart
[8] https://www.youtube.com/watch?v=uqZwcUTVew8
[9] https://dev.to/ar2pi/publish-your-markdown-docs-on-github-pages-6pe
[10] https://marketplace.visualstudio.com/items?itemName=blackgirlbytes.deploy-to-github-pages
[11] https://code.visualstudio.com/docs/sourcecontrol/github
[12] https://github.com/MichaelCurrin/gh-pages-no-jekyll
[13] https://docs.github.com/en/codespaces/developing-in-a-codespace/using-github-codespaces-in-visual-studio-code
[14] https://cloudblogs.microsoft.com/opensource/2019/04/05/publishing-github-pages-from-azure-pipelines/
[15] https://haralduebele.github.io/2021/02/15/Test-your-Github-Pages-content-locally/
[16] https://vscode.github.com
[17] https://daiyi.co/blog/pr-previews-for-github-pages/
[18] https://learn.microsoft.com/en-us/training/paths/collaborate-markdown-github-pages/
[19] https://www.youtube.com/watch?v=_WEyoLuuyYo
[20] https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax
