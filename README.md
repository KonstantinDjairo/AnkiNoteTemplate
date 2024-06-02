# AnkiNoteTypes
<br></br><br></br>
### The "Japanese sentences" template:
![image](https://github.com/KonstantinDjairo/AnkiNoteTemplate/assets/53496273/dcc7120d-ecf4-41cd-bb09-94753b24ce0a)
- Note that this repo contains all the fonts & files needed to reproduce that template as in the picture above.
<br></br><br></br><br></br>
--
A collection of user-created note types for Anki 2.1. It includes a super user-friendly mechanism of importing and exporting them, and everyone is welcome to add their templates by making a pull request.

## Usage

Install [Python](https://wiki.archlinux.org/title/Python) 3.10 or later if you haven't already.

Clone the repository and `cd` into it.
If you have never cloned a repository before,
you need to install [git](https://git-scm.com/).
If you have `git` installed,
open your terminal and type the following commands.

```
git clone "https://github.com/Ajatt-Tools/AnkiNoteTypes.git"
cd AnkiNoteTypes
```

Make sure Anki is running, and you have
[AnkiConnect](https://ankiweb.net/shared/info/2055492159)
installed.

### Importing

To import one of the
[available Note Types](https://github.com/Ajatt-Tools/AnkiNoteTypes/tree/main/templates)
to Anki, run:

```
./antp.sh import
```

https://user-images.githubusercontent.com/69171671/143988488-ff70960c-840c-48e2-90d3-a24468da8942.mp4

### Updating

If you imported a note type from this collection before,
it received an update,
and you want to import the new version, run:

```
./antp.sh update
```

### Exporting

To export one of your Note Types, run:

```
./antp.sh export
```

Then write a helpful readme and commit your changes:

```
git add templates fonts && git commit
```

After committing your template, please [create a pull request](https://github.com/Ajatt-Tools/AnkiNoteTypes/pulls).
