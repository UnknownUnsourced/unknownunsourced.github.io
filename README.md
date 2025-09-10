# https://unknownunsourced.github.io/
## Hvordan kan jeg download denne website hvis den bliver slettet?
På toppen af websiten skulle der være en "< > Code" knap. Tryk på den, og så tryk på "Download ZIP" nederst.

## Terminal download (Windows og Linux)
### Tjek hvis du har npm og git installeret;
```sh
npm -v
git -v
```
Hvis du ikke har npm, så installere fra [nodejs](https://nodejs.org/en).

Hvis du ikke har git, så installere fra [git](https://git-scm.com/)

```sh
git clone https://github.com/UnknownUnsourced/unknownunsourced.github.io.git
cd unknownunsourced.github.io
npm install http-server
http-server # åben en af links'ne
```
