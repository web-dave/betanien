# Strukturierung

Ab der 3. Überschrift wird automatisch ein Seiten Menu erstellt

```
====== Headline Level 1 ======
===== Headline Level 2 ====
==== Headline Level 3 ====
=== Headline Level 4 ===
== Headline Level 5 ==
```

# Headline Level 1

## Headline Level 2

### Headline Level 3

#### Headline Level 4

##### Headline Level 5

# Textformatierung

```
**fett**
```

**fett**

```
 //italic//
```

<i>italic</i>

```
 __underlined__
```

__underlined__

<u>underlined</u>

```
 ''monospaced''
```

<code>monospaced</code>

```
**__//''combine''//__**
```

<b><i><u><code>combine</code></u></i></b>

## Text align

`Text <sub>tief</sub> oder <sup>hoch</sup> stellen.`

Text <sub>tief</sub> oder <sup>hoch</sup> stellen.

```
<del>Gelöschter</del> Text.
```

<del>Gelöschter</del> Text.

## Zeilenumbruch

```
Text mit Zeilenumbrüchen \\ Beachten sie, dass die Backslashes nur am ende einer Zeile erkannt werden \\
oder wenn\\ ein Leerseichen folgt. \\So sieht der Fehlerfall aus.
```

Text mit Zeilenumbrüchen <br> Beachten sie, dass die Backslashes nur am Ende einer Zeile erkannt werden <br>
oder wenn<br> ein Leerseichen folgt. \\\So sieht der Fehlerfall aus.

# Links

## Externe Links und Email links

http://www.google.com oder www.google.com

```
<mailto:foo@bar.org>
```

foo@bar.org

```
[[http://www.google.com|Linktext]]
```

[Linktext](http://www.google.com)

## Interne Links

```
[[seitenname]]
```

[seitenname]()

```
[[seitenname#meinabschnitt|mein Abschnitt]]
```

[mein Abschnitt]()

## Fußnoten

```
Fussnoten werden durch zweifache klammern ((Moin)) erstellt
```

Fussnoten werden durch zweifache klammern <span title="Moin">1)</span> erstellt

# Unterhaltungen / Kommentare

```
Wir brauchen das!

> Nein tun wir nicht!

> > Ich denke doch.

> Bist du dir sicher?

> > Ja!

> > > Na gut, dann besorge ich Kaffe!
```

Wir brauchen das!

> Nein tun wir nicht!

> > Ich denke doch.

> Bist du dir sicher?

> > Ja!

> > > Na gut, dann besorge ich Kaffe!

# Tabellen

```
^ Heading 1      ^ Heading 2       ^ Heading 3          ^
| blablabla      | blablabla       | blablabla          |
| blablabla      | colspan (!!doupple Pipe)      ||
| blablabla      | Kein colspan    |                    |
| blablabla      | rowspan         | blablabla          |
| blablabla      | :::             | blablabla          |
| blablabla      | :::             | blablabla          |
| blablabla      | :::             | blablabla          |
| left           |   center        |               right|
```

<table border=1>
<thead>
<tr>
<td>Heading 1</td><td>Heading 2</td><td>Heading 3</td>
</tr>
</thead>
<tbody>
<tr>
<td>blablabla</td><td>blablabla</td><td>blablabla</td>
</tr>
<tr>
<td>blablabla</td><td colspan=2>colspan (!!doupple Pipe)</td>
</tr>
<tr>
<td>blablabla</td><td>Kein colspan</td><td></td>
</tr>
<tr>
<td>blablabla</td><td rowspan=4>rowspan</td><td>blablabla</td>
</tr>
<tr><td>blablabla</td><td>blablabla</td></tr>
<tr><td>blablabla</td><td>blablabla</td></tr>
<tr><td>blablabla</td><td>blablabla</td></tr>
<tr>
<td valign="left">left</td>
<td style="text-align='enter'">center</td>
<td valign="right">right</td></tr>
</tbody>
</table>
