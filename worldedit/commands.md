# Worldedit / Commands

## //wand
Gibt dem Spieler eine Holzaxt, mit welcher man WorldEdit Bereiche auswählen kann.
Beispiel:
```
//wand
```


## //set <block>
Ersetzt den ausgewählten Bereich durch einen bestimmten Block. Mit einem Komma kann man mehrere Blöcke nutzen.
Beispiel:
```
//set grass_block,dirt
```


## //walls <block>
Ersetzt den Rand des ausgewählten Bereiches, die "Wände", mit einem bestimmten Block. Mit einem Komma kann man mehrere Blöcke nutzen.
Beispiel:
```
//walls oak_planks
```


## //replace <target> <block>
Ersetzt im ausgewählten Bereich alle Blöcke `<target>` durch einen bestimmten Block. Mit einem Komma kann man mehrere Blöcke nutzen.
Beispiel:
```
//replace air stone
```

## //middle <block>
Ersetzt den mittlersten Block im ausgewählten Bereich durch einen bestimmten Block. Mit einem Komma kann man mehrere Blöckr nutzen.
Beispiel:
```
//middle obsidian
```

## //expand vert
Erweitert die Auswahl von oben nach unten der Welt.
Beispiel:
```
//expand vert
```

## //copy
Kopiert die Blöcke innerhalb Auswahl.
Beispiel:
```
//copy
```

## //paste
Fügt die kopierte Auswahl ein.
Beispiel:
```
//paste
```

## //undo
Macht den letzten Command rückgängig.
Beispiel:
```
//undo
```

## //redo
Wiederholt das letzte //undo.
Beispiel:
```
//redo
```

## //schem <load|save> <name>
Speichert oder lädt eine Schematic.
Beispiel:
```
//schem save my_schem
```
```
//schem load my_schem
```
