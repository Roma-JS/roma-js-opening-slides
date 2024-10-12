---
theme: ./theme
class: text-center
highlighter: shiki
lineNumbers: false
info: |
  ## Welcome to RomaJS
  The Rome's Javascript community

  Learn more at [romajs.org](https://romajs.org)
drawings:
  persist: false
transition: slide-left
# used for theme customization, will inject root styles as `--slidev-theme-x` for attribute `x`
title: Welcome to RomaJS
mdc: true
favicon: https://romajs.org/assets/favicon.ico
fonts:
  # basically the text
  sans: "Robot"
  # use with `font-serif` css class from windicss
  serif: "Robot Slab"
  # for code blocks, inline code, etc.
  mono: "Fira Code"
---

# Benvenuti a RomaJS

La community di appassionati Javascript a Roma

<v-click>

<div class="abs-br m-6 flex gap-2">
  <Logo />
</div>

<div class="flex items-center justify-center align-center gap-2 mt-7">
  <h2>Open source night edition</h2>
  <SocialIcon type="github" size="32" />
</div>
<Confetti />
<img class="fixed bottom-1 left-1" width="240" height="240" src="https://octodex.github.com/images/manufacturetocat.png" />
</v-click>

---

# Cosa è RomaJS?

RomaJS è una community di appassionati e professionisti del mondo tech.

<v-clicks>

- 📅 **Appuntamento fisso** - ci incontriamo il terzo mercoledì del mese
- 🧑‍💻 **Aperta a tutti** - non ci sono limiti di esperienza o barriere di nessun tipo per proporre un talk a RomaJS
- 🤹 **Community** - la passione per la tecnologia e la voglia di condividere è alla base di RomaJS
- 🎥 **In diretta** - quasi tutti gli appuntamenti sono registrati e disponibili online

</v-clicks>

---
layout: two-cols
---

# I nostri contatti

<ul class="mt-7">
  <li class="flex gap-2 items-center text-2xl"><SocialIcon type="discord" size="32" />Discord</li>
  <li class="flex gap-2 items-center text-2xl"><SocialIcon type="github" size="32" />Github</li>
  <li class="flex gap-2 items-center text-2xl"><SocialIcon type="youtube" size="32" />Youtube </li>
  <li class="flex gap-2 items-center text-2xl"><SocialIcon type="facebook" size="32" />Facebook </li>
  <li class="flex gap-2 items-center text-2xl"><SocialIcon type="twitter" size="32" />X (Twitter)</li>
</ul>

::right::

<div class="flex flex-col justify-center items-center w-full mt-16">
<img width="240" class="rounded-md border-4 border-current" src="/media/qrcode/qrcode-romajs-org.svg" alt="https://romajs.org" />
<p class="text-2xl !leading-6 text-center">
Trovate tutti i nostri contatti sul sito <strong><a href="https://romajs.org">https://romajs.org</a></strong>
</p>
</div>

---
layout: intro
---

# Un grazie per la location! 🙏

---
layout: intro
---

# Si parte! 

---
layout: intro
---


# Open source night 🚀

---
layout: two-cols
---


# Board dei progetti

## https://github.com/orgs/Roma-JS/projects/2


<v-clicks>

- <span class="text-2xl">I partecipanti potranno scegliere una di queste issue e lavorarci.</span>

- <span class="text-2xl">Tra i presenti ci saranno alcuni contributor abituali di progetti open source che offriranno supporto a chi ne ha bisogno.</span>

</v-clicks>

::right::


<img class="rounded-md border-4 border-current fixed bottom-2 right-2"  width="280" height="280" src="/media/qrcode/board-progetti.svg" />

---

<h1 class="flex align-center gap-2">Presentazione progetti open source <SocialIcon class="mt-1" type="github" size="32" /></h1>

<div class="mt-10">
<v-clicks>

- <span class="text-3xl mt-4">A breve mostreremo lascieremo lo spazio per la presenzatione di progetti open source.</span>

- <span class="text-3xl">Chiunque può presentare un progetto a cui sta cuore.</span>

</v-clicks>
</div>

---
layout: intro
---

# L'evento termina alle 23 👋

---
layout: intro
---

# Come creare una PR in 5 passaggi

---
layout: intro
---

# 1. Crea una fork del progetto al quale vuoi contribuire

---
layout: intro
---

<img width="2422" height="1310" src="/media/fork-pic.webp" />

---
layout: intro
---

# 2. Clona la fork sul tuo computer e configura git

---
layout: intro
---

```bash
# clona il progetto
git clone <git-url-della-fork>

# setta il progetto originale come upstream remote
git remote add upstream <git-url-del-progetto-originale>

# imposta user ed email | opzionale
git config user.name 'FirstName Lastname'
git config user.email 'my-email@gmail.com'
```

---
layout: intro
---

# 3. Crea in una nuova branch le modifiche

---
layout: center
---

# git switch -c &lt;nome-della-feature&gt;

---
layout: intro
---

# 4. Fai il push delle modifiche

---
layout: center
---

# git push -u origin $(git branch --show-current)

---
layout: intro
---

# 5. Crea la PR

---
layout: center
---

<img width="2416" height="1322" src="/media/pull-request-pic.jpg" />

---
layout: center
---

<img width="480" height="480" src="https://octodex.github.com/images/mona-the-rivetertocat.png" />