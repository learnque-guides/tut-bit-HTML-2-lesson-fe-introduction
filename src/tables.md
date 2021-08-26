# Lentelės (ang. tables)

* Duomenų lenteles apibrėžia žyma (ang. tag) `<table>`.
* Lentelėje yra `<thead>` ir `<tbody>` konteinerio žymos duomenims atskirti nuo
antraščių
* `<thead>` turi savyje `<tr>` ir `<th>` žymų (ang. tags).
* `<tbody>` turi savyje `<tr>` ir `<td>` žymų (ang. tags).
* `<tr>` yra lentelės eilutė (ang. row), kurioje yra keli langeliai (ang. cells).
* `<th>` yra lentelės antraštė.
* `<td>` yra lentelės langelis (ang. cell).

---
* Kiek šita lentelė turi eilučių (ang. rows)?
* Kiek sita lentelė turi stulpelių (ang. columns)?

```html
<!DOCTYPE html>
<html>
<body>
    <table>
        <thead>
            <tr>
                <th>First name</th>
                <th>Last name</th>
                <th>Age</th>
            </tr>
        </thead>
        <tbody> 
            <tr>
                <td>John</td>
                <td>Wick</td>
                <td>33</td>
            </tr> 
            <tr>
                <td>Eve</td>
                <td>Jackson</td>
                <td>27</td>
            </tr>
        </tbody>
    </table>
</body>
</html>
```
