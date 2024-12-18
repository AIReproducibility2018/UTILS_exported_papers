# UTILS_exported_papers

The set of papers exported as a result of the search query (repeated for each of the years 2012, 2013, 2014, 2015, 2016).

2k papers per year, ordered by citation count.

The Scopus search term, repeated for each of the years papers were selected from, this one for 2012.
The year is specified in the last search term of the string. The search was performed at some point in
2017.

```
KEY ( "Artificial Intelligence" ) AND NOT ( TITLE-ABS-KEY ( "survey" ) OR TITLE-ABS-KEY ( "review" ) ) AND ( LIMIT-TO ( DOCTYPE , "cp " ) OR LIMIT-TO ( DOCTYPE , "ar " ) OR LIMIT-TO ( DOCTYPE , "ch " ) OR LIMIT-TO ( DOCTYPE , "ip " ) ) AND ( LIMIT-TO ( PUBYEAR , 2012 ) )
```

Below is a more readable formatting, of the same search term, but it is not guaranteed that it will
work in Scopus with newlines.

```
KEY ( "Artificial Intelligence" )
AND NOT (
     TITLE-ABS-KEY ( "survey" )
  OR TITLE-ABS-KEY ( "review" )
)
AND (
     LIMIT-TO ( DOCTYPE , "cp " )
  OR LIMIT-TO ( DOCTYPE , "ar " )
  OR LIMIT-TO ( DOCTYPE , "ch " )
  OR LIMIT-TO ( DOCTYPE , "ip " ) )
AND ( LIMIT-TO ( PUBYEAR , 2012 ) )
```

With the reservation that Scopus may have changed their systems since 2017, the goal of the above formulation
is to:
- Exclude survey and review papers
- Limit the document type to one of the following Scopus document types
- - conference papers
  - articles
  - articles in press
  - book chapter
- Pertain to artificial intelligence.
- Be from the specified year

