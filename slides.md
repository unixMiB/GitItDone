---
transition: slide-left
---

<h1 class="main"><span class="title">git</span> it done</h1>
<h2 class="sub">the <span class="title">git</span> workshop</h2>
<img src="/img/gitflow.png" class="gitflow">

<p class="decorations">
$ git init
<br>
$ git add workshop.txt
<br>
$ git commit -m "WIP: Workshop git"
<br>
$ git push origin main
<br>
$ git checkout -b help/students
<br>
$ git add cheatsheet.txt
<br>
$ git commit -m "Add cheatsheet"
<br>
$ git push origin help/students
</p>

<!--
Note
-->

---
transition: slide-left
title: Download
hideInToc: true
---
<h1 class="title">Download</h1>
<ul>
  <li>
    Windows:
      <a href="https://github.com/git-for-windows/git/releases/download/v2.40.0.windows.1/Git-2.40.0-64-bit.exe">git-scm.com</a>
  </li>
  <li>
    Linux:  
```bash
  apt install git # (Ubuntu, Debian, Mint, etc.)
```
```bash
  pacman -S git # (Arch, Manjaro, etc.)
```
```bash
  dnf install git # (Fedora, Red Hat, CentOS, etc.)
```
  </li>
  <li>
    Mac: Dovrebbe essere già installato, altrimenti:
```bash
  brew install git
```
  </li>
</ul>

---
transition: slide-left
title: Indice
hideInToc: true
---
<h1 class="title">Indice</h1>

<Toc></Toc>

---
transition: slide-left
title: Cos'è Git?
---

<h1 class="title">Cos'è Git?</h1>

### Linus Torvalds: "Git può significare qualsiasi cosa a seconda del tuo umore"

<ul>
  <li>Una combinazione casuale di tre lettere che sia pronunciabile e non utilizzato da un comune comando UNIX.  Il fatto che sia una storpiatura di "get" può essere rilevante o meno.</li>
  <li>Stupido. spregevole e ignobile. semplice. Scegliete voi.</li>
  <li>"Tracker di informazioni globali": siete di buon umore, e funziona. Gli angeli cantano e una luce improvvisa riempie la stanza.</li>
  <li>"Goddam idiotic truckload of sh*t": quando si rompe</li>
</ul>

<!--
Note
-->
---
transition: slide-left
title: Come nasce Git?
---

<h1 class="title">Come nasce Git?</h1>

<div class="greentext">
> Sei Linus Torvalds e stai sviluppando il kernel Linux
<br>
> Hai migliaia di file, e devi tenere traccia di ogni modifica
<br>
> Esiste SubVersioN, ma è lento e non ti permette di lavorare offline
<br>
> Decidi di scrivere il tuo sistema di versioning, semplice e veloce
<br>
> Letteralmente tutto il mondo inizia a utilizzarlo
<br>
> linus.wav
</div>

<img src="https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fs.libertaddigital.com%2Ffotos%2Fnoticias%2F300%2F300%2Flinus-torvalds-240709.jpg&f=1&nofb=1&ipt=ef5318910254c5def33716404066f74bc23f973da6c3bd8929a685a8f4ff49ea&ipo=images" alt="Linus Torvalds" class="sideGTimg"/>

---
transition: slide-left
title: Parole chiave
---

<h1 class="title">Parole chiave</h1>
<ul>
  <li>
    <span class="icon"></span>
    <span class="keyword">Repository</span> - La cartella dove si trovano i file
    </li>
  <li>
    <span class="icon">󰜘</span>
    <span class="keyword">Commit</span> - Un punto di riferimento per il codice
  </li>
  <li>
    <span class="icon">󰘬</span>
    <span class="keyword">Branch</span> - Una linea temporale di commit
  </li>
  <li>
    <span class="icon"></span>
    <span class="keyword">Merge</span> - Unire due branch
  </li>
  <li>
    <span class="icon"></span>
    <span class="keyword">Pull</span> - Scaricare le modifiche da un repository remoto
  </li>
  <li>
    <span class="icon"></span>
    <span class="keyword">Push</span> - Caricare le modifiche su un repository remoto
  </li>
</ul>


