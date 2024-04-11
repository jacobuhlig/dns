# Quick guide

## Filtering

### Blocking

Missing blocking description

#### Example

In order to block the domain `example.dk`, one has to add `||example.dk^` to a blocklist.

It is important to be aware that domains often redirect to other domains over the course of various spans of browsing.

In order to then effectively block any access to the domain, they should also be added to the list like so

```
||example.dk^
||example.com^
```

Provided there were only the two.

</br>

### Whitelisting

Missing whitelisting description

#### Example

In order to whitelist the domain `example.dk`, one has to add `@@||example.dk^` to a whitelist.

To ensure full functionality, all the related domains should be included.

```
@@||example.dk^
@@||example.com^
```
