# dragonrealms-language-imitator
A random word generator that learns and imitates patterns in language word lists.

## How it works

1. Start with a word set.

```
Lorem ipsum dolor sit amet
```

2. Calling trainWords() with this group will parse out the consonant and vowel "groups".

```
consonantGroups: Lo,re,m,do,lo,r,si,t
vowelGroups: ips,um,am,et
```

3. Calling createWord() will randomly put together the groups to create new words.

```
lodomr
sit
ipsamum
amumet
```

