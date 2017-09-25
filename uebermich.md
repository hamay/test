---
layout: default
---


<div class="test">
  <a href="index.html" id="testlogo"><img src="img/logo.png" alt="logo"></a>
</div>

<div class="test">
  <a href="uebermich.html">Über mich</a>
  <a href="betreuung.html">Betreuung</a>
  <a href="spielraum.html">Spielraum</a>
  <a href="yoga.html">Yoga</a>
  <a href="kontakt.html">Kontakt</a>
  <a href="links.html">Links</a>
</div>


.test {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}

.test a {
  padding: 10px;
  text-decoration: none;
  font-size: 20px;
  list-style: none;
  color: black;
}

.test a:hover {
      background-color: #DC5133;
      color: white;
}

@media screen and (max-width: 600px) {
  .test {
    flex-direction: column;
    align-items: stretch;
  }
}
