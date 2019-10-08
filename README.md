# Schemas

Current versions of the ELTeC schema in RELAX NG  are available from this repository, either for download to your
local system, or directly via HTTP.

To check whether a text is valid against an ELTeC schema in oXygen, insert a PI like the following at the
start of the document:

```
<?xml-model href="https://github.com/COST-ELTEC/Schemas/raw/master/eltec-1.rng" ?>
```
or, if you have downloaded this repository to a location on your system:
```
<?xml-model href="file://path/to/myCopyOf/Schemas/eltec-1.rng" ?>
```

# Documentation

For complete documentation of each schema, please read
- https://distantreading.github.io/Schema/eltec-0.html (level 0)
- https://distantreading.github.io/Schema/eltec-1.html (level 1)
- https://distantreading.github.io/Schema/eltec-2.html (level 2)

# ODD sources

The schemas and their documentation are produced by processing a TEI-conformant ODD specification, which
is also available from this repository, in the folder ODD. 


