<h1 align="center">Hadith API</h1>

**URL Structure:**

`https://rawcdn.githack.com/arugaz-api/hadith-api/0741c58cfa4bd2a4d81a35028e3310a15c88653c/{endpoint}`

`https://rawcdn.rawgit.net/arugaz-api/hadith-api/0741c58cfa4bd2a4d81a35028e3310a15c88653c/{endpoint}`

`https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/{endpoint}`

`https://cdn.statically.io/gh/arugaz-api/hadith-api/z/{endpoint}`

**Formats:**

The Endpoints Supports HTTP GET Method and returns the data in two formats:

`/{endpoint}.json` - json prettified

`/{endpoint}.min.json` - json minified

**Endpoints:**

- `/editions`<br>
  > Lists all the available editions<br>[https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions.json](https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions.min.json "https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions.min.json")

---

- `/editions/{editionName}`<br>
  > Get the whole hadith and section<br>[https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim.json](https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim.min.json "https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim.min.json")

---

- `/editions/{editionName}/hadiths`<br>
  > Get the whole hadith<br>[https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/hadiths.json](https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/hadiths.min.json "https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/hadiths.min.json")

---

- `/editions/{editionName}/hadiths/{hadithNo}` <br>
  > Get the N hadith<br>[https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/hadiths/1001.json](https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/hadiths/1001.min.json "https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/hadiths/1001.min.json")

---

- `/editions/{editionName}/sections`<br>
  > Get the whole section<br>[https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections.json](https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections.min.json "https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections.min.json")

---

- `/editions/{editionName}/sections/{sectionNo}`<br>
  > Get the N section<br>[https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections/4.json](https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections/4.min.json "https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections/4.min.json")

---

- `/editions/{editionName}/sections/{sectionNo}/{hadithNo}`<br>
  > Get the N hadith on the spesific N section<br>[https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections/4/1001.json](https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections/4/1001.min.json "https://cdn.jsdelivr.net/gh/arugaz-api/hadith-api@z/editions/eng-muslim/sections/4/1001.min.json")
