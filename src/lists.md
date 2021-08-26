# Sąrašai (ang. lists)

* Žyma (ang. tag) `<ul>` apibrėžia nenumeruojama (ang. unordered) sąrašą. Jo viduje yra `<li>` žymos (ang. tags), kurios ir ir sudaro sąrašo elementą.
* Žyma (ang. tag) `<ol>` (ang. ordered) apibrėžia numeruotą sąrašą. Jame taip pat naudojamos <li> žymos, tačiau jų vaizdas bus pakeistas! Šį kartą jis bus sunumeruotas.
* Žymas (ang. tags) `<ul>`ir `<ol>` galima įdėti viena į kitą!

---
```html
<ul>
    <li>
        Nupirkti saldainius.
    </li>
    <li>
        Aplankyti gimines.
    </li>        
</ul>

<ol>
    <li>
        Nupirkti saldainius.
    </li>
    <li>
        Aplankyti gimines.
    </li>        
</ol>


<ol>
    <li>
        <ul>
            <li>
                Nupirkti saldainius.
            </li>
            <li>
                Aplankyti gimines.
            </li>        
        </ul>
    </li>
    <li>
        Aplankyti gimines.
    </li>        
</ol>
```