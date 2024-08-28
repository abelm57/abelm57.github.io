# Vantage 

## Chiamate

```query
path:(CEDIA-PROVA -Ricerca) line:(/^> \[![^\]]+].+((?:\n.+)+)|^> \[![^\]]+].+$/)
```


## Testo evidenziato

```
path:(CEDIA-PROVA -Ricerca) line:(/==[^=]+/==)
```

```query
path:(CEDIA-PROVA/) line:/(?<===|^==)[^=]+(?===[,.;:_ ]*)/
```

## Etichette

```query
path:(CEDIA-PROVA -Ricerca) tag:#nota
```


---

## lookbehind + lookahed

```query
path:(CEDIA-PROVA -Ricerca) line:(/(?<=\`att\.)[^`]+(?=\`)/)
```

---

# Text expand

### Testo evidenziato

```expander 
path:(CEDIA-PROVA) line:(/==[^=]+==/)
``` 

### Inline admonitions

```expander
path:(CEDIA-PROVA) line:(/`att.[^`]+`/)
```

### Empty query

```expander

```
